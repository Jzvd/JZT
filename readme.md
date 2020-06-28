# 饺子白皮书2.0

> 摘要：本文提出了一种完全通过数字通证驱动开源项目的组织形式，它使得参加开源项目的人能直接或者间接获得回报，最大限度的团结开发力量、传播项目的使用、达成对代码和社群的共识。通过多人协作、深耕技术、发掘人才、社群共享等多种形式，让[饺子视频播放器](https://github.com/Jzvd/JiaoZiVideoPlayer)(以下简称饺子)成为运行最稳定、接入最方便、功能最齐全、代码最精炼的安卓视频播放器。

### 1.简介

饺子是开源的安卓视频播放框架，它可以让开发者三五行代码在其App中集成视频播放功能，包含可以直接上线的完整的全套服务，满足全屏、列表、小窗等需求，并且提供了精简的自定义接口可以让开发者实现任何功能和UI，饺子还可以通过自定义播放内核以满足开发者对不同播放内核的需求。饺子至今开发了五年，收获10000+个Star，解决了2500+个Issue，100+个Pr，累计参与30余位开发者，发布100+个版本，解决开发者的问题不计其数，Library累计被引用10万+次，间接服务千万手机用户。

### 2.Github

Github是世界最大的开源项目聚集地，也是世界程序员精英的所在，越来越多的优秀开发者给开源项目贡献代码，优胜劣汰竞争激烈。我们假设，一场有限听众的演讲，和将这场演讲录制成视频，前者是"动态沟通"，后者是"静态沟通"，如果演讲的主题是普惠思想，那么静态沟通比动态沟通的效率高几个量级。Github就是高效的静态沟通的平台，让我们的劳动成果做到**可积累、可复制**，与其他开发者分享我们的代码和思想，通过最纯粹的表达方式向世界表达我们的想法和态度，高效的展示自己从而获得更多机会。

### 3.数字通证Token

数字通证是基于共识的可流通的有价值的权益证明。比特币实现了资产转移的自由，以太坊实现了票据证券化自由，基于以太坊的ERC20 Token是数字通证的常见形式，区块链的加密性为通证提供了信任基础。JiaoZiToken（JZT）是基于对饺子的权益证明，它是对饺子付出工作的体现，饺子的工作既包含代码的开发也包含社群运营，只要对饺子的贡献落实到Commit上，就会得到JZT。因为开源项目和数字通证的结合是史无前例的没有参考，我们一起探索JZT的用途。

### 4.饺子的由来

饺子原名为节操视频播放器，几年前安卓视频播放器市场一片空白找不到功能完整的视频播放器，主要因为全屏功能无法妥善解决，当时使用最多的做法是全屏时将布局扩大到铺满屏幕，这种做法在复杂布局、列表布局中问题很多，无法使用。经过几天的潜心研究之后发现了安卓中全屏的两种做法，一种是切换MediaPlayer的Surface另一种是移动SurfaceView都能达到在不同Activity之间图像和声音的无缝切换，经过几年的改进全屏功能日趋完善和简洁，饺子作为首款首屈一指功能完善的视频播放器，填补了市场的空白，并且迅速被市场接受。

### 5.开发者

随着工作的日渐深入和丰富，为了推进常规的开发工作和深入研究复杂的工作，饺子需要更多志同道合的人协作开发，饺子开发者是饺子Token的主要受益者。将饺子拆分成多个模块，确定每个模块的责任编辑，做自己熟悉的事情。

### 6.社群

饺子广泛用于安卓的视频播放，积累了大量开发者，饺子社群多数直接使用过饺子，参与饺子的讨论并影响饺子的发展，几年来饺子社群对饺子的产品质量有非常积极的作用，社群对饺子的开发计划有着举足轻重的地位。团结社群力量，接受社群监督，听取社群意见，发掘技术储备，让饺子社群更好的服务饺子，服务每一位开发者的日常工作。

### 7.三个核心价值观

* **(1)服务菜鸟**。高效的回应每一个开发者的问题，让每一个问题都能得到回复，提供解决思路让开发者少走弯路，引导开发者实现研发需求。整理开发者的问题，通过静态沟通的形式解决绝大多数问题。

* **(2)工作优先级：稳定>简单>功能>代码风格**。工作内容要有取舍，即便最牛技术最高精力再充沛投入再多的资源也不可能把所有想象变成现实。运行稳定是第一优先级，没有稳定就没有一切。其次是简单，包括**接入简单、维护简单、读懂简单，这是所有代码的价值所在**，我们工作的意义是让别人的工作变得简单。不是所有产品都懂产品，有时候只是一个细化工作的工具，功能的优先级也很高，满足开发者的日常需求，展示项目的工作能力有着重要的意义。代码风格是一个非常抽象模糊的东西，尽量少讨论，以解决问题为主。

* **(3)保证Demo质量**。让Demo展示的内容做到运行稳定，UI合理，可以直接上线。

### 8.代码风格和审美

饺子分为Library和Demo两个模块，Library是饺子的框架，包含了对视频播放框架必不可少的类，Demo是例子，它包含了饺子的常见用法和自定义例子。没有项目能像饺子这样代码越写越少。**写代码的极致追求是审美**。在追求功能的基础上让别人容易读懂，让别人容易上手，展示我们最高级的代码水平。

### 9.总结

数字通证将来会有举足轻重的地位，会和各行各业相结合，它会推进项目未来的工作进展，而不是为了瓜分现有的东西。饺子正在探索数字通证和开源项目相结合，通过数字通证推进饺子的开发进度，深入研究难点技术。


**2020.06.28
Update by 李盼**
