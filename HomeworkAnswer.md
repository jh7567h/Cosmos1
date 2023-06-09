# Cosmos1
## 一、选择题（多选）
1 Cosmos Network 是指什么？ 4  
Cosmos Hub 主网   
区块链的互联网   
ATOM 区块链网络    
多个区块链网络组成的超级网络    

2 以下哪些不是跨链基金会的议程（Program） 23   
促进发展负责任的监管环境    
提升 ATOM 代币的价格   
为全球 Builders 提供全方位支持    
提供 Cosmos 技术栈相关的在线培训    

3 以下哪些不是应用专有链的特性 13    
可升级性    
可扩展性    
高可用性    
独立自主性   
可互操作性   

4 以下哪些不是 Cosmos 技术栈的核心产品 25    
Tendermint    
Substrate   
Cosmos SDK    
IBC 跨链协议    
Ignite CLI    

5 以下哪些说法是正确的 14   
Cosmos SDK 被全球超过 200 个 PoS 区块链项目采用    
Tendermint 是支持拜占庭容错的 PoW 共识引擎   
IBC 是基于哈希锁机制的跨链协议   
Tendermint 被全球超过 40% 的 PoS 区块链网络采用    

6 以下哪些 ABCI 方法不是用于执行交易的 2   
BeginBlock    
CheckTx   
EndBlock    
DeliverTx   

7 以下哪些是 Cosmos 链节点的功能分层 145   
共识层   
连接层   
会话层   
网络层   
应用层   

8 Tendermint Core 与应用层之间的通讯接口是 25   
REST API    
ABCI    
Socket    
GRPC    
ABCI++    

9 以下哪些是 Tendermint Core 的特性 235   
交易的概率最终性    
拜占庭容错 BFT   
交易的快速最终性    
基于工作量证明 PoW   
交易的绝对最终性    

10 以下哪些说法是正确的 34    
通过向网络增加节点可提高网络的吞吐能力   
ABCI++ 是对区块链网络的水平扩展   
应用专有链可对链上治理机制做定制化设计   
IBC 是区块链之间的互操作协议    

## 二、填空题
1 Cosmos 的愿景是构建 ____区块链互联网______________________    
2 Cosmos Hub 的主网代号是 ___Gaia__________, 主通证是 ___ATOM______   
3 Tendermint 是 ___Jae Kwon、Ethan Buchman________________ 发明的？       
4 Tendermint Core 正确运行需要至少占  __1/3_____ 投票权的验证人不作恶？    
5 如果你想授权他人代管你的链账户通证资产，你会使用 __authz_______ 模块功能   
6 如果你想替他人支付交易手续费，你会使用 ____feegrant_____ 模块功能    
7 如果你想修改一个链上系统参数，你需要使用 _upgrade________ 模块功能   
8 如果你需要使用 Rust 语言编写智能合约，你会加载 ____CosmWasm__________ 合约模块    
9 如果你需要把以太坊上的通证跨链转移到 Cosmos 生态，你可以使用 _Axelar_________ 或 __Gravity Bridge________ 网络   
10 如果你需要查看一笔跨链交易的分阶段详情，你可以使用 ___Mintscan___________ 或 ____MapOfZones___________ 跨链浏览器   

## 三、问答题
1 IBC 数据包为什么会超时？    答：因为 relayer 没有及时地把 A 链用户发的数据包转到 B 链上，数据包中会记录超时高度，并构造不存在证明，通过 timeoutPacket 提交到 A 链上，A 链进行验证，验证后锁定的资产会被释放。
2 来自中国的技术团队为 IBC 协议贡献了哪些标准？   ICS-721、ICS-100
3 跨链 NFT 转移协议（ICS-721）的 Go 语言实现代码库在哪儿？    https://github.com/bianjieai/nft-transfer   
4 同时支持 Web, Android, iOS 平台的 Cosmos 生态钱包有哪些（不少于两个）？   Keplr、Cosmostation、MathWallet
5 Cosmos 中文技术社区翻译的关于 ABCI++ 的最近一篇微信公众号文章链接是什么？    https://mp.weixin.qq.com/s/fC3d1vqcdpvGLeorNIpDUQ   
