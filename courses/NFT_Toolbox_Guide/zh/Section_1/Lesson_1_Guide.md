# 什么是 NFT？

NFT 是区块链上的一种加密代币，代表一种独特的资产。NFT 是非同质化代币（non-fungible token）的缩写，所以 NFT 的显著特征是非同质化。要解释同质化，一个很好的例子就是货币——具有同质性，人们可以轻松地将一张10元的纸币换成另一张10元的纸币，之所以可以交换，是因为两张纸币由价值而不是独特性来定义。

NFT 不能互相替换。每个 NFT 都有一个独特的标识符，使其不同于其他 NFT。这是数字领域真实性和所有权的证明。NFT 几乎可以代表任何事物，从艺术品到会员资格，再到游戏内物品，并作为所有权的数字记录。

# NFT Toolbox 上的 NFT 如何运作？

NFT 基于区块链技术运行，NFT Toolbox 当前使用的区块链为 Polygon（原生代币是 MATIC）。创建 NFT有多种不同的框架，最受欢迎的框架是 ERC-721 和 ERC-1155。NFT Toolbox 当前版本选择 ERC-721 进行扩展。任何人都可以在 NFT Toolbox 创建 NFT。

# 创建 NFT 需要什么

1. 一个链上钱包（如：MetaMask）
2. 一些用于支付所在链的交易费的代币（如：Matic）

# 使用 NFT Toolbox 创建和赠送 NFT 的步骤

## 第一步：完成 NFT 信息填写

在 NFT 创建页面，依次输入各字段内容：

1. 上传图片：选择符合规范的图片作为你的 NFT 展示图
2. 设置名称：
   1. 名称：输入你的 NFT 的名字，它是 NFT 的展示名称（如：无聊猿的名称为“BoredApeYachtClub”）
   2. 缩写：输入你的 NFT 的缩写，它是 NFT 的标识（如：无聊猿的缩写为“BAYC”）
3. 设置参数： 
   1. 最大供应量：输入你要创建的 NFT 最大发行（可赠送）数量 
   2. 描述：输入你的 NFT 的描述

![create_nft.png](http://gcdncs.101.com/v0.1/download?dentryId=3e161ab4-bacd-4a81-a07e-ac78964ccb40)

## 第二步：“创建”NFT

1. 点击“创建 NFT”后则会发起链上交易，此时 MetaMask 将弹出交易弹窗，核对你的交易信息后点击“确定”，等待交易被打包上链。 
2. 当交易完成后，你将看到创建成功的提示信息，表明你的 NFT 已创建，可以在“我创建的 NFT”列表中看到 NFT。 
   
## 第三步：“赠送” NFT 

1. 选择要进行“赠送”的 NFT，点击它进入 NFT 详情页面，在赠送 NFT 区域输入接收者的钱包地址 
2. 点击“赠送”按钮后则会发起链上交易，此时 MetaMask 将弹出交易弹窗，核对你的交易信息后点击“确定”，等待交易被打包上链。 
3. 当交易完成后该笔赠送将出现在“赠送记录”列表，接收者在他的“我收到的 NFT”列表将看到该 NFT

![send_nft.png](http://gcdncs.101.com/v0.1/download?dentryId=762ea87f-11d2-4fb4-ab7d-6a41fbedae28)

# 附

## 名词释义：

1. ERC-721协议定义了一组标准接口和方法，用于管理和交易NFT。它使数字资产能够唯一标识和在区块链上流通，为数字艺术、虚拟资产和游戏等领域提供了强大的功能和灵活性。
2. ERC-1155框架基于ERC-721扩展而来，其目的是为了提高代币的效率和互操作性。使用ERC-1155，可以在一次交易中批量发送多个代币，减少交易成本和链上负载。
