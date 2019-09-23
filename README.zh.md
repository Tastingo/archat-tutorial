# AR聊天室教程

### 什么是AR聊天室
AR聊天室为用户提供匿名IRC聊天频道，基于排名算法自动计算全网账户（目前已支持以太坊）指数，拥有较高账户指数的区块链用户可无门槛进入聊天室，否则需支付一定代币（CAT Token）。

### 如何进入聊天室
* 登录[IRC freenode](https://webchat.freenode.net/)，进入聊天室频道`/join #archat`
* 查看相关帮助`.help`，目前聊天室支持API包括：
    - `.cbind [address]:[signature]`，绑定（以太坊）地址与nickname的签名
    - `.cinfo`，查询个人信息
    - `.ar_of_eth [address]`，查询某个地址的account rank
    - `.ar_top`，查询top5 account rank信息
    - `.get_cat`，获取CAT Token介绍
* 拥有较高账户指数与支付了CAT的用户可在该周期內（一般3天）聊天，否则在一定时间后会被踢出。

### 如何获取CAT Token
* 拥有较高的账户指数（[如何提高账户指数]()）。每个周期会对账户指数前10,000名，随机选取100名进行airdrop；
* 通过[合约](https://ropsten.etherscan.io/address/0x351C54BE57c7d49CB074A47E030d8c5994eEAA16)购买，调用合约`exchange`方法，转入一定数量的ETH，可获得CAT。兑换请参见[模型]()。

### 如何充值CAT Token至聊天室账户
* 调用[合约](https://ropsten.etherscan.io/address/0xf8711d5FB1387B3d4b3ae4Bc47F40593b192bC85)`transfer`方法，向[账户](https://ropsten.etherscan.io/address/0xf8711d5FB1387B3d4b3ae4Bc47F40593b192bC85)转入相应数量的CAT，完成充值。
