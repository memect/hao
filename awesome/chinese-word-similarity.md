contributors: 杜振东_java , 刘知远THU , 昊奋, 算文解字,  Mr_UnderWaterrrrrr, 朱鉴

card list:  
 * Word2vector: http://bigdata.memect.com/?tag=word2vec
 * ESA:  http://nlp.memect.com/?tag=esa
 * python gensim: http://nlp.memect.com/?tag=gensim

## readings
### word2vector
https://github.com/danielfrg/word2vec

http://radimrehurek.com/2013/09/deep-learning-with-word2vec-and-gensim/

http://radimrehurek.com/2014/02/word2vec-tutorial/

@Mr_UnderWaterrrrrr :
http://t.cn/8Fc67pF 如何用word2vector 去训练中文语料。获得词的距离
http://www.weibo.com/1969853791/Atq0vz18S

@朱鉴 :
LDA or Word2Vec: http://t.cn/8DkHrFg
http://www.weibo.com/1656097544/AiJDZbfQ5

@朱鉴 :
这两天看了一下google的word2vec，目前看还是google的版本较容易理解，强调算法。这个算法的思想有点类似于latent factor model，假设设任何词可以用latent factor来表示，然后使用sgd算法去训练生成这个latent factor，假设非常棒！
http://www.weibo.com/1656097544/AhM49jMYL

### glove 
http://stanford.edu/~jpennin/papers/glove.pdf  Richard Socher, EMNLP2014, GloVe: Global Vectors for Word Representation

http://blog.csdn.net/adooadoo/article/details/38505497 glove入门实战 

@杜振东_java :
深夜总算完成了《glove入门实战》的码字工作，发出两张利用glove聚类的效果图，具体工作参考 http://t.cn/RP0xXNx ，代码在此 http://t.cn/RP0xOx0   感谢@刘知远THU 老师提供关于glove的信息，并感谢@张成_ICT 的帮助,顺便@夏睿 老师和@章成志 老师
http://www.weibo.com/1247953577/BhRfpyyJw

@刘知远THU :
斯坦福Richard Socher在EMNLP2014发表新作：GloVe: Global Vectors for Word Representation 粗看是融合LSA等算法的想法，利用global word co-occurrence信息提升word vector学习效果，很有意思，在word analogy task上准确率比word2vec提升了11%。 http://t.cn/RPohHyc
http://www.weibo.com/1464484735/BhbLD70wa

＠董力at北航 :
Yoav Goldberg写了个测评文档，大致结论就是GloVe和word2vec如果正常比的话 效果差不多，没有宣称的11%这么大。。 链接：http://t.cn/RP0gMXB
http://www.weibo.com/1895401411/BhVDWofI5

### ESA (Explicit Semantic Analysis)

http://en.wikipedia.org/wiki/Explicit_semantic_analysis

http://www.cs.technion.ac.il/~gabr/papers/ijcai-2007-sim.pdf Computing Semantic Relatedness using Wikipedia-based Explicit Semantic Analysis, (2007) IJCAI


@刘知远THU : 
可以考虑用传统的distributional representation/similarity的方法，即选取这些关键词出现的上下文的词来表示它，构建分类器。或者explicit semantic analysis（ESA），即用关键词在wikipedia文章中出现的情况来表示它。这些应该都比LDA的topic distribution更具区分能力。
http://www.weibo.com/1464484735/BfMxEh40q

@昊奋 : 
对于ESA，如果单纯使用wikipedia，由于中文维基百科的语料相比英语小很多，所以其实不满足ESA本身需要有高覆盖率的好处，需要自行采用百度百科或互动百科进行处理。我们会考虑利用zhishi.me来为大家提供ESA的服务。
http://www.weibo.com/2045933955/BhWfr2LYv

### python gensim

https://github.com/piskvorky/gensim/

@算文解字 :
基于分布的：Python gensim一般就够用了，包括了传统的bag-of-words (1-hot) vector representation基础上的模型，以及几种常见相似度表征，还有最新的word2vec都有。
基于资源的：中文没有免费的类似wordnet的资源，hownet是要收费的。然而也许会有帮助的一个免费资源是哈工大的扩展板"同义词词林"

@西瓜大丸子汤 : 
刚才说到python优化，举个具体的例子 Gensim的作者把word2vec(深度学习)做了几个经典优化：循环，numpy/BLAS，cython，多线程（真的可以）结果效率提高了上千倍，比Google开源出来的原始C版本还快3倍。他最近还写了个word2vec教程。无论是学习word2vec还是python优化，都不可不看 http://t.cn/Rvkt0Hk
http://www.weibo.com/1932835417/BcSwEc2iu

@尘绳聋-SYSU：Sklearn没有LDA/LSA让我很郁闷，不过还好有好用的gensim: http://t.cn/8k2M2tU PS. Python搞NLP好方便！
http://www.weibo.com/1254062861/B8WGG8Yii


### more readings
http://cs.tju.edu.cn/szdw/jsfjs/fengwei/papers/ICASSP2013_Nie/icassp2013.pdf MEASURING SEMANTIC SIMILARITY BY CONTEXTUAL WORD CONNECTIONS IN CHINESE NEWS STORY SEGMENTATION


http://www.cs.york.ac.uk/semeval-2012/task4/  Peng Jin, Yunfang Wu,  Evaluating Chinese Word Similarity

