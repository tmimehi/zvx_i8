# bsc八代推广分红代币合约  由于币安WBNB的兑换逻辑变更了 所以现在不能分红WBNB了  
# 转账绑定上下级关系  下级交易上级获得本币分红  可分八代



支持分红SHIB/ETH/USDT/DOGE等BSC所有代币。
# 源码：
https://github.com/tmimehi/zvx_i8/blob/main/dividendcontract.sol

# 如果遇到问题可联系TG：

https://t.me/zvx_Staff

# TG电报群交流群

https://t.me/ZVX_Official

# Remix

https://remix.ethereum.org/

# 编译/开源参数

COMPILER: v0.8.7+commit.e28d00a7.js

Enable optimization: 开启并使用默认值200

Other Settings: default evmVersion, MIT license

# 部署参数

Value填写：200000000000000000 （0.2BNB）

CONTRACT 选择 dividendcontract，

name_: BTC COIN (代币名称)

symbol_: BTC (代币简称)

totalSupply_: 21000000 (发行量 发多少就写多少)

rewardAddr_: 要分红的代币合约，BSC常用代币地址在下方

marketingWalletAddr_:      你自己的营销钱包地址

buyFeeSetting_: [4,3,2,1] (分红、流动性、营销钱包、燃烧)

sellFeeSetting_: [5,4,3,2] (分红、流动性、营销钱包、燃烧)

INVITERFEE_： 1      八代分红占比

tokenBalanceForReward_: 10000000000000000000000 (持有多少代币参与分红。数量后要加18个0)

# BSC常用代币合约地址

SHIB: 0x2859e4544C4bB03966803b044A93563Bd2D0DD4D

USDT: 0x55d398326f99059fF775485246999027B3197955

ETH: 0x2170Ed0880ac9A755fd29B2688956BD959F933F8

DOGE: 0xbA2aE424d960c26247Dd6c32edC70B295c744C43

BUSD: 0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56

CAKE: 0x0E09FaBB73Bd3Ade0a17ECC321fD13a19e81cE82

# 图文教程

1，打开Remix：https://remix.ethereum.org

2，点击GitHub

![1](https://user-images.githubusercontent.com/100020516/157315295-03669f3a-7377-4162-b97a-a53e7c639da6.png)


3，输入合约地址

https://github.com/tmimehi/zvx_i8/blob/main/dividendcontract.sol

4，点击import

5，选择dividendcontract.sol

![2](https://user-images.githubusercontent.com/100020516/157315411-06f4fbfc-a09e-4525-beef-29e9226c8a69.png)

6，点击编译

7，选择编译版本0.8.7

9，点击 编译

![3](https://user-images.githubusercontent.com/100020516/157315496-71ef72fc-ebda-4b91-9519-1c8e13aaab70.png)

10,选择ZVX_CC_I8
![8](https://user-images.githubusercontent.com/100020516/159698008-c875fd42-d35c-463f-a8ab-561cf90915ab.png)

11,ENVIRONMENT选择：injected Web3

VALUE输入：200000000000000000

name_: BTC COIN (代币名称)

symbol_: BTC (代币简称)

totalSupply_: 21000000 (发行量 发多少就写多少)

rewardAddr_: 要分红的代币合约，BSC常用代币地址在下方

marketingWalletAddr_: 你自己的营销钱包地址

buyFeeSetting_: [4,3,2,1] (买入分红、流动性、营销钱包、燃烧)

sellFeeSetting_: [5,4,3,2] (卖出分红、流动性、营销钱包、燃烧)

INVITERFEE_： 1      八代分红占比

tokenBalanceForReward_: 10000000000000000000000 (持有多少代币参与分红。数量后要加18个0)

![9](https://user-images.githubusercontent.com/100020516/159698411-0959b7cc-02b2-4d0e-96ec-af7358a74a43.png)


12，点击 transact 

13，小狐狸钱包点击确认

![6](https://user-images.githubusercontent.com/100020516/157315652-1c51536d-e273-48e2-96b0-bbce00976588.png)

14，等待几十秒，你的代币合约将出现在REdmix右下角

![7](https://user-images.githubusercontent.com/100020516/157315810-8df6bae5-c9f2-45bc-b36e-ba3dca4e96e4.png)







