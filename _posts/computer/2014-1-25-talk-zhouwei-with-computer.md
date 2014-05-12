---
layout: post
title: 由计算机谈最强大脑周玮
category : computer
tagline: "原创"
tags : [计算机]
keywords: [最强大脑, 周玮， 计算机]
description: 
---
{% include JB/setup %}

最近看了，江苏卫视的最强大脑，特别当看到周玮的时候，让我想起了以前看到说印度有个人能算几百位数书的开方（前段时间这个人好像死了），看的时候很是振奋，可以说是不明觉历，以我的能力心算22\*22都费劲的人，真的很佩服此人 ，开始也没多想，只是觉得很厉害。

下面是周玮现场计算的三道题

![]({{ BLOG_IMG }}56.png)

随后看到网上有很多人质疑，关于质疑的种种声音我就不提了，有兴趣的可以自行搜索。

当看到有人给出了三道题的算法，可以看这里[http://www.guokr.com/article/437913/](http://www.guokr.com/article/437913/)。

看完后更是觉得五体投地了，这么复杂的过程，难度很大啊，网上的质疑文章都给出了算法，也都说常人经过训练也可做到，我想说的是，再怎么训练你，你能跑过博尔特吗，这个是需要天赋的，除了天赋之外，我想说的就是周玮一定有什么地方异于常人，也许在大脑的构造上。

我想肯定是多方面的原因，成就了周玮，下面就几方面展开。

## 方法论 ##

其实网友给出的解体方法，可以算作方法论，如下：

	613 = ( (63)2)2×6=...

具体步骤参见文章链接，其实这样分解开来，对常人而言，也是不可完成的任务。

这其实让我想到计算机的移位操作，比如仔汇编里面同样计算1024/2时，我们可以用除指令，也可以用移位指令，这其实就是方法的问题，其实在高级语言中，编辑器会帮我们优化的，不信看下的图，vc6将除以2优化为移位操作，当然优化的过程很复杂，这里只举了一个特例，有兴趣的同学可以自己研究。

![]({{ BLOG_IMG }}57.png)

假如两台同样配置的计算机，肯定是移位的速度更快了，只是计算机太快了，1/10000秒和1/100秒之间的差别我们根本就感觉不到，这其实也是写程序的时候要在性能和可维护性之间折中的原因，如果不影响用户体验，1毫秒和10毫秒又有什么区别呢，这其实也是开发时会把优化放到最后来做，因为根据80/20原则，1个月才会被用回执行一次的操作，优化它的意义不大。

好了，打住吧，扯远了，继续本文的主题，方法其实很重要，比如在发明乘法之前，计算11个11只和，只能计算11遍了，但有了乘法后就不同了，同样对数的发明将乘法运算降级为加法运算，这同样是方法的重要性，我们不能否定，周玮发明了自己的方法，毕竟乘法发明前，计算100个同样数字的和可以算天文数字了。

这其实在我们小学的时候也很常见，比如那些出水管，进水管的题，开始的时候我们学的都是算数法，后来我们学习了方程，可是用方程的速度明显没有算数算的快，因为寻找算数的过程其实 刚好是解方程最后的结果，我想现在很多人，都已经不会用算术法来解决这些问题，。

著名的爱迪生测灯泡体积的故事，其实也是方法的问题；我们计算机学的算法，也是方法的问题，同样的问题，算法不同，时间可能差很多，因为随着问题难度的增加，不同算法之间所差的时间会成爆炸式增长，计算25\*25，周玮的速度可能和常人一样，或者比常人慢，但计算123456789\*123456789，周玮的方法可能是和时间成对数，而普通人可能就是指数了。

## 天赋论 ##

如果将人脑比喻成计算机的话，正常人的脑子如果是pc的话，那周玮的大脑可以说是超级计算机，就上前面说的，博尔特在百米上有天赋，这个可能是常人再怎么训练也达不到的，古人说世上无难事只怕有心人，只要功夫深铁杵磨成针，但前提也要选择自己有天赋的方面，不然再怎么训练可能也只是平平常常。

继续方法轮的例子，假如两个台电脑用同样的方法计算，但是超级计算机的速度肯定会比pc快得不是一点半点，道理是一样的，一个人的大脑肯定和别人不一样，智商也不相同，在我们从小到大的学习生涯中，总有一些人，不怎么学习，但人家学习成绩就是好，没办法，智商高，每个人的人脑发育也不同，像我这种从下营养不良发育不好的可能不光是身体，我们的大脑压根就和周玮不再同一个频率，他是酷睿i7我是酷睿i1，不具可比性，这个问题没法解决，如果是电脑的话我们可以换一台，但是人的话就没办法了。

有些人天生记忆力好，有些人天生对数字敏感，有些人天生能吃，这都是父母给的，后天无法改变。

## 效率论 ##

众所周知，我们的大脑体积是固定的，脑细胞数目也是固定的，理论上在容量一定的情况下，能装下的东西就是有限的，如果你满脑子装着金钱，那你还能淡泊名利吗。

我们都有体会，我们没有小时候的记忆力好，而且都会说，现在不行了，上学的时候记忆力多么多么好，不知大家有没有想过我们现在要做的事情太多了，脑子里想的东西太多了，很难在塌下心来专心做一件事情了，从出生到现在，其实我们还是很厉害的，出生是一张白纸，到现在能在社会中生存，其实每个人都很厉害，小孩1岁会走路，3岁会说话，小学初中那么多知识，我们都能轻松应对，为什么，因为那时候我们专一，没有烦心事，小孩一天到晚都在学汉语，那能学的不快吗。

周玮很少与身边人交往，他脑子里面肯定没我们这么多乱七八糟的事情，心思都在算数上，效率100%，我们呢，可能连1%都不到，自然比不过了。

看见过一个从小失去双手的孩子，学会了用脚，穿衣服，用脚弹钢琴，我敢说，有手的人一定学不会，因为不能全心全意做这件事，自然会觉得别人做到了很厉害。

女孩子到了初中，成绩很容易下滑，不少有青春期女孩子比男孩子事情多的缘故，每天心理装着事情，自然干什么都干不好。

有人说我赋予感性，有人说我赋予理性，总之厚此薄彼，分配好优先级也是一种能力。

## 结构论 ##

接下来进入本文的重点，看了网友的分析，其实我想起了大学时，计算机组成结构老师讲的串行加法器和并行加法器，学过计算机的人都是知道，其实计算机里面只有加法器，加减乘除最后都会用加法来模拟，说不定我们人脑也是如此，丰富的情感，缜密的逻辑，都是几千亿可脑细胞并行做加法模拟出来的，其实很奇怪，大脑就是肉，怎么会有思想，同样是肉的大腿，为啥没有思想，空气中的无数细菌为啥没有智慧（当然可能有）。

又扯远了，回到我们的主题，我们的加法器假如它是四位加法器，如果我们要算8位数的运算就需要两个加法器，第一个计算低四位，第二个计算高四位，这时就有问题了，计算高四位的计算器只有等待低四位计算完成，才能进行计算，因为不确定有没有进位，串行结构就是这样，但是有牛人设计成了并行加法器，高位计算不需要等待低位的进位，进位可以瞬间计算出来，这样其实计算的效率就大大提高了，如果我们要计算10000位数的运算，如果高位需要等待低位的话，即便每秒能算100个数的加减法，那也需要100s，而并行的话就大大提高了效率，只需要1s。

上面只是举个例子，我想周玮的大脑结构可能和常人不同，我们计算100+200\*300/100的时候可能是顺序计算的，也许周玮是并行也说不定，也许他没发明算法，而它的脑子就是算法，能瞬间出结果，这也不是不可能的，大千世界无奇不有吗。

## 结论 ##

当上帝为你关闭一扇门时，也会为你打开一扇窗，塞翁失马焉知非福啊，我想可能不是上面的某一个原因造就了周玮，可能是综合的，也可能是其他原因，我们能做的就是祝福他，也祝福我们自己，上帝从不眷顾谁，愿世界更美好。

 

 

 