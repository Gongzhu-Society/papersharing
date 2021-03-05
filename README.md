# papersharing
A repository for sharing mater's work in machine learning, optimization, statistics, etc.

* Klaverjas.pdf: 一种流行于德语区的扑克游戏，按墩打，拣正分，只用 4x8=32 张牌，某些情况下要求必须要出比之前大的牌（这有点像斗地主）。这是一本书太长没必要看，只要看 Springer 上他们自己写的简介就够了 (https://link.springer.com/chapter/10.1007/978-3-030-31978-6_9) 。
* shuffle: 关于洗牌的一些研究，这是纯粹的概率论，但我觉得很有趣
    * bayer92.pdf: 最主要的一篇文章，他论证了用 dovetail （燕尾，一种洗牌方法，最常见的分成两堆然后左右交错的洗法） 要洗8次才能洗匀，用石聚最喜欢的从中间抽出一部分放到最上面的方法要大约10000次，用桥牌比赛时摊开在桌子上揉的方法要好几分钟。他还描述了一种类似于相变的现象：在洗到七八次的时候牌的混乱程度（文章中有定义）突然就有一个上升。但是文章我有好几处看不懂，第二章那个魔术怎么变也就是他要引入的基础概念没看懂，定理3也没看懂。Youtube 上有文章作者亲身讲解，还挺清楚的 [The Best (and Worst) Ways to Shuffle Cards - Numberphile](https://www.youtube.com/watch?v=AxJubaijQbI)。
    * aldous86.pdf、0501401.pdf: 另外两篇与洗牌相关的文章，但我没看。
    * 我想洗牌方面有两个自然的推广，第一是他们都没有考虑 (S13)^4 的对称群，这会让8次才能匀的结果降低。第二是将之应用于麻将机，麻将机要洗多久一直是各大厂家争论不休的问题，我们可以给出建议的值，最好还能演示洗牌时间不够+无穷好的记忆力可以明显提高胜率。