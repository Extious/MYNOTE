---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
计算duration ^0ff5GONp

timereminderChan ^ye5vZrrE

type TimeReminder struct {
	Uid      int64
	Gid      int64
	Content  string
	Duration time.Duration
} ^dtE66vow

设置timereminder ^owCDr0ay

redis
valid+last+lperiod+content ^9frCXkUo

存入redis（TTL=duration） ^CrfXfHwM

if exist ^pVq1hQe3

if valid ^bzPB1cXQ

continue ^imBkQfJw

Y ^8ZNMYc5m

Y ^3A4dIUWz

robotChan ^s214dK0D

N ^1aJzYBxr

N ^0V0HAiEu

delete in redis ^LvOXEEJZ

return ^zgAbHMsw

chan-> ^gyZREPsG

->chan ^BMqhXkib

->chan ^cMKqH6sD

syncTimeReminder ^d6Zp7mEy

get msg ^8hC95Whz

计算duration ^fv2Sdw1U

timereminderChan ^l1Z2GGwD

存入redis（TTL=duration） ^cbATxa3u

type TimeReminder struct {
	Uid     int64
	Gid     int64
	Content string
	Timer   time.Timer
} ^izcMrIiw

设置timereminder ^LBaGVb4Y

redis
valid+last+lperiod+content ^lxrNQncQ

robotChan ^kRfoHJgg

chan-> ^4K9oyUIK

->chan ^szgQlYIA

TimeExitChan ^dvpEJSaS

gid ^F4ialOll

<-timereminder.Timer.C ^YXmxPUwk

系统启动 ^c24aOJvx

加载已存在timereminder ^l6T5meXa

golang内部计时 ^6ufSqLOl

redis内部计时 ^aVTNnERF

消息处理队列 ^p9Oj2W1Y

设置计时任务 ^ZQJv1uKN

系统启动 ^8QcLNl4X

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/2.0.10",
	"elements": [
		{
			"type": "rectangle",
			"version": 186,
			"versionNonce": 1050533438,
			"isDeleted": false,
			"id": "5EZ9W57l5nwdst8OZmWtF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -722.8368395780541,
			"y": -817.3142539500684,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 141.5,
			"height": 80,
			"seed": 277306413,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "0ff5GONp"
				},
				{
					"id": "EbPD1CARZZMIqvibEjYF_",
					"type": "arrow"
				},
				{
					"id": "64mWYyizPubw5gdjFO2Es",
					"type": "arrow"
				},
				{
					"id": "oOMmrvOOPplpcW9pDWKmV",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 150,
			"versionNonce": 1308845694,
			"isDeleted": false,
			"id": "0ff5GONp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -712.4767779325463,
			"y": -789.8142539500684,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120.77987670898438,
			"height": 25,
			"seed": 2120378243,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078659568,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "计算duration",
			"rawText": "计算duration",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "5EZ9W57l5nwdst8OZmWtF",
			"originalText": "计算duration",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 2131,
			"versionNonce": 599078782,
			"isDeleted": false,
			"id": "cIxCtQC2RgrndXQO3Djxi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -350.9017344585651,
			"y": -365.10609852810137,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 516.5741232976739,
			"height": 58,
			"seed": 1235351939,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ye5vZrrE"
				},
				{
					"id": "64mWYyizPubw5gdjFO2Es",
					"type": "arrow"
				},
				{
					"id": "RM5UVw9aUfcAodPjV4H2O",
					"type": "arrow"
				},
				{
					"id": "UsdN1xx67LUYTUYQ-B0tJ",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2054,
			"versionNonce": 1633523646,
			"isDeleted": false,
			"id": "ye5vZrrE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -173.3945876656852,
			"y": -348.60609852810137,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 161.55982971191406,
			"height": 25,
			"seed": 651022627,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078659568,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "timereminderChan",
			"rawText": "timereminderChan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "cIxCtQC2RgrndXQO3Djxi",
			"originalText": "timereminderChan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1682,
			"versionNonce": 1384746420,
			"isDeleted": false,
			"id": "EbPD1CARZZMIqvibEjYF_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -570.6885823305131,
			"y": -797.4512701817105,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 392.48262804034687,
			"height": 3.696073116195066,
			"seed": 1655364429,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "CrfXfHwM"
				}
			],
			"updated": 1705245907899,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "5EZ9W57l5nwdst8OZmWtF",
				"gap": 10.648257247540982,
				"focus": -0.5140269774901844
			},
			"endBinding": {
				"elementId": "4fj4olWMR-CcSI5lkI1uH",
				"gap": 18.927076851785188,
				"focus": 0.00029400634960918446
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					392.48262804034687,
					3.696073116195066
				]
			]
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 584737534,
			"isDeleted": false,
			"id": "CrfXfHwM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -153.0339558845779,
			"y": -563.1676192030436,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 263.41973876953125,
			"height": 25,
			"seed": 196255469,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528833,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "存入redis（TTL=duration）",
			"rawText": "存入redis（TTL=duration）",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "EbPD1CARZZMIqvibEjYF_",
			"originalText": "存入redis（TTL=duration）",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 2937,
			"versionNonce": 1347215540,
			"isDeleted": false,
			"id": "64mWYyizPubw5gdjFO2Es",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -678.2326750021846,
			"y": -724.3299135948932,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.89887191979642,
			"height": 374.3418445883184,
			"seed": 621572685,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "dtE66vow"
				}
			],
			"updated": 1705245907908,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "5EZ9W57l5nwdst8OZmWtF",
				"gap": 12.984340355175163,
				"focus": 0.38362052814157765
			},
			"endBinding": {
				"elementId": "dgUODhnpFd5u5StsbUvkh",
				"gap": 8.070924549270956,
				"focus": -0.902280531286918
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					9.89887191979642,
					374.3418445883184
				]
			]
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 627482292,
			"isDeleted": false,
			"id": "dtE66vow",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -287.01845399436047,
			"y": -160.2248677029626,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 159.375,
			"height": 153.6,
			"seed": 763720739,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705245907894,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "type TimeReminder\nstruct {\nUid      int64\nGid      int64\nContent  string\nDuration\ntime.Duration\n}",
			"rawText": "type TimeReminder struct {\n\tUid      int64\n\tGid      int64\n\tContent  string\n\tDuration time.Duration\n}",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "64mWYyizPubw5gdjFO2Es",
			"originalText": "type TimeReminder struct {\n\tUid      int64\n\tGid      int64\n\tContent  string\n\tDuration time.Duration\n}",
			"lineHeight": 1.2,
			"baseline": 149
		},
		{
			"type": "rectangle",
			"version": 166,
			"versionNonce": 1743847678,
			"isDeleted": false,
			"id": "JH12rZmYeRfGnI_F3oxLk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -1007.4257392473924,
			"y": -812.121022310409,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 188.734542414958,
			"height": 80,
			"seed": 276367373,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "owCDr0ay"
				},
				{
					"id": "oOMmrvOOPplpcW9pDWKmV",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 151,
			"versionNonce": 241447230,
			"isDeleted": false,
			"id": "owCDr0ay",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -991.1183893045618,
			"y": -784.621022310409,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 156.11984252929688,
			"height": 25,
			"seed": 1171163469,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078659568,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "设置timereminder",
			"rawText": "设置timereminder",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "JH12rZmYeRfGnI_F3oxLk",
			"originalText": "设置timereminder",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 402,
			"versionNonce": 1721084596,
			"isDeleted": false,
			"id": "oOMmrvOOPplpcW9pDWKmV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -811.2271188838203,
			"y": -778.6895474074979,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.28055690972167,
			"height": 2.6556018257974756,
			"seed": 1238053635,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907898,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "JH12rZmYeRfGnI_F3oxLk",
				"gap": 7.46407794861409,
				"focus": -0.23121580895442742
			},
			"endBinding": {
				"elementId": "5EZ9W57l5nwdst8OZmWtF",
				"gap": 9.109722396044504,
				"focus": -0.09335197377170998
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					79.28055690972167,
					2.6556018257974756
				]
			]
		},
		{
			"type": "ellipse",
			"version": 383,
			"versionNonce": 1474350462,
			"isDeleted": false,
			"id": "4fj4olWMR-CcSI5lkI1uH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -159.29492491130043,
			"y": -945.6799326392938,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 398.2011701465724,
			"height": 308.0461474586813,
			"seed": 1828240845,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "9frCXkUo"
				},
				{
					"id": "EbPD1CARZZMIqvibEjYF_",
					"type": "arrow"
				},
				{
					"id": "9fOgtsWkaWbLKsoprGbFU",
					"type": "arrow"
				}
			],
			"updated": 1705078722376,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 429,
			"versionNonce": 1895472830,
			"isDeleted": false,
			"id": "9frCXkUo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -89.18625665029401,
			"y": -844.0676188031656,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 258.4130859375,
			"height": 105,
			"seed": 1742734253,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078722376,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "redis\nvalid+last+lperiod+\ncontent",
			"rawText": "redis\nvalid+last+lperiod+content",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "4fj4olWMR-CcSI5lkI1uH",
			"originalText": "redis\nvalid+last+lperiod+content",
			"lineHeight": 1.25,
			"baseline": 95
		},
		{
			"type": "diamond",
			"version": 1090,
			"versionNonce": 855033918,
			"isDeleted": false,
			"id": "PgV61zxYzsZEozwnsYr_S",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 842.741671526679,
			"y": -268.5530881720223,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 159.93790645517996,
			"height": 100,
			"seed": 907960227,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "pVq1hQe3"
				},
				{
					"id": "fNqRRe7ouMqZnTuT-W_yi",
					"type": "arrow"
				},
				{
					"id": "JO0PAhTS9fARUH6Z4Dshn",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1098,
			"versionNonce": 1367975934,
			"isDeleted": false,
			"id": "pVq1hQe3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 893.5980811238725,
			"y": -228.55308817202229,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.256134033203125,
			"height": 20,
			"seed": 1901096387,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078722377,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "if exist",
			"rawText": "if exist",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "PgV61zxYzsZEozwnsYr_S",
			"originalText": "if exist",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "diamond",
			"version": 1411,
			"versionNonce": 1711913278,
			"isDeleted": false,
			"id": "hBXhV-gqXpQjvoh5yz9q2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 853.6620968157322,
			"y": -67.46539131484292,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 159.93790645517996,
			"height": 100,
			"seed": 1308272771,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "bzPB1cXQ"
				},
				{
					"id": "fNqRRe7ouMqZnTuT-W_yi",
					"type": "arrow"
				},
				{
					"id": "aaHgKsgWwgqFO5hS7IFT9",
					"type": "arrow"
				},
				{
					"id": "1ZT3iGpmyYvDTiFN4rGg4",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1432,
			"versionNonce": 758395326,
			"isDeleted": false,
			"id": "bzPB1cXQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 906.0785116009139,
			"y": -27.46539131484292,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 55.13612365722656,
			"height": 20,
			"seed": 439918627,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078722377,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "if valid",
			"rawText": "if valid",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "hBXhV-gqXpQjvoh5yz9q2",
			"originalText": "if valid",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 1296,
			"versionNonce": 1163407998,
			"isDeleted": false,
			"id": "FZzulOy-1CEy2qHZ40oqt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 871.1737253187757,
			"y": 129.67958911793835,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.48587773526106,
			"height": 47.74265864333722,
			"seed": 1998175309,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "imBkQfJw"
				},
				{
					"id": "aaHgKsgWwgqFO5hS7IFT9",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1265,
			"versionNonce": 1373332094,
			"isDeleted": false,
			"id": "imBkQfJw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 906.3046036395313,
			"y": 143.55091843960696,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 62.22412109375,
			"height": 20,
			"seed": 834996483,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078722377,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "continue",
			"rawText": "continue",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FZzulOy-1CEy2qHZ40oqt",
			"originalText": "continue",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 3805,
			"versionNonce": 513382836,
			"isDeleted": false,
			"id": "fNqRRe7ouMqZnTuT-W_yi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 928.111690655599,
			"y": -162.71757480491675,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.7626791382488136,
			"height": 85.66876484468978,
			"seed": 660776973,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "8ZNMYc5m"
				}
			],
			"updated": 1705245907901,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "PgV61zxYzsZEozwnsYr_S",
				"gap": 7.811324005701962,
				"focus": -0.036873065181110165
			},
			"endBinding": {
				"elementId": "hBXhV-gqXpQjvoh5yz9q2",
				"gap": 9.743091831220113,
				"focus": 0.0107578988175972
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					3.7626791382488136,
					85.66876484468978
				]
			]
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 195126818,
			"isDeleted": false,
			"id": "8ZNMYc5m",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 834.090786449845,
			"y": 163.673933500204,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.256011962890625,
			"height": 20,
			"seed": 222885763,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Y",
			"rawText": "Y",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "fNqRRe7ouMqZnTuT-W_yi",
			"originalText": "Y",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 3641,
			"versionNonce": 2056241844,
			"isDeleted": false,
			"id": "aaHgKsgWwgqFO5hS7IFT9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 935.8738706325244,
			"y": 34.694465614782814,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.8172872119666863,
			"height": 85.43659177448845,
			"seed": 1024960333,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "3A4dIUWz"
				}
			],
			"updated": 1705245907901,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hBXhV-gqXpQjvoh5yz9q2",
				"gap": 3.020379607473444,
				"focus": -0.014172367007740674
			},
			"endBinding": {
				"elementId": "FZzulOy-1CEy2qHZ40oqt",
				"gap": 9.548531728667086,
				"focus": 0.014761703922406232
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					1.8172872119666863,
					85.43659177448845
				]
			]
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 278155746,
			"isDeleted": false,
			"id": "3A4dIUWz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 852.5910666741381,
			"y": 418.5003740090168,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 8.256011962890625,
			"height": 20,
			"seed": 1605836611,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Y",
			"rawText": "Y",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "aaHgKsgWwgqFO5hS7IFT9",
			"originalText": "Y",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 2321,
			"versionNonce": 1950458622,
			"isDeleted": false,
			"id": "TiWZ7QfmGv_J2zRisiR5l",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1962.3294593452028,
			"y": -248.19843156222942,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 598.7975208211885,
			"height": 58,
			"seed": 953513539,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "s214dK0D"
				},
				{
					"id": "1L6DwkDTgbV02BaC4R2k6",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2260,
			"versionNonce": 1280348990,
			"isDeleted": false,
			"id": "s214dK0D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2212.898271330504,
			"y": -231.69843156222942,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 97.65989685058594,
			"height": 25,
			"seed": 66303459,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078659568,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "robotChan",
			"rawText": "robotChan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "TiWZ7QfmGv_J2zRisiR5l",
			"originalText": "robotChan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 5366,
			"versionNonce": 948758196,
			"isDeleted": false,
			"id": "JO0PAhTS9fARUH6Z4Dshn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1010.4716139655692,
			"y": -222.5125155054992,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.81636311072646,
			"height": 3.401021787770958,
			"seed": 1342253507,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "1aJzYBxr"
				}
			],
			"updated": 1705245907910,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "PgV61zxYzsZEozwnsYr_S",
				"gap": 8.740302602342652,
				"focus": -0.14957049308521733
			},
			"endBinding": {
				"elementId": "sLXsBF6RD0FmMKhFtpo-v",
				"gap": 11.793644536908005,
				"focus": -0.07714365807341926
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					84.81636311072646,
					3.401021787770958
				]
			]
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 976142690,
			"isDeleted": false,
			"id": "1aJzYBxr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1018.6663698506234,
			"y": 41.93015395969422,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 10.30401611328125,
			"height": 20,
			"seed": 1474044621,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "N",
			"rawText": "N",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "JO0PAhTS9fARUH6Z4Dshn",
			"originalText": "N",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 4076,
			"versionNonce": 1632553140,
			"isDeleted": false,
			"id": "1ZT3iGpmyYvDTiFN4rGg4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1015.9176913948303,
			"y": -18.027763857022222,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 89.17471219221136,
			"height": 1.0755490975313435,
			"seed": 112670531,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "0V0HAiEu"
				}
			],
			"updated": 1705245907904,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hBXhV-gqXpQjvoh5yz9q2",
				"gap": 2.3849404847812394,
				"focus": -0.031096872426606154
			},
			"endBinding": {
				"elementId": "urfe1ssaoufIeYyoQNu7M",
				"gap": 10.57955742345257,
				"focus": -0.11677514193439445
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					89.17471219221136,
					1.0755490975313435
				]
			]
		},
		{
			"type": "text",
			"version": 16,
			"versionNonce": 324289826,
			"isDeleted": false,
			"id": "0V0HAiEu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1043.7312656383756,
			"y": 296.75659446850705,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 10.30401611328125,
			"height": 20,
			"seed": 247067053,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "N",
			"rawText": "N",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "1ZT3iGpmyYvDTiFN4rGg4",
			"originalText": "N",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 2827,
			"versionNonce": 1329564734,
			"isDeleted": false,
			"id": "urfe1ssaoufIeYyoQNu7M",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1115.6719610104942,
			"y": -35.508203833214225,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 161.45655446386172,
			"height": 35,
			"seed": 1031276109,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "LvOXEEJZ"
				},
				{
					"id": "1ZT3iGpmyYvDTiFN4rGg4",
					"type": "arrow"
				},
				{
					"id": "TCloGvsNQZR4vbZoMTwAJ",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2784,
			"versionNonce": 2050970750,
			"isDeleted": false,
			"id": "LvOXEEJZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1126.0803224709407,
			"y": -30.508203833214225,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 140.63983154296875,
			"height": 25,
			"seed": 1654371501,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078659568,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "delete in redis",
			"rawText": "delete in redis",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "urfe1ssaoufIeYyoQNu7M",
			"originalText": "delete in redis",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1352,
			"versionNonce": 97549630,
			"isDeleted": false,
			"id": "UCIvf2Xg9PgreqCW58ufr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1133.6230215218482,
			"y": 81.36863663672352,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.48587773526106,
			"height": 47.74265864333722,
			"seed": 2061607885,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "zgAbHMsw"
				},
				{
					"id": "TCloGvsNQZR4vbZoMTwAJ",
					"type": "arrow"
				},
				{
					"id": "4KE7URy3F1ejZizeHMoSe",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1325,
			"versionNonce": 87948542,
			"isDeleted": false,
			"id": "zgAbHMsw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1175.8099072278576,
			"y": 95.23996595839213,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.11210632324219,
			"height": 20,
			"seed": 1274389037,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078722378,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "return",
			"rawText": "return",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "UCIvf2Xg9PgreqCW58ufr",
			"originalText": "return",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 1386,
			"versionNonce": 777477054,
			"isDeleted": false,
			"id": "IcOY2vqHfRmPZ--BXDjph",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 306.2396448510724,
			"y": -356.23890008859365,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 222.00336269151842,
			"height": 53.71049097375453,
			"seed": 1839856867,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "gyZREPsG"
				},
				{
					"id": "UsdN1xx67LUYTUYQ-B0tJ",
					"type": "arrow"
				},
				{
					"id": "mNYnLBBZISDZWBb4eHBiz",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1419,
			"versionNonce": 1621761598,
			"isDeleted": false,
			"id": "gyZREPsG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 393.0332726079644,
			"y": -339.3836546017164,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.416107177734375,
			"height": 20,
			"seed": 1175562083,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078722378,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "chan->",
			"rawText": "chan->",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "IcOY2vqHfRmPZ--BXDjph",
			"originalText": "chan->",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 3750,
			"versionNonce": 1700449972,
			"isDeleted": false,
			"id": "TCloGvsNQZR4vbZoMTwAJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1198.6714333194427,
			"y": 3.9986906610334927,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.5558341781559193,
			"height": 66.8182174724968,
			"seed": 1132751085,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907905,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "urfe1ssaoufIeYyoQNu7M",
				"gap": 4.506894494247717,
				"focus": -0.021676925467861034
			},
			"endBinding": {
				"elementId": "UCIvf2Xg9PgreqCW58ufr",
				"gap": 10.551728503193232,
				"focus": 0.017408008089272585
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					1.5558341781559193,
					66.8182174724968
				]
			]
		},
		{
			"type": "arrow",
			"version": 3947,
			"versionNonce": 1042626484,
			"isDeleted": false,
			"id": "4KE7URy3F1ejZizeHMoSe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1392.681171397056,
			"y": -189.93066931170677,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 114.27866668277352,
			"height": 305.5701754491125,
			"seed": 1411264451,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907906,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ldHkUfBcZqrgyqYk_iPW9",
				"gap": 9.532349870744724,
				"focus": 0.10818366458673913
			},
			"endBinding": {
				"elementId": "UCIvf2Xg9PgreqCW58ufr",
				"gap": 12.293605457173271,
				"focus": 0.9872222535963903
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-9.434996653220196,
					200.51325677812667
				],
				[
					-114.27866668277352,
					305.5701754491125
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2947,
			"versionNonce": 1607268030,
			"isDeleted": false,
			"id": "ldHkUfBcZqrgyqYk_iPW9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1322.0474451372745,
			"y": -234.4630191824515,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 161.45655446386172,
			"height": 35,
			"seed": 714518019,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "BMqhXkib"
				},
				{
					"id": "JO0PAhTS9fARUH6Z4Dshn",
					"type": "arrow"
				},
				{
					"id": "4KE7URy3F1ejZizeHMoSe",
					"type": "arrow"
				},
				{
					"id": "1L6DwkDTgbV02BaC4R2k6",
					"type": "arrow"
				},
				{
					"id": "n6_acc5zgGUstikATm8pB",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2924,
			"versionNonce": 448491262,
			"isDeleted": false,
			"id": "BMqhXkib",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1372.515750750553,
			"y": -229.4630191824515,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 60.51994323730469,
			"height": 25,
			"seed": 1614280099,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078659568,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "->chan",
			"rawText": "->chan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ldHkUfBcZqrgyqYk_iPW9",
			"originalText": "->chan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 3924,
			"versionNonce": 1264179892,
			"isDeleted": false,
			"id": "1L6DwkDTgbV02BaC4R2k6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1490.6308594491256,
			"y": -215.7300888285573,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 463.7763171380693,
			"height": 1.124823598488831,
			"seed": 2043564163,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907906,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ldHkUfBcZqrgyqYk_iPW9",
				"gap": 7.126859847989408,
				"focus": 0.05763234691568933
			},
			"endBinding": {
				"elementId": "TiWZ7QfmGv_J2zRisiR5l",
				"gap": 7.922282758007896,
				"focus": -0.17959036164803854
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					463.7763171380693,
					1.124823598488831
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1770,
			"versionNonce": 206587134,
			"isDeleted": false,
			"id": "dgUODhnpFd5u5StsbUvkh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -677.757778165312,
			"y": -341.9171444573039,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 227.10271009845042,
			"height": 58,
			"seed": 250238467,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "cMKqH6sD"
				},
				{
					"id": "64mWYyizPubw5gdjFO2Es",
					"type": "arrow"
				},
				{
					"id": "RM5UVw9aUfcAodPjV4H2O",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1702,
			"versionNonce": 1149831358,
			"isDeleted": false,
			"id": "cMKqH6sD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -594.4663947347391,
			"y": -325.4171444573039,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 60.51994323730469,
			"height": 25,
			"seed": 1272356259,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078722378,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "->chan",
			"rawText": "->chan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "dgUODhnpFd5u5StsbUvkh",
			"originalText": "->chan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1137,
			"versionNonce": 1416315828,
			"isDeleted": false,
			"id": "RM5UVw9aUfcAodPjV4H2O",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -440.30815287517424,
			"y": -319.85056194111075,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80.38312359675405,
			"height": 1.6125196590483029,
			"seed": 34007469,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907908,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "dgUODhnpFd5u5StsbUvkh",
				"gap": 10.346915191687287,
				"focus": -0.14220798408679008
			},
			"endBinding": {
				"elementId": "cIxCtQC2RgrndXQO3Djxi",
				"gap": 9.023294819855096,
				"focus": -0.27151232752479526
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					80.38312359675405,
					-1.6125196590483029
				]
			]
		},
		{
			"type": "arrow",
			"version": 2940,
			"versionNonce": 1755142964,
			"isDeleted": false,
			"id": "UsdN1xx67LUYTUYQ-B0tJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 171.71118484622343,
			"y": -327.5627310277838,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 124.71479178969952,
			"height": 5.5306018140245214,
			"seed": 398030701,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907905,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "cIxCtQC2RgrndXQO3Djxi",
				"gap": 6.038796007114684,
				"focus": 0.5009433578154879
			},
			"endBinding": {
				"elementId": "IcOY2vqHfRmPZ--BXDjph",
				"gap": 9.813668215149448,
				"focus": 0.2853368259620536
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					124.71479178969952,
					-5.5306018140245214
				]
			]
		},
		{
			"type": "arrow",
			"version": 696,
			"versionNonce": 1155647924,
			"isDeleted": false,
			"id": "n6_acc5zgGUstikATm8pB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1277.9727648997457,
			"y": -217.0012247890329,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 37.42609534342341,
			"height": 0,
			"seed": 837771075,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907910,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "sLXsBF6RD0FmMKhFtpo-v",
				"gap": 9.434588822680325,
				"focus": -2.598556290779795e-14
			},
			"endBinding": {
				"elementId": "ldHkUfBcZqrgyqYk_iPW9",
				"gap": 6.648584894105397,
				"focus": 0.0021831775189379435
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					37.42609534342341,
					0
				]
			]
		},
		{
			"type": "frame",
			"version": 1089,
			"versionNonce": 1531178622,
			"isDeleted": false,
			"id": "DeoKofS06YzzHm-ZAJBFx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 797.852554423511,
			"y": -296.19921799560166,
			"strokeColor": "#bbb",
			"backgroundColor": "transparent",
			"width": 726.8230664326248,
			"height": 506.5063148992179,
			"seed": 1449428739,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "mNYnLBBZISDZWBb4eHBiz",
					"type": "arrow"
				},
				{
					"id": "9fOgtsWkaWbLKsoprGbFU",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false,
			"customData": {
				"frameColor": {
					"stroke": "#D4D4D4",
					"fill": "#ADADAD",
					"nameColor": "#949494"
				}
			},
			"name": "goroutine"
		},
		{
			"type": "arrow",
			"version": 1530,
			"versionNonce": 297737780,
			"isDeleted": false,
			"id": "mNYnLBBZISDZWBb4eHBiz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 537.1931956690571,
			"y": -316.58681499738367,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 250.02396985109021,
			"height": 13.590656133087748,
			"seed": 742244035,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907905,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "IcOY2vqHfRmPZ--BXDjph",
				"gap": 8.950188126466287,
				"focus": 0.1908408425700608
			},
			"endBinding": {
				"elementId": "DeoKofS06YzzHm-ZAJBFx",
				"gap": 12.621802656448153,
				"focus": 0.8780640785994054
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					250.02396985109021,
					13.590656133087748
				]
			]
		},
		{
			"type": "ellipse",
			"version": 631,
			"versionNonce": 1752285054,
			"isDeleted": false,
			"id": "-gs17qPsnf_31M8bjJiV7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 178.59996825124267,
			"y": -617.330688556758,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1690.7386034541425,
			"height": 946.6270735432261,
			"seed": 1705983437,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 266,
			"versionNonce": 1833508798,
			"isDeleted": false,
			"id": "d6Zp7mEy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 941.1194187883402,
			"y": -505.5558246758866,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.38427734375,
			"height": 20,
			"seed": 121714627,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078659568,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "syncTimeReminder",
			"rawText": "syncTimeReminder",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "syncTimeReminder",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 1482,
			"versionNonce": 1193324724,
			"isDeleted": false,
			"id": "9fOgtsWkaWbLKsoprGbFU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 198.04509006092565,
			"y": -673.6985332669221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 596.988169528125,
			"height": 360.37120482999495,
			"seed": 1356880077,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907899,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "4fj4olWMR-CcSI5lkI1uH",
				"gap": 18.141230572631883,
				"focus": 0.1148472533567877
			},
			"endBinding": {
				"elementId": "DeoKofS06YzzHm-ZAJBFx",
				"gap": 17.358588383098976,
				"focus": 0.1043244546194788
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					596.988169528125,
					360.37120482999495
				]
			]
		},
		{
			"type": "rectangle",
			"version": 3144,
			"versionNonce": 1602244670,
			"isDeleted": false,
			"id": "sLXsBF6RD0FmMKhFtpo-v",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1107.0816216132037,
			"y": -234.50122478903245,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 161.45655446386172,
			"height": 35,
			"seed": 1726442179,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "8hC95Whz"
				},
				{
					"id": "JO0PAhTS9fARUH6Z4Dshn",
					"type": "arrow"
				},
				{
					"id": "n6_acc5zgGUstikATm8pB",
					"type": "arrow"
				}
			],
			"updated": 1705078659568,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 3129,
			"versionNonce": 1304926334,
			"isDeleted": false,
			"id": "8hC95Whz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1149.9099430956228,
			"y": -229.50122478903245,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 75.79991149902344,
			"height": 25,
			"seed": 1959991907,
			"groupIds": [],
			"frameId": "DeoKofS06YzzHm-ZAJBFx",
			"roundness": null,
			"boundElements": [],
			"updated": 1705078659568,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "get msg",
			"rawText": "get msg",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "sLXsBF6RD0FmMKhFtpo-v",
			"originalText": "get msg",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 200,
			"versionNonce": 1375724066,
			"isDeleted": false,
			"id": "P-khjaSEeuM7tocuNQnDO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -597.6298957903266,
			"y": 1101.805836072372,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 141.5,
			"height": 80,
			"seed": 1287765731,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "fv2Sdw1U"
				},
				{
					"id": "spc76493MoKsZZs_cK9VV",
					"type": "arrow"
				},
				{
					"id": "ecD6QLsGsKjNMDV08nOqF",
					"type": "arrow"
				},
				{
					"id": "eECy3c2DZdjCf7UDbskkk",
					"type": "arrow"
				}
			],
			"updated": 1705078528834,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 164,
			"versionNonce": 939542782,
			"isDeleted": false,
			"id": "fv2Sdw1U",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -587.2698341448188,
			"y": 1129.305836072372,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120.77987670898438,
			"height": 25,
			"seed": 814606979,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "计算duration",
			"rawText": "计算duration",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "P-khjaSEeuM7tocuNQnDO",
			"originalText": "计算duration",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 2177,
			"versionNonce": 2109951458,
			"isDeleted": false,
			"id": "vGSrtpJGTs4ccPnbX8G3P",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -228.0819236030045,
			"y": 1563.5625232230063,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 516.5741232976739,
			"height": 58,
			"seed": 219390499,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "l1Z2GGwD"
				},
				{
					"id": "ecD6QLsGsKjNMDV08nOqF",
					"type": "arrow"
				},
				{
					"id": "XkmQ68b-Gd9jfuUxNW0lH",
					"type": "arrow"
				},
				{
					"id": "5ufcECcucHh7PP1EyXMfF",
					"type": "arrow"
				}
			],
			"updated": 1705078528834,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2101,
			"versionNonce": 759855422,
			"isDeleted": false,
			"id": "l1Z2GGwD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -50.574776810124604,
			"y": 1580.0625232230063,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 161.55982971191406,
			"height": 25,
			"seed": 725706179,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "timereminderChan",
			"rawText": "timereminderChan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "vGSrtpJGTs4ccPnbX8G3P",
			"originalText": "timereminderChan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1950,
			"versionNonce": 335514420,
			"isDeleted": false,
			"id": "spc76493MoKsZZs_cK9VV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -443.7804523908118,
			"y": 1150.840063642497,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 388.4657604101463,
			"height": 11.49327238078854,
			"seed": 842380643,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "cbATxa3u"
				}
			],
			"updated": 1705245907918,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "P-khjaSEeuM7tocuNQnDO",
				"gap": 12.349443399514826,
				"focus": 0.27303283020532004
			},
			"endBinding": {
				"elementId": "5K6fIMRkL-w1EixRfMsP3",
				"gap": 18.927076851785074,
				"focus": 0.0985279912986692
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					388.4657604101463,
					-11.49327238078854
				]
			]
		},
		{
			"type": "text",
			"version": 19,
			"versionNonce": 308584830,
			"isDeleted": false,
			"id": "cbATxa3u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -641.3769369424792,
			"y": 987.2497393437616,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 263.41973876953125,
			"height": 25,
			"seed": 1631523075,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "存入redis（TTL=duration）",
			"rawText": "存入redis（TTL=duration）",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "spc76493MoKsZZs_cK9VV",
			"originalText": "存入redis（TTL=duration）",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 2996,
			"versionNonce": 1925897524,
			"isDeleted": false,
			"id": "ecD6QLsGsKjNMDV08nOqF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -553.0257047592094,
			"y": 1194.790176427547,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.89884928774984,
			"height": 374.3418445883185,
			"seed": 165410979,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "izcMrIiw"
				}
			],
			"updated": 1705245907921,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "P-khjaSEeuM7tocuNQnDO",
				"gap": 12.984340355175163,
				"focus": 0.383620128033327
			},
			"endBinding": {
				"elementId": "pj4KtYMkA0yyH0-od1ilt",
				"gap": 8.070924549270785,
				"focus": -0.9022805312869175
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					9.89884928774984,
					374.3418445883185
				]
			]
		},
		{
			"type": "text",
			"version": 44,
			"versionNonce": 1451833652,
			"isDeleted": false,
			"id": "izcMrIiw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -627.7637801153344,
			"y": 1276.3610987217064,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 159.375,
			"height": 153.6,
			"seed": 1236986947,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705245907913,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "type TimeReminder\nstruct {\nUid     int64\nGid     int64\nContent string\nTimer\ntime.Timer\n}",
			"rawText": "type TimeReminder struct {\n\tUid     int64\n\tGid     int64\n\tContent string\n\tTimer   time.Timer\n}",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ecD6QLsGsKjNMDV08nOqF",
			"originalText": "type TimeReminder struct {\n\tUid     int64\n\tGid     int64\n\tContent string\n\tTimer   time.Timer\n}",
			"lineHeight": 1.2,
			"baseline": 149
		},
		{
			"type": "rectangle",
			"version": 181,
			"versionNonce": 680837410,
			"isDeleted": false,
			"id": "eGT5D7DODmD896zVUBOLq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -882.2187954596648,
			"y": 1106.9990677120313,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 188.734542414958,
			"height": 80,
			"seed": 79326179,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "LBaGVb4Y"
				},
				{
					"id": "eECy3c2DZdjCf7UDbskkk",
					"type": "arrow"
				},
				{
					"id": "qg7JJ3rqSht1rGXNxhwV9",
					"type": "arrow"
				}
			],
			"updated": 1705078528834,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 165,
			"versionNonce": 1760352766,
			"isDeleted": false,
			"id": "LBaGVb4Y",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -865.9114455168342,
			"y": 1134.4990677120313,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 156.11984252929688,
			"height": 25,
			"seed": 518584195,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "设置timereminder",
			"rawText": "设置timereminder",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "eGT5D7DODmD896zVUBOLq",
			"originalText": "设置timereminder",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 460,
			"versionNonce": 798344500,
			"isDeleted": false,
			"id": "eECy3c2DZdjCf7UDbskkk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -686.0201750960927,
			"y": 1140.420186113935,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.28055690972155,
			"height": 2.6609846283781735,
			"seed": 1988431651,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907916,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "eGT5D7DODmD896zVUBOLq",
				"gap": 7.46407794861409,
				"focus": -0.23158157086608447
			},
			"endBinding": {
				"elementId": "P-khjaSEeuM7tocuNQnDO",
				"gap": 9.109722396044504,
				"focus": -0.09335197377171282
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					79.28055690972155,
					2.6609846283781735
				]
			]
		},
		{
			"type": "ellipse",
			"version": 449,
			"versionNonce": 1361381428,
			"isDeleted": false,
			"id": "5K6fIMRkL-w1EixRfMsP3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -36.66646270869137,
			"y": 994.0680100640933,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 398.2011701465724,
			"height": 308.0461474586813,
			"seed": 503132867,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "lxrNQncQ"
				},
				{
					"id": "spc76493MoKsZZs_cK9VV",
					"type": "arrow"
				}
			],
			"updated": 1705245907918,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 493,
			"versionNonce": 768368802,
			"isDeleted": false,
			"id": "lxrNQncQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 33.442205552315045,
			"y": 1095.6803239002215,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 258.4130859375,
			"height": 105,
			"seed": 1441784419,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "redis\nvalid+last+lperiod+\ncontent",
			"rawText": "redis\nvalid+last+lperiod+content",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "5K6fIMRkL-w1EixRfMsP3",
			"originalText": "redis\nvalid+last+lperiod+content",
			"lineHeight": 1.25,
			"baseline": 95
		},
		{
			"type": "rectangle",
			"version": 2495,
			"versionNonce": 740356734,
			"isDeleted": false,
			"id": "eQ8SeyH1oN8O6ioKqZtLX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1173.059805894099,
			"y": 1567.6977500278465,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 598.7975208211885,
			"height": 58,
			"seed": 1194040835,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "kRfoHJgg"
				},
				{
					"id": "v6p9hzr0plFynvzdLzEor",
					"type": "arrow"
				}
			],
			"updated": 1705078528834,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2431,
			"versionNonce": 1484520546,
			"isDeleted": false,
			"id": "kRfoHJgg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1423.6286178794003,
			"y": 1584.1977500278465,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 97.65989685058594,
			"height": 25,
			"seed": 2091836835,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528834,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "robotChan",
			"rawText": "robotChan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "eQ8SeyH1oN8O6ioKqZtLX",
			"originalText": "robotChan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 1625,
			"versionNonce": 678782900,
			"isDeleted": false,
			"id": "-rz3NEXDROJAu8PX3YCeD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 437.2620200997782,
			"y": 1577.4197685862923,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 222.00336269151842,
			"height": 53.71049097375453,
			"seed": 497563971,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "4K9oyUIK"
				},
				{
					"id": "5ufcECcucHh7PP1EyXMfF",
					"type": "arrow"
				},
				{
					"id": "QfwwQcWFNEv0vbJqC6wXN",
					"type": "arrow"
				},
				{
					"id": "Q-sH98z0hgrSeTKYG_k3P",
					"type": "arrow"
				},
				{
					"id": "PHIZc5OU-YHNJcZz60zQd",
					"type": "arrow"
				}
			],
			"updated": 1705245907919,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1652,
			"versionNonce": 172105762,
			"isDeleted": false,
			"id": "4K9oyUIK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 524.0556478566702,
			"y": 1594.2750140731696,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.416107177734375,
			"height": 20,
			"seed": 1735792867,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528835,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "chan->",
			"rawText": "chan->",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "-rz3NEXDROJAu8PX3YCeD",
			"originalText": "chan->",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 4331,
			"versionNonce": 1512515764,
			"isDeleted": false,
			"id": "v6p9hzr0plFynvzdLzEor",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1027.0253678128036,
			"y": 1603.9666537962455,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 133.88750406279382,
			"height": 0.1136753642633721,
			"seed": 1738998915,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907925,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "4IH7c9De7B49DacPbjRwX",
				"gap": 8.55423466420524,
				"focus": 0.11359822259354531
			},
			"endBinding": {
				"elementId": "eQ8SeyH1oN8O6ioKqZtLX",
				"gap": 12.14693401850161,
				"focus": -0.26140153040094805
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					133.88750406279382,
					0.1136753642633721
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1784,
			"versionNonce": 789433314,
			"isDeleted": false,
			"id": "pj4KtYMkA0yyH0-od1ilt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -552.5508343775844,
			"y": 1577.2029455651364,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 227.10271009845042,
			"height": 58,
			"seed": 1979284515,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "szgQlYIA"
				},
				{
					"id": "ecD6QLsGsKjNMDV08nOqF",
					"type": "arrow"
				},
				{
					"id": "XkmQ68b-Gd9jfuUxNW0lH",
					"type": "arrow"
				}
			],
			"updated": 1705078528835,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1716,
			"versionNonce": 1785649982,
			"isDeleted": false,
			"id": "szgQlYIA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -469.2594509470115,
			"y": 1593.7029455651364,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 60.51994323730469,
			"height": 25,
			"seed": 1851523011,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528835,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "->chan",
			"rawText": "->chan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "pj4KtYMkA0yyH0-od1ilt",
			"originalText": "->chan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1303,
			"versionNonce": 1811161140,
			"isDeleted": false,
			"id": "XkmQ68b-Gd9jfuUxNW0lH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -315.1012090874466,
			"y": 1601.495566565558,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 77.995990664587,
			"height": 0.19885747454372904,
			"seed": 720179043,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907922,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "pj4KtYMkA0yyH0-od1ilt",
				"gap": 10.346915191687344,
				"focus": -0.14994898525896597
			},
			"endBinding": {
				"elementId": "vGSrtpJGTs4ccPnbX8G3P",
				"gap": 9.023294819855096,
				"focus": -0.27151232752479615
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					77.995990664587,
					-0.19885747454372904
				]
			]
		},
		{
			"type": "arrow",
			"version": 3624,
			"versionNonce": 593365684,
			"isDeleted": false,
			"id": "5ufcECcucHh7PP1EyXMfF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 294.53099570178404,
			"y": 1603.1280551009904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.91735618284486,
			"height": 3.900151903251299,
			"seed": 1039870723,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907920,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "vGSrtpJGTs4ccPnbX8G3P",
				"gap": 6.038796007114684,
				"focus": 0.5008788442819005
			},
			"endBinding": {
				"elementId": "-rz3NEXDROJAu8PX3YCeD",
				"gap": 9.813668215149335,
				"focus": 0.28533682596206217
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					132.91735618284486,
					-3.900151903251299
				]
			]
		},
		{
			"type": "arrow",
			"version": 2181,
			"versionNonce": 575538612,
			"isDeleted": false,
			"id": "QfwwQcWFNEv0vbJqC6wXN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 672.5771445134968,
			"y": 1603.1326990839254,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 115.73649036075028,
			"height": 1.5430427434253033,
			"seed": 570608867,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907925,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "-rz3NEXDROJAu8PX3YCeD",
				"gap": 13.311761722200202,
				"focus": 0.018178083409795803
			},
			"endBinding": {
				"elementId": "4IH7c9De7B49DacPbjRwX",
				"gap": 8.154135582832794,
				"focus": 0.02833327797905056
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					115.73649036075028,
					-1.5430427434253033
				]
			]
		},
		{
			"type": "rectangle",
			"version": 2417,
			"versionNonce": 2139333566,
			"isDeleted": false,
			"id": "vlW0Hcc3qxU8Q_3Ltkv49",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -228.34469832743002,
			"y": 1840.407886855131,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 516.5741232976739,
			"height": 58,
			"seed": 548100899,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "dvpEJSaS"
				},
				{
					"id": "Q-sH98z0hgrSeTKYG_k3P",
					"type": "arrow"
				},
				{
					"id": "e85QAFcM0fK0Ut209rSY_",
					"type": "arrow"
				}
			],
			"updated": 1705078528835,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2369,
			"versionNonce": 1724383010,
			"isDeleted": false,
			"id": "dvpEJSaS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -35.007564962284505,
			"y": 1856.907886855131,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 129.8998565673828,
			"height": 25,
			"seed": 1165622979,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528835,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "TimeExitChan",
			"rawText": "TimeExitChan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "vlW0Hcc3qxU8Q_3Ltkv49",
			"originalText": "TimeExitChan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 796,
			"versionNonce": 1743299380,
			"isDeleted": false,
			"id": "Q-sH98z0hgrSeTKYG_k3P",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 292.526985859762,
			"y": 1875.3417276744096,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 135.39359346575014,
			"height": 274.4952930548807,
			"seed": 1189466275,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907923,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "vlW0Hcc3qxU8Q_3Ltkv49",
				"gap": 4.297560889518195,
				"focus": 0.974028065166565
			},
			"endBinding": {
				"elementId": "-rz3NEXDROJAu8PX3YCeD",
				"gap": 9.341440774266033,
				"focus": 0.9821835317490077
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					135.39359346575014,
					-274.4952930548807
				]
			]
		},
		{
			"type": "rectangle",
			"version": 180,
			"versionNonce": 1568656098,
			"isDeleted": false,
			"id": "pjMXZwX5ADUjxNlK_1VIQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -542.4934679400346,
			"y": 1836.9213008717165,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 155.16364059084617,
			"height": 62.06545623633838,
			"seed": 861311555,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "F4ialOll"
				},
				{
					"id": "e85QAFcM0fK0Ut209rSY_",
					"type": "arrow"
				},
				{
					"id": "qg7JJ3rqSht1rGXNxhwV9",
					"type": "arrow"
				}
			],
			"updated": 1705078528835,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 156,
			"versionNonce": 325078078,
			"isDeleted": false,
			"id": "F4ialOll",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -477.8016317754709,
			"y": 1855.4540289898857,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 25.77996826171875,
			"height": 25,
			"seed": 68319533,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528835,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "gid",
			"rawText": "gid",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "pjMXZwX5ADUjxNlK_1VIQ",
			"originalText": "gid",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 510,
			"versionNonce": 1962109236,
			"isDeleted": false,
			"id": "e85QAFcM0fK0Ut209rSY_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -380.1684285526877,
			"y": 1866.1012785087712,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 141.55833700532276,
			"height": 0.4574960068666769,
			"seed": 389381443,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907925,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "pjMXZwX5ADUjxNlK_1VIQ",
				"gap": 7.161398796500748,
				"focus": -0.0504698920988396
			},
			"endBinding": {
				"elementId": "vlW0Hcc3qxU8Q_3Ltkv49",
				"gap": 10.265393219934936,
				"focus": 0.1552561190163339
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					141.55833700532276,
					-0.4574960068666769
				]
			]
		},
		{
			"type": "arrow",
			"version": 432,
			"versionNonce": 1788355252,
			"isDeleted": false,
			"id": "qg7JJ3rqSht1rGXNxhwV9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -790.6365348028169,
			"y": 1199.5390830526126,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 234.0711163043751,
			"height": 674.2686117829182,
			"seed": 1075664739,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245907925,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "eGT5D7DODmD896zVUBOLq",
				"gap": 12.540015340581249,
				"focus": 0.053254144624035424
			},
			"endBinding": {
				"elementId": "pjMXZwX5ADUjxNlK_1VIQ",
				"gap": 14.071950558407138,
				"focus": -0.6917629685044563
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					26.169441574402185,
					588.8124354240492
				],
				[
					234.0711163043751,
					674.2686117829182
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1658,
			"versionNonce": 1531968098,
			"isDeleted": false,
			"id": "4IH7c9De7B49DacPbjRwX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 796.46777045708,
			"y": 1573.9486083732347,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 222.00336269151842,
			"height": 53.71049097375453,
			"seed": 2084249645,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "YXmxPUwk"
				},
				{
					"id": "QfwwQcWFNEv0vbJqC6wXN",
					"type": "arrow"
				},
				{
					"id": "v6p9hzr0plFynvzdLzEor",
					"type": "arrow"
				}
			],
			"updated": 1705078528835,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1715,
			"versionNonce": 1032639678,
			"isDeleted": false,
			"id": "YXmxPUwk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 822.293266194929,
			"y": 1590.803853860112,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 170.3523712158203,
			"height": 20,
			"seed": 1906348685,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078528835,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "<-timereminder.Timer.C",
			"rawText": "<-timereminder.Timer.C",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "4IH7c9De7B49DacPbjRwX",
			"originalText": "<-timereminder.Timer.C",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 241,
			"versionNonce": 36172340,
			"isDeleted": false,
			"id": "mzJYYZOjHwk6s_seOi5hn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 405.6683780676469,
			"y": 1010.2739479486645,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 301.4285714285713,
			"height": 98.57142857142867,
			"seed": 241641826,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "c24aOJvx"
				},
				{
					"id": "PHIZc5OU-YHNJcZz60zQd",
					"type": "arrow"
				}
			],
			"updated": 1705245907927,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 288,
			"versionNonce": 1123495230,
			"isDeleted": false,
			"id": "c24aOJvx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 516.3826942995107,
			"y": 1047.0596622343787,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.99993896484375,
			"height": 25,
			"seed": 1491755106,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078638965,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "系统启动",
			"rawText": "系统启动",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "mzJYYZOjHwk6s_seOi5hn",
			"originalText": "系统启动",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 702,
			"versionNonce": 1381206964,
			"isDeleted": false,
			"id": "PHIZc5OU-YHNJcZz60zQd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 394.2398066390757,
			"y": 1078.56832625165,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 187.14285714285728,
			"height": 491.34847883987095,
			"seed": 1810004386,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "l6T5meXa"
				}
			],
			"updated": 1705245907927,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "mzJYYZOjHwk6s_seOi5hn",
				"gap": 11.428571428571217,
				"focus": 0.9695066976537005
			},
			"endBinding": {
				"elementId": "-rz3NEXDROJAu8PX3YCeD",
				"gap": 7.50296349477162,
				"focus": -0.02788400464170778
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-67.50000000000028,
					281.3484788398712
				],
				[
					119.642857142857,
					491.34847883987095
				]
			]
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 370057570,
			"isDeleted": false,
			"id": "l6T5meXa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 255.82276540546758,
			"y": 1141.7025193772356,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 216.1197967529297,
			"height": 25,
			"seed": 368948926,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705078576308,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "加载已存在timereminder",
			"rawText": "加载已存在timereminder",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "PHIZc5OU-YHNJcZz60zQd",
			"originalText": "加载已存在timereminder",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 230,
			"versionNonce": 763105460,
			"isDeleted": false,
			"id": "hEkMRykB27cJv6TczVW02",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 347.30052369979217,
			"y": 3058.229880904598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 360,
			"height": 137.77777777777783,
			"seed": 2106249086,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "6ufSqLOl"
				},
				{
					"id": "BDWowD5Sud80WLwulHX5e",
					"type": "arrow"
				},
				{
					"id": "0P43AHGeNenSTXzr9QFlX",
					"type": "arrow"
				},
				{
					"id": "0HlMuDPBZEl8cqVtS3fOs",
					"type": "arrow"
				}
			],
			"updated": 1705245919670,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 245,
			"versionNonce": 1788860980,
			"isDeleted": false,
			"id": "6ufSqLOl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 402.14647096541717,
			"y": 3104.6187697934865,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 250.30810546875,
			"height": 45,
			"seed": 388560382,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705245919670,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "golang内部计时",
			"rawText": "golang内部计时",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "hEkMRykB27cJv6TczVW02",
			"originalText": "golang内部计时",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "rectangle",
			"version": 346,
			"versionNonce": 316088372,
			"isDeleted": false,
			"id": "hi0MNrOpDoIvPw3u9VAt2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 336.1894125886812,
			"y": 3618.229880904598,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 360,
			"height": 137.77777777777783,
			"seed": 1376442786,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "aVTNnERF"
				},
				{
					"id": "CmspVqgNSOAVrUWdee6-p",
					"type": "arrow"
				},
				{
					"id": "GHLLY-TD5706TZjRozLB_",
					"type": "arrow"
				}
			],
			"updated": 1705245919670,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 366,
			"versionNonce": 552401332,
			"isDeleted": false,
			"id": "aVTNnERF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 402.6453680940523,
			"y": 3664.6187697934865,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 227.0880889892578,
			"height": 45,
			"seed": 1082348898,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705245919670,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "redis内部计时",
			"rawText": "redis内部计时",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "hi0MNrOpDoIvPw3u9VAt2",
			"originalText": "redis内部计时",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "rectangle",
			"version": 579,
			"versionNonce": 976971316,
			"isDeleted": false,
			"id": "HtYOoSu7LvhAB_ty41vr2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 856.1894125886815,
			"y": 3051.563214237929,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 415.55555555555543,
			"height": 142.22222222222217,
			"seed": 1636056062,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "p9Oj2W1Y"
				},
				{
					"id": "0HlMuDPBZEl8cqVtS3fOs",
					"type": "arrow"
				}
			],
			"updated": 1705245919670,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 563,
			"versionNonce": 534282164,
			"isDeleted": false,
			"id": "p9Oj2W1Y",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 955.9671445900921,
			"y": 3100.1743253490404,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 216.00009155273438,
			"height": 45,
			"seed": 1429438690,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705245919670,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "消息处理队列",
			"rawText": "消息处理队列",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "HtYOoSu7LvhAB_ty41vr2",
			"originalText": "消息处理队列",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "rectangle",
			"version": 249,
			"versionNonce": 1054548660,
			"isDeleted": false,
			"id": "If8CggFJBgEtZtUDgPgak",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -154.92169852243023,
			"y": 3320.452103126819,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 386.6666666666665,
			"height": 140,
			"seed": 2019712546,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ZQJv1uKN"
				},
				{
					"id": "BDWowD5Sud80WLwulHX5e",
					"type": "arrow"
				},
				{
					"id": "CmspVqgNSOAVrUWdee6-p",
					"type": "arrow"
				}
			],
			"updated": 1705245919670,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 257,
			"versionNonce": 1649191988,
			"isDeleted": false,
			"id": "ZQJv1uKN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -69.58841096546416,
			"y": 3367.952103126819,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 216.00009155273438,
			"height": 45,
			"seed": 276919074,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705245919670,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "设置计时任务",
			"rawText": "设置计时任务",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "If8CggFJBgEtZtUDgPgak",
			"originalText": "设置计时任务",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "arrow",
			"version": 744,
			"versionNonce": 2067066252,
			"isDeleted": false,
			"id": "BDWowD5Sud80WLwulHX5e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 249.8780554738015,
			"y": 3312.0146186735947,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 88.53357933710242,
			"height": 138.8988923909892,
			"seed": 2128959678,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245919716,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "If8CggFJBgEtZtUDgPgak",
				"focus": 0.6785878728321804,
				"gap": 18.133087329565228
			},
			"endBinding": {
				"elementId": "hEkMRykB27cJv6TczVW02",
				"focus": 0.712656784492587,
				"gap": 8.888888888888232
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					88.53357933710242,
					-138.8988923909892
				]
			]
		},
		{
			"type": "arrow",
			"version": 795,
			"versionNonce": 992475788,
			"isDeleted": false,
			"id": "CmspVqgNSOAVrUWdee6-p",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 241.93879843836305,
			"y": 3477.6592476875703,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 78.44784497175056,
			"height": 132.42680923778153,
			"seed": 1769128574,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245919716,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "If8CggFJBgEtZtUDgPgak",
				"focus": -0.6467912537398525,
				"gap": 17.207144560751203
			},
			"endBinding": {
				"elementId": "hi0MNrOpDoIvPw3u9VAt2",
				"focus": -0.6800888642043778,
				"gap": 15.802769178567587
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					78.44784497175056,
					132.42680923778153
				]
			]
		},
		{
			"type": "rectangle",
			"version": 551,
			"versionNonce": 1482066868,
			"isDeleted": false,
			"id": "WSFHYVmFS-CLSSSMw1MHX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 349.522745922015,
			"y": 3322.6743253490395,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 326.66666666666674,
			"height": 131.11111111111086,
			"seed": 1327246206,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "8QcLNl4X"
				},
				{
					"id": "GHLLY-TD5706TZjRozLB_",
					"type": "arrow"
				},
				{
					"id": "0P43AHGeNenSTXzr9QFlX",
					"type": "arrow"
				}
			],
			"updated": 1705245919670,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 544,
			"versionNonce": 1785918772,
			"isDeleted": false,
			"id": "8QcLNl4X",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 440.85613418698904,
			"y": 3365.729880904595,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 143.99989013671876,
			"height": 45,
			"seed": 147312034,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1705245919670,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "系统启动",
			"rawText": "系统启动",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "WSFHYVmFS-CLSSSMw1MHX",
			"originalText": "系统启动",
			"lineHeight": 1.25,
			"baseline": 32
		},
		{
			"type": "arrow",
			"version": 544,
			"versionNonce": 2038155148,
			"isDeleted": false,
			"id": "GHLLY-TD5706TZjRozLB_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 526.7654544056415,
			"y": 3600.4521031268187,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.4200072126330383,
			"height": 131.1111111111113,
			"seed": 619344738,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245919716,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hi0MNrOpDoIvPw3u9VAt2",
				"focus": 0.06370643849590699,
				"gap": 17.777777777778965
			},
			"endBinding": {
				"elementId": "WSFHYVmFS-CLSSSMw1MHX",
				"focus": -0.07077939961443189,
				"gap": 15.555555555556793
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-1.4200072126330383,
					-131.1111111111113
				]
			]
		},
		{
			"type": "arrow",
			"version": 349,
			"versionNonce": 620778636,
			"isDeleted": false,
			"id": "0P43AHGeNenSTXzr9QFlX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 513.047533775038,
			"y": 3307.1187697934847,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.29217971318570335,
			"height": 93.33333333333258,
			"seed": 323458174,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245919716,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WSFHYVmFS-CLSSSMw1MHX",
				"focus": 0.0027233492696339587,
				"gap": 15.555555555554974
			},
			"endBinding": {
				"elementId": "hEkMRykB27cJv6TczVW02",
				"focus": 0.08221527287399871,
				"gap": 17.77777777777669
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-0.29217971318570335,
					-93.33333333333258
				]
			]
		},
		{
			"type": "arrow",
			"version": 157,
			"versionNonce": 948281740,
			"isDeleted": false,
			"id": "0HlMuDPBZEl8cqVtS3fOs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 727.3005236997928,
			"y": 3120.7046359643073,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 115.55555555555563,
			"height": 1.665647375341905,
			"seed": 971946338,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1705245919716,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hEkMRykB27cJv6TczVW02",
				"focus": -0.13005785823685623,
				"gap": 20.000000000000682
			},
			"endBinding": {
				"elementId": "HtYOoSu7LvhAB_ty41vr2",
				"focus": -0.038905180840664653,
				"gap": 13.333333333333144
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					115.55555555555563,
					1.665647375341905
				]
			]
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "#a5d8ff",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 36,
		"currentItemTextAlign": "center",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 2640.6473591780195,
		"scrollY": 213.54707447845885,
		"zoom": {
			"value": 0.2
		},
		"currentItemRoundness": "round",
		"gridSize": null,
		"gridColor": {
			"Bold": "#C9C9C9FF",
			"Regular": "#EDEDEDFF"
		},
		"currentStrokeOptions": null,
		"previousGridSize": null,
		"frameRendering": {
			"enabled": true,
			"clip": true,
			"name": true,
			"outline": true
		}
	},
	"files": {}
}
```
%%