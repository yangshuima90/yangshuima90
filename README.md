{
	"id": "cenbomintest.app.sub",
	"name": "CenBomin.TestScript",
	"author": "@cenbomin",
	"icon": "https://avatars0.githubusercontent.com/u/75375782?s=400&u=86eee41f7f138c5d0187aa10d2242bfc9799182e&v=4",
	"repo": "https://github.com/CenBoMin/TEST",
	"apps": [{
		"id": "helpbang",
		"name": "互利帮",
		"keys": ["helpbang","helpbangkey"],
		"settings": [
			{
				"id": "helpbang",
				"name": "Cookie数据",
				"val": "",
				"type": "textarea",
				"desc": "JSON 格式"
			}
		],
		"author": "@cenbomin",
		"repo": ["https://raw.githubusercontent.com/CenBoMin/GithubSync"],
		"script": "https://raw.githubusercontent.com/CenBoMin/GithubSync/main/CONGHUA/chonghua.js",
		"icons": ["",
			""
		]
	},{
	  "id": "nioapp",
	  "name": "NIoNio(失效)",
	  "keys": ["fornum", "niocoinbody", "niocoinkey", "nioexpbody", "nioexpkey", "niocoinbody2", "niocoinkey2", "nioexpbody2", "nioexpkey2", "niocoinbody3", "niocoinkey3", "nioexpbody3", "nioexpkey3", "niocoinbody4", "niocoinkey4", "nioexpbody4", "nioexpkey4", "niocoinbody5", "niocoinkey5", "nioexpbody5", "nioexpkey5", "niocoinbody6", "niocoinkey6", "nioexpbody6", "nioexpkey6", "niocoinbody7", "niocoinkey7", "nioexpbody7", "nioexpkey7", "niocoinbody8", "niocoinkey8", "nioexpbody8", "nioexpkey8", "niocoinbody9", "niocoinkey9", "nioexpbody9", "nioexpkey9", "niocoinbody10", "niocoinkey10", "nioexpbody10", "nioexpkey11", "niocoinbody11", "niocoinkey11", "nioexpbody11", "nioexpkey11", "niocoinbody12", "niocoinkey12", "nioexpbody12", "nioexpkey12"],
	  "settings": [
	    {
				"id": "nioSuffix",
				"name": "当前抓取ck账号",
				"val": "1",
				"type": "number",
				"desc": "当前抓取ck记录的账号序号，如：1、2、3、"
			},{
				"id": "nioCount",
				"name": "脚本执行账号个数",
				"val": "1",
				"type": "number",
				"desc": "指定任务最多跑几个账号，根据抓取的账号数据个数来设值"
			},{
				"id": "fornum",
				"name": "脚本执行循环次数",
				"val": "120",
				"type": "number",
				"desc": "指定任务每次跑几次,初始次数120"
			}
	  ],
	  "author": "@cenbomin",
	  "repo": ["https://raw.githubusercontent.com/CenBoMin/nio"],
	  "script": "https://raw.githubusercontent.com/CenBoMin/GithubSync/main/nio.js",
	  "icons": ["", ""
	  ]
	}]
}
