---
tags: 
作者: 赵展
简要介绍: 
时间: 2024-01-08
---
官方文档：[http://selenium-python.readthedocs.io/index.html]()
# **1. 下载谷歌浏览器驱动**

1. 查看谷歌浏览器的版本 设置-->帮助-->关于Chrome
2. 进入网站下载 https://npmmirror.com 选择 Selenium 镜像: https://npmmirror.com/mirrors/chromedriver 对应我们浏览器的版本下载Selenium版本
3. 新建python工程 将下载解压后的exe文件拖入根目录下
4. 案例 百度查询⬇

#encoding:utf-8
from selenium import webdriver
​
# 调用环境变量指定的PhantomJS浏览器创建浏览器对象
from selenium.webdriver.common.by import By
​
driver = webdriver.Chrome("./chromedriver.exe")
# get方法会一直等到页面被完全加载,然后才会继续程序,通常测试会在这里选择 time.sleep(2)
driver.get("http://www.baidu.com/")
​
kw = driver.find_element(By.ID,"kw")
kw.send_keys("丢丢")
​
# driver.find_element(By.CSS_SELECTOR,"#su").click()
su = driver.find_element(By.ID,"su").click()
su.click()

### **1.元素定位**

#### **1. 获取单个元素**

driver.find_element(By.ID，"inputorigina”）
driver.find_element(By.CSS_SELECTOR，"#inputoriginal"）
driver.find_element(By.TAG_NAME，"div"）
driver.find_element（By.NAME，"username")
driver.find_element(By.LINK_TEXT,“下一页”）

#### **2. 如果找不到相应的元素会报错**

selenium.common.exceptions.NosuchElementException: Message:no such element:Unable to 7ocate element:XX

#### **3. 获取多个元素**

driver.find_elements(By.ID，"inputoriginal”）
driver.findelements(By.CSS_SELECTOR，“inputoriginal”）
driver.find_elements(By.TAG_NAME,“div")
driver.findelements(By.NAME，“username”)
driver.find_elements(By.LINK_TEXT，"下一页”）

#### **4. 内容获取**

1. size 返回元素大小
2. text 获取元素的文本 <div>hello</div>
3. title 获取页面的title
4. current_url 获取当前页面URL
5. get_attribute() 获取属性值<a href="www.baidu.com"></a>
6. is_display() 判断元素是否可见
7. is_enabled() 判断元素是否可用

#### **5. 窗口操作**

1. maximize_window() 窗口最大化
2. set_window_size(100,100) 浏览器大小 设置浏览器的宽高(像素点)
3. set_window_position(300,200) 浏览器位置 设置浏览器位置
4. back() 后退
5. forward() 前进
6. refresh() 刷新
7. close() 关闭浏览器按钮(关闭单个窗口)
8. quit() 关闭webDriver启动的窗口

#### **6. 访问有道翻译网站，输入单词，并获取翻译后的内容**

#encoding:utf-8
from datetime import time
​
from selenium import webdriver
# 调用环境变量指定的PhantomJS浏览器创建浏览器对象
from selenium.webdriver.common.by import By
​
driver = webdriver.Chrome("./chromedriver.exe")
# get方法会一直等到页面被完全加载,然后才会继续程序,通常测试会在这里选择 time.sleep(2)
driver.get("https://fanyi.youdao.com/")
time.sleep(4)
# 获取输入框
input = driver.find_element(By.ID,"inputOriginal")
# 输入内容
input.send_keys("hello")
# 获取翻译按钮
tbtn = driver.find_element(By.ID,"transMachine")
# 先获取遮挡的广告条 点击关闭按钮
close_btn = driver.find_element(By.CSS_SELECTOR,".guide-con .guide-close")
close_btn.click()
# 点击翻译
tbtn.click()
# 获取翻译后的内容
transTarget = driver.find_element(By.ID,"transTarget")
print(transTarget.text)

#### **7. 爬当当网书籍的数据**
```python
#encoding:utf-8
from datetime import time
​
from selenium import webdriver
```

# 调用环境变量指定的PhantomJS浏览器创建浏览器对象
from selenium.webdriver.common.by import By
​
driver = webdriver.Chrome("./chromedriver.exe")
driver.implicitly_wait(30)
# get方法会一直等到页面被完全加载,然后才会继续程序,通常测试会在这里选择 time.sleep(2)
driver.get("https://www.dangdang.com/")
driver.maximize_window()
# 获取输入框
key = driver.find_element(By.ID,"key_S")
key.send_keys("科幻")
# 获取搜索框 点击搜索
search = driver.find_element(By.CSS_SELECTOR,"#form_search_new .button")
search.click()
# 获取商品标题及价格
for i in range(5):
  shoplist = driver.find_elements(By.CSS_SELECTOR,".shoplist li")
  for li in shoplist:
    print(li.find_element(By.CSS_SELECTOR,"a").get_attribute("title"))
    print(li.find_element(By.CSS_SELECTOR,".search_now_price").text)
​
  # 获取下一页的按钮
  next = driver.find_element(By.LINK_TEXT,"下一页")
  next.click()

#### **8. 显示等待**

from selenium.webdriver.support.ui import WebDriverwait
from selenium.webdriver.support import expected_conditions as EC
#程序每0.5秒检查，是否满足：标题包含“百度一下”这个条件，检查是否满足条件的最长时间为：15秒，超过15秒仍未满足条件则抛出异常
WebDriverwait（driver，15).until（Ec.title_contains（“百度一下”）
#程序每0.5秒检查，是否满足：某定位的元素出现，检查是否满足条件的最长时间为：15秒，超过15秒仍未满足条件则抛出异常
WebDriverwait(driver，15）.until（Ec.visibility_of_element_located(By.CSS_SELECTOR，“XX”））

#### **9. 隐式等待**

implicitly_wait(time_to_wait)

设置时间单位为秒 例如30秒 implicitly_wait(30) 意思是超过30秒没有定位到一个元素 程序就回抛出异常,期间会一直轮询查找定位元素

### **2. 鼠标及键盘操作**

#### **1. 鼠标操作**

1. context_click() 右击
2. double_click() 双击
3. drag_and_drop() 拖动
4. move_to_element() 悬停
5. perform()    执行
driver.get("https://www.baidu.com/")
more = driver.find_element(By.LINK_TEXT,"更多")
# 将鼠标移动到更多按钮
ActionChains(driver).move_to_element(more).perform()

案例 打开百度鼠标移动到更多位置

#encoding:utf-8
from datetime import time
​
from selenium import webdriver
# 调用环境变量指定的PhantomJS浏览器创建浏览器对象
from selenium.webdriver import ActionChains
from selenium.webdriver.common.by import By
​
driver = webdriver.Chrome("./chromedriver.exe")
# get方法会一直等到页面被完全加载,然后才会继续程序,通常测试会在这里选择 time.sleep(2)
driver.get("https://www.baidu.com/")
more = driver.find_element(By.LINK_TEXT,"更多")
# 将鼠标移动到更多按钮
ActionChains(driver).move_to_element(more).perform()

#### **2. 键盘操作**

1. send_keys（Keys,BACK_SPACE）删除键（Backspace）
2. send_keys（Keys.SPACE）空格键（Space）
3. send_keys（Keys.TAB）制表键（Tab）
4. send_keys（Keys·ESCAPE）回退键（ESC）
5. send_keys（Keys·ENTER）回车键（Enter）
6. send_keys（Keys.CONTROL，'a'）全选（Ctrl+A）
7. send_keys（Keys.CONTROL，'c'）复制（Ctr1+C）
from selenium.webdriver.common.keys import Keys
driver.get("https://www.baidu.com/")
​
element = driver.find_element(By.ID,"kw")
​
#输入用户名
element.send_keys("admin1")
#删除1
element.send_keys(Keys.BACK_SPACE)
#全选
element.send_keys(Keys.CONTROL,'a')
#复制
element.send_keys(Keys.CONTROL,'c')
#粘贴
element.send_keys(Keys.CONTROL,'v')

### **3. 滚动条**

在HTML页面中，由于前端技术框架的原因，页面元素为动态显示，元素根据滚动条的下拉而被加载

#1.设置]avascritp脚本控制滚动条，（0:左边距；1000：上边距；单位像素）
js="window.scro11To(0,1000)"
#2，WebDriver调用js脚本方法
driver.execute_script(js）

### **4. 窗口截图**

自动化脚本是由程序去执行的，因此有时候打印的错误信息并不是十分明确。如果在执行出错的时候对当前窗口截图保存，那么通过图片就可以非常直观地看到出错的原因

#截取当前窗口
driver.get_screenshot_as_file("./demo.png")

### **5. 数据存储**

1. 将数据写入CSV文件

#读写CSV文件
import csv
#以写入方式打开文件，如果文件不存在则自动创建
f = open("d:/test.csv",'w')
#获取csvwriter，用于写入csv格式数据
writer = csv.writer(f)
#写入数据
writer.writerow(["张三","男","1.7"])
#关闭文件
f.c1ose()

1. 将数据写到MySql
2. 安装模块

pip install pymysql
import pymysq1
#创建连接
conn = pymysql.connect(host='127.0.0.1',port=3306,user='root',passwd='',db='tkq1',charset='utf8')
#创建游标
cursor = conn.cursor()
#执行SQL，并返回收影响行数
effect_row = cursor.execute("select * from tb7")
#执行SQL，并返回受影响行数
#effect_row = cursor.execute("update tb7 set pass= 123’where nid= %s",(11,))
#执行SQL，并返回受影响行数，执行多次
#effect_row=cursor.executemanyC"insert into tb7(user,pass,icnese）values（s,%s,%s）”
[（“ui"，“ulpass”11111)，（“u2”，u2pass”，*22222”)]）
#提交，不然无法保存新建或者修改的数据
conn.commit()
#关闭游标
cursor.close()
#关闭连接
conn.close()

### **6. 数据分析网站**

https://www.heywhale.com/home

https://kaggle.com/