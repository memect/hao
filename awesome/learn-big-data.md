#  
大数据是一个内涵非常广泛的概念，涵盖了统计，数据科学，机器学习，数据挖掘，分布式数据库，分布式计算，云端存储，信息可视化等等诸多领域．
更详细的领域列表可以见Github上的 [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata)

一般个人和中小企业学习大数据可以先了解一些大数据应用的案例,再基于自身拥有的数据与业务(不论大小)进行实践.
注意, 盲目上大数据技术很容易浪费学习时间，也能带来大量不必要的运营成本．

http://www.planet-data.eu/sites/default/files/presentations/Big_Data_Tutorial_part4.pdf 这个大数据讲义(2012, 41页)综合了很多关于大数据的分析图表,也列举了不少关键技术用例. 


# 应用流

从产品经理的角度来看, 首先要了解大数据的基本概念和特点,从而找到与自身业务流程相关的地方. 

下文 ["7 Key Drivers for the Big Data Market"](http://hortonworks.com/blog/7-key-drivers-for-the-big-data-market/)作者很概括地整理他在高盛云计算大会学习到的知识.
![](http://hortonworks.com/wp-content/uploads/2012/05/bigdata_diagram.png)

此外, 要多看看大数据应用案例,注意这些应用的规模很有可能只能在500强企业中才会出现. 中小企业可以从中借鉴经验,但不必完全照搬技术框架.

http://book.douban.com/review/6131027/ "大数据时代从入门到全面理解", 作者看法有些片面, 有很多吸引眼球的段子, 但与技术流结合地不够紧密.

http://www.ibm.com/big-data/us/en/big-data-and-analytics/case-studies.html IBM的一些大数据分析案例

http://www.sas.com/resources/asset/Big-Data-in-Big-Companies.pdf SAS的大数据案例

http://www.teradata.com/big-data/use-cases/ Teradata的大数据案例

# 技术流

要想成为数据科学家, 通常可以选修网上相关课程，如coursera和小象学院．
这里我们面向Excel为基础的中小企业初学者设计一个极简版进阶方案．

第0级：电子表格Excel -- 实现简单的数据分析与图表

第1级：关系数据库和SQL语言，例如Access和MySQL -- 利用数据库查询聚合大量业务数据纪录

第2级：基础的编程语言，例如Python/R，Java -- 通过程序将数据处理流程自动化

第3级：在程序中访问数据库，例如ODBC, JDBC -- 进一步提高数据处理自动化程度

第4级：学一个NoSQL数据库，例如redis，mongodb，neo4j，elasticsearch -- 针对大数据 *高速度*，*大容量* 特性寻找解决方案. 根据业务需要选择一个合用的就可以了．

第5级：学一点数据分析常识，如线性回归，多项式拟合，逻辑回归，KNN聚类，决策树，Naive贝叶斯等．Python/R/Java都有现成实现

第6级：如果有变态的容量，计算要求，学如何使用云计算平台，如亚马逊的EC2, S3

第7级：如果有变态的分析要求，了解一点Hadoop和MapReduce的原理，然后用一个现成的实现，如Amazon Elastic MapReduce (Amazon EMR)

第8级：如果有更变态的分析要求，学一点spark或任何一个SQL on Hadoop．

这时候恭喜你，在任何一个＂大数据群＂都可以指点江山了．
