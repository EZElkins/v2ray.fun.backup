# v2ray.fun.backup
# V2ray.fun
V2ray控制脚本，向导式更改端口，加密方式，传输协议，享受V2ray的乐趣~

## 功能

- 一键 启动 / 停止 / 重启 V2ray 服务端
- 自动随机生成 UUID
- 自助修改端口
- 快速查看服务器连接信息
- 一键下载客户端配置文件（**仅限 Xshell**）
- 自由更改**传输配置**：
  - 常规TCP
  - HTTP头部伪装
  - WebSocket流量
  - 常规mKCP流量
  - mKCP 伪装 FaceTime通话流量
  - mKCP 伪装 BT下载流量
  - mKCP 伪装 微信视频通话流量

**WebSocket不包括Nginx分流，请自行安装Nginx来分流。**


## 系统要求

- Debian 7 
- **Debian 8（推荐）**
- Ubuntu 14 
- Ubuntu 16 
- CentOS 7

**不支持Centos 6**

## 软件要求

请使用**Xshell**连接服务器，以获得完美的中文支持以及配置文件下载功能。
## xyyhqq版安装
## 1xyyhqq版安装命令
```bash
wget -N --no-check-certificate https://raw.githubusercontent.com/xyyhqq/v2ray.fun.backup/master/install.sh && bash install.sh
```
## 2xyyhqq版卸载命令
```bash
wget -N --no-check-certificate https://raw.githubusercontent.com/xyyhqq/v2ray.fun.backup/master/uninstall.sh && bash uninstall.sh
```
## 第二步：下载VPS上 /root/config.json 客户端配置文件，与V2ray放在同一个文件夹下。
V2ray下载地址：https://github.com/v2ray/v2ray-core/releases/latest

## 截图

![1](1.png)

![2](2.png)

![3](3.png)

![4](4.png)
## original版本
## 安装命令

```bash
wget -N --no-check-certificate https://raw.githubusercontent.com/KiriKira/v2ray.fun/kiriMod/install.sh && bash install.sh
```

#不提供升级。因为不喜欢。

## 卸载命令
```bash
wget -N --no-check-certificate https://raw.githubusercontent.com/KiriKira/v2ray.fun/kiriMod/uninstall.sh && bash uninstall.sh
```

## 更新日志

**2017.9.4**
第一版通过测试发布。

**2017.10.16**
新增TLS功能，自动获取证书。

**2017.11.25**
原作者删库，接手魔改但未准备拓展新功能。

## 特别说明

有任何问题或者新功能想法欢迎提交 Issue，我会抽空回答。

本程序遵循 GPL v3协议发布，请Fork保留源项目地址，谢谢！

## 感谢

https://github.com/FunctionClub/V2ray.fun （一个不存在的项目）
V2ray : [https://v2ray.com](https://v2ray.com)
