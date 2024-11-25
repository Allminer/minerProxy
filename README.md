# Allminer


关于软件开发费，所有币种统一固定0.2% 不上浮

Golang编写性能极高，算法升级（独家），抽水平稳0算力损耗，Web后台实时查看抽水算力，支持本地部署混淆加密客户端，Web后台HTTPS访问。

Web界面操作，简单易用，一键安装，小白可以轻松上手。开机自启动，进程守护运行，自动调整连接数限制。  支持/BTC/FB/ETH/ETC/BCH/LTC/RVN/ERGO/CFX/KAS/IRON/CKB/DASH/KDA/ZEC/ZEN/NEXA/ETC+ZIL/ZEPH/KLS/space  程序持续更新中

# 一键安装升级命令

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Allminer/minerProxy/main/allminer.sh)"
```

# 尝鲜版安装升级命令

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Allminer/minerProxy/main/allminer_beta.sh)"
```

> 选择 `1` 为安装服务.
> 选择 `2` 为更新程序.
> 
>安装后访问https://服务器地址:11113  默认用户名admin 密码1122345  注意是https不是http

# 安全客户端（用于矿场本地加密，突破运营商连接数限制） https://github.com/Allminer/SecClient  


# 1000G/1T压力测试
![bcb1764c0f9407424413e1fa155f00f](https://user-images.githubusercontent.com/105292192/188649421-67bdabd3-49f0-40cd-8791-64b6feedab92.png)
![image](https://user-images.githubusercontent.com/105292192/168423593-595242fc-0808-4609-b438-7911ab1a92db.png)
![image](https://user-images.githubusercontent.com/105292192/168423650-f37b8da0-2a5e-4961-b7f7-eed841cd81b3.png)

# 设置模板
![image](https://user-images.githubusercontent.com/105292192/190327307-5dc6eb95-f2aa-46ff-8ad1-ae24d5b2612e.png)


# 更新日志
```bash
2024-11-20
BETA版更新至v1.6.58-001ed16f50beta
更新内容：
新增币种 鱼池SC

2024-9-30
BETA版更新至v1.6.57-0012761023beta
更新内容：
支持LTC自定义矿池，跨池抽水

2024-9-11
BETA版更新至v1.6.56-00127024cebeta
更新内容：
1.支持币种FB

2024-8-27
BETA版更新至v1.6.55-0012589cefbeta 
更新内容：
1.修复kas抽水不够的问题

2024/5/29
BETA版更新至v1.6.52-00155b58c9beta   BETA版本稳定放心更
更新内容：
1.新增支持ZEC蚂蚁矿池 (支持跨池抽水)

2024-4-21
BETA版更新至v1.6.50-001d1f0804beta   BETA版本稳定放心更
更新内容：
1.新增支持币种 BCH(支持跨池抽水)

2024-3-25
BETA版更新至v1.6.49-00399b9dc5beta   BETA版本稳定放心更
更新内容：
1.新增支增币种 space

2024-3-22
BETA版更新至v1.6.49   BETA版本稳定放心更
更新内容：
1.WEB后台增加google二次验证,防止后台爆破入侵
2.改善抽水逻辑
3.修复一些偶发BUG

2023-12-25
BETA版更新至v1.6.43   BETA版本同样稳定放心更
更新内容：
1.增加币种支持GRIN 
2.增加币种支持PYI
3.支持BTC跨池抽水

2023-12-19
BETA版更新至v1.6.42   BETA版本同样稳定放心更
更新内容：
1.增加币种支持BEL

2023-12-11
BETA版更新至v1.6.40   BETA版本同样稳定放心更
更新内容：
1.新增支持币种BLOCX
2.优化币安BTC

2023-12-7
BETA版更新至v1.6.40   BETA版本同样稳定放心更
更新内容：
1.新增支持币种KLS
2.新增支持币种ZEPH
3.新增多服务器群控
4.邮件警报

2023-11-25
BETA版更新至v1.6.39   BETA版本同样稳定放心更
更新内容：
1.新增支持鱼池ZEN

2023-10-28
BETA版更新至v1.6.37-0037532bd1beta

增加对secpool的支持
修复特定情况下抽水引起的协议中断导致矿机重连的问题

2023-9-13
BETA版更新至v1.6.36-0012a53267beta

优化kas抽水，修复一些崩溃问题

2023-7-28
正式版V1.6.32未更新

BETA版更新至v1.6.34-00165554dcbeta
更新内容：
1.新增支持DASH
2.新增支持DCR
3.优化KS专业机算力损耗

2023-6-19  v1.6.32   正式版更新
最稳版本，同步BETA版本小币种至正式版


2023-5-22  v1.6.31-BETA版本更新   正式版未更新
新增支持币安BTC

2023-5-11  v1.6.30-BETA版本更新   正式版未更新
修复ETHW  E9PRO的支持
新增支持铁鱼IRON 
新增支持CKB

2023-4-27  正式版:v1.6.29-003483e3de 小更新
修复ETC E9PRO跑不起来的问题

2023-4-25   正式版:v1.6.29
1.新增支持ETC+ZIL鱼池
2.修复优化LTC抽水
3.新增支持LTC蚂蚁矿池

2023-4-20   尝鲜版本：v1.6.29
1.支持NEXA
2.修复偶尔服务崩溃重启问题

2023-3-31   版本：v1.6.28
1.修复KASPA抽水
2.修复鱼池某些币种ssl下连接失败的问题

2023-1-31   版本：v1.6.27
1.修复BTC 币印抽水问题

2022-11-1   版本：v1.6.23.dec6950
1.修复一个可能会导致程序崩溃的BUG


2022-10-6   版本：v1.6.21.bcfbcbe
1.新增币种 ： ZEC 鱼池
2.已支持币种 Eth ETHW ETC ETHF BTC LTC ERGO RVN KAS CFX ZEC

2022-10-4   版本：v1.6.20.6e3c350
1.新增BTC矿池  BTC.COM
2.新增LTC矿池  鱼池F2POOL

2022-9-20    版本：v1.6.19.ec7df6a
1. 新支持kaspa币种
2. 优化逻辑

2022-9-16 1：44   版本：v1.6.18.5a0dc44
1.增加币种ETHW 可以自定义矿池 在矿池栏写入  取消ETH自定义矿池地址

2022-9-15 21：46  版本：1.6.17
1. 增加鱼池ETF

2022-9-15 13：50  版本：1.6.16   
增加RVN HIVE池 CFX 鱼池SSL ERGO鱼池SSL地址

版本v1.6.15修正版  
1.增加ERGO 2M矿池 鱼池 支持部份矿池跨池抽水
2.已支持币种 Eth Etc Btc Ltc Ergo Rvn CFX
3.优化BTC一个空白指针

版本：v1.6.15
1.优化抽水算法
2.增加币种CFX   已支持币种 Eth Etc Btc Ltc Ergo Rvn CFX
3.优化BTC

版本：v1.6.11
针对BTC 多矿池 进行优化  没有BTC的可以不更新

版本：v1.6.8
强烈建议167版本升至168  修复了167的一个己知BUG

版本：v1.6.7
增加币种Ergo Ltc 支持Eth Etc Btc Ltc Ergo Rvn

版本：v1.5.6
增加芯片机亚米的支持
增加BTC鱼池
程序配置支持备份还原导入导出
增 加币种 RVN支持ETH ETC BTC RVN

版本：v1.4.3
修复一个BUG

版本：v1.4.1
WEB后台支持HTTPS安全访问 矿机证书自定义
```
