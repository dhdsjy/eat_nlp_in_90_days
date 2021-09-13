[TOC]

## 初衷

作为一个有着传统机器学习背景的打工人，却一直对当下火热的深度学习一知半解，缺乏实践，实在惭愧。回顾过去的深度学习的历程：杂而不精、浮于表面、缺乏思考！导致即使到现在，感觉还是个没入门的 “老白”。

基于过去的教训，准备花3个月左右的时间踏上深度学习之路。为了避免过去的杂而不精、浮于表面。这次准备通过以下措施改善这次的深度学习之旅

+ 为了专注，仅选择pytorch作为深度学习的框架，并将主要学习经历放在自己感兴趣的nlp方向
+ 为了逼迫自己思考，选择通过输出这种方式，每天总结整理，然后内化

另外，受《eat_pytorch_in_20_days》作者启发，开启这个《eat_nlp_in_90_days》仓库，希望也能帮忙降低一些深度学习爱好者的入门难度。

## 计划

**时间跨度**：2021.9.13-2021.12.13 最迟2021.12.31， 当作自己2021年的礼物吧

**主要学习时间**：工作日晚上 ：8：00-10：00；周末：下午+晚上

按照时间跨度初步将计划分为3个阶段：

### 阶段1：pytorch与深度学习入门

该阶段重点是pytorch和深度学习入门，尤其是pytorch的使用。这个阶段不追求“不求甚解”，关键是掌握pytorch的基本使用，对一些细节知识，不做深究，关健是形成pytorch的主干，细枝末节在后期补充。学习暂定资源如下：

+ [eat_pytorch_in_20_days](https://github.com/lyhue1991/eat_pytorch_in_20_days) ：正是受该仓库作者的启发，才有了这个项目。但是仅仅依据该项目还是很难把pytorch玩的溜溜的，因为这只是作者经过大量pytorch的学习实践，呈现出最终的一个结果，而其中的许多坑和细节是不为人所知。
+ [Python深度学习基于PyTorch](http://www.feiguyunai.com/index.php/2019/06/13/python-ml-pytorch/) ：一本介绍使用pytorch学习深度学习的书，从目录来看，是一本比较系统介绍pytorch的书籍了。先从numpy入手，在介绍pytorchtensor和Autorgrad，然后再介绍实现神经网络的工具箱：torchvision、nn、tensorboardX, 再到深度学习相关知识[这部分可以不看]。B站上还有个该书的视频[Python深度学习：基于Pytorch ](https://www.bilibili.com/video/BV12Z4y1W7px?p=1) 
+ NLP with pytorch：160多页的一本小书，比较粗略和概况，同上面的书结合起来进行pytorch的学习，应该不错！
+ [PyTorch深度学习快速入门教程（绝对通俗易懂！）小土堆](https://www.bilibili.com/video/BV1hE411t7RN/?spm_id_from=333.788.recommend_more_video.0)  B站上评价很高的一个pytorch入门介绍，值得一看！

+ [Practical Deep Learning for Coders (fast.ai)](https://course.fast.ai/) ：大名鼎鼎的fast.ai项目配套的MOOC，该课程的设计理论：To start, focus on what things DO, not what they ARE。这种先实践后理论的学习方式让人首先对学习的东西有个整体的感知，然后可以让人更有动力或兴趣去探索案例中的理论基础。我觉得很适合作为深度学习的入门。8个课时，相对来说比较基础（对有机器学习背景的人来说），计划集中学习一个周末解决
+ [Part 2: Deep Learning from the Foundations | fast.ai course v3](https://course19.fast.ai/part2) ：一共14个课时，前半部分集中于深度学习的一些基本知识：SGD、Backprop、CNN、Resnet、U-net、GANs；后半部分的9-14比较，该阶段暂时不考虑

+ 《深度学习入门：基于python的理论与实现》：这也许是和fast.ai设计截然相反的一本书，但是在日本非常流行。其理念是费曼所推崇的：What i cannot create, i do not understand!
+ [pytorch与神经网络形象讲解](https://www.bilibili.com/video/BV1SK4y1M7Xj?p=27) 莫烦的讲解视频，还是比较浅显易懂的，有时间可以看下

所以阶段1这两种学习理念的结合会迸发出什么样的火花呢？该阶段更重视知识的积累和内化整理，打好地基先！

### 阶段2：NLP由浅入深

该阶段重点是NLP知识的学习，由浅入深，形成自己的一套框架，该阶段在学习理论知识的同时，更应该注重实践。学习资源暂定如下：

+ [new fast.ai course: A Code-First Introduction to Natural Language Processing · fast.ai](https://www.fast.ai/2019/07/08/fastai-nlp/)  同样是fast.ai下的MOOC，有一段时间看过，但没有入门。
+ [李宏毅NLP(自然语言处理)完整课程](https://www.bilibili.com/video/BV1hM4y157xX?from=search&seid=8270551540266836821&spm_id_from=333.337.0.0) 名声在外的一位教授了，从这门课了解下这位教授
+ [【莫烦Python】机器要说话 NLP 自然语言处理教程 W2V Transformer BERT Seq2Seq GPT_](https://www.bilibili.com/video/BV1LA411n73X?p=2&spm_id_from=pageDriver) 简单入门了解，比较通俗易懂
+ [20个小时玩转NLP自然语言处理](https://www.bilibili.com/video/BV17y4y1m737?p=11&spm_id_from=pageDriver) 黑马的一个培训课程，B站的评价不怎么样，但是看着目录挺系统的，到阶段2再看下

+ 《深度学习进阶：自然语言处理》：日本人工智能领域非常畅销的一本书，该书是《深度学习入门：基于python的理论与实现》的续作。两本书的理念都是不使用深度学习框架，通过从0开始编写深度学习程序，借此了解背后运行原理。通过自己造轮子的掌握知识的方式，我是很认同的。What i cannot create, i do not understand! [【一起啃书】深度学习进阶自然语言处理_](https://www.bilibili.com/video/BV1ui4y1w7si?p=2&spm_id_from=pageDriver)

阶段2的除了理论知识的学习和内化，更注重实践技能，因此参考复旦大学邱锡鹏教授给实验室同学制定的[练习](https://github.com/FudanNLP/nlp-beginner)进行，即以下5个任务[nlp-beginner_solution](https://github.com/htfhxx/nlp-beginner_solution)：

1. 基于机器学习的文本分类 2周 [情感分析·推特文本情感分类 - Heywhale.com](https://www.heywhale.com/home/activity/detail/611cbe90ba12a0001753d1e9) 
2. 基于深度学习的文本分类 2周
3. 基于注意力机制的文本匹配 2周
4. 基于LSTM+CRF的序列标注 2周 放在阶段3
5. 基于神经网络的语言模型 2周 放在阶段3

### 阶段3：NLP进阶及应用

该阶段主要是阶段1和阶段2的查补缺漏，然后将知识应用于实践项目中。该阶段主要有2本书进行参考学习，然后通过竞赛融会贯通前期所学。

+ 《**深入浅出Embedding：原理解析与应用实践**》 自然语言处理的核心，我认为就是EMbeding技术，所以想通过这本书再次深入下对NLP的理解及应用
+ 《nlp实战》：和《机器学习实战》是同一出版社，还是有必要认真阅读的

阶段3的任务是参与异常NLP的竞赛，希望能进入top 5%。

## 产出

1. 2天形成一个比较系统的主题笔记，该笔记能系统梳理出这两天的学习精华（原理及推到 + 代码 + 应用），最好时能让别人看了你的笔记就不用再花2天时间去走你走过的坑了！建议思维导图和jupyter并用。每个周末一定要完善一周的笔记，对自己严格一点！
2. 3个阶段结束，有个高质量的pytorch入门教程和nlp入门教程
3. 希望每个月都有个比赛督促与检验自己的学习

## 记录

### 



