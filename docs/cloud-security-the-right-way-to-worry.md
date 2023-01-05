# 云安全:担心的正确方式

> 原文：<https://www.dominodatalab.com/blog/cloud-security-the-right-way-to-worry>

这里有一个我们经常听到的问题:从安全的角度来看，我们对云并不满意——您能在本地安装 Domino 吗？答案是肯定的(我们有 Domino [数据科学平台](https://www.dominodatalab.com?utm_source=blog&utm_medium=post&utm_campaign=cloud-security-the-right-way-to-worry)的本地和云托管版本，因为这是客户想要的),但我们认为这个问题的核心假设值得进一步考虑，因为它通常是错误的。

> 问题不是“我的数据在云中安全吗？”问题是:“我的数据在哪里更安全，是在云中还是在我管理的基础架构上？”

当考虑云时，一些公司会问一系列深思熟虑的问题，谨慎对待，并仔细考虑具体的风险。但是数量惊人的公司顽固地完全拒绝云，理由听起来像是偏执狂、教条或一般的 FUD。

## 哪个更安全...

无论是在创办 Domino 的过程中，还是我之前在一家大型对冲基金担任高管的工作中，我都在安全问题上做了大量工作，确保两家公司都有一个强大的战略来应对日益复杂的威胁。

从这个角度来看，云的安全优势对我来说是显而易见的。除非你是一家非常复杂的大型公司(甚至可能是这样)，否则你的数据在云中可能比在你自己的基础设施上更安全。问题不是“我的数据在云中安全吗？”问题是:“我的数据在哪里更安全:在云中还是在我管理的基础架构上？”

让我提供两个理由来说明为什么云可能对您的公司更安全。

首先，系统原因:对于云基础设施提供商来说，安全可能比您的公司更重要，这意味着当您将他们用作服务提供商时，您会从更高的安全优先级中受益。以索尼为例。网络安全可能是该公司的十大要务，但几乎肯定不在前三或前五名。除此之外，还要挑选优秀的电影，制作电影，雇用人才，发行和营销电影，谈判交易等等。现在想想亚马逊网络服务。安全可能是其第二或第三优先考虑的问题，因为安全漏洞代表着对其业务的生存威胁，而在索尼的案例中，正如最近的黑客攻击(尽管令人绝望)所证明的，情况并非如此。因此，亚马逊将在安全方面投入巨资——这是必须的。

其次，让我们看一下公司数据面临的一些主要威胁，以及从安全角度来看，我们的两种基础架构选项有何不同。(这种基于威胁的分析实际上是所有安全决策的制定方式。)在每种情况下，从安全角度来看，云要么更好，要么是中性的。

## 你应该担心的是

### 你的人民

内部威胁是任何公司面临的最大风险之一。根据 2014 年威瑞森数据泄露调查报告，2013 年，内部攻击占所有数据泄露事件的 18%。员工经常会拿走知识产权——为了经济利益，出于怨恨，为了好玩，有时甚至是出于意外。

除此之外，“物理盗窃或丢失”占 2013 年事件的 14%，当然，其中大多数发生在员工手中。“杂项事件”占事件的 25%，威瑞森报告指出，这些错误的来源“当然，几乎完全是内部人员”。最终用户、系统管理员和开发人员在把事情搞砸的问题上处于领先地位。”

换句话说，在明显的内部攻击、盗窃或丢失以及内部错误之间，**超过 50%的数据泄露事件是内部人员造成的**。对于一个心怀不满的员工来说，泄露您的一些安全数据有多困难？您的员工是否接受过避免钓鱼邮件的适当培训？你确定吗？他们中有多少人通不过网络钓鱼测试？你怎么知道你的员工是善意的呢？

这和云有什么关系？在最坏的情况下，使用云不会使内部威胁(可能是您最大的风险)变得更糟。但实际上，我们经常发现使用云可以减少这种威胁，因为将云用于其基础架构的公司会对其网络进行更多细分，这意味着员工更难从他们应该去的地方转移到他们不应该去的地方。此外，云网络往往会受到更多的监控。

### 您的软件更新过程

您是否正在运行带有任何已知漏洞的过期软件？你怎么知道的？当发布安全补丁时，您部署它们的速度有多快？

大多数云提供商，包括亚马逊，都极其积极地解决其底层基础设施中的关键漏洞。例如，在 2014 年早些时候，亚马逊在公布后的几天内就处理了严重的 Heartbleed 漏洞。

对于那些认为自己的安全性优于云提供商的公司来说，Heartbleed 是一个很好的基准。询问您的 IT 团队，您的公司用了多长时间才完全修补了 Heartbleed，并将其与 Amazon Web Services 用了多长时间进行比较。

### 人身安全

您的服务器在哪里？在你的办公楼里？在数据中心？谁能接触到这些机器？对于一个人来说，简单地捡起一个并带走它有多难？进入你们大楼的安全措施有多严密？

抛开威胁和攻击不谈，面对可能导致停机或数据丢失的灾难，您有多脆弱？这些威胁到你的可用性，另一个层面的安全。您的物理基础架构在火灾、加热和冷却问题、电气故障方面是否安全？

你可以读到很多关于 AWS 的物理安全的文章，但可以说它在访问控制和安全措施方面是世界一流的。大多数组织会发现这是不可能匹配的。

### 加密

你所有的内部流量都加密了吗？如果有人——一名员工或任何走进你办公室的人——将一个数据包嗅探器插入以太网插孔，他们能从电线上扯下什么？密码？用户数据？财务数据？许多公司要求对外部流量进行加密，但对其网络内的流量加密却相当宽松(这意味着他们的网络安全性与物理安全性一样好)。

您的服务器和员工机器上的硬盘是否加密？否则，如果有人带走了其中一个设备，后果会更加严重。

云基础架构即服务提供商通常具有一些功能，可以轻松实现静态和传输中数据的加密，或者在默认情况下提供此类配置。许多建立在云提供商之上的服务(包括 Domino 的云托管服务)自动使用加密。

这是一个很好的例子，说明了与比你更重视安全的合作伙伴合作所带来的安全好处。许多公司不在内部加密他们的数据。但是云提供商甚至不会考虑不提供这一功能。你要做的就是打开它。

## 点

当然，即使你使用云，上面的一些风险也是存在的(你的员工的计算机上可能仍然有易受攻击的敏感数据)。与此同时，一家成熟的大公司完全可以实施一套完整的安全机制，与 AWS 相媲美。

关键是云可能更安全，因为云提供商不得不在安全方面投入巨资，以使他们的业务更加。

## 情节

我已经描述了一小部分准备进攻的地区。重要的是要记住，聪明的攻击者会利用这些漏洞的组合。为了好玩，这里有一些让你晚上睡不着觉的假设场景，如果你使用云基础设施，其中大多数都不太可能发生:

*   有人闯入您的办公室或数据中心，偷走了您的机器。
*   一名天真的员工被一封在他的机器上安装了恶意软件的网络钓鱼邮件所迷惑，这反过来利用了您的一台服务器上的一个未打补丁的漏洞。
*   攻击者假扮成一名求职者，获得了贵公司的面试机会。当面试官不在房间时，攻击者将一个设备插入您的网络，从网络中获取密码和其他安全数据。
*   一天晚上，一名心怀不满的员工来到办公室，偷走了装有安全数据的物理机。
*   攻击者冒充您的电话公司的电工或修理工，讲述一个故事，说服接待员带他去电气室或服务器室。在那里，他把一个 u 盘插到你的服务器上，这个 u 盘可以做很多破坏性的事情。

## 结论和建议

良好的安全性是基于威胁的:您应该确保对威胁进行优先排序，并且对每种威胁都有良好的策略。在对云还是本地基础架构做出决策时，或者任何其他决策时，您都应该逐个威胁地比较每个选项的风险。无论您的决定如何，以下是一些保护您资产安全的建议:

1.  **系统地、分析性地思考威胁**。哪些资产对攻击者来说最有价值，攻击者可以通过哪些不同的方式来获取这些资产？您的系统的不同层(包括人员和物理基础设施)中最薄弱的环节是什么？
2.  请专业公司**进行安全审计**和渗透测试，找出你的安全弱点。您需要找出问题，以便解决它们。
3.  让安全成为你**员工培训**的一部分。所有员工都应该了解常见的社会工程技术和网络钓鱼技术，以便他们能够识别它们。警惕应该成为你文化的一部分。
4.  **关注你的人**。雇佣他们的时候要做背景调查。注意员工不满的迹象。如果您的安全团队有资源，监控员工的电子邮件和行为，寻找可疑活动。
5.  **锁定您的人身安全**。锁电脑，锁门，使用警卫，摄像头等。
6.  **加密您基础设施中的静态和传输数据**。
7.  设计并实现一个**补丁程序**，当漏洞被修复时，让你的软件保持最新。