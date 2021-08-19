# StarLink 公测游戏指南

<font color=#FFC0CB size=3>本次公测时间从北京时间 2021.08.16 上午 10:00 开始，至 2021.08.30 上午 10:00 截止，本次公测为 【删档测试】，玩家所获得的卡牌都会在正式上线时弃用，但在游戏测试过程中，玩家将会获得主网正式的 GFT 代币。相比上一次测试，这次的测试有更多的优化。游戏中使用的 gas 费也相比上一次大幅降低了约 50%。【划重点：执行任何操作请保证钱包里有至少 10 枚 iotx 以确保能够正常玩游戏。】</font>

**【游戏内通证介绍】**

**GFT：GFT 为硬顶 3000w 的 StarLink 游戏内使用的货币通证。（此上限不可更改，合约删除了更改的方法）在 StarLink 内所参与的一切交易活动均使用 GFT 来进行，包括以后预计开发的竞技场功能，其他社交活动等等。GFT 可与 IOTX 进行兑换，绝大部分的 GFT 将采用挖矿的形式产出，游戏内系统收益的通证将加入奖金池中供 GFS 持有者共享。**

**GFS：GFS 为总量 3000w 的 GameFantasy 的社区通证。完全 100%公平发放，没有团队份额，没有生态份额。以后会开放更多游戏内的获取方式。可以用于游戏内 GFS 专享的奖金池挖矿，未来预计开放的各种糖浆池的挖矿以及 StarLink 的 DAO 权利。更多通证经济将在游戏上线后公布，敬请期待～**

**【公测网络及准备说明】**

**本次测试的网络为 iotex 主网，游戏内使用的通证为主网 GFT,其中流动性挖矿为 IOTX-GFT 的 LP，产出为 DAO 代币 GFS。**

**游戏期间请关闭 vpn 的全局模式，以免
出现连接不上钱包的问题。如果您的浏览器有安装 adblock，请暂时关闭 adblock，避免出现连不上服务器的问题。**

测试过程中建议大家尽量使用 iopay 的桌面版（这样能在浏览器中打开开发者工具查询日志，便于我们定位问题并快速解决）

游戏 loainding 界面结束以后大约等待 5-10 秒钟（根据网络情况可能会有所延长，请耐心等待）会弹出来钱包的签名，点击确认即可进入游戏。

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/loading.png)

**【如何获得 GFS】**

如果您想要进行流动性挖矿挖取 GFS，首先需要打开 mimov2，为 IOTX-GFT 交易提供流动性，并在游戏内进行质押，以获得 LP token,LP token 可用于挖矿获取 GFS。

## 如何在 mimo v2 上给 GFT 提供流动性？

请打开 https://mimo.exchange/

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/lp1.png)

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/lp2.png)

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/lp3.png)

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/lp4.png)

然后您就可以在游戏内流动性挖矿界面中看到您提供的 lp token 了。质押挖矿的奖励将会是 GFS。

**【游戏玩法及界面介绍】**

游戏主界面下方有四个按钮分别对应为：

- NFT 展示界面(My Starmon)
- NFT 合成界面(Polymerization)
- NFT 交易拍卖界面(Market)
- NFT 挖矿界面(StarMine)

## NFT 展示界面

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/main.png)

点击进第一个按钮进入 nft 展示界面，这也是游戏默认初始化界面。一开始可能大家都没有新卡牌。不用着急，你可以在交易拍卖界面中获得您的卡牌。如果你获得了属于你的卡牌的话可以在这里看到您的卡牌信息。右上角的感叹号可以查看卡牌详细的品质和信息。如果您的卡牌身体部位总分达到一个分值的时候，卡牌的背景将会发生改变。

游戏界面上方中间可以切换游戏中显示的语言。斜下方的查找功能可以让你很方便地查看目前某个 id 对应的卡牌属性。每张卡牌下半部分的中间有 8 个带颜色的水晶球，每个水晶球对应这张卡牌某个部位的品质。这样你可以很方便地知道这张卡牌的大概品质信息，以及合成的时候找到适合的对应卡牌。

## NFT 合成界面

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/mix.png)

nft 合成界面可以将两张 nft 卡牌进行合成。从而有机会获得品质更高的卡牌，所有属性将从父母亲卡牌中继承和进化。所有身体部位的稀有度会根据父母双方的稀有度进行重置。所以合成的时候大家一定要掌握好这个最基本的原则。如果您想您的卡牌某个部位保持某个稀有度，那你必须至少让父母双方都达到这个稀有度，这样安全性会比较高。选定好合成的卡牌以后，点击合成调用合约，等待大约 10 秒左右合约会执行完毕将会播放合成动画，生成新的卡牌。

## NFT 交易拍卖界面

nft 交易拍卖界面我们分为三部分来说：

#### NFT 交易界面

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/freedom.png)

进入市场默认打开的就是 nft 自由交易界面。在这里可以看到玩家自己在游戏中挂出来售卖的卡牌。上方红框内会有别的玩家的售价，点击购买会弹出猫咪的详情界面，可以在此查看售卖猫咪的详情。在此点击确认调用合约以后等待 10 秒左右如果您的 GFT 余额足够则会将这张卡牌购买到您的仓库中。一页显示 10 个项目，多出的可以在下方红框内进行翻页，点击中间页码可以弹出跳转页面，跳转到任意一个页码。方便玩家浏览的卡牌的筛选功能后期会加入，请耐心等待。

#### NFT 拍卖界面：

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/bid.png)

这里是官方直拍的界面。在这里永远都会有 20 张卡牌等待大家的领养。只要任何一个玩家对其中一个出价则会开始倒计时。在经过一定的区块数（一个区块大概是 5 秒）如果有人继续出价，则这个卡牌的倒计时会增加一定数量的区块。直到没有人出价为止，这个卡牌则会进入个人所有流程。你可以在第三个界面中领取这个卡牌。注意，目前刷新这块目前还在优化中，列表刷新速度不是很快，请耐心等待。

#### 我的卡牌界面：

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/myshop.png)

这个界面会列出来所有你拥有的卡牌，包括你正在售卖，可以领取的卡牌。你也可以在这个界面将自己的卡牌挂到市场上售卖。别的玩家将可以在第一个界面里查看到你的挂单信息。如果成交，会从你能获得的金额中扣除 0.3%(日后可以通过 DAO 进行调整)作为手续费。这个手续费会存入到游戏的分红池内。供持有 GFS 的玩家共享。
如上图所示，receive 表示您从系统拍卖那里竞价获得的卡牌，getback 表示您可以下架一个您上架了的卡牌。sale 表示您可以将您的这张卡牌上架进行售卖。售卖没有时间限制。

## NFT 挖矿界面：

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/mining.png)

NFT 卡牌有一个属性叫做挖矿力，这个能力决定了您所拥有的这张卡牌派遣出去挖矿所占的权重。挖矿矿池将会根据所有卡牌的挖矿力总和来进行 GFT 的分配。一旦您将 NFT 卡牌派遣去挖矿了，这张卡牌将会从您的仓库里移除。但是您仍然能在挖矿见面看到它并且将它召回。在您将卡牌召回前，这张 NFT 卡牌将暂时不属于您。图上最下方灰色带 dispatching 的卡牌就是您已经派遣去挖矿的卡牌。

![image](https://github.com/GameFantasyDev/StarLinkBetaTest/blob/main/IMG/lpmining.png)

NFT 挖矿界面有一个 LP 挖矿，这里您可以使用 GFT 和 IOTX 配对，在 mimo v2 上提供流动性以获得 LP token。您在这里将 LP token 质押就可以参与流动性挖矿，流动性挖矿的奖励将是游戏的 DAO 治理代币 GFS。持有 GFS 就相当于持有 LinkStar 的股票一样，之后您将可以分享到游戏分红池内的奖励。GFS 以后还会开放到游戏内以其他新游戏玩法的形式获取。GFS 将采取公平分发的方式，获得方式目前只有为游戏做出贡献（即增加 GFT 流动性）。游戏上线时将放出 GFS 的通证经济。

主网 GFS 的地址为 io1t585efypl4e9ex7xks2upnjm8saawfk0v0s5sj。您可以通过在添加自定义 xrc20 将地址输入查看钱包拥有的 GFS 情况。在文档的一开始有介绍如何进行 LP 流动性提供。

我们测试的总群：
For English：https://t.me/GameFantasyToken

For Chinese: 请微信找游戏人生（FantasyGame）加入 GFT 微信群

# 最后，希望大家能够喜欢我们的游戏！
