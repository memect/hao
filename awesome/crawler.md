# 网络爬虫（Web crawler）资料

## 概念
http://en.wikipedia.org/wiki/Web_crawler A Web crawler is an Internet bot that systematically browses the World Wide Web, typically for the purpose of Web indexing. A Web crawler may also be called a Web spider,[1] an ant, an automatic indexer,[2] or (in the FOAF software context) a Web scutter.

http://zh.wikipedia.org/zh-cn/%E7%B6%B2%E8%B7%AF%E8%9C%98%E8%9B%9B 网络蜘蛛（Web spider）也叫网络爬虫（Web crawler）[1]，蚂蚁（ant），自动检索工具（automatic indexer），或者（在FOAF软件概念中）网络疾走（WEB scutter），是一种“自动化浏览网络”的程序，或者说是一种网络机器人。它们被广泛用于互联网搜索引擎或其他类似网站，以获取或更新这些网站的内容和检索方式。它们可以自动采集所有其能够访问到的页面内容，以供搜索引擎做进一步处理（分检整理下载的页面），而使得用户能更快的检索到他们需要的信息。

## 基本爬虫框架和最简单的例子

![](http://upload.wikimedia.org/wikipedia/commons/thumb/d/df/WebCrawlerArchitecture.svg/300px-WebCrawlerArchitecture.svg.png)
* queue: 数据表，包含一组URL。需要初始化，每次循环后加入未访问过的URL。要有去重机制。 高级一些还要避免爬虫陷阱。
* scheduler：调度模块，选择queue里的URL，以设定的频率调用下载模块。注意遵循[爬虫机器人须知 Robots.txt](http://en.wikipedia.org/wiki/Robots_exclusion_standard)。
* downloader：下载模块，给定一个URL，下载URL的网页内容(content) 以及相关元数据(http header)，写到下载数据storage中；此外还要提取网页内容中提到的URL，写到queue里
* storage：下载数据存储，同时保存网页内容（文本、图片...)和下载时的相关元数据(URL,下载时间, 文件大小, 服务器端最后更新时间...）

下面是两个非常简单的可执行代码样例
* https://gist.github.com/palianytsia/4246680  - java 
* https://github.com/kezakez/python-web-crawler  - python


## 进阶讲义
* http://www.slideshare.net/denshe/icwe13-tutorial-webcrawling
