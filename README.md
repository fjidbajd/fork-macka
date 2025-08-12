# 一、项目介绍

## 核心

- Xray-core
- sing-box

## 协议

> 以下均使用TLS，支持多种协议组合

- VLESS(Reality、Vision(TCP)、WS、gRPC、XHTTP)
- VMess(TCP、WS、HTTPUpgrade)
- Trojan(TCP、gRPC)
- Hysteria2(sing-box)
- Tuic(sing-box)
- NaiveProxy(sing-box)


# 四、安装使用

## 1.下载脚本

- 支持快捷方式启动，安装完毕后，shell输入【**vasma**】即可打开脚本，脚本执行路径[**/etc/v2ray-agent/install.sh**]

- Github

```
wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/mack-a/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```

- 官方网站【备用】

```
wget -P /root -N --no-check-certificate "https://www.592083.xyz/v2ray-agent/install.sh" && chmod 700 /root/install.sh && /root/install.sh
```

# 七、许可证

[AGPL-3.0](https://github.com/mack-a/v2ray-agent/blob/master/LICENSE)
