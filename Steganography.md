
## 隐写简介

隐写是一个开放的问题，目标是构建隐蔽信道以隐藏通信行为的存在性。同密码的区别：密码是保护通信内容，往往容易泄漏通信行为。

隐写模型：载体（c）-消息（m）-隐写操作（Emb-Ext）-密钥(k)-载密（s）-分析操作（d(c,s)）。

隐写的核心挑战：载体的模型。 高维的未知分布模型，并且保持一般的分布模型是NPHard问题。

载体分为很多种，比如图像，文本，网络协议数据等。尽管有多种载体，其实目标都是一致的。

隐写操作-Emb-Ext：生成式（选择式）、修改式。其实一般来讲都是修改式。Emb将消息隐藏在cover中，Ext则从stego中恢复出消息。可以结合密钥提升隐写的安全性。

分析操作：检测载体是否被修改过，即暴露可能的隐藏的通信行为。

#
总结： Ext( Emb(c,m,k) = s, k ) = m, s.t. P(d(c,s)) ~ Perr. 
#

此时，想一想，如何将消息隐藏在载体中？有怎样的办法？简单还是困难？

最应该思考的是如何进行一般性的隐写。


#

技术总是从简单到复杂，从特殊到一般。此时应该暂时结束了。





##

- 参考书籍 : 

1. Jessica Fridrich.《数字媒体中的隐写术-原理、算法和应用》
2. 赵险峰 张弘.《隐写学原理与技术》



- ####  [回主页](./README.md) 



