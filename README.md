# V2Ray for Docker

## 概述

用于部署 V2Ray Websocket 容器的镜像。

## 镜像

 - DockerHub 的镜像：`billin9/docker-v2ray`。
 
## ENV 设定

### CONFIG_JSON

`CONFIG_JSON` > `服务端 Websocket 配置文件`。

## 注意

V2Ray 将在部署时自动安装最新版本。

设定 ENV CONFIG_JSON 时，务必将配置文件的换行符 `\r\n` 变更为 `\n`，然后填入 ENV 。使用 Linux 的朋友可以忽略这一步。
