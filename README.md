# A Chatroom for "Ether ACTIVISTS" 

### ETHERACT CHAT
Let's CHAT with ETHER ADDRESSES!

The ETHERACT CHAT is an anoymous chatroom for ETH holders. The only identity in the chatroom will be your Ethereum address. 

The Chatroom is built upon IRC, to enter into the chatroom, you need to be an active address on Ethereum Network. 

### Steps to CHAT with the Ether ACTIVISTS
* Login into [IRC freenode](https://webchat.freenode.net/)，enter the channel #archat (`/join #archat`) with a nickname, for eg Vitalik :)
* You will join the ETHERACT Chatroom with the nickname of Vitalik. 
* The chatbot in the chatroom will ask you to bind your address with nickname saying : `Welcome Vitalik, please bind you nick to eth address ASAP. Type ".help" check how to bind your address"`
* Type `".help"` to view the complete list of commands of the chatroom
* Type `".cbind"` to call the chat_bot to bind your address, you will enter into a private chat with the chatbot
* Enter [your eth address]:[your signature of nick] in the private chat 
* to get you signature of the nick, visit http://39.107.32.62:8020. If you would like to sign offline, visit the repo  https://github.com/Tastingo/web3js-signature
* Then you could go back to the chatroom and chat with the ETHers！ 

### FAQs
#### 1. Why I got kicked out of the chatroom after I bind my ETH address?
* The Chatroom is available for "active" ETH address only. Only top 20,000 "active" address holders will be dropped with CAT (the native token of the chatroom) upon binding to the nickname, you need a minimum of 6 CATs to stay in the chatroom. If your CAT balance is lower than 6, you need to get more CAT to stay in the chatroom. 

#### 2. How is "activity" decided?
* To evaluate the activity of the address, we applied for the Account Rank Algorithm. The activity is mainly affected the `amount of ETH` ,  `coin days` and the `transaction relationship graph`of the address, learn more details about the algorithm, please visit [here](https://github.com/Tastingo/archat-tutorial/blob/master/ar-en.pdf)

#### 3. What is CAT and how could I get CAT?
* CAT is the native token of the chatroom, you need to holder a minimum balance of 6 CAT to stay in the chat room
* You will be dropped with CAT by the time you bind your address to your nickname
* You could also get through the CAT contract by call the `exchange` in the smart contract by sending a certain amount of ETH. To Understand about the exchange rate of ETH and CAT , please visit [CAT price model](https://github.com/Tastingo/archat-tutorial/blob/master/cat-en.pdf)

#### 4. Other interesting commands to play around
 *  `.cinfo`，Check your personal information, like your `"activity score"`
 *  `.ar_of_eth [address]`，check the `"activity score"` of a certain ETH address
 *  `.ar_top`，check the info of the addresses with top 5 `"activity score"`
 *  `.get_cat`，check the info of CAT 
    

### Share your ideas with the ETHerACTIVISTS

@Tastingo is currently prototyping the chatroom and the underlying algorithm for the chatroom with plan to implementing on more chat tools and supporting additional ERC20 tokens. If you'd like to get involved, you can leave your idea under the github or leave your ideas in the chatroom. Thanks for reading!



### Language
#### [EN](README.md)|[中文](README.zh.md)

