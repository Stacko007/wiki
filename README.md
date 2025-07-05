# wiki
2025-07-05 转型web3.0开始----

## 第一阶段
### 1.1 阶段目标
 掌握区块链基础+钱包交互+查询链上数据

### 1.2 学习内容
	• 区块链技术概念(账户模型、公钥私钥、Nonce、Gas、交易池)
	• 钱包地址、公钥私钥生成机制
	• 稳定币(USDT|USDC)与ERC2.0的基本原理
	• 使用Web3 SDK(Java使用Web3j、GO使用 go-ethereum):
   		1.2.1 查询ETH 和 ERC20代币余额
   		1.2.2 监听链上转账事件

### 1.3 推荐工具：
	•	本地开发链：Ganache（或 Anvil）模拟以太坊网络
	•	钱包工具：MetaMask
	•	区块链浏览器：Etherscan（或 Ganache 内置 Explorer）

### 1.4 实践任务：
	链上钱包余额查询工具
	•	输入地址，返回 ETH 和某个 Token（如 USDT）的余额
	•	实现一个 REST API，支持前端查询
	•	选做）监听该地址是否收到新 Token（合约事件）