# 大数据入门 - 简版进阶方案

大数据是一个内涵非常广泛的概念，涵盖了统计，数据科学，机器学习，数据挖掘，分布式数据库，分布式计算，云端存储，信息可视化等等诸多领域．
更详细的领域列表可以见Github上的 [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata)

一般个人和中小企业学习大数据可以先了解一些大数据应用的案例,再基于自身拥有的数据与业务(不论大小)进行实践.
注意, 盲目上大数据技术很容易浪费学习时间，也能带来大量不必要的运营成本．

http://www.planet-data.eu/sites/default/files/presentations/Big_Data_Tutorial_part4.pdf 这个大数据讲义(2012, 41页)综合了很多关于大数据的分析图表,也列举了不少关键技术用例. 


## 技术流

要想成为数据科学家, 通常可以选修网上相关课程，如coursera和小象学院．
这里我们面向Excel为基础的中小企业初学者设计一个简版进阶方案．

第0级：电子表格Excel -- 实现简单的数据分析与图表

第1级：关系数据库和SQL语言，例如Access和MySQL -- 利用数据库查询聚合大量业务数据纪录

第2级：基础的编程语言，例如Python/R，Java -- 通过程序将数据处理流程自动化

第3级：在程序中访问数据库，例如ODBC, JDBC -- 进一步提高数据处理自动化程度

第4级：了解一个NoSQL数据库，例如redis，mongodb，neo4j，elasticsearch --  根据业务需要选择一个合用的就行,传统关系数据库的性能未必不够用.

第5级：了解一点数据分析(含机器学习/数据挖掘)常识，如线性回归，多项式拟合，逻辑回归，KNN聚类，决策树，Naive贝叶斯等．Python/R/Java都有现成实现

第6级：如果要使用变态多的计算/存储资源，学习云计算平台，如亚马逊的EC2, S3, Google Compute Engine, Microsoft Azure

第7级：如果要处理变态多的数据，学习分布式计算Hadoop和MapReduce的原理，然后使用一个现成的实现，如Amazon Elastic MapReduce (Amazon EMR)

第8级：如果要在变态多的数据上做数据分析，学习spark, mahout 或任何一个SQL on Hadoop．

到此恭喜你，在任何一个＂大数据群＂都可以指点江山了．


## 应用流

从产品经理的角度来看, 首先要了解大数据的基本概念和特点,从而找到与自身业务流程相关的地方. 

下文 ["7 Key Drivers for the Big Data Market"](http://hortonworks.com/blog/7-key-drivers-for-the-big-data-market/)作者很概括地整理他在高盛云计算大会学习到的知识.
![](http://hortonworks.com/wp-content/uploads/2012/05/bigdata_diagram.png)

此外, 要多看看大数据应用案例,注意这些应用的规模很有可能只能在500强企业中才会出现. 中小企业可以从中借鉴经验,但不必完全照搬技术框架.


# 学习资源

## 数据科学家

http://www.douban.com/note/247983915/ 数据科学家的各种资源

http://www.aboutyun.com/thread-7569-1-1.html 大数据入门：各种大数据技术介绍

https://class.coursera.org/datasci-001  coursera上的公开课 大数据科学入门 Introduction to Data Science


## 应用案例分析
http://www.ibm.com/big-data/us/en/big-data-and-analytics/case-studies.html IBM的一些大数据分析案例

http://www.sas.com/resources/asset/Big-Data-in-Big-Companies.pdf SAS的大数据案例

http://www.teradata.com/big-data/use-cases/ Teradata的大数据案例

http://book.douban.com/review/6131027/ "大数据时代从入门到全面理解", 作者看法有些片面, 有很多吸引眼球的段子, 但与技术流结合地不够紧密.

