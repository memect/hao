# 机器学习入门资源不完全汇总
2014-10-14版,好东西传送门编辑,转载请保留原作者和原文链接。


[入门攻略](#入门攻略) ｜ [课程资源](#课程资源) ｜ [论坛网站](#论坛网站)  ｜ [东拉西扯](#东拉西扯)  


## 基本概念
[机器学习](http://zh.wikipedia.org/zh/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0) 机器学习是近20多年兴起的一门多领域交叉学科，涉及概率论、统计学、逼近论、凸分析、算法复杂度理论等多门学科。机器学习理论主要是设计和分析一些让计算机可以自动“学习”的算法。机器学习算法是一类从数据中自动分析获得规律，并利用规律对未知数据进行预测的算法。因为学习算法中涉及了大量的统计学理论，机器学习与统计推断学联系尤为密切，也被称为统计学习理论。算法设计方面，机器学习理论关注可以实现的，行之有效的学习算法。


<img src="http://www.nltk.org/images/supervised-classification.png"/>

图1: 机器学习的例子：NLTK监督学习的工作流程图 (source: http://www.nltk.org/book/ch06.html)

<img src="http://work.caltech.edu/images1/map.png"/>

图2: 机器学习概要图 by Yaser Abu-Mostafa (Caltech) (source: http://work.caltech.edu/library/181.html)


<img src="http://nirvacana.com/thoughts/wp-content/uploads/2013/07/RoadToDataScientist1-1024x831.png"/>

图3: 机器学习和其他学科的关系： 数据科学的地铁图 by Swami Chandrasekaran (source: http://nirvacana.com/thoughts/becoming-a-data-scientist/)


## 入门攻略
* [机器学习入门者学习指南 @果壳网](http://www.guokr.com/post/512037/) (2013) 作者 [白马](http://www.guokr.com/group/i/0373595356/)  -- 研究生型入门者的亲身经历

* [有没有做机器学习的哥们？能否介绍一下是如何起步的](http://ourcoders.com/thread/show/2837/) -- 研究生型入门者的亲身经历，尤其要看[reyoung](http://ourcoders.com/user/show/25895/reyoung/)的建议 

* [tornadomeet 机器学习 笔记](http://www.cnblogs.com/tornadomeet/tag/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0/) (2013) -- 学霸的学习笔记，看看小伙伴是怎样一步一步地掌握“机器学习”

* [Machine Learning Roadmap: Your Self-Study Guide to Machine Learning](https://machinelearningmastery.com/machine-learning-roadmap-your-self-study-guide-to-machine-learning/) (2014) Jason Brownlee -- 虽然是英文版，但非常容易读懂。对Beginner,Novice,Intermediate,Advanced读者都有覆盖。
 * 他的这篇也非常好 [A Tour of Machine Learning Algorithms](http://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/)  （2013）
 * [Best Machine Learning Resources for Getting Started](http://machinelearningmastery.com/best-machine-learning-resources-for-getting-started/)（2013） 这片有中文翻译 [机器学习的最佳入门学习资源 @伯乐在线](http://blog.jobbole.com/56256/) 译者 [programmer_lin](http://www.jobbole.com/members/linwenhui/)


* 门主的几个建议
  * 既要有数学基础，也要编程实践
  * 别怕英文版，你不懂的大多是专业名词，将来不论写文章还是读文档都是英文为主

为了帮助中文用户有效跟踪发展趋势，我们做了一个[机器学习日报](http://ml.memect.com) 每天花几分钟就能长知识，网站上有样板。订阅 请给hao@memect.com发邮件，标题＂订阅机器学习日报＂。


### 更多攻略

* [机器学习该怎么入门 @知乎](http://www.zhihu.com/question/20691338) (2014) 
* [What's the easiest way to learn machine  learning @quora](http://www.quora.com/Whats-the-easiest-way-to-learn-machine-learning) (2013)
* [What is the best way to study machine learning @quora](http://www.quora.com/What-is-the-best-way-to-study-machine-learning)  (2012)
* [Is there any roadmap for learning Machine Learning (ML) and its related courses at CMU Is there any roadmap for learning Machine Learning (ML) and its related courses at CMU](http://www.quora.com/Is-there-any-roadmap-for-learning-Machine-Learning-ML-and-its-related-courses-at-CMU) (2014)

## 课程资源
Tom Mitchell 和 Andrew Ng 的课都很适合入门


### 2011 Tom Mitchell(CMU)机器学习
 [英文原版视频与课件PDF](http://www.cs.cmu.edu/~tom/10701_sp11/lectures.shtml)  他的《机器学习》在很多课程上被选做教材，有中文版。
* Decision Trees
* Probability and Estimation 
* Naive Bayes 
* Logistic Regression 
* Linear Regression 
* Practical Issues: Feature selection，Overfitting ...
* Graphical models: Bayes networks, EM，Mixture of Gaussians clustering ...
* Computational Learning Theory: PAC Learning, Mistake bounds ...
* Semi-Supervised Learning
* Hidden Markov Models
* Neural Networks
* Learning Representations: PCA, Deep belief networks, ICA, CCA ...
* Kernel Methods and SVM
* Active Learning 
* Reinforcement Learning
以上为课程标题节选

### 2014 Andrew Ng (Stanford)机器学习
 [英文原版视频](https://www.coursera.org/course/ml) 这就是针对自学而设计的，免费还有修课认证。“老师讲的是深入浅出，不用太担心数学方面的东西。而且作业也非常适合入门者，都是设计好的程序框架，有作业指南，根据作业指南填写该完成的部分就行。”（参见白马同学的入门攻略）"推荐报名，跟着上课，做课后习题和期末考试。(因为只看不干，啥都学不会)。" (参见reyoung的建议）  

 1.  Introduction (Week 1)
 2. Linear Regression with One Variable (Week 1)
 3. Linear Algebra Review (Week 1, Optional)
 4. Linear Regression with Multiple Variables (Week 2)
 5. Octave Tutorial (Week 2)
 6. Logistic Regression (Week 3)
 7. Regularization (Week 3)
 8. Neural Networks: Representation (Week 4)
 9. Neural Networks: Learning (Week 5)
 10. Advice for Applying Machine Learning (Week 6)
 11. Machine Learning System Design (Week 6)
 12. Support Vector Machines (Week 7)
 13. Clustering (Week 8)
 14. Dimensionality Reduction (Week 8)
 15. Anomaly Detection (Week 9)
 16. Recommender Systems (Week 9)
 17. Large Scale Machine Learning (Week 10)
 18. Application Example: Photo OCR
 19. Conclusion



### 更多选择

**2008年Andrew Ng CS229 机器学习** -- 这组视频有些年头了，主讲人这两年也高大上了.当然基本方法没有太大变化，所以课件PDF可下载是优点。
[中文字幕视频@网易公开课](http://v.163.com/special/opencourse/machinelearning.html)  |  [英文版视频@youtube](https://www.youtube.com/playlist?list=PLA89DCFA6ADACE599)  |
[课件PDF@Stanford](http://cs229.stanford.edu/materials.html)
 
 第1集.机器学习的动机与应用
 第2集.监督学习应用.梯度下降
 第3集.欠拟合与过拟合的概念
 第4集.牛顿方法
 第5集.生成学习算法
 第6集.朴素贝叶斯算法
 第7集.最优间隔分类器问题
 第8集.顺序最小优化算法
 第9集.经验风险最小化
 第10集.特征选择
 第11集.贝叶斯统计正则化
 第12集.K-means算法
 第13集.高斯混合模型
 第14集.主成分分析法
 第15集.奇异值分解
 第16集.马尔可夫决策过程
 第17集.离散与维数灾难
 第18集.线性二次型调节控制
 第19集.微分动态规划
 第20集.策略搜索

**2013年Yaser Abu-Mostafa (Caltech) Learning from Data**  -- 内容更适合进阶
[课程视频,课件PDF@Caltech](http://work.caltech.edu/lectures.html)

 1.The Learning Problem
 2.Is Learning Feasible?
 3.The Linear Model I
 4.Error and Noise
 5.Training versus Testing
 6.Theory of Generalization
 7.The VC Dimension
 8.Bias-Variance Tradeoff
 9.The Linear Model II
 10.Neural Networks
 11.Overfitting
 12.Regularization
 13.Validation
 14.Support Vector Machines
 15.Kernel Methods
 16.Radial Basis Functions
 17.Three Learning Principles
 18.Epilogue


**2012年余凯(百度)张潼(Rutgers) 机器学习公开课** -- 内容更适合进阶
[课程主页@百度文库](http://wenku.baidu.com/course/view/49e8b8f67c1cfad6195fa705)  ｜ [课件PDF@龙星计划](http://bigeye.au.tsinghua.edu.cn/DragonStar2012/download.html)

 第1节Introduction to ML and review of linear algebra, probability, statistics (kai)
 第2节linear model (tong) 
 第3节overfitting and regularization(tong)
 第4节linear classification (kai)
 第5节basis expansion and kernelmethods (kai)
 第6节model selection and evaluation(kai)
 第7节model combination (tong)
 第8节boosting and bagging (tong)
 第9节overview of learning theory(tong)
 第10节optimization in machinelearning (tong)
 第11节online learning (tong)
 第12节sparsity models (tong)
 第13节introduction to graphicalmodels (kai)
 第14节structured learning (kai)
 第15节feature learning and deeplearning (kai)
 第16节transfer learning and semi supervised learning (kai)
 第17节matrix factorization and recommendations (kai)
 第18节learning on images (kai)
 第19节learning on the web (tong)




## 论坛网站
### 中文
http://www.52ml.net/ 我爱机器学习

http://www.mitbbs.com/bbsdoc/DataSciences.html MITBBS－ 电脑网络 - 数据科学版

http://cos.name/cn/forum/22  统计之都 » 统计学世界 » 数据挖掘和机器学习

http://bbs.byr.cn/#!board/ML_DM  北邮人论坛 >> 学术科技 >> 机器学习与数据挖掘


### 英文
https://github.com/josephmisiti/awesome-machine-learning  机器学习资源大全

http://work.caltech.edu/library/ Caltech 机器学习视频教程库，每个课题一个视频

http://www.kdnuggets.com/ 数据挖掘名站

http://www.datasciencecentral.com/  数据科学中心网站


## 东拉西扯
一些好东西，入门前未必看得懂，要等学有小成时再看才能体会。

[机器学习与数据挖掘的区别](http://en.wikipedia.org/wiki/Machine_learning#Machine_learning_and_data_mining)
* 机器学习关注从训练数据中学到已知属性进行预测
* 数据挖掘侧重从数据中发现未知属性

[Dan Levin, What is the difference between statistics, machine learning, AI and data mining?](http://www.quora.com/What-are-some-good-machine-learning-jokes)
* If there are up to 3 variables, it is statistics.
* If the problem is NP-complete, it is machine learning.
* If the problem is PSPACE-complete, it is AI.
* If you don't know what is PSPACE-complete, it is data mining.

几篇高屋建瓴的领域概论 （参见[原文](http://machinelearningmastery.com/best-machine-learning-resources-for-getting-started/)
* [The Discipline of Machine Learning](http://www.cs.cmu.edu/~tom/pubs/MachineLearning.pdf)Tom Mitchell 当年为在CMU建立机器学习系给校长写的东西。
* [A Few Useful Things to Know about Machine Learning](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) Pedro Domingos教授的大道理，也许入门时很多概念还不明白，上完公开课后一定要再读一遍。
