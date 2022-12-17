大规模集成网页 (LSIP)
====================
大萌　 	2022

　　大规模集成电路，LSIC，指的是，集成超过1000个晶体管的电路。  
　　大规模集成网页，LSIP，指的是，集成超过1000个超链接的网页。  

　　‘集成网页’是基于万维网(WWW)的一种新网页形态：在单一网页上集成同一个主题下的全部超链接，以实现该主题的网址全集。　按照集成规模，当超链接数量超过一百，称之为‘中型集成网页(MSIP)’；当超链接数量超过一千，称之为‘大规模集成网页’(LSIP，Large Scale Integrated web Page)；当超链接数量超过一万，称之为‘超大规模集成网页(VLSIP)’。

　　这种数据全集在以往，一般以数据库形式保存于服务器，然后由服务器脚本向用户输出查询子集。实现该查询过程的网页被称为‘动态网页’。　而随着网络速度的提高和浏览器能力的增强，服务器也可以直接发送数据全集给用户。集成网页就是一种包含某方面数据全集的‘静态网页’，用户的查询通过浏览器在本地实现，不需要再次经过服务器，节省了网络交互次数。

　　大规模集成网页(LSIP)利用更快更强的网络，把数据库网页化，是 [web 3.0](https://cn.bing.com/search?q=web+3.0) 的一种可能形式。本概念由大萌于2022年7月通过[在Github建立项目](https://diamonwoo.github.io/LSIP/)首次发表，该项目将以LSIP为基础，讨论‘集成网页’涉及的技术与应用。


LSIP 缘起与命名
--------------

　　‘集成网页’的实践，最早在2019年大萌制作《老生常谈云媒体》网页时出现，大萌在新冠疫情初期搜索各地官方媒体网站时遇到困难，便萌发出，要把所有官媒网站收录在一个网页的想法 ……

　　[LSIP 缘起与命名](named)

　　新概念诞生了！《中国千县政府网》可以称作：‘大规模集成网页’！英文：Large Scale Integrated web Page，缩写为：LSIP。


LSIP的适用领域
--------------

　　大规模集成网页(LSIP)把数据交给用户，在技术上主动提供了网站数据被复制的可能。这与传统动态网页在安全策略上是相反的。　动态网页把数据全集藏在服务器后面的数据库，用户无法直接获取，如果有黑客绕过了服务器脚本，下载了网站的数据库，叫做‘被拖库’，是严重的网络安全事故。　

　　所以，大规模集成网页 适合原本公开的数据，比如法律条款、政策文件、政府公开数据……等等。这些数据本来就允许用户复制，而LSIP能让用户复制得更快。

　　LSIP的数据不仅向用户开放，而且向互联网开放——这是App不愿意做的事情。包括搜索引擎在内的其他用户均可以复制或利用数据，这使得数据的复用率增加。　数据复用率增加将帮助数据获得进一步利用：统计、识别、机器学习，LSIP由此产生衍生信息。这个过程常被称为‘[数据挖掘(Data Mining)](https://www.zhihu.com/topic/19553534/hot)’。所以，LSIP可以成为人工智能(AI)的基础工程。

　　但是公开数据中有一些并不适合LSIP。那些随时随地会变化的数据，比如互联网的域名注册信息。用户即使下载了某一时刻的数据全集，下一秒的变化仍然需要到服务器查询，起不到节省网络交互次数的作用。　那些没有明确数量的数据，也不适合LSIP，网页的制作永远无法完成，只能‘集’，无法‘成’。

　　综上所述，大规模集成网页(LSIP)适用于公开类数据、有限集数据。


大萌的LSIP项目
-------------

+	📑[中国千县政府网](https://Laosheng.top/fuwu/qianxian)　超3000个超链接　中国3212个县级以上政府网址。
+	[法治政府有关部门](https://Laosheng.top/fuwu/fazhi)　超2000个超链接  
	　中国333个地级市的立法/普法/执法/司法/监察部门网址
+	🗺[世界国别速查表](https://Laosheng.top/ydyl/nations)　超1200个超链接  
	　249个国家或地区的概况、政府网址、中英文名称、双方使馆、ISO代码……
+	　中国法律简目 (规划中，暂停)

中等规模集成网页：

+	☁[中国新闻云媒体](https://laosheng.top/fly)　超900个超链接
+	🌞[一带一路云媒体](Laosheng.Top/ydyl/)　约500个超链接
+	💱[中国金融交易所](https://Laosheng.top/fuwu/jiaoyisuo)　预计300个超链接，建设中……

周边：

+	LSIP的应用示范文档　——　《[从世界杯看国别表](https://laosheng.top/broad/2022/worldcup)🏆》
+	LSIP在[老生常谈](https://laosheng.top/Lab/LSIP)网站的转载页

　　大萌希望**有识之士**加入LSIP创作者队伍，欢迎大家在自己感兴趣的领域设计、制作‘大规模集成网页’，为祖国高质量发展出力！　有关设计制作的问题，可以通过留言板、电子邮件、github网站[联系大萌](https://laosheng.top/author/helpme.txt)。

　　I hope users of other languages to make LSIP projects for their fellow citizens, which can help people understand the whole world more easily, which is not something that Twitter and Facebook can do.


LSIP的发展方向
--------------

　　LSIC和LSIP这两个概念非常相似，一个是硬件，一个是软件。单个晶体管的结构很简单，一个二极管只有阴、阳两个极，一个三极管只有 B、C、E 三个极；这和超链接的结构很相似。一个超链接也只有 超文本、链接网址 2个核心语法段，再加上Title和Target等标签。单个晶体管的功能也很单纯：实现电流增益；单个超链接的功能也很单纯：实现文件跳转。

　　LSIC之所以能流行，是因为它为广泛需求提供了低成本解决方案，这一点同样是LSIP的发展方向。‘普遍需求’这个词，定义好下，但列表难出，大家先去做吧。我们现在来分析成本。

　　LSIC的初级原料非常便宜，是二氧化硅（沙），成本可以忽略。所以，LSIC的成本主要在设计环节和生产环节，而且往往由不同的企业分工。比如，华为设计海思芯片，交给台积电生产。

　　LSIP的初级原料是公开数据，通常也很便宜；而软件的生产环节(拷贝)几乎是零成本，所以，LSIP设计环节的成本是整个成本的重头戏。　集成电路的设计有相当的难度，需要计算机辅助，集成网页也将朝这个方向发展，集成规模越大，设计难度越大。

　　但是LSIP还有一个硬件没有的成本——更新。传统硬件在出售之后，除了故障维修基本上不再有产品更新，我们的手机内存用满了能找厂家换个大的吗？不能。 但是软件项目可以升级到最新内容。　LSIP的本质是一个集文档、软件、互联网项目于一体的综合性产品，文档有审校任务，软件有升级任务，互联网有更新任务，不同的领域对产品后续维护的说法不一样。读者当然会期待在LSIP上能够看到最新最全的内容，这是LSIP的价值所在。

　　综上所述，集成电路的成本在设计、制造，集成网页的成本在设计、更新。如果您想加入LSIP创作者队伍，您需要准备设计和更新的能力。


LSIP的技术路径
-------------

　　未完待续……

+	大规模集成网页版权协议	—— 保护LSIP版权，促进LSIP发展，防止LSIP滥用
+	《用大规模集成网页对抗互联网垃圾农场》	—— 论文

　　欢迎读者[留言讨论](https://xoyondo.com/mb/yY8PqZMjKUgdcpn)，github用户可提交issue。


in English
----------

　　The 'integrated web page' is a new web form based on the World Wide Web (WWW):
Integrate all hyperlinks under the same topic on a single web page, to implement the full set of URLs for that topic.

　　When the number of hyperlinks exceeds one thousand, it is called a 'Large Scale Integrated  web Page' (LSIP), named by [DiamonWoo](https://diamonwoo.github.io/LSIP/) on github.com , 202207.

　　If you have a strong will and a pure heart, join in!

```
	大规模集成网页 © 大萌 202207-202212
	https://diamonwoo.github.io/LSIP
	CC 3.0 BY-NC-ND 　可转载-需署名-非演绎
```
回到首页<a href=".." title="返回老生常谈首页"><img src="../indexQR-Blue.png" /></a>  
https://Laosheng.top  
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-179794713-1"></script>
<script>  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());  gtag('config', 'UA-179794713-1');
</script>
