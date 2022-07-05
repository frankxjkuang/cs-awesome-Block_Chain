## 以太坊项目简介

![以太坊项目](_images/ethereum_logo.png)

以太坊（Ethereum）项目的最初目标，是打造一个运行智能合约的平台（Platform for Smart Contract）。该平台支持图灵完备的应用，按照智能合约的约定逻辑自动执行，理想情况下将不存在故障停机、审查、欺诈，以及第三方干预等问题。

以太坊平台目前支持 Golang、C++、Python 等多种语言实现的客户端。由于核心实现上基于比特币网络的核心思想进行了拓展，因此在很多设计特性上都与比特币网络十分类似。

基于以太坊项目，以太坊团队目前运营了一条公开的区块链平台——以太坊网络。智能合约开发者使用官方提供的工具和以太坊专用应用开发语言 Solidity，可以很容易开发出运行在以太坊网络上的“去中心化”应用（Decentralized Application，DApp）。这些应用将运行在以太坊的虚拟机（Ethereum Virtual Machine，EVM）里。用户通过以太币（Ether）来购买燃料（Gas），维持所部署应用的运行。

以太坊项目的官网网站为 [ethereum.org](https://ethereum.org)，代码托管在 [github.com/ethereum](github.com/ethereum)。


### 以太坊项目简史

相对比特币网络自 2009 年上线的历史，以太坊项目要年轻的多。

2013 年底，比特币开发团队中有一些开发者开始探讨将比特币网络中的核心技术，主要是区块链技术，拓展到更多应用场景的可能性。以太坊的早期发明者 Vitalik Buterin 提出应该能运行任意形式（图灵完备）的应用程序，而不仅仅是比特币中受限制的简单脚本。该设计思想并未得到比特币社区的支持，后来作为以太坊白皮书发布。

2014 年 2 月，更多开发者（包括 Gavin Wood、Jeffrey Wilcke 等）加入以太坊项目，并计划在社区开始以众筹形式募集资金，以开发一个运行智能合约的信任平台。

2014 年 7 月，以太币预售，经过 42 天，总共筹集到价值超过 1800 万美金的比特币。随后在瑞士成立以太坊基金会，负责对募集到的资金进行管理和运营；并组建研发团队以开源社区形式进行平台开发。

2015 年 7 月底，以太坊第一阶段 Frontier 正式发布，标志着以太坊区块链网络的正式上线。这一阶段采用类似比特币网络的 PoW 共识机制，参与节点以矿工挖矿形式维护网络；支持上传智能合约。Frontier 版本实现了计划的基本功能，在运行中测试出了一些安全上的漏洞。这一阶段使用者以开发者居多。

2016 年 3 月，第二阶段 Homestead 开始运行（区块数 1150000），主要改善了安全性，同时开始提供图形界面的客户端，提升了易用性，更多用户加入进来。

2016 年 6 月，DAO 基于以太坊平台进行众筹，受到漏洞攻击，造成价值超过 5000 万美金的以太币被冻结。社区最后通过硬分叉（Hard Fork）进行解决。

2017 年 3 月，以太坊成立以太坊企业级联盟（Enterprise Ethereum Alliance，EEA），联盟成员主要来自摩根大通，微软，芝加哥大学和部分创业企业等。

2017 年 11 月，再次暴露多签名钱包漏洞，造成价值 2.8 亿美元的以太币被冻结。

目前，以太坊网络支持了接近比特币网络的交易量，成为广受关注的公有链项目。

后续按照计划将发布第三阶段 Metropolis 和第四阶段 Serenity，主要特性包括支持 PoS 股权证明的共识机制，以降低原先 PoW 机制造成的能耗浪费；以及图形界面的钱包，以提升易用性。

包括 DAO 在内，以太坊网络已经经历了数次大的硬分叉，注意每次硬分叉后的版本对之前版本并不兼容。

### 主要特点

以太坊区块链底层也是一个类似比特币网络的 P2P 网络平台，智能合约运行在网络中的以太坊虚拟机里。网络自身是公开可接入的，任何人都可以接入并参与网络中数据的维护，提供运行以太坊虚拟机的资源。

跟比特币项目相比，以太坊区块链的技术特点主要包括：

* 支持图灵完备的智能合约，设计了编程语言 Solidity 和虚拟机 EVM；
* 选用了内存需求较高的哈希函数，避免出现强算力矿机、矿池攻击；
* 叔块（Uncle Block）激励机制，降低矿池的优势，并减少区块产生间隔（10 分钟降低到 15 秒左右）；
* 采用账户系统和世界状态，而不是 UTXO，容易支持更复杂的逻辑；
* 通过 Gas 限制代码执行指令数，避免循环执行攻击；
* 支持 PoW 共识算法，并计划支持效率更高的 PoS 算法。

此外，开发团队还计划通过分片（Sharding）方式来解决网络可扩展性问题。

这些技术特点，解决了比特币网络在运行中被人诟病的一些问题，让以太坊网络具备了更大的应用潜力。
