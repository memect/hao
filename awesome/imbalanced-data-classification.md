Editor(s): 刘知远THU , xierqi , eacl_newsmth , 好东西传送门
https://github.com/memect/hao/blob/master/awesome/imbalanced-data-classification.md

## keywords
  Positive only,
  Imbalanced data,
  classification,
  
  link prediction,
  relation learning,

## readings
http://www.cs.cmu.edu/~qyj/IR-Lab/ImbalancedSummary.html  Yanjun Qi, A Brief Literature Review of Class Imbalanced Problem


http://homes.cs.washington.edu/~pedrod/papers/kdd99.pdf  (@xierqi 推荐) Domingo,  MetaCost: A General Method for Making Classifiers Cost, KDD 1999

http://www.aclweb.org/anthology/P/P13/P13-2141.pdf (@eacl_newsmth 推荐)  Towards Accurate Distant Supervision for Relational Facts Extraction, acl 2013

http://cseweb.ucsd.edu/~elkan/posonly.pdf  Learning Classiﬁers from Only Positive and Unlabeled Data

http://www.ele.uri.edu/faculty/he/PDFfiles/ImbalancedLearning.pdf He and   Haibo He,  Edwardo A. Garcia . (2009). Learning from Imbalanced Data. IEEE Transactions on Knowledge and Data Engineering, 21(9), 1263-1284.

http://www.computer.org/csdl/proceedings/icnc/2008/3304/04/3304d192-abs.html Guo, X., Yin, Y., Dong, C., Yang, G., & Zhou, G. (2008). On the Class Imbalance Problem. 2008 Fourth International Conference on Natural Computation (pp. 192-201).


## tools

http://www.nltk.org/_modules/nltk/classify/positivenaivebayes.html   nltk

http://weka.wikispaces.com/MetaCost  Weka


## datasets

http://pages.cs.wisc.edu/~dpage/kddcup2001/  Prediction of Molecular Bioactivity for Drug Design -- Binding to Thrombin

http://code.google.com/p/imbalanced-data-sampling/ Imbalanced Data Sampling Using Sample Subset Optimization

#### dataset list
https://archive.ics.uci.edu/ml/datasets.html?format=&task=cla&att=&area=&numAtt=&numIns=&type=&sort=nameUp&view=table  UCI dataset repo, classification category

http://www.inf.ed.ac.uk/teaching/courses/dme/html/datasets0405.html  dataset list


## discussion
### @eastone01 不平衡数据分类数据集 https://github.com/memect/hao/issues/47

<b>请问目前有木有关于不平衡数据分类（imbalance dataset classification）任务的人工二维toy dataset?</b>

刘知远THU: 不平衡数据分类，尤其是标注正例特别多，几乎没有标注负例，但有大量未标注数据的话，应当怎么处理呢？这个问题在relation extraction中很普遍。现在只能在大量未标注数据中随机抽样作为负例。

xierqi: 有段调研过这方面，90%都是采样，最大问题是评估方法不适合真实场景。个人推荐domingos的meta-cost，非常实用，经验设下cost就好。http://t.cn/RPiexE9

eacl_newsmth: 在关系抽取中，是正例特别多? 没有负例么？我怎么觉得很多情况下是正例有限，但负例很多（当然你也可以argue说负例其实很难界定）。。。。

刘知远THU：回复@eacl_newsmth: 就像knowledge graph中可以提供很多正例，但负例需要通过随机替换正例中的entity来产生，这样容易把也是正确的样例当成负例来看。

eacl_newsmth：回复@刘知远THU:恩，我估计你就要说这个例子，所以我在后面说，看你怎么界定负例，哈哈，我也纠结过好久，后来觉得其实还是正例少，而且很多时候你能保证正例是对的么？	

刘知远THU：回复@eacl_newsmth: 正例基本是正确的，例如来自Freebase的，但负例对效果影响很大。:)今年AAAI有篇MSRA做的TransH的模型中，就提出一个负例选取的trick，效果拔群。

eacl_newsmth：回复@刘知远THU:恩，KB中的实例确实是正确的，但是依据这些实例去海量文档中寻找的那些样本未必是正确的啊。 就目前的工作来看，确实很多在负例上做文章的工作都能把效率提升一些，去年语言所的一个学生利用“关系”特性，优选训练样本，也确实能提升性能。但单就这个问题而言，不能回避正例的可靠性	

刘知远THU：回复@eacl_newsmth: 你说的这篇文章能告诉一下题目么？我现在关注的还不是从文本中抽关系，而是做knowledge graph completion，有点类似于graph上的link prediction，但要预测的link是有不同类型的relation。

eacl_newsmth：回复@刘知远THU:http://t.cn/RPX75A3 恩，看了你们那里一个小伙的talk，感觉和sebastian之前的工作很相关啊，也许是他表述的问题？啥时候回北京？可以好好讨论一下。

