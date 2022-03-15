# 非科班后端程序媛：我是怎么补齐基础cs知识的

来自: [NP-Complete](https://www.douban.com/people/ptsnmg/?_i=7377726FQMtshO) 2021-09-23 03:22:18

[原帖链接](https://www.douban.com/group/topic/247696395/?_i=7377709FQMtshO)

我本科时候想做金融，所以只上了三节计算机系的课：入门课、算法基础、还有基础机器学习。毕业的时候语言上我只会写python，基础算法和数据结构记得牢牢的，然后机器学习的理论框架搭的马马虎虎（但也能装逼是徒手写过神经网络的人了）。

后来做了几年交易员之后发现初阶交易员的工作跟SRE（site reliability engineer）特别像，于是就决定转码了。如果有姐妹们好奇SRE的话可以在下面留言，我可以开个新帖子单讲。

决定转码之后我非常幸运的上岸了，这里要感谢大四的自己拼着老命上完了算法课，应对各种算法题杠杠的。如果有姐妹们好奇金融转码的心路历程也欢迎在下面留言，开个帖子单讲。

我选了个infra组，主要写非常low level的C++，有时候还读一读assembly。入职的时候我还只会熟练的写Python，唯一一个稍微能沾边的strongly typed language就是Java，但也只会读，不怎么会写。上组之后非常抓狂，连大家拿来消遣的lunch and learn期间看的tech talk我都十有八九看不懂。

写了这么多context，下面着重来讲一讲我是怎么补齐基础知识，现在tech talk基本能看懂的：

自己打造cs的辅修（必修课们）

一般辅修的必修课就那么几个——算法，系统，还有硬件课（electrical engineering的入门）。

我本科上过了算法基础（MIT课号是6.006，神课），所以第一个开始学的是intro to systems engineering。这里面也涵盖了大多数我在组里必须必须要懂得的内容（比如线程间机器间怎么沟通，synchronization有哪些方法）。我挺懒的，基本就只听了公开课，作业什么就懒得写了。毕竟我的目的不是记得牢，而是了解框架、之后如果有需要继续补细节。我上的是MIT的6.033，在优tube和b站搜6.033能看到。

除了系统入门之外，我还看到操作系统在挺多学校课程里都是必修。这个我没看公开课，就一直在啃The Linux Programming Interface，觉得里面各个方面的设计都讲的挺清楚的。我目前看了……十分之一 ：）

硬件课的公开课应该也挺多的。我上的MIT公开课（课号是6.004，优tube和b站），也是只听lecture没写作业。现在过去一年了什么MOSFET之类全忘了，但是重要的东西还一直记得挺清楚，比如TLB、memory hierarchy这些工作上直接用得到的东西。

选修课

必修课上完，我再推荐几个有意思且有用的辅修课。

我心中的第一位是MIT的软件工程入门（而不是计算机科学入门）。这门课里偏重的是工科而不是理论，比如说怎么用git。我很喜欢里面讲的关于测试还有API contract的理论知识，比如怎么去partition unit test的problem space，还有怎么去定义API的pre condition和post condition。每次写unit test的时候有了partitioning框架之后马上就知道该写多少个test case。有了pre和post condition框架之后，我个人感觉跟组员讨论API design的时候我的逻辑更清晰，也更容易说到点上。课号是6.031，讲义在此：https://web.mit.edu/6.031/www/fa21/

第二位叫做missing semester，是几年前MIT的几位博士生发起的，意图在于教本科生们学校现有课程里缺失的关键技能——比如用vim，读shell script。这门课是以寒假兴趣小组形式出现的，所以大纲很短，我是入职之前一周过完的，后来上手之后实在感恩这些vim启蒙老师们。讲义：https://missing.csail.mit.edu/

其他日积月累

C++的话，Cppcon的tech talk是个很好的资源，优tube和b站都有。每年cppcon都有一个back to basics部分，讲比较基础的语法。每年也会有那种浅显的介绍一个大方向的talk，比如介绍concurrency，c++20 new features，或者各种各样的std library algorithms。

观察行业前沿的话，我关注了各个大厂们的engineering blog，做头发的时候集中看个几个小时。有几个podcast也偶尔有我很感兴趣的话题，比如software engineering daily，里面每期会介绍一个软件公司的产品，上下班路上听。

如果有对low level programming感兴趣的姐妹，lwn.net上有很多有意思的帖子，然后Matt Godbolt有个podcast叫two's complement也很有趣！

姐妹们有什么想要补充的或者问题的话，都欢迎在下面留言！

顺便链接一下我的其他帖子：

[怎么做一个能让人愿意教的新人](https://www.douban.com/group/topic/244035044/)

[改简历——我的五条小建议](https://www.douban.com/group/topic/231763869/)

[SRE工作简介 ｜ 我是怎么把卖方交易员的工作经历忽悠成软件相关的](https://www.douban.com/group/topic/250731282/)

更新：

谢谢这位姐妹 [ZFYT](https://www.douban.com/people/48469555/) ： 2021-09-30 12:11:32

好贴dd！我也来推荐一个神课，educative.io 的 Scalability and System Design for Developers. https://www.educative.io/path/scalability-system-design 这是一个learning path，它的最后一门课就是大名鼎鼎的Grokking System Design Interview，但直接看这门课可能会一头雾水，能背下来却不易理解。从头开始上，作者会用大白话给你介绍大型分布式网站的各种部件，比如database，cache，message queue, microservice...都是非常好理解的大白话，没有数学没有算法。看完一遍就有senior的基础视野了，然后再去细致领域钻研。
