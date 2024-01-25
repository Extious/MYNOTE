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
valid+last+period+content ^lxrNQncQ

robotChan ^kRfoHJgg

chan-> ^4K9oyUIK

->chan ^szgQlYIA

TimeExitChan ^dvpEJSaS

gid ^F4ialOll

<-timereminder.Timer.C ^YXmxPUwk

golang内部计时 ^6ufSqLOl

redis内部计时 ^aVTNnERF

消息处理队列 ^p9Oj2W1Y

设置计时任务 ^ZQJv1uKN

系统启动 ^8QcLNl4X

计算duration ^NoBhjfcZ

timereminderChan ^UaU3LfYW

存入redis（TTL=duration） ^Fv1w5mlO

type TimeReminder struct {
	Uid     int64
	Gid     int64
	Content string
	Timer   time.Timer
} ^N0axy4SH

设置timereminder ^5qN6Dugz

redis
uid+gid+last+period+content ^W9bUYBjO

chan-> ^K0gxHp8n

->chan ^wNxwSAJd

TimeExitChan ^PQyYGg9e

gid ^0OKpZTbn

<-timereminder.Timer.C ^aCHRf50a

系统启动 ^8VE3UR0Q

加载已存在timereminder ^GUHDjCMu

robotChan ^bpKLbm73

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
			"version": 190,
			"versionNonce": 698922661,
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
			"updated": 1706012340543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 154,
			"versionNonce": 727659051,
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
			"updated": 1706012340543,
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
			"version": 2135,
			"versionNonce": 587504133,
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
			"updated": 1706012340543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2058,
			"versionNonce": 1890432203,
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
			"updated": 1706012340543,
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
			"version": 1694,
			"versionNonce": 30216549,
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
			"updated": 1706012340543,
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
			"version": 20,
			"versionNonce": 441639787,
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
			"updated": 1706012340543,
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
			"version": 2949,
			"versionNonce": 323984581,
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
			"updated": 1706012340543,
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
			"version": 42,
			"versionNonce": 1083784715,
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
			"updated": 1706012340543,
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
			"version": 170,
			"versionNonce": 522828837,
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
			"updated": 1706012340543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 155,
			"versionNonce": 242959531,
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
			"updated": 1706012340543,
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
			"version": 414,
			"versionNonce": 491319173,
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
			"updated": 1706012340543,
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
			"version": 387,
			"versionNonce": 1805875019,
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
			"updated": 1706012340543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 433,
			"versionNonce": 736802533,
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
			"updated": 1706012340543,
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
			"version": 1094,
			"versionNonce": 1718375915,
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
			"updated": 1706012340543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1102,
			"versionNonce": 1167888965,
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
			"updated": 1706012340543,
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
			"version": 1415,
			"versionNonce": 1574985867,
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
			"updated": 1706012340543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1436,
			"versionNonce": 926679461,
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
			"updated": 1706012340543,
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
			"version": 1300,
			"versionNonce": 1807357739,
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
			"updated": 1706012340543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1269,
			"versionNonce": 1442219269,
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
			"updated": 1706012340543,
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
			"version": 3817,
			"versionNonce": 241433035,
			"isDeleted": false,
			"id": "fNqRRe7ouMqZnTuT-W_yi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 928.1116906555987,
			"y": -162.71757480491658,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 3.7626791382489273,
			"height": 85.66876484468963,
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
			"updated": 1706012340543,
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
					3.7626791382489273,
					85.66876484468963
				]
			]
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 1967758437,
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
			"updated": 1706012340543,
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
			"version": 3653,
			"versionNonce": 318277739,
			"isDeleted": false,
			"id": "aaHgKsgWwgqFO5hS7IFT9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 935.8738706325244,
			"y": 34.694465614782736,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.8172872119668,
			"height": 85.43659177448853,
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
			"updated": 1706012340543,
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
					1.8172872119668,
					85.43659177448853
				]
			]
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 486721477,
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
			"updated": 1706012340543,
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
			"version": 2325,
			"versionNonce": 1061307147,
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
			"updated": 1706012340543,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2264,
			"versionNonce": 2134869797,
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
			"updated": 1706012340543,
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
			"version": 5378,
			"versionNonce": 1002154411,
			"isDeleted": false,
			"id": "JO0PAhTS9fARUH6Z4Dshn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1010.4716139665446,
			"y": -222.51251550357946,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.81636310975102,
			"height": 3.401021786799646,
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
			"updated": 1706012340543,
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
					84.81636310975102,
					3.401021786799646
				]
			]
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 778918533,
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
			"updated": 1706012340543,
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
			"version": 4088,
			"versionNonce": 1032797259,
			"isDeleted": false,
			"id": "1ZT3iGpmyYvDTiFN4rGg4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1015.9176913948342,
			"y": -18.0277638570062,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 89.1747121922075,
			"height": 1.0755490975229698,
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
			"updated": 1706012340544,
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
					89.1747121922075,
					1.0755490975229698
				]
			]
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 323600869,
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
			"updated": 1706012340544,
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
			"version": 2831,
			"versionNonce": 1888975595,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2788,
			"versionNonce": 585252165,
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
			"updated": 1706012340544,
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
			"version": 1356,
			"versionNonce": 559867275,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1329,
			"versionNonce": 1419005093,
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
			"updated": 1706012340544,
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
			"version": 1390,
			"versionNonce": 656407595,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1423,
			"versionNonce": 1477275653,
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
			"updated": 1706012340544,
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
			"version": 3762,
			"versionNonce": 231030475,
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
			"updated": 1706012340544,
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
			"version": 3955,
			"versionNonce": 189474661,
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
			"updated": 1706012340544,
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
			"version": 2951,
			"versionNonce": 2145987947,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2928,
			"versionNonce": 815461061,
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
			"updated": 1706012340544,
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
			"version": 3936,
			"versionNonce": 1893091339,
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
			"updated": 1706012340544,
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
			"version": 1774,
			"versionNonce": 1687835173,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1706,
			"versionNonce": 109514411,
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
			"updated": 1706012340544,
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
			"version": 1149,
			"versionNonce": 1412875653,
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
			"updated": 1706012340544,
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
			"version": 2952,
			"versionNonce": 1134952779,
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
			"updated": 1706012340544,
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
			"version": 708,
			"versionNonce": 850250981,
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
			"updated": 1706012340544,
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
			"version": 1093,
			"versionNonce": 1905106923,
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
			"updated": 1706012340544,
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
			"version": 1538,
			"versionNonce": 1871505477,
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
			"updated": 1706012340544,
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
			"version": 636,
			"versionNonce": 1246259851,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 270,
			"versionNonce": 749836197,
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
			"updated": 1706012340544,
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
			"version": 1490,
			"versionNonce": 1653661995,
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
			"updated": 1706012340544,
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
			"version": 3148,
			"versionNonce": 1950964485,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 3133,
			"versionNonce": 1406239691,
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
			"updated": 1706012340544,
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
			"version": 204,
			"versionNonce": 785494629,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 639947371,
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
			"updated": 1706012340544,
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
			"version": 2181,
			"versionNonce": 1494752709,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2105,
			"versionNonce": 2052410635,
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
			"updated": 1706012340544,
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
			"version": 1968,
			"versionNonce": 2050628901,
			"isDeleted": false,
			"id": "spc76493MoKsZZs_cK9VV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -443.7804523908118,
			"y": 1150.8400636384038,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 388.46576041024014,
			"height": 11.493272378165102,
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
			"updated": 1706012340544,
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
					388.46576041024014,
					-11.493272378165102
				]
			]
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 1943892907,
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
			"updated": 1706012340544,
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
			"version": 3008,
			"versionNonce": 1503998085,
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
			"updated": 1706012340544,
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
			"version": 49,
			"versionNonce": 1659356747,
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
			"updated": 1706012340544,
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
			"version": 185,
			"versionNonce": 1964431333,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 169,
			"versionNonce": 776914155,
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
			"updated": 1706012340544,
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
			"version": 472,
			"versionNonce": 916230981,
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
			"updated": 1706012340544,
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
			"version": 458,
			"versionNonce": 2107436939,
			"isDeleted": false,
			"id": "5K6fIMRkL-w1EixRfMsP3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -36.66646270869137,
			"y": 994.0680100640932,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 499,
			"versionNonce": 1788076709,
			"isDeleted": false,
			"id": "lxrNQncQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 30.096197251533795,
			"y": 1095.6803239002215,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 265.1051025390625,
			"height": 105,
			"seed": 1441784419,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340544,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "redis\nvalid+last+period+c\nontent",
			"rawText": "redis\nvalid+last+period+content",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "5K6fIMRkL-w1EixRfMsP3",
			"originalText": "redis\nvalid+last+period+content",
			"lineHeight": 1.25,
			"baseline": 95
		},
		{
			"type": "rectangle",
			"version": 2574,
			"versionNonce": 588039723,
			"isDeleted": false,
			"id": "eQ8SeyH1oN8O6ioKqZtLX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1166.905959740253,
			"y": 1569.236211566308,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 217.25905928272718,
			"height": 56.46153846153855,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2510,
			"versionNonce": 1974093317,
			"isDeleted": false,
			"id": "kRfoHJgg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1226.7055409563236,
			"y": 1584.9669807970772,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 97.65989685058594,
			"height": 25,
			"seed": 2091836835,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340544,
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
			"version": 1632,
			"versionNonce": 1166592203,
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
				}
			],
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1656,
			"versionNonce": 1256013157,
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
			"updated": 1706012340544,
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
			"version": 4527,
			"versionNonce": 1252751211,
			"isDeleted": false,
			"id": "v6p9hzr0plFynvzdLzEor",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1027.0253678128036,
			"y": 1604.226663956215,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 127.73365790894786,
			"height": 0.3597220897727311,
			"seed": 1738998915,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340544,
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
					127.73365790894786,
					0.3597220897727311
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1788,
			"versionNonce": 561662149,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1720,
			"versionNonce": 12538379,
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
			"updated": 1706012340544,
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
			"version": 1315,
			"versionNonce": 1797187621,
			"isDeleted": false,
			"id": "XkmQ68b-Gd9jfuUxNW0lH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -315.1012090874466,
			"y": 1601.4952609016186,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 77.995990664587,
			"height": 0.19880008748623368,
			"seed": 720179043,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340544,
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
					-0.19880008748623368
				]
			]
		},
		{
			"type": "arrow",
			"version": 3636,
			"versionNonce": 146725035,
			"isDeleted": false,
			"id": "5ufcECcucHh7PP1EyXMfF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 294.5309957017841,
			"y": 1603.1280569653718,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.9173561828448,
			"height": 3.9001530192053906,
			"seed": 1039870723,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340544,
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
					132.9173561828448,
					-3.9001530192053906
				]
			]
		},
		{
			"type": "arrow",
			"version": 2193,
			"versionNonce": 163093381,
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
			"updated": 1706012340544,
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
			"version": 2421,
			"versionNonce": 5540683,
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
			"updated": 1706012340544,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2373,
			"versionNonce": 1166336741,
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
			"updated": 1706012340545,
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
			"version": 808,
			"versionNonce": 1809508843,
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
			"updated": 1706012340545,
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
			"version": 184,
			"versionNonce": 51461701,
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
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 160,
			"versionNonce": 1616671883,
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
			"updated": 1706012340545,
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
			"version": 522,
			"versionNonce": 960179621,
			"isDeleted": false,
			"id": "e85QAFcM0fK0Ut209rSY_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -380.16842855268777,
			"y": 1866.1012783283513,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 141.5583370053228,
			"height": 0.45749593784194076,
			"seed": 389381443,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340545,
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
					141.5583370053228,
					-0.45749593784194076
				]
			]
		},
		{
			"type": "arrow",
			"version": 440,
			"versionNonce": 1838394155,
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
			"updated": 1706012340545,
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
			"version": 1662,
			"versionNonce": 657469701,
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
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1719,
			"versionNonce": 1206586827,
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
			"updated": 1706012340545,
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
			"version": 262,
			"versionNonce": 1648931621,
			"isDeleted": false,
			"id": "hEkMRykB27cJv6TczVW02",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 413.01480941407794,
			"y": 4101.08702376174,
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
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 277,
			"versionNonce": 1244347819,
			"isDeleted": false,
			"id": "6ufSqLOl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 467.86075667970294,
			"y": 4147.475912650629,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 250.30810546875,
			"height": 45,
			"seed": 388560382,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
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
			"version": 378,
			"versionNonce": 795936389,
			"isDeleted": false,
			"id": "hi0MNrOpDoIvPw3u9VAt2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 401.903698302967,
			"y": 4661.08702376174,
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
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 398,
			"versionNonce": 15487051,
			"isDeleted": false,
			"id": "aVTNnERF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 468.35965380833807,
			"y": 4707.475912650629,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 227.0880889892578,
			"height": 45,
			"seed": 1082348898,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
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
			"version": 613,
			"versionNonce": 251129317,
			"isDeleted": false,
			"id": "HtYOoSu7LvhAB_ty41vr2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 921.9036983029673,
			"y": 4094.420357095071,
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
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 597,
			"versionNonce": 1865551595,
			"isDeleted": false,
			"id": "p9Oj2W1Y",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1021.6814303043778,
			"y": 4143.031468206182,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 216.00009155273438,
			"height": 45,
			"seed": 1429438690,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
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
			"version": 281,
			"versionNonce": 1609230661,
			"isDeleted": false,
			"id": "If8CggFJBgEtZtUDgPgak",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -89.20741280814445,
			"y": 4363.309245983961,
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
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 289,
			"versionNonce": 394721675,
			"isDeleted": false,
			"id": "ZQJv1uKN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -3.874125251178384,
			"y": 4410.809245983961,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 216.00009155273438,
			"height": 45,
			"seed": 276919074,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
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
			"version": 844,
			"versionNonce": 1135048869,
			"isDeleted": false,
			"id": "BDWowD5Sud80WLwulHX5e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 313.547495531771,
			"y": 4358.079886616151,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 90.57842499341871,
			"height": 142.1070174764036,
			"seed": 2128959678,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "If8CggFJBgEtZtUDgPgak",
				"gap": 16.916788097465883,
				"focus": 0.6785878728321825
			},
			"endBinding": {
				"elementId": "hEkMRykB27cJv6TczVW02",
				"gap": 8.888888888888232,
				"focus": 0.7126567844925873
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
					90.57842499341871,
					-142.1070174764036
				]
			]
		},
		{
			"type": "arrow",
			"version": 895,
			"versionNonce": 1193644075,
			"isDeleted": false,
			"id": "CmspVqgNSOAVrUWdee6-p",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 305.0049642756842,
			"y": 4516.046133064576,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 83.10879037623181,
			"height": 140.2948918877155,
			"seed": 1769128574,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "If8CggFJBgEtZtUDgPgak",
				"gap": 14.80425743507567,
				"focus": -0.6467912537398525
			},
			"endBinding": {
				"elementId": "hi0MNrOpDoIvPw3u9VAt2",
				"gap": 14.583794108476809,
				"focus": -0.6800888642043781
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
					83.10879037623181,
					140.2948918877155
				]
			]
		},
		{
			"type": "rectangle",
			"version": 583,
			"versionNonce": 1406868485,
			"isDeleted": false,
			"id": "WSFHYVmFS-CLSSSMw1MHX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 415.2370316363008,
			"y": 4365.531468206182,
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
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 576,
			"versionNonce": 1073238731,
			"isDeleted": false,
			"id": "8QcLNl4X",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 506.5704199012748,
			"y": 4408.587023761737,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 143.99989013671876,
			"height": 45,
			"seed": 147312034,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
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
			"version": 644,
			"versionNonce": 411259749,
			"isDeleted": false,
			"id": "GHLLY-TD5706TZjRozLB_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 592.4797401199273,
			"y": 4643.30924598396,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1.4200072126329815,
			"height": 131.1111111111104,
			"seed": 619344738,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hi0MNrOpDoIvPw3u9VAt2",
				"gap": 17.777777777779193,
				"focus": 0.06370643849590699
			},
			"endBinding": {
				"elementId": "WSFHYVmFS-CLSSSMw1MHX",
				"gap": 15.555555555556566,
				"focus": -0.07077939961443189
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
					-1.4200072126329815,
					-131.1111111111104
				]
			]
		},
		{
			"type": "arrow",
			"version": 449,
			"versionNonce": 580501867,
			"isDeleted": false,
			"id": "0P43AHGeNenSTXzr9QFlX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 578.7618194893237,
			"y": 4349.975912650627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.2921797131855328,
			"height": 93.33333333333212,
			"seed": 323458174,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "WSFHYVmFS-CLSSSMw1MHX",
				"gap": 15.555555555554747,
				"focus": 0.0027233492696326685
			},
			"endBinding": {
				"elementId": "hEkMRykB27cJv6TczVW02",
				"gap": 17.777777777777374,
				"focus": 0.08221527287399819
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
					-0.2921797131855328,
					-93.33333333333212
				]
			]
		},
		{
			"type": "arrow",
			"version": 257,
			"versionNonce": 1038982853,
			"isDeleted": false,
			"id": "0HlMuDPBZEl8cqVtS3fOs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 793.0148094140786,
			"y": 4163.5617788214495,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 115.55555555555566,
			"height": 1.665647375341905,
			"seed": 971946338,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "hEkMRykB27cJv6TczVW02",
				"gap": 20.000000000000682,
				"focus": -0.13005785823685623
			},
			"endBinding": {
				"elementId": "HtYOoSu7LvhAB_ty41vr2",
				"gap": 13.333333333333087,
				"focus": -0.038905180840676915
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
					115.55555555555566,
					1.665647375341905
				]
			]
		},
		{
			"type": "rectangle",
			"version": 206,
			"versionNonce": 408181771,
			"isDeleted": false,
			"id": "4FLtLhdFMrjnh-7k13yl7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -500.1223504824486,
			"y": 2196.158674893979,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 141.5,
			"height": 80,
			"seed": 1896295813,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "3uVJLHbqIyNdWXiC4ax-q"
				},
				{
					"id": "WqLmBNnbjk9Fk4A73zjro",
					"type": "arrow"
				},
				{
					"id": "MAcozGdgN0gfaVq_teK1b",
					"type": "arrow"
				},
				{
					"id": "AWJNwHx-QMelsBRexxuQ5",
					"type": "arrow"
				}
			],
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 170,
			"versionNonce": 179797541,
			"isDeleted": false,
			"id": "NoBhjfcZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -489.7622888369408,
			"y": 2223.658674893979,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 120.77987670898438,
			"height": 25,
			"seed": 691090661,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "计算duration",
			"rawText": "计算duration",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "4FLtLhdFMrjnh-7k13yl7",
			"originalText": "计算duration",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 2183,
			"versionNonce": 1025680043,
			"isDeleted": false,
			"id": "GR1qjoOpq9nlr2PKsLKAo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -130.5743782951265,
			"y": 2657.915362044613,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 516.5741232976739,
			"height": 58,
			"seed": 291721285,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "hx0gfgyS10t6vARDx9tD2"
				},
				{
					"id": "MAcozGdgN0gfaVq_teK1b",
					"type": "arrow"
				},
				{
					"id": "0nofsBDmFUbls7s-85Usk",
					"type": "arrow"
				},
				{
					"id": "lT60LpFbdmaT8eXiEigh9",
					"type": "arrow"
				}
			],
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2107,
			"versionNonce": 365851013,
			"isDeleted": false,
			"id": "UaU3LfYW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 46.932768497753386,
			"y": 2674.415362044613,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 161.55982971191406,
			"height": 25,
			"seed": 393936805,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "timereminderChan",
			"rawText": "timereminderChan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "GR1qjoOpq9nlr2PKsLKAo",
			"originalText": "timereminderChan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1972,
			"versionNonce": 1236211019,
			"isDeleted": false,
			"id": "WqLmBNnbjk9Fk4A73zjro",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -346.2729070829338,
			"y": 2245.192902460011,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 388.46576041024014,
			"height": 11.49327237816533,
			"seed": 296076037,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Fv1w5mlO"
				}
			],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "4FLtLhdFMrjnh-7k13yl7",
				"gap": 12.349443399514826,
				"focus": 0.27303283020532004
			},
			"endBinding": {
				"elementId": "6jP8Sk1UJNxx-ufcCf3Vp",
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
					388.46576041024014,
					-11.49327237816533
				]
			]
		},
		{
			"type": "text",
			"version": 26,
			"versionNonce": 1013971173,
			"isDeleted": false,
			"id": "Fv1w5mlO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -283.74989626257934,
			"y": 2226.9462662709357,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 263.41973876953125,
			"height": 25,
			"seed": 878778981,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "存入redis（TTL=duration）",
			"rawText": "存入redis（TTL=duration）",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "WqLmBNnbjk9Fk4A73zjro",
			"originalText": "存入redis（TTL=duration）",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 3010,
			"versionNonce": 2102670315,
			"isDeleted": false,
			"id": "MAcozGdgN0gfaVq_teK1b",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -455.5181594513313,
			"y": 2289.1430152491544,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.898849287749726,
			"height": 374.34184458831805,
			"seed": 1215989189,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "N0axy4SH"
				}
			],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "4FLtLhdFMrjnh-7k13yl7",
				"gap": 12.984340355175163,
				"focus": 0.383620128033327
			},
			"endBinding": {
				"elementId": "TnV_7ww_X8agYS-uNFqLG",
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
					9.898849287749726,
					374.34184458831805
				]
			]
		},
		{
			"type": "text",
			"version": 52,
			"versionNonce": 1479119941,
			"isDeleted": false,
			"id": "N0axy4SH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -530.2562348074566,
			"y": 2399.5139375433127,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 159.375,
			"height": 153.6,
			"seed": 554665253,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "type TimeReminder\nstruct {\nUid     int64\nGid     int64\nContent string\nTimer\ntime.Timer\n}",
			"rawText": "type TimeReminder struct {\n\tUid     int64\n\tGid     int64\n\tContent string\n\tTimer   time.Timer\n}",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "MAcozGdgN0gfaVq_teK1b",
			"originalText": "type TimeReminder struct {\n\tUid     int64\n\tGid     int64\n\tContent string\n\tTimer   time.Timer\n}",
			"lineHeight": 1.2,
			"baseline": 149
		},
		{
			"type": "rectangle",
			"version": 187,
			"versionNonce": 1209826955,
			"isDeleted": false,
			"id": "YFKHMRNxVu_R2Et9atePO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -784.7112501517868,
			"y": 2201.351906533638,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 188.734542414958,
			"height": 80,
			"seed": 1368234117,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "04DSXN37q7dHzNzEfUVWa"
				},
				{
					"id": "AWJNwHx-QMelsBRexxuQ5",
					"type": "arrow"
				},
				{
					"id": "NHzzhha2IQBqcpXCpSdGJ",
					"type": "arrow"
				}
			],
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 171,
			"versionNonce": 886621093,
			"isDeleted": false,
			"id": "5qN6Dugz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -768.4039002089562,
			"y": 2228.851906533638,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 156.11984252929688,
			"height": 25,
			"seed": 598884325,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "设置timereminder",
			"rawText": "设置timereminder",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "YFKHMRNxVu_R2Et9atePO",
			"originalText": "设置timereminder",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 474,
			"versionNonce": 885159211,
			"isDeleted": false,
			"id": "AWJNwHx-QMelsBRexxuQ5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -588.5126297882147,
			"y": 2234.773024935542,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.28055690972155,
			"height": 2.6609846283781735,
			"seed": 1300953925,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YFKHMRNxVu_R2Et9atePO",
				"gap": 7.46407794861409,
				"focus": -0.23158157086608447
			},
			"endBinding": {
				"elementId": "4FLtLhdFMrjnh-7k13yl7",
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
			"version": 459,
			"versionNonce": 1185613573,
			"isDeleted": false,
			"id": "6jP8Sk1UJNxx-ufcCf3Vp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 60.84108259918662,
			"y": 2088.4208488857003,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 398.2011701465724,
			"height": 308.0461474586813,
			"seed": 1735740069,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"id": "WqLmBNnbjk9Fk4A73zjro",
					"type": "arrow"
				},
				{
					"type": "text",
					"id": "W9bUYBjO"
				}
			],
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 520,
			"versionNonce": 538828389,
			"isDeleted": false,
			"id": "W9bUYBjO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 128.97575183675553,
			"y": 2190.0331627218284,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 262.361083984375,
			"height": 105,
			"seed": 572435973,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "redis\nuid+gid+last+period\n+content",
			"rawText": "redis\nuid+gid+last+period+content",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "6jP8Sk1UJNxx-ufcCf3Vp",
			"originalText": "redis\nuid+gid+last+period+content",
			"lineHeight": 1.25,
			"baseline": 95
		},
		{
			"type": "rectangle",
			"version": 2701,
			"versionNonce": 1610704491,
			"isDeleted": false,
			"id": "dJPDQJ48EA7ve2l9ecLw7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1270.567351201977,
			"y": 2662.0505888494536,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 240.13085415452196,
			"height": 56.66666666666654,
			"seed": 1015326053,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "gjkT3TUpn6pmhnu_2T8n9",
					"type": "arrow"
				},
				{
					"type": "text",
					"id": "bpKLbm73"
				}
			],
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"id": "bpKLbm73",
			"type": "text",
			"x": 1341.802829853945,
			"y": 2677.883922182787,
			"width": 97.65989685058594,
			"height": 25,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1347218763,
			"version": 5,
			"versionNonce": 2005555621,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1706012345036,
			"link": null,
			"locked": false,
			"text": "robotChan",
			"rawText": "robotChan",
			"fontSize": 20,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 18,
			"containerId": "dJPDQJ48EA7ve2l9ecLw7",
			"originalText": "robotChan",
			"lineHeight": 1.25
		},
		{
			"type": "rectangle",
			"version": 1632,
			"versionNonce": 258689317,
			"isDeleted": false,
			"id": "9Gnhmx-D-QUXA4xjFw2KV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 534.7695654076563,
			"y": 2671.772607407899,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 222.00336269151842,
			"height": 53.71049097375453,
			"seed": 1477201957,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "YS-k7FjgzGR2n2XVFpv2w"
				},
				{
					"id": "lT60LpFbdmaT8eXiEigh9",
					"type": "arrow"
				},
				{
					"id": "-r1ZKja_ZqcE3inu5Eiu4",
					"type": "arrow"
				},
				{
					"id": "R43n25zez_Ctkop802XRy",
					"type": "arrow"
				},
				{
					"id": "8AIi_QXkwKiYWTTkGqQGV",
					"type": "arrow"
				}
			],
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1658,
			"versionNonce": 1722091435,
			"isDeleted": false,
			"id": "K0gxHp8n",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 621.5631931645482,
			"y": 2688.6278528947764,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.416107177734375,
			"height": 20,
			"seed": 1152975749,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "chan->",
			"rawText": "chan->",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "9Gnhmx-D-QUXA4xjFw2KV",
			"originalText": "chan->",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "arrow",
			"version": 4807,
			"versionNonce": 131128453,
			"isDeleted": false,
			"id": "gjkT3TUpn6pmhnu_2T8n9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1124.5329131206815,
			"y": 2698.1011480000893,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 133.88750406279405,
			"height": 0.13990215293142683,
			"seed": 339233509,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "ga6g1r9czbTd-XZdC-Jxx",
				"gap": 8.55423466420524,
				"focus": 0.11359822259354531
			},
			"endBinding": {
				"elementId": "dJPDQJ48EA7ve2l9ecLw7",
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
					133.88750406279405,
					-0.13990215293142683
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1790,
			"versionNonce": 1067244107,
			"isDeleted": false,
			"id": "TnV_7ww_X8agYS-uNFqLG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -455.04328906970636,
			"y": 2671.555784386743,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 227.10271009845042,
			"height": 58,
			"seed": 1998038597,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "EOyaBeD_PAj8aUpVhrPz6"
				},
				{
					"id": "MAcozGdgN0gfaVq_teK1b",
					"type": "arrow"
				},
				{
					"id": "0nofsBDmFUbls7s-85Usk",
					"type": "arrow"
				}
			],
			"updated": 1706012340546,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1723,
			"versionNonce": 955057125,
			"isDeleted": false,
			"id": "wNxwSAJd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -371.7519056391335,
			"y": 2688.055784386743,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 60.51994323730469,
			"height": 25,
			"seed": 808752549,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "->chan",
			"rawText": "->chan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "TnV_7ww_X8agYS-uNFqLG",
			"originalText": "->chan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 1317,
			"versionNonce": 1531009259,
			"isDeleted": false,
			"id": "0nofsBDmFUbls7s-85Usk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -217.5936637795686,
			"y": 2695.8480997232255,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 77.995990664587,
			"height": 0.19880008748623368,
			"seed": 1253873925,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "TnV_7ww_X8agYS-uNFqLG",
				"gap": 10.346915191687344,
				"focus": -0.14994898525896597
			},
			"endBinding": {
				"elementId": "GR1qjoOpq9nlr2PKsLKAo",
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
					-0.19880008748623368
				]
			]
		},
		{
			"type": "arrow",
			"version": 3638,
			"versionNonce": 1993162565,
			"isDeleted": false,
			"id": "lT60LpFbdmaT8eXiEigh9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 392.0385410096621,
			"y": 2697.480895786979,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 132.9173561828448,
			"height": 3.9001530192058453,
			"seed": 271396965,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "GR1qjoOpq9nlr2PKsLKAo",
				"gap": 6.038796007114684,
				"focus": 0.5008788442819005
			},
			"endBinding": {
				"elementId": "9Gnhmx-D-QUXA4xjFw2KV",
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
					132.9173561828448,
					-3.9001530192058453
				]
			]
		},
		{
			"type": "arrow",
			"version": 2195,
			"versionNonce": 387777419,
			"isDeleted": false,
			"id": "-r1ZKja_ZqcE3inu5Eiu4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 770.0846898213748,
			"y": 2697.4855379055325,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 115.73649036075028,
			"height": 1.5430427434253033,
			"seed": 1045683141,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "9Gnhmx-D-QUXA4xjFw2KV",
				"gap": 13.311761722200202,
				"focus": 0.018178083409795803
			},
			"endBinding": {
				"elementId": "ga6g1r9czbTd-XZdC-Jxx",
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
			"version": 2423,
			"versionNonce": 936316581,
			"isDeleted": false,
			"id": "XkhmZKzm3stK3RfMAaUZZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -130.83715301955203,
			"y": 2934.760725676738,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 516.5741232976739,
			"height": 58,
			"seed": 2102270757,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "3Ih9LvvAFaBrOO3YO4q5F"
				},
				{
					"id": "R43n25zez_Ctkop802XRy",
					"type": "arrow"
				},
				{
					"id": "dEXaJSl-Y4gelAMHWoNQz",
					"type": "arrow"
				}
			],
			"updated": 1706012340546,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 2375,
			"versionNonce": 996825643,
			"isDeleted": false,
			"id": "PQyYGg9e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 62.499980345593485,
			"y": 2951.260725676738,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 129.8998565673828,
			"height": 25,
			"seed": 361328261,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "TimeExitChan",
			"rawText": "TimeExitChan",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "XkhmZKzm3stK3RfMAaUZZ",
			"originalText": "TimeExitChan",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 810,
			"versionNonce": 1251996165,
			"isDeleted": false,
			"id": "R43n25zez_Ctkop802XRy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 390.03453116764,
			"y": 2969.6945664960167,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 135.3935934657502,
			"height": 274.49529305488113,
			"seed": 1707300325,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "XkhmZKzm3stK3RfMAaUZZ",
				"gap": 4.297560889518195,
				"focus": 0.974028065166565
			},
			"endBinding": {
				"elementId": "9Gnhmx-D-QUXA4xjFw2KV",
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
					135.3935934657502,
					-274.49529305488113
				]
			]
		},
		{
			"type": "rectangle",
			"version": 186,
			"versionNonce": 622058699,
			"isDeleted": false,
			"id": "8G3d4M0vNqwZi1s61QvtV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -444.98592263215664,
			"y": 2931.2741396933234,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 155.16364059084617,
			"height": 62.06545623633838,
			"seed": 420041029,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "J4FyLFUUYiuyj77SHOoAa"
				},
				{
					"id": "dEXaJSl-Y4gelAMHWoNQz",
					"type": "arrow"
				},
				{
					"id": "NHzzhha2IQBqcpXCpSdGJ",
					"type": "arrow"
				}
			],
			"updated": 1706012340546,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 162,
			"versionNonce": 1279093093,
			"isDeleted": false,
			"id": "0OKpZTbn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -380.29408646759293,
			"y": 2949.8068678114923,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 25.77996826171875,
			"height": 25,
			"seed": 481878181,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "gid",
			"rawText": "gid",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "8G3d4M0vNqwZi1s61QvtV",
			"originalText": "gid",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 524,
			"versionNonce": 800328555,
			"isDeleted": false,
			"id": "dEXaJSl-Y4gelAMHWoNQz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -282.6608832448097,
			"y": 2960.4541171499573,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 141.55833700532276,
			"height": 0.45749593784194076,
			"seed": 1451197445,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "8G3d4M0vNqwZi1s61QvtV",
				"gap": 7.161398796500748,
				"focus": -0.0504698920988396
			},
			"endBinding": {
				"elementId": "XkhmZKzm3stK3RfMAaUZZ",
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
					-0.45749593784194076
				]
			]
		},
		{
			"type": "arrow",
			"version": 442,
			"versionNonce": 1576334533,
			"isDeleted": false,
			"id": "NHzzhha2IQBqcpXCpSdGJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -693.1289894949389,
			"y": 2293.8919218742194,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 234.0711163043751,
			"height": 674.268611782918,
			"seed": 442153829,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "YFKHMRNxVu_R2Et9atePO",
				"gap": 12.540015340581249,
				"focus": 0.053254144624035424
			},
			"endBinding": {
				"elementId": "8G3d4M0vNqwZi1s61QvtV",
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
					674.268611782918
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1665,
			"versionNonce": 1603626507,
			"isDeleted": false,
			"id": "ga6g1r9czbTd-XZdC-Jxx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 893.9753157649579,
			"y": 2668.301447194842,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 222.00336269151842,
			"height": 53.71049097375453,
			"seed": 1620575941,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "BcmajEHjeq38rWWPKRq1I"
				},
				{
					"id": "-r1ZKja_ZqcE3inu5Eiu4",
					"type": "arrow"
				},
				{
					"id": "gjkT3TUpn6pmhnu_2T8n9",
					"type": "arrow"
				}
			],
			"updated": 1706012340546,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1724,
			"versionNonce": 459543589,
			"isDeleted": false,
			"id": "aCHRf50a",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 919.8008115028069,
			"y": 2685.156692681719,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 170.3523712158203,
			"height": 20,
			"seed": 1003808293,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "<-timereminder.Timer.C",
			"rawText": "<-timereminder.Timer.C",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ga6g1r9czbTd-XZdC-Jxx",
			"originalText": "<-timereminder.Timer.C",
			"lineHeight": 1.25,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 249,
			"versionNonce": 1269984427,
			"isDeleted": false,
			"id": "CghhW-KuKvC1BGkEHgKVg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 503.1759233755249,
			"y": 2104.626786770271,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 301.4285714285713,
			"height": 98.57142857142867,
			"seed": 251582853,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "8VE3UR0Q"
				},
				{
					"id": "8AIi_QXkwKiYWTTkGqQGV",
					"type": "arrow"
				}
			],
			"updated": 1706012340546,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 295,
			"versionNonce": 1350059909,
			"isDeleted": false,
			"id": "8VE3UR0Q",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 613.8902396073887,
			"y": 2141.412501055985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.99993896484375,
			"height": 25,
			"seed": 55795941,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "系统启动",
			"rawText": "系统启动",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "CghhW-KuKvC1BGkEHgKVg",
			"originalText": "系统启动",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 712,
			"versionNonce": 1203085131,
			"isDeleted": false,
			"id": "8AIi_QXkwKiYWTTkGqQGV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 491.7473519469537,
			"y": 2172.921165073257,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 187.1428571428575,
			"height": 491.3484788398705,
			"seed": 1046477893,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "GUHDjCMu"
				}
			],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "CghhW-KuKvC1BGkEHgKVg",
				"gap": 11.428571428571217,
				"focus": 0.9695066976537005
			},
			"endBinding": {
				"elementId": "9Gnhmx-D-QUXA4xjFw2KV",
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
					119.64285714285722,
					491.3484788398705
				]
			]
		},
		{
			"type": "text",
			"version": 98,
			"versionNonce": 1869549285,
			"isDeleted": false,
			"id": "GUHDjCMu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 316.1874535704886,
			"y": 2441.7696439131278,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 216.1197967529297,
			"height": 25,
			"seed": 1476537253,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340546,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "加载已存在timereminder",
			"rawText": "加载已存在timereminder",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "8AIi_QXkwKiYWTTkGqQGV",
			"originalText": "加载已存在timereminder",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 248,
			"versionNonce": 1248708709,
			"isDeleted": true,
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
			"updated": 1706012340545,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 293,
			"versionNonce": 847060075,
			"isDeleted": true,
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
			"updated": 1706012340545,
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
			"version": 712,
			"versionNonce": 348222405,
			"isDeleted": true,
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
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"startBinding": null,
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
			"version": 96,
			"versionNonce": 689198859,
			"isDeleted": true,
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
			"updated": 1706012340545,
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
			"id": "tPzwmqTJ",
			"type": "text",
			"x": 251.15629382894303,
			"y": 2220.0331627218284,
			"width": 18,
			"height": 45,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 2010499621,
			"version": 6,
			"versionNonce": 313563083,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 36,
			"fontFamily": 1,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 32,
			"containerId": "6jP8Sk1UJNxx-ufcCf3Vp",
			"originalText": "",
			"lineHeight": 1.25
		},
		{
			"type": "text",
			"version": 2441,
			"versionNonce": 1937727755,
			"isDeleted": true,
			"id": "JRuuTqZv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.6327859086325,
			"y": 2677.883922182787,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 9.999984741210938,
			"height": 25,
			"seed": 972337349,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1706012340545,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "",
			"rawText": "",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "dJPDQJ48EA7ve2l9ecLw7",
			"originalText": "",
			"lineHeight": 1.25,
			"baseline": 18
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
		"currentItemFontSize": 20,
		"currentItemTextAlign": "center",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": 862.0931024842231,
		"scrollY": -1931.2105350994614,
		"zoom": {
			"value": 0.7500000000000001
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