# ETH活跃分子才能加入的聊天室 ETHERACT 聊天室

### ETHERACT 聊天室
ETHERACT聊天室是为ETH地址提供的一个匿名的聊天室。聊天室中唯一的身份是你的以太坊地址。

聊天室建立在IRC上，进入聊天室之前。你需要先绑定你的以太坊地址。

### 如何进入聊天室
* 登录[IRC freenode](https://webchat.freenode.net/)，用任意昵称（比如Vitalk）进入聊天室频道`/join #archat`；
* CHAT BOT会提示你绑定你的地址：`Welcome Vitalik, please bind you nick to eth address ASAP. Type ".help" check how to bind your address";` （欢迎Vitalik，请尽快绑定你的以太坊地址。在聊天框输出“.help"查看如何绑定地址）；
* 输入`".cbind" ` 开始绑定地址，你将进入和CHAT BOT的私聊频道；
* 在私聊频道中输入 [你的以太坊地址]:[以太坊地址绑定昵称的确认信息]。你可以用下面的[小工具](http://39.107.32.62:8020/)进行在线或者离线签名；
* 完成地址绑定，查询地址的活跃分数，就可以和ETHers进行聊天啦！

### FAQs
#### 1. 为什么我绑定了我的ETH地址，还是没有办法进入聊天室?
   - 聊天室是为以太坊的“活跃”地址提供的，智能合约会按照地址的“活跃度”分数在地址完成绑定后想地址发放CAT token，你需要至少持有6个CAT token才能在聊天室中聊天。

#### 2. 活跃度分数是如何计算的?
   - 我们参考了账户指数算法来计算地址的活跃度。账户活跃度主要由该地址的币量、币龄和地址交易关系图计算决定。了解更多关于[账户指数](https://github.com/Tastingo/archat-tutorial/blob/master/AR/ch/main.pdf)。
    
#### 3. CAT 是什么，如何获得CAT？
   - CAT是进入聊天室的代币，只有持有最少6个CAT的地址才能进入聊天室；
   - 进入聊天室绑定地址后，CAT合约会根据地址的活跃度向地址发放CAT；
   - 你也可以调用CAT合约中的`exchange`功能，向合约发送ETH，兑换CAT。了解CAT的[兑换模型](https://github.com/Tastingo/archat-tutorial/blob/master/CAT/ch/main.pdf)。
   
#### 4. 玩转聊天室相关指令
   - `.cbind [address]:[signature]`，绑定（以太坊）地址与nickname的签名
   - `.cinfo`，查询个人信息
   - `.ar_of_eth [address]`，查询某个地址的account rank
   - `.ar_top`，查询top5 account rank信息
   - `.get_cat`，获取CAT Token介绍

### 加入我们一起玩转 ETHerACTIVISTS
目前ETHERACT的原型由@Tastingo 开发完成，欢迎在下面留下任何你对ETHERACT的想法，加入我们一起玩转ETHEACT！

### 语言
#### [EN](README.md)|[中文](README.zh.md)
