# CSGO和DOTA2的处刑BOT

## 介绍
在群友打完一把游戏后, bot会向群里更新这局比赛的数据

DOTA2的数据来自于V社的官方API, 每日请求数限制100,000次

CSGO的数据则来自于[完美官方APP](https://pvp.wanmei.com/appdownload-dota2/index.html)

YYGQ的文来自于[dota2_watcher](https://github.com/unilink233/dota2_watcher)

有任何建议可以发issue, 随缘更新

**Windows下可以按照安装指南下载Windows版本的MiraiOK**

**我这两天找了一下没有合适的免费开源微信机器人, 所以可能不会有微信版本**

## 一键脚本

- 修改`config.json`来配置bot

- `chmod +x go.sh`

- `bash go.sh`


## 安装指南

- 下载对应版本的[miraiOK](https://github.com/LXY1226/MiraiOK), 有hxd说下不动, 我传了个Linux64版本的[度盘](https://pan.baidu.com/s/1bLYwWWHCcgmnLHoofXTHxQ) 提取码: 5trx 

- 运行一下miraiOK, 然后关闭, 会自动生成一个`plugins`文件夹

- 把[mirai-http-api](https://github.com/project-mirai/mirai-api-http)里的release的jar扔进plugins文件夹

- 通过`screen -S bot && ./miraiOK_linux-amd64`启动miraiOK, 登陆你的BOT账号, 这一步可能有一些登陆上的问题, 可以自行`screen -r bot`上去查看

- 在[这里](http://steamcommunity.com/dev/apikey)申请你的steam API key, 修改`config.json`中的`api_key`

- 安装requests模块: `pip install requests`

- 修改config.json来配置bot

- 通过screen来后台运行: `screen -S dota_bot`, Windows可以直接运行miraiok

- 运行`run.py`脚本来启动BOT: `python3 run.py`

## 后续计划

- [x] 搞个一键安装, 方便部署

- [ ] 丰富YYGQ内容(大家可以直接提交, 我会合并分支)

- [ ] 更详细的CSGO数据

## 运行效果

### CSGO:

![CSGO](./running_image/IMG_0079.PNG)

### DOTA2:

![DOTA2](./running_image/IMG_0080.png)

## 免责声明

由于CSGO的数据来源于完美非公开的API, 所以如果完美方面不允许调用此API的话请发送邮件到`1nv0k3r@protonmail.com`来联系我删除CSGO功能