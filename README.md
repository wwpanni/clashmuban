# 订阅转换服务地址
```sh
192.168.31.2:25500/sub
```
# 模板地址
```sh
https://git.workgo.top/https://raw.githubusercontent.com/wwpanni/clashmuban/refs/heads/main/clash.ini
```
# XMRth订阅链接
https://www.xmrth.lol/user
# 红杏订阅链接
https://hongxingyun.xyz/

# 订阅转换服务搭建
docker compose
```compose
version: '3.1' 
services:
    "subconverter":
        image: tindy2013/subconverter
        container_name: "subconverter"
        restart: always
        ports:
            - '25500:25500'
```
