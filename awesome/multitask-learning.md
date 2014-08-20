# MultiTask Learning 资源合集

contributors: 唐小sin 王威廉 李沐M 李航博士 李沐M Copper_PKU 复旦李斌 eeyangc 李晗littlefool 李亚超NLP lby9
   
keywords
  multi-task learning

## 微博讨论
问: @唐小sin 有没有multi-task learning的相关学习资料呢？
答: 维基百科上有不少经典文献。AAAI和ICML都有论文(北大/清华)。找到今年Honglak Lee (U Michigan 教授)的短教程。Lan Žagar 博士论文(2014) Ranking by Multitask Learning. 问答追踪: #93 求补充
http://www.weibo.com/5220650532/BiZl47k80?ref=

唐小sin：补充下吧，刚自己也找了一遍classic paper里面的Caruana的博士论文就是Multitask Learning，他是Tom Mitchell的学生。



王威廉：今年SIGKDD最佳博士论文颁给了CMU计算机系金光熹同学的论文 Reconstruction and Applications of Collective Storylines from Web Photo Collections http://t.cn/RPNmgEw 还有一个优胜奖也由CMU的multitask learning论文（Mladen Kolar，现芝大教授）获得。
http://weibo.com/1657470871/BhG9eDbcm

黄厝海滨：可以说说他的导师啊，因为这两者的导师都是Eric Xing (8月10日 22:42)




李航博士 ：#WSDM2014# Best paper award: Amr Ahmed, Abhimanyu Das, Alex Smola, Hierarchical multitask learning: scalable algorithms and an application to conversion optimization in display advertising
http://weibo.com/2060750830/AyJKFeZmQ

李沐M ：恭喜小伙伴和老板。这篇文章先被拒了一次，然后狠下心好好改了改写作。然后就happy ending了。老板然后眨着眼说，你懂了吗？我问懂神码？一呢，写作很重要，二呢，我写作很糟糕，你不能太依靠了。。。 (2月28日 03:53)


Copper_PKU：six NLP Task from Ronan Collobert, Jason Weston. A Unified Architecture for Natural Language Processing:Deep Neural Networks with Multitask Learning. ICML. 2008....畅读版【http://t.cn/8FOioh1】
http://weibo.com/1758509357/AwFYMa0ot


复旦李斌：最右说的应该就是vowpal wabbit中使用的feature hash方法，Ping Li每篇论文都会提到这个，Smola在ICML-09把这个方法用multitask learning，我也把这个方法用于graph控制特征维度。//@鲁东东胖: 有没有具体一点的描述啊 //@夏粉_百度: 在那次Adworkshop上，yahoo介绍了另外一种降维方法，通过hash的方法
http://weibo.com/2303649634/A83kaktRT


eeyangc：从生物角度，你可以说是共同的遗传作用；从machine learning角度看，你可以看成multitask learning；从统计学角度看，你可以说是random-effects and hierarchical structures。横看成岭侧成峰，远近高低各不同。
http://weibo.com/2107700352/A4CuScVmV



李晗littlefool：deep learning造冗余特征的思路不错，boosted decision tree 和 kernel svm 现在有用但是有其局限性。坚持我的观点 基于deep learning的无监督特征工程，和现有的非线性模型。配以online learning的实时特征抽取和模型更新，并借用multitask和transfer learning的知识来进行信息扩展和加强问题适用性。
http://weibo.com/1489962750/zp3daxlC6

李亚超NLP：A Unified Architecture for Natural Language Processing: Deep Neural Networks with Multitask Learning http://t.cn/aued1i
http://weibo.com/1732906091/zjTJ94IaH

lby9：1) Deep learning在文本中的应用比较有意思的是这篇《A Unified Architecture for Natural Language Processing: Deep Neural Networks with Multitask Learning》。基本上网络结构是底层的low level features是共享的，上层的任务（POS, Chunking, NER等）共享部分的底层feature。网络结构如图。
http://weibo.com/1873273890/zhvrbkS8c


## overview and survey
http://en.wikipedia.org/wiki/Multi-task_learning

https://sites.google.com/site/deeplearningcvpr2014/DL-Multimodal_multitask_learning.pdf Multimodal learning and multitask learning (2014)

http://www.siam.org/meetings/sdm12/zhou_chen_ye.pdf Multi-Task Learning: Theory, Algorithms, and Applications  (2012, SDM tutorial)

http://jcse.kiise.org/files/JCSE-V5N3-09.pdf  A Survey of Transfer and Multitask Learning in Bioinformatics (2009, JCSE)

http://www.cse.wustl.edu/~kilian/research/multitasklearning/multitasklearning.html  
Multitask Learning / Domain Adaptation related publications, maintained by Prof. Kilian Q. Weinberger

## classic paper
http://www.eecs.berkeley.edu/~russell/classes/cs294/f05/papers/caruana-1997.pdf  Caruana, R. (1997). Multitask learning: A knowledge-based source of inductive bias. Machine Learning

http://www.thespermwhale.com/jaseweston/papers/unified_nlp.pdf
Ronan Collobert and Jason Weston. 2008. A unified architecture for natural language processing: deep neural networks with multitask learning. In Proceedings of the 25th international conference on Machine learning (ICML '08)
* Copper_PKU, 李亚超NLP, lby9 共同推荐

## current
http://research.microsoft.com/pubs/210041/wsdm2014-multitask.pdf 
Amr Ahmed, Abhimanyu Das, Alex Smola, Hierarchical multitask learning: scalable algorithms and an application to conversion optimization in display advertising 
* 李航博士 ：#WSDM2014# Best paper award

http://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/download/8486/8820 Encoding Tree Sparsity in Multi-Task Learning: A Probabilistic Framework (2014) AAAI

http://machinelearning.wustl.edu/mlpapers/paper_files/icml2014c2_lic14.pdf Bayesian Max-margin Multi-Task Learning with Data Augmentation , (2014) ICML

http://link.springer.com/chapter/10.1007/978-3-642-37331-2_1  Beyond Dataset Bias: Multi-task Unaligned Shared Knowledge Transfer (2013)

## thesis
http://repository.cmu.edu/dissertations/229/ 
Uncovering Structure in High-Dimensions: Networks and Multi-task Learning Problems
(2013) Mladen Kolar, PhD Thesis
* 王威廉 推荐， KDD 2014 dissertation award Honorable mention http://www.kdd.org/blog/2014-doctoral-dissertation-award

http://eprints.fri.uni-lj.si/2486/  
Lan Žagar (2014) Ranking by Multitask Learning. PhD thesis.

http://gogoshen.org/ml/Research%20Paper%20Library/caruana97multitask2.pdf  
Caruana, (1997) Multitask Learning, PhD Thesis
* 唐小sin：补充下吧，刚自己也找了一遍classic paper里面的Caruana的博士论文就是Multitask Learning，他是Tom Mitchell的学生。

## related
http://burrsettles.com/pub/settles.activelearning.pdf  Active Learning Literature Survey, Burr Settles (2010)  1000+ citation

http://bigdata.memect.com/?s=multitask


