# 工科PhD转码总结

来自: [收到offer了吗](https://www.douban.com/people/jiusiya/) 2022-01-26 00:23:53

[原帖链接](https://www.douban.com/group/topic/258695859/?_i=7378664FQMtshO)

基本上岸了，朋友说我这几年还蛮励志的，建议我总结一下写篇文章。不如就发在这里，大家一起讨论吧。打算从以下几个方面讲，我慢慢补充，也欢迎大家踊跃提问~

* * *

不知道触发了什么关键词，总是被转为仅自己可见TAT，我把完整内容都放[notion](https://juvenile-cuticle-d35.notion.site/PhD-aeb80986a2e64fdeb8e0f65ef4bded74)上了，大家可以在这里评论，也可以在notion里comment。我测试出关键词了再放回来~

### 1\. 背景介绍

我是Engineering的PhD，research会写一些Python，但是用的不多。大量刷题前我对数据结构的了解仅限于list，算法从没学过。下面是具体的时间线：

- 2018年中，意识到我的research方向在业界基本没有什么机会，我也不是很喜欢学术界，所以决定摸索一下其他方向，开始上一亩三分地看帖子。
- 2019年，决定试试data science，开始上一些统计的课。
- 2020年，开始试着投Machine Learning Eng和DS的实习。Zillow第一个给我面试（1月），是MLE intern的电面，考coding。为了准备coding，我开始刷leetcode。一周时间从零开始刷（抄）了100题，然后挂掉了面试。刷题前我看了一个视频，8小时快速过了一遍数据结构。但是面试的内容是Machine Learning coding，要实现KNN算法，我当时并不知道Machine Learning coding和普通coding的区别。后来irobot给我发了个DS的take home challenge，我看了要求侧重于visualization，所以找来[Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)，重点看了visualization的章节，然后完成了challenge。很快就收到了电面，但是也挂了。疫情来了后，零星有几个local的公司面试，但都挂了。后来我心想，反正也没准备好，不如趁着疫情在家，全心全意刷题。就这样刷了400多，到了秋天继续投DS的面试，顺手投了一个亚麻的SDE。结果只有这唯一的一个SDE捞了我，DS只有一个校友直招的给了一个面试，面完也挂了。亚麻的offer给的也很早（10月中），加上当时research和上课比较繁重，所以之后我也没继续面别的。这次秋招带给我最大的认知就是，DS真的好难。所以之后我就决定全心刷题转SDE。
- 2021年，上半年继续刷题，写paper，学一些实习可能会用到的东西。下半年收到return offer后也不敢放松，还想试试更好的。不过既然有了亚麻的保底，我就只投了一些自认为比亚麻SDE更好的position，主要是大厂的PhD NG。收到了5个的公司的AS, RS, SDE PhD的面试。其实我还挺意外的，没想到这些厂都搭理我。可能是有了实习后简历关好过很多，也可能是疫情好转，市场回暖。我非常兴奋，很认真的准备面试，然鹅还是面一个挂一个。整个fall非常郁闷，特别是看到其他同学动辄25万28万的大offer，非常羡慕。但是生活还是要继续，我调整了心态，迎接最后一个onsite。特意选在2022年，一方面是毕业前要准备论文和答辩，另一方面我觉得自己非常累，很想歇一歇再来战斗。
- 2022年，歇了几周后又投入到onsite的准备中。我觉得这个onsite也没有十全十美，有的问题我也没有答上来，已经做好挂掉的准备。我是这么安慰自己的，即便没有offer，但是我非常清楚地感受到3次onsite一次比一次表现好。假以时日，我肯定可以收到offer的，所以现在需要的就是耐心和等待。但是很意外很惊喜，我收到了offer！

从最开始摸索新方向，到上岸（拿到PhD level的offer）用了三年半。希望给姐妹们一点参考~

### 2\. 转码方向

#### 2.1 Data Scientist（不推荐）

这是我最先考虑的方向，因为想逃避刷题，而且看到大家都说PhD转这个方向比较好转。后来才发现，Data Scientist包含的东西太多了，有的公司侧重于做model，有的做analyst，面试的侧重点也不同。我觉得工科PhD需要格外注意（格外吃亏）的是，product sense和统计实验设计之类的。这两点对经济社科PhD来说应该问题不大，但是对于工科背景的我们来说，是不同的思维方式。后来又考虑到openings确实不如SDE多，我就放弃了这条路。

#### 2.2 SDE（强推）

这个方向我觉得是工科PhD最得心应手的，不就是刷code么。工科大家多多少少都有一点写代码的基础，即便是纯实验的工科，上手写code也很快，因为我们的思维方式是一脉相承的。另外，SDE的openings很多，发展前景也不错，即便从L3干起，以我们读PhD的毅力也能很快升职。所以我非常推荐没有ML背景的同学专注SDE，上岸后如果对ML感兴趣可以再转。

#### 2.3 Machine Learning Engineer（因人而异）

我的理解是MLE = SDE + ML，但是据我在论坛上看帖和向前辈请教所知，不同公司MLE的职责也不太一样。有的MLE主要做算法model，有的主要做ML infra。有人说MLE薪资比SDE略高，不过似乎也没有高很多，而且对于发展前景大家众说纷纭。大厂的AS, RS, SDE PhD其实和MLE差不多，只是title不一样（我听来的，如果不对请大家指正）。因此，我觉得对于有ML背景的同学可以考虑MLE，不过还是建议主攻SDE，毕竟上岸要紧。

### 3\. 面试准备

#### 3.1 Coding

说啥都没用，就得刷题。

刷题前学一下基本数据结构和算法，求速成的可以看看油管上8小时总结的数据结构（不让放链接没办法大家搜关键词吧），时间充裕的还是上个网课。另外强烈建议看看别人总结的视频，刷题效果事半功倍。付费的我就不推荐了，大家预算充裕可以考虑。推荐[古城算法](https://space.bilibili.com/21630984/)，他用的Java刷题，免费而且质量不错，up主是很认真准备的。另外看到很多人参加大雪菜的各种班什么的，价格很便宜，我也想报来着，但是他是用C++刷的所以最后也没报过。

整个学习路线可以这么规划：

1.  油管8小时数据结构总结（~20h，可以倍速看，另外听不明白的可能需要反复听，所以估计用20h）看到b站有人搬运：[【自学】谷歌大佬带你8小时速通数据结构+常用算法_哔哩哔哩_bilibili bilibili.com](https://m.bilibili.com/video/BV1Qo4y1973V)
2.  MIT/Princeton/其他学校网课快速过一遍视频和slides，最好做个笔记，方便以后刷题遇到了回头复习（~50h）
3.  Leetcode Explore Learn各个专题（可以先跳过DP和ML的部分）。由易到难，还有总结分析，我觉得非常适合初学者。刚开始刷题可能会慢些，但是没关系。一共14个专题，就估算成14*3 = 42h吧。
4.  这时候就可以开始面试或者跟同学朋友mock了。如果面试很近了，建议抛下一切立刻开始刷面经和LeetCode tag题。还没有面试的话可以跟着古城算法刷。都刷完了时间还很充裕，而且没有特别明确要面的公司的话，建议重点刷Facebook tag题。因为题目难度适中，基本涵盖Google和热门startup以外其他公司的考题范围，适合长期刷题用。

#### 3.2 Machine Learning

ML的面试一般有这几种：

1.  ML basics（必考）。也就是快问快答。问题大概是解释underfitting、overfitting，如何improve。大家可以到网上搜索ML interview questions，LinkedIn上[Machine learning community](https://www.linkedin.com/groups/961087/)也有人分享整理好的pdf。我主要是看了这里的一个data science interview和百面机器学习。和朋友前辈们互相mock也能了解到更详细的问题和答法。总之，这一步是可以速成的，只要你上过coursera的机器学习就可以。除了上面提到的，我还快速读了一遍[ISL](https://www.statlearning.com/)。大家如果时间紧迫就不必看书了，直接看总结好的面经题和答案。
2.  ML design（必考）。这部分是我最头疼的，因为它其实考察的是平时工作中的积累。我只有三个月实习经验，远远不够，而且这一部分需要比较强的专业背景。我主要参考了[grokking](https://www.educative.io/courses/grokking-the-machine-learning-interview)的design。以我的片面观察，NG常遇到的是recommender system（我遇到一次），和detect bad content（我遇到两次，同学遇到一次）。前者grokking上有，请大家熟记并背诵。后者涉及CV，NLP，由于我缺乏相关背景，挂的相当惨烈。多说两句，bad content这个会重点问data collection, label。
3.  ML project（必考）。有个小建议（不知是否有效我还没来得及试），讲你做过的ML project时，按照ML design的格式讲：problem definition, data collection, label, model, how would you improve it if you do it again。最后这个improvement相当重要，肯定会被问到，必须提前想一两招。Again，全文熟记并背诵。
4.  ML algorithm（可能不考）。这个一般在ML depth中被问到，就是考某些deep learning算法，需要长期的积累。我遇到的主要是问computer vision， NLP相关。挂的很惨。

#### 3.3 BQ

不管投不投亚麻，建议都按照亚麻的LP来准备。一亩三分地上有很多精华帖讲BQ的，大家可以比葫芦画瓢。[这里](https://www.douban.com/group/topic/259571990/?_dtcc=1&_i=4342928mQyaOhu)贴了几个例子。

#### 3.4 Mock interview

这个很多人都说过了，但是重要的事情可以多重复几遍。面试经验不足的话，一定要mock！！！一是熟悉一下场子，二是通过面试官的feedback可以查漏补缺。

### 4\. 心态

这是最最最重要的。我觉得啊，保持一个好心情，健康开心地活着才是活着的意义。

<这里不知道触发了什么关键词总之就是不让说不然转自己可见，完整版在[这里](https://juvenile-cuticle-d35.notion.site/PhD-aeb80986a2e64fdeb8e0f65ef4bded74)>

扯这么多，point就是大家要照顾好自己的mental health。让自己轻松一点。我会偶然读到《被讨厌的勇气》，也是因为我觉得那段时间都好累，想做点让自己开心完全放松的事。于是就拿起kindle看和学习无关的书。

找工作时，挫败感，委屈和急躁肯定都是有的。急躁焦虑的时候一定要calm down，安慰自己没有关系，你缺少的只是时间。不要看一些三个月六个月转码成功上岸blabla的帖子，从零开始的话做好以年为单位的持久战准备。和我一起转码刷题的朋友们，两年三年比比皆是。每个人的背景不一样，而且面试本来就有很大的偶然，面试官和面到的题目都充满了不确定性。我们能做的就是耐心和等待。

### 5\. 给转码PhD的建议

1.  刷题不要停
2.  瞄准大厂。首先大厂headcount多，其次问问题比较常规，而且对转专业PhD非常友好。
3.  导师好相处的话，可以一边读博士一边读一个CS相关master。不好相处的话趁早quit。我找工作以来已经听到好几个高年级PhD被老板坑的例子了。尤其提醒大家，Google PhD NG通过面试后是需要导师推荐信才能move forward，在这一步被导师坑就太可惜了。
4.  对无ML背景的PhD：强推Google PhD NG和Meta SDE PhD ML intern。基本不考或者考很浅显可速成的ML知识。
5.  对有ML背景的PhD（上过几门课的不算，需要research和ML强相关，比如做deep learning，有publication的）：海阔任您跃，天高任您飞。大中小厂的AS，RS，MLE尽管投，基本和CS的PhD差不多待遇，拿不到面试你来找我，我来帮你改简历。
6.  办个油管会员，找几个人一起组一个family plan，一个月3刀免广告看视频。我初期刷题的时候，主要靠看别人的视频讲解，搜题号就能出来一大堆。ML也有很多人讲的很好，比如statQuest，他的视频很短，可以迅速了解一个概念。

### Q&A

1.  关于简历里的项目。我没有做网上的一些转码项目，所以没有办法推荐具体的project。我找实习的时候放的三个项目分别是一个校内比赛（和data science有关），一个写了点code的research project，一个和ML有一丢丢关系的research project。整体来说，我的简历是非常弱的，所以没有什么面试机会。把实习的project加上后，基本能过大厂的简历关。

### 讨论区

<blockquote>

- 姐妹思路好清晰！ 请问有了解ds和sde待遇上的差别吗？
    - DS会比SDE工资低一些。可以在[levels.fyi](https://www.levels.fyi/?compare=Google,Facebook,Microsoft&track=Software%20Engineer)上看同一个公司各个level的DS和SDE的工资，大公司的数据还挺多的~  
</blockquote>
