# nodeparty-ppt-20170729

![11WechatIMG1.jpeg](//dn-cnode.qbox.me/FsXSwv674JMk95C6iLYfzZDtTN7q)

北京7月29日Node Party线下活动（周六）下午2点到6点，将近100人，二次筛选后的基本都到了，5位讲师（justjavac，精子，@stonephp，张晋涛，胡戎），场地由裕波（360的波大）赞助，茶歇由stuq赞助（第一次办，没资源，厚着脸皮找stuq要的），晚上在很久以前羊肉串AA聚餐（我结的账，然后微信群AA付款，大家都付款了，非常厚道）。

![合影](img/合影.jpeg)

首先要说一下，为啥要组织一次这样的活动，最近很久没有纯node的活动了，而go类的活动非常多，前端也多，但大家都默认node流行，这其实对于node社区来说并不好，所以还是需要适当的曝光，我是非常希望大家能够多组织这样的活动，为社区繁荣，为大家能有一个更好的学习交流环境，我个人会尽全力去帮忙。

> 对于node party是node社区下的品牌，大家都可以组织node party活动，唯一的要求是要node相关，请大家注意！cnode官方会支持大家组织活动

![现场](img/现场.jpeg)

## 主题分享

**justjavac（jjc）《面向前端程序员的 V8 知识》**

狼叔点评：v8的内容略深，但介乎于chrome浏览器原理和node之间，是优化，了解原理必备技能。讲之前我就知道效果不会特别好，怕大家听不太懂，但能够让大家了解这些，有优化意识其实就足够了。jjc的演讲风格也非常好，非常逗。

![Jjc](img/jjc.jpeg)

QA环节，有人问jjc如何看大型项目源码，这个问题太麻烦了，希望jjc能写篇文章，对大家也能有帮助。

不知道谁偷拍的，狼叔显胖

![狼叔与Jjc](img/狼叔与jjc.jpeg)

**王子亭（精子）《如何通过索引加速数据库查询》** 

王子亭（精子），知名程序员，1995 年生于辽宁沈阳，现居江苏苏州，目前在 LeanCloud 任 Node.js 服务器端开发工程师。

- 什么是索引、二分查找、B-Tree
- 单字段索引：可加速哪些查询、不可加速哪些查询
- 复合索引：可加速哪些查询、不可加速哪些查询
- 索引的区分度、选择合适的字段
- 如何创建索引
- 索引的属性：主键、唯一、稀疏、TTL、数组

![精子演讲](img/精子演讲.jpeg)

狼叔点评：子亭非常年轻，这篇分享对索引知识的涵盖还是相当不错的，从原理到各种例子讲解，虽然是以 MongoDB 为例，但举例的是sql，所以也适用 MySQL等关系型数据库。数据库运维优化是非常重要的一个领域，目前node社区存在一个问题，就是单一技能，用node就只是用node，其实tps如果卡住，你一样无法做到性能很好的系统。子亭自己带了一个发光的名牌，非常有趣，最后还送了大家很多精子头像的帖子！

![精子回答问题](img/精子回答问题.jpeg)

**张晋涛《DevOPS 的养成之道》**

个人介绍： 张晋涛，网名 TaoBeier，美图公司 DevOPS 工程师。长期沉迷于二次元的程序猿。

![张晋涛](img/张晋涛.jpeg)

狼叔点评：选题时我和晋涛聊过，他对devops理解，很多开发工具实践都非常不错，虽然我没见过他，但对其水平还是相当认可的，这次分享ppt的前几页吓我一跳，基本都大标题，不过还好后面分享了美图的自动化运维实践，每周4000次的发布，基于ansible的经验分享，这部分社区内分享的不多。我个人认为需要有这样专业的人才来分享更多相关内容，这对node来说是必要的。ps：晋涛的电脑桌面很二次元，哈哈

**赵雄飞(stonephp)《Node.js 下 restful 最佳实践》** 

![Stonephp](img/stonephp.jpeg)

狼叔点评：精硕的首席架构师 赵雄飞（@stonephp）是cnode非常活跃的会员，他早年是写php的，所以对比php和node，讲的太直接，把现场很多人都逗乐了，他这次主要分享他写的框架 https://github.com/open-node/open-rest ，此框架在精硕落地多年，在多个系统里深度实践总结的一个框架。其业务深度，约定思想，快速开发等是非常值得借鉴的。现场演示代码，没视频录制，有点可惜。


**胡戎《DDD领域模型与微服务拆分》**

狼叔点评：核心3部分：介绍DDD领域模型微服务，领域模型微服务拆分落地，GraphQL API设计，这次时间给的有点少，而且这个主题相对来说比深，是很多人不太熟悉的领域，不过是很好的话题，希望大家能够多多讨论。

## 致谢

**感谢裕波**

感谢裕波所在的360公司提供场地，非常棒！裕波（波大）在360奇舞团。360奇舞团（奇虎75Team）是 奇虎360公司Web平台部前端工程师 + 部分特约嘉宾 组成的一个前端团队。有很多名人，像李松峰，李成银等都在奇舞团，他们的奇舞周刊也不错，https://weekly.75team.com/，另外还有一个单身美丽可爱的团花，关注他们的公众号可以找到她。另外波大在组织了一个高逼格的前端大会feday，北京，国际会议中心，8月26日，有教主，张克军等名家，主题相当不错。还有早鸟票，来和狼叔一起面基

![FEDAY](img/FEDAY.jpg)

**感谢StuQ赞助茶歇**

斯达克（StuQ）学院是极客邦科技旗下的技术教育品牌。

斯达克学院致力于推出实战驱动的IT课程，目前已推出系列人工智能、前端、后端、大数据、架构、云计算等热门技术课程。联系我们：StuQ微信小助手：stuq2017，资讯电话：17090404423，下面这个课程比较贵，内容涵盖比较全，是中高端精品课程。

![Stuq](img/stuq.png)


**感谢100offer提供的cherry鼠标垫**

![100offer](img/100offer.jpeg)

100offer 严格筛选来自世界各地的优质公司，打造了一个优秀人才和公司的平台，致力于帮最好的人才发现更好的工作机会。使用 100offer ，互联网人可在一周内收到来自中国、美国、新加坡等数千家优质企业的工作机会。

## 求职招聘

大家在微信群或演讲里说的，整理如下


- 北京美图招 Python, Golang, Vue.js ，简历投至 yt@meitu.com  注明来源 cnode 社区
 
- 闪银奇异招前端，技术栈Vue.js，简历投至 wildnode@gmail.com 注明来源 cnode 社区

- 在残酷的世界战斗，最让人热血沸腾的，是在漫长的征途中，寻找到并肩作战的人。美团点评酒旅招 Node.js, Vue.js , 简历投至 anchengjian@meituan.com, 注明来源 cnode 社区

- 北京 凡普金科企业发展（上海）有限公司  招聘前端 方向vue.js,react和node.js等 简历投至lipei01@finupgroup.com   注明来源 cnode 社区

- LeanCloud 招聘 Web 前端开发、Android 开发、技术支持（iOS 方向），可在 https://leancloud.cn/jobs/ 了解更多信息

- Admaster 招聘 Node.js 以及前端，技术栈 linux / Node.js / mysql / React / Bootstrap 简历投至 zhaoxiongfei@admaster.com.cn 注明来源 cnode 社区

- 17年应届毕业生，一年实习经验，工作中一个人负责前端，主要用vue.js做微信公众号，写微信小程序，自己的开源项目中用过react，node等，简历 http://wangyaxing.deercv.com/


## 欢迎大家也多多组织node party，社区会尽力帮忙

如果有想组织node party，社区会尽力帮忙, i5ting@126.com