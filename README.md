# CSGO和DOTA2的处刑BOT

## 介绍
在群友打完一把游戏后, bot会向群里更新这局比赛的数据

DOTA2的数据来自于V社的官方API, 每日请求数限制100,000次

CSGO的数据则来自于[完美官方APP](https://pvp.wanmei.com/appdownload-dota2/index.html)

YYGQ的文来自于[dota2_watcher](https://github.com/unilink233/dota2_watcher)

有任何建议可以发issue, 随缘更新

**一键脚本目前仅支持Linux 64**

## 安装指南

- 修改config.json来配置bot的QQ账号密码, 以及名单

- `chmod +x go.sh`

- `bash go.sh` 

- 走过路过点个star吧

## 后续计划

- [ ] 搞个一键安装, 方便部署

- [ ] 丰富YYGQ内容(大家可以直接提交, 我会合并分支)

- [ ] 更详细的CSGO数据

## 运行效果

### CSGO:

![CSGO](./running_image/IMG_0079.PNG)

### DOTA2:

![DOTA2](./running_image/IMG_0080.png)

## 免责声明

由于CSGO的数据来源于完美非公开的API, 所以如果完美方面不允许调用此API的话请发送邮件到`1nv0k3r@protonmail.com`来联系我删除CSGO功能