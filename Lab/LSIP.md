大规模集成网页 (LSIP)
=====================

　　大规模集成电路，LSIC，指的是，集成超过一千个晶体管的电路。  
　　大规模集成网页，LSIP，指的是，集成超过一千个超链接的网页。  

　　‘集成网页’是基于万维网(WWW)的一种新网页形态：在单一网页上集成同一个主题下的全部超链接，以实现该主题的网址全集。

　　这种数据全集在以往，一般以数据库形式保存于服务器，然后由服务器脚本向用户输出查询子集。实现该查询过程的网页被称为‘动态网页’。　而随着网络速度的提高和浏览器能力的增强，服务器也可以直接发送数据全集给用户。集成网页就是一种包含某方面数据全集的‘静态网页’，用户的查询通过浏览器在本地实现，不需要再次经过服务器，节省了网络交互次数。

　　集成网页按照集成规模，当超链接数量超过一百，称之为‘中型集成网页(MSIP)’；当超链接数量超过一千，称之为‘大规模集成网页’(LSIP)；当超链接数量超过一万，称之为‘超大规模集成网页(VLSIP)’。

　　大规模集成网页(LSIP)利用更快更强的网络，把数据库网页化，是 [web 3.0](https://cn.bing.com/search?q=web+3.0) 的一种可能形式。本项目以LSIP为基础，讨论‘集成网页’涉及的技术与应用。


LSIP的适用领域
--------------

　　大规模集成网页(LSIP)把数据交给用户，在技术上主动提供了网站数据被复制的可能。这与传统动态网页是相反的。　动态网页把数据全集藏在服务器后面的数据库，用户无法直接获取，如果有黑客绕过了服务器脚本，下载了网站的数据库，叫做‘被拖库’，是严重的网络安全事故。　

　　所以，大规模集成网页 适合原本公开的数据，比如法律条款、政策文件、政府公开数据……等等。这些数据本来就允许用户复制，而LSIP能让用户复制得更快。

　　LSIP的数据不仅向用户开放，而且向互联网开放。包括搜索引擎在内的其他用户均可以复制或利用数据，这使得数据的复用率增加。　数据复用率增加将帮助数据获得进一步利用：统计、识别、机器学习，LSIP由此产生衍生信息。这个过程常被称为‘[数据挖掘(Data Mining)](https://www.zhihu.com/topic/19553534/hot)’。所以，LSIP可以成为人工智能(AI)的基础工程。

　　但是公开数据中有一些并不适合LSIP。那些随时随地会变化的数据，比如互联网的域名注册信息。这样的数据需要随时随地更新，用户即使下载了某一时刻的数据全集，下一秒的变化仍然需要到服务器查询，起不到节省网络交互次数的作用。　那些没有明确数量的数据，也不适合LSIP，因为网页的制作永远无法完成。

　　综上所述，大规模集成网页(LSIP)适用于公开类数据、有限集数据。


LSIP 缘起
--------

+	[中国新闻云媒体](https://Laosheng.top/fly)


LSIP 示例项目
-------------

+	[中国千县地名图](https://Laosheng.top/fuwu/qianxian)


相关词汇
--------
*    IC = Integrated Circuit ，集成电路，也称‘芯片(Chip)’。
*  MSIC = Medium Scale Integration Circuit ，中型集成电路，晶体管100~1k个。
*  LSIC = Large Scale Integrated Circuit ，大规模集成电路，晶体管1k~10k个。
* VLSIC = Very Large Scale Integrated Circuit ，超大规模集成电路，晶体管10k~100k个。
*  LSIP = Large Scale Integrated Page ，大规模集成网页
* HyperLink，超链接，超文本标记语言(HTML)中的连接，也简称为 连接(Link)。


in English
----------
　　The 'integrated web page' is a new web form based on the World Wide Web (WWW):
Integrate all hyperlinks under the same topic on a single web page, to implement the full set of URLs for that topic.

<https://laosheng.top/lab/LSIP>
