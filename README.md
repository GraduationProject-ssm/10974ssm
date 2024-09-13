# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 10974ssm酒店管理系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1Sh44eDEx6?p=73)


﻿酒店管理系统

摘  要

酒店管理系统采用B/S结构、java开发语言、以及Mysql数据库等技术。系统主要分为管理员和用户二部分，管理员：首页、个人中心、用户管理、客房类型管理、客房信息管理、客房预订管理、入住登记管理、退房评价管理、系统管理，用户；首页、个人中心、客房预订管理、入住登记管理、退房评价管理、我的收藏管理，前台首页；首页、客房信息、酒店公告、个人中心、后台管理、在线咨询等功能，基本上实现了整个酒店管理系统信息管理的过程。本系统在一般酒店管理系统的基础上增加了最新信息的功能方便用户快速浏览，是一个高效的、动态的、相互友好的酒店管理系统。

**关键词** ：酒店管理系统；Java技术；Mysql数据库；B/S结构； SSM框架
























Abstract



Hotel management system uses B / S structure, java development language, and MySQL database technology. The system is mainly divided into two parts: administrator and user, administrator: home page, personal center, user management, room type management, room information management, room reservation management, check-in management, check-out evaluation management, system management, user; home page, personal center, room reservation management, check-in management, check-out evaluation management, my collection management, front page Home page, room information, hotel announcement, personal center, backstage management, online consultation and other functions basically realize the whole process of information management of the hotel management system. Based on the general hotel management system, this system adds the function of the latest information, which is convenient for users to browse quickly. It is an efficient, dynamic and friendly hotel management system.

Key words: hotel management system; Java technology; MySQL database; B / S structure; SSM framework

**目  录**

[**摘  要	I****](#_Toc7748)**

[**ABSTRACT	II****](#_Toc32241)

[**目 录	II****](#_Toc21453)

[第1章 绪论	1](#_Toc14970)

[1.1背景及意义	1](#_Toc14561)

[1.2 研究现状	2](#_Toc9430)

[1.3 研究意义	3](#_Toc28716)

[第2章 相关技术	4](#_Toc21117)

[2.1 系统开发平台	5](#_Toc18620)

[2.2 平台开发相关技术	6](#_Toc4059)

[第3章 系统分析	7](#_Toc28711)

[3.1 系统目标	8](#_Toc3646)

[3.2系统流程和逻辑	9](#_Toc13495)

[第4章系统概要设计	10](#_Toc31763)

[4.1 概述	11](#_Toc20965)

[4.2 系统结构	12](#_Toc10073)

[4.3 数据库设计	13](#_Toc3981)

[4.3.1 数据库实体	14](#_Toc10073)

[4.3.2 数据库设计表	15](#_Toc3981)

[第5章 系统详细设计	16](#_Toc8826)

[5.1管理员功能模块	1](#_Toc24471)8

[5.2用户功能模块	1](#_Toc24471)8

[5.3前台首页功能模块	1](#_Toc24471)8

[第6章  系统测试	1](#_Toc5909)9

[6.1系统测试的目的	20](#_Toc2824)

[6.2系统测试方法	21](#_Toc16093)

[6.3测试结果	22](#_Toc6016)

[**结  论	23****](#_Toc1953)

[**致  谢	24****](#_Toc1495)

[**参考文献	2**](#_Toc10582)5





1 绪论

1.1研究背景

以往的酒店管理系统相关信息管理，都是工作人员手工统计。这种方式不但时效性低，而且需要查找和变更的时候很不方便。随着科学的进步，技术的成熟，计算机信息化也日新月异的发展，如今计算机已经进入了人类社会发展的各个领域，并且发挥着十分重要的作用。本系统充分利用网络的便捷，在工作效率上，得到极大地提高，延伸至服务水平也会有好的收获，有了网络，酒店管理系统的各方面的管理更加科学和系统，更加规范和简便。为用户提供酒店管理系统，方便管理员及时高效的管理所有的信息，给用户提供简单方便快捷的方式，并且数据准确，用户可以足不出户就可以对酒店管理系统相关信息进行查询等操作，而且还能节省用户查询信息的等待时间，所以开发酒店管理系统给工作人员带来很大的方便，可以大大的提高系统人员工作效率。


1.2研究现状

随着全球信息化的发展，人们的生活节奏越来越快，对信息的时效性越来越重视。以传统的宣传方式为载体的传统媒介早已不能满足人们对获取信息的方式、便捷性的需求。所以酒店管理系统渐渐成为人们关注的焦点。首先，酒店管理系统 ，网上获取信息的实时性、便捷性要远远高于传统媒介。系统一经上线，无论用户在世界的哪个角落，只要能够连接互联网，就能在第一时间获得想要的信息。

随着我国经济迅速发展，互联网对人们的生活及工作都带来了非常大的方便，各种管理系统都在不断的增加，但是酒店管理系统查询方面缺乏系统的管理方式，为提高酒店管理系统查询效率，特开发了本酒店管理系统。

酒店管理系统将通过计算机进行整体智能化操作，对于酒店管理系统信息的管理及数据保存都是非常多的，为用户提供一个智能化的管理信息平台，方便管理员可以随时随地的查看用户所需的详细信息及所有信息内容，增加管理员与用户之间的关系，计算机技术在现代管理中的应用，使计算机成为人们应用现代技术的重要工具。能够有效的解决获取信息便捷化、全面化的问题，提高效率。

如今，互联网已经深入人们的生活，智能手机、笔记本电脑等已经是人们获取信息的主要工具，因此，利用网络来进行酒店管理系统的管理也成为大势所趋，所以，开发一个酒店管理系统是必须的。

1.3 研究意义

而如今，21世纪是信息化的世界，互联网行业发展迅猛带动了生活中方方面面，信息管理的规范化、高效化的重要性日益凸显。

酒店管理系统利用信息的合理管理，动态的、高效的、安全的实现了用户所需信息，改变了传统的管理方式，使用户可以足不出户的查询需求信息。

1.4研究目的

虽然目前已有很多基于SSM平台的酒店管理系统，但尚未出现更详细的功能显示和信息查询。经过分析，用户的第一眼往往是看到一个软件的外观，一个漂亮的界面将吸引用户下一次点击和理解。为了让用户通过无意识的点击尝试进入每个界面和每个按钮，用户可以进一步了解软件的质量，因此良好的软件界面将是吸引用户注意力的第一步。因此，对于每个软件界面设计工作来说，一个应用程序是占据非常重要的一部分，在高端大气中吸引用户界面，满足用户体验将进一步完成整个应用程序的各项功能，良好的用户体验度将继续使用并经常打开并使用此软件。

此网站基本上实现了整个酒店管理系统信息管理的过程，向用户提供了一个安全、动态、高效的酒店管理系统。














2 系统开发环境

为了能够使本系统较好、较为完善的被设计实现出来，在功能上，我对新系统进行了细致的分析。通过详细的分析，我选择了SSM框架来进行开发设计，在数据存储上，采用 Mysql数据库来进行设计。本系统选择的开发语言为Java语言，系统开发平台为Windows 10系统，采用了B/S的结构。

## 2.1  系统开发平台
在线酒店管理系统中，ECLIPSE技术可以给用户带来极大方便，其主要特点就是可以使用户学习起来方便、快捷，另一方面就是信息储存量也是非常大的，该功能主要被应用为数据库中进行查询和编程。并且该功能的数据应用比较灵活，通过我们现在的发展可以得知，只要利用一小部分代码就可以来实现非常强大的功能。因此，该系统数据库开发主要是由ECLIPS技术进行系统代码管理。
## 2.2 平台开发相关技术
## ` `2.2.1 java简介
Java语言是在二十世纪末由Sun公司发布的，而且公开源代码，这一优点吸引了许多世界各地优秀的编程爱好者，也使得他们开发出当时一款又一款经典好玩的小游戏。Java语言是纯面向对象语言之一，从发布初期到现今，可以说有将近20多年的历史，已发展成为人类计算机编程语言发展史上的一个深远影响。

Java语言具有非常多种的特性：（1）跨平台的无关性；（2）面向对象； （3）安全性得以保障；（4）支持多个任务；（5）多种编写方式，代码编写简单。对比其他的低级语言、高级语言，Java语言具有明显的显著优势以及未来开阔的前景，可以广泛的应用在个人笔记本电脑、大数据、大型游戏等等。

首先，Java语言具有面向对象的特性，并且易于理解。关于对象，其实可以理解成每一种事物都是一种对象，包括我们人类自身都是一种对象。利用面向对象语言的基本特征来解决软件开发中的实际问题，为有效软件开发提供了技术支持。

其次，Java 语言具有很好的跨平台无关性。所编写出来的应用程序是Java语言编写的，那么就无需再使用编译器来修改程序代码，可以直接在任何计算机系统中运行，Windows系统可以运行，在Linux系统中也可以，也就是经过一次编译，可以到处运行，所以Java语言具有卓越的可移植性，可以很好的跨平台实现。
## 2.2.2 Mysql数据库
Mysql是一个多用户、多线程的服务器，采用SQL的数据库，数据库管理系统是基于SQL的用户以及服务器模式的关系，它的优点有强大的功能、操作简单、管理方便、可靠安全、运行较快、多线程、跨平台性、完全网络化、稳定性等，非常适合Web站点或者其他应用软件，在数据库后端的开发。此外，利用许多语言，用户可以编写和访问Mysql数据库的程序。Mysql数据库也是开放源代码的，开发者越来越喜欢使用Mysql关系数据库，应用范围也被推而广之。这是由于速度快和易用性， Web站点或应用软件的数据库后端的开发也都在使用它。

mysql 数据库它有很多的优点，例如它在操作上能够让人通俗易懂、功能强大、信息储存量高等优点。所以被人们广泛应用，对于mysql数据库来说它一般主要是对数据进行编码和查询，而且在很多的设计当中都应用到了该数据库，在此过程当中我们可以对常规的数据进行查询和组合，所以我们在进行使用mysql数据库的时候只要对编写一小段的数据就能实现相应的功能。数据库，就是数据存储的储藏室，只不过数据是存储在计算机上的，而不是现实中的储藏室，数据的存放是按固定格式，而不是无序的，则定义就是 ：长期有固定格式，可以共享的存储在计算机存储器上。数据库管理主要包括数据表的建立，数据存储、修改和增加数据，为了使数据库系统能够正常运行，相关人员进行的管理工作。数据表的建立，可以对数据表中的数据进行调整，数据的重新组合及重新构造，保证数据的安全性。
## 2.2.3 B/S结构
BROWSER/SERVER程序架构方式是使用电脑中安装的各种浏览器来进行访问和使用的，相比C/S的程序结构不需要进行程序的安装就可以直接使用。BROWSER/SERVER架构的运行方式是在远程的服务器上进行安装一个，然后在任何接入互联网的电脑上访问和使用。BROWSER/SERVER架构的开发方式给用户带来了极大的便利，在任何时间和地点都可以使用开发的程序系统。

在B/S的结构中，用户可以在任何可以上网的地方访问和使用系统网站的功能，没有地域和时间等方面的限制，B/S结构是把程序完整放置到计算机网络的服务器上，通过计算机互联网给用户提供远程的网络服务。在三层体系结构的B/S系统中，通过浏览器，用户可以对很多服务器发出请求， B/S系统会很大程度的降低工作量，用户只需要安装运行较少的用户端即可，大量的工作将由服务器承担，另外，服务器也完成包括访问数据库，执行应用程序的工作等等。

B/S结构主要有三层，分别为数据层、控制逻辑层和视图层。用户通过视图层，让控制层调用数据层的数据，从而达到整个访问过程。三层相互独立，维护方便，使用安全，三层有互相调用，提高效率。
#########
## 2.2.4 SSM三大框架
1.Spring的优势:
通过Spring的IOC特性，将对象之间的依赖关系交给了Spring控制，方便解耦，简化了开发。

2.Spring MVC的优势:
SpringMVC是使用了MVC设计思想的轻量级web框架，对web层进行解耦，使我们的开发更简洁。

3.Mybatis的优势:

数据库的操作(sql)采用xml文件配置，解除了sql和代码的耦合，提供映射标签，支持对象和和数据库orm字段关系的映射，支持对象关系映射标签，支持对象关系的组建提供了xml标签，支持动态的sql。

#########

**3 需求分析**

所谓需求分析就是，需求人员通过与用户的沟通，所获取的信息，然后把这些信息通过需求说明书的方式展示给用户和开发人员。

需求的可行性是分析和讨论发达的系统能达到什么样的要求。开发的系统或网站是否符合之前的要求。只有在预先评估系统的开发中，才能在系统开发和实施之前完成需求。系统在开发和运用过程中，在技术可行性、操作可行性、经济可行性和法律可行性这几点展开的详细说明，证明了这几点是可行的。在技术可行性中主要说明了Java是目前是较为通用、成熟的技术，具有较为强大的数据库开发功能、以及具有方便快捷的数据库接口设计功能。在现有的调研情况和所掌握的技术是必要可行的。在经济可行性中，主要说明了系统从调研时期的费用和后期维护和可节约的成本。操作可行性主要说明了系统和操作的简便性具有操作简便和上手快的特点。在法律可行性上，符合要求不涉及到侵权等问题在社会中能起到提高效率的作用。

**3.1系统目标**

本系统设计的是一个酒店管理系统的网站，此网站使用户实现了不需出门就可以在电脑前进行网上查询需求信息等。

用户在注册登陆后，在后台可以实现；首页、个人中心、客房预订管理、入住登记管理、退房评价管理、我的收藏管理等。然而管理员则可以在后台直接管理；首页、个人中心、用户管理、客房类型管理、客房信息管理、客房预订管理、入住登记管理、退房评价管理、系统管理等信息。本网站模块设计的独立性强，用户体验良好、后期维护修改管理十分方便。

3.2系统功能

此系统的功能分为用户模块和管理员模块：
######### （1）实现管理系统信息关系的系统化、规范化和自动化；
######### （2）减少维护人员的工作量以及实现用户对信息的控制和管理。
######### （3）方便查询信息及管理信息等；
######### （4）通过网络操作，改善处理问题的效率，提高操作人员利用率；
######### （5）考虑到用户多样性特点，要求界面简单，操作简便。
3.3系统流程和逻辑

系统业务流程图，如图所示：

![](/md/blog.001.png)

图3-1登录流程图

![](/md/blog.002.png) 

图3-2添加信息流程图

![](/md/blog.003.png) 

图3-3注册信息流程图



**4系统概要设计**

**4.1 概述**

酒店管理系统基于Web服务模式，是一个适用于Internet环境下的模型结构。只要用户能连上Internet,便可以在不受时间、地点的限制来使用这个系统。酒店管理系统工作原理图，如图4-1所示：

![](/md/blog.004.png)

图4-1  系统工作原理图

**4.2 系统结构**

本系统架构网站系统，本系统的具体功能如下：

酒店管理系统登陆界面

用户登录

密码正确

管理员界面

用户界面

![](/md/blog.005.png)

图4-2系统功能结构图

系统结构图，如图4-3所示：

![](/md/blog.006.png)

图4-3 系统结构图

管理员功能图，如图4-4所示：

![](/md/blog.007.png)

图4-4 管理员功能图

用户功能图，如图4-5所示：

![](/md/blog.008.png)
######### 图4-5 用户功能图

**4.3数据库设计**

4.3.1 **数据库实体**

管理员信息图，如图4-6所示：

![](/md/blog.009.png)

` `图4-6管理员信息实体图

用户信息实体属性图，如图4-7所示：

![](/md/blog.010.png)

图4-7用户信息实体属性图

客房信息实体属性图，如图4-8所示：

![](/md/blog.011.png)

图4-8客房信息实体属性图

入住登记信息实体属性图，如图4-9所示：

![](/md/blog.012.png)

图4-9入住登记信息实体属性图

#########

4.3.2 **数据库设计表**

此系统需要后台数据库，下面介绍数据库中的各个表的详细信息。

表4-1 allusers表

|列名|数据类型|长度|约束|
| :-: | :-: | - | :-: |
|id|int|11|NOT NULL|
|username|varchar|50|` `default NULL|
|pwd|varchar|50|` `default NULL|
|cx|varchar|50|` `default NULL|


表4-2 kefangxinxi表

|列名|数据类型|长度|约束|
| :-: | :-: | - | :-: |
|id|int|11|NOT NULL|
|addtime|varchar|50|default NULL|
|fangjianhao|varchar|50|default NULL|
|kefangmingcheng|varchar|50|default NULL|
|kefangleixing|varchar|50|default NULL|
|kefangtupian|varchar|50|default NULL|
|kefangsheshi|varchar|50|default NULL|
|kefangjiage|varchar|50|default NULL|
|kefangzhuangtai|varchar|50|default NULL|
|kefangjieshao|varchar|50|default NULL|

表4-3：kefangyuding表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|dingdanbianhao|varchar|50|default NULL|
|fangjianhao|varchar|50|default NULL|
|kefangmingcheng|varchar|50|default NULL|
|kefangleixing|varchar|50|default NULL|
|kefangzhuangtai|varchar|50|default NULL|
|kefangjiage|varchar|50|default NULL|
|yudingtianshu|varchar|50|default NULL|
|zongjiage|varchar|50|default NULL|
|xiadanshijian|varchar|50|default NULL|
|ruzhushijian|varchar|50|default NULL|
|yonghuming|varchar|50|default NULL|
|lianxidianhua|varchar|50|default NULL|
|shenfenzheng|varchar|50|default NULL|
|sfsh|varchar|50|default NULL|
|shhf|varchar|50|default NULL|


表4-4：ruzhudengji表

|列名|数据类型|长度|约束|
| :-: | :-: | :-: | :-: |
|id|` `int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|dingdanbianhao|varchar|50|default NULL|
|fangjianhao|varchar|50|default NULL|
|kefangmingcheng|varchar|50|default NULL|
|yudingtianshu|varchar|50|default NULL|
|zongjiage|varchar|50|default NULL|
|banlishijian|varchar|50|default NULL|
|ruzhurenshu|varchar|50|default NULL|
|dingfangyajin|varchar|50|default NULL|
|tiwen|varchar|50|default NULL|
|jinqixingcheng|varchar|50|default NULL|
|yonghuming|varchar|50|default NULL|
|lianxidianhua|varchar|50|default NULL|
|shenfenzheng|varchar|50|default NULL|

表4-5：tuifangpingjia表

|列名|数据类型|长度|约束|
| :-: | - | :-: | :-: |
|id|int|11|NOT NULL |
|addtime|varchar|50|default NULL|
|dingdanbianhao|varchar|50|default NULL|
|fangjianhao|varchar|50|default NULL|
|kefangmingcheng|varchar|50|default NULL|
|kefangleixing|varchar|50|default NULL|
|ruzhushijian|varchar|50|default NULL|
|tuifangshijian|varchar|50|default NULL|
|fangjianpingfen|varchar|50|default NULL|
|fuwupingfen|varchar|50|default NULL|
|zhengtipingjia|varchar|50|default NULL|
|yonghuming|varchar|50|default NULL|
|sfsh|varchar|50|default NULL|
|shhf|varchar|50|default NULL|

5 系统详细设计

**5.1管理员功能模块**

管理员登录，管理员通过输入用户名，密码，角色等信息即可进行系统登录，如图5-1所示。

![](/md/blog.013.png)图5-1管理员登录界面图

管理员登录进入酒店管理系统可以查看首页、个人中心、用户管理、客房类型管理、客房信息管理、客房预订管理、入住登记管理、退房评价管理、系统管理等内容，如图5-2所示。

![](/md/blog.014.png)

图5-2管理员功能界面图

客房类型管理，在客房类型管理页面可以查看客房类型等信息，并可根据需要进行删除，修改等操作，如图5-3所示。

![](/md/blog.015.png)

图5-3客房类型管理界面图

客房信息管理，在客房信息管理页面可以查看房间号、客房名称、客房类型、客房图片、客房设施、客房价格、客房状态等内容，并可根据需要进行删除，修改等操作，如图5-4所示。

![](/md/blog.016.png)

图5-4客房信息管理界面图

酒店公告，在酒店公告页面可以查看标题、图片等信息，并可根据需要进行删除，修改等操作，如图5-5所示。

![](/md/blog.017.png)

图5-5酒店公告界面图

轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作，如图5-6所示。

![](/md/blog.018.png)图5-6轮播图管理界面图

客房预订管理，在客房预订管理页面可以查看订单编号、房间号、客房名称、客房类型、客房状态、客房价格、预订天数、总价格、下单时间、入住时间、用户名、联系电话、身份证、是否支付、审核回复、审核状态、审核等信息，并可根据需要进行修改操作，如图5- 7所示。

![](/md/blog.019.png)

图5-7客房预订管理界面图
#########
入住登记管理，在入住登记管理页面可以查看订单编号、房间号、客房名称、预订天数、总价格、办理时间、入住人数、订房押金、体温、用户名、联系电话、身份证等信息，并可根据需要进行详情、修改、删除操作，如图5- 8所示。

![](/md/blog.020.png)

图5-8入住登记管理界面图

退房评价管理，在退房评价管理页面可以查看订单编号、房间号、客房名称、客房类型、入住时间、退房时间、房间评分、服务评分、用户名、审核回复、审核状态、审核等信息，并可根据需要进行详情、修改、删除操作，如图5- 9所示。

![](/md/blog.021.png)

图5-9退房评价管理界面图



**5.2用户功能模块**

用户登录，用户通过输入用户名，密码、角色等信息即可进行系统登录，如图5-10所示。

![](/md/blog.022.png)图5-10用户登录界面图

用户登录进入酒店管理系统可以查看首页、个人中心、客房预订管理、入住登记管理、退房评价管理、我的收藏管理等内容，如图5-11所示。![](/md/blog.023.png)

图5-11用户功能界面图

我的收藏管理，在我的收藏管理页面可以查看收藏名称、收藏图片等内容，并可根据需要对我的收藏管理进行详情、删除，如图5-12所示。

![](/md/blog.024.png)

图5-12我的收藏管理界面图

入住登记管理，在入住登记管理页面可以查看订单编号、房间号、客房名称、预订天数、总价格、办理时间、入住人数、订房押金、体温、用户名、联系电话、身份证等内容，并可根据需要对入住登记管理进行详情、删除，如图5-13所示。

![](/md/blog.025.png)

图5-13入住登记管理界面图

退房评价管理，在退房评价管理页面可以查看订单编号、房间号、客房名称、客房类型、入住时间、退房时间、房间评分、服务评分、用户名、审核回复、审核状态、审核等内容，并可根据需要对退房评价管理进行详情、删除，如图5-14所示。

![](/md/blog.026.png)

图5-14退房评价管理界面图
#########

#########
## 5.3前台首页功能模块
酒店管理系统，在系统首页可以查看首页、客房信息、酒店公告、个人中心、后台管理、在线咨询等内容，如图5-15所示。

![](/md/blog.027.png)

图5-15前台首页功能界面图



`    `用户登录、用户注册，在注册页面可以填写用户名、密码、姓名、联系电话、身份证等信息进行注册、登录，如图5-16所示。

![](/md/blog.028.png)

![](/md/blog.029.png)


图5-16用户登录、用户注册界面图

个人中心，在个人中心页面通过填写用户名、密码、姓名、性别、联系电话、身份证等信息进行更新信息、退出登录，如图5-17所示。

在客房信息页面通过查看房间号、客房名称、客房类型、客房图片、客房设施、客房价格、客房状态等信息进行点我收藏操作，如图5-18所示。

![](/md/blog.030.png)

图5-17个人中心界面图


![](/md/blog.031.png)

图5-18客房信息界面图
#########
**6 系统测试** 

**6.1系统测试的目的** 

程序设计不能保证没有错误，这是一个开发过程，在错误或错误的过程中都是难以避免的。虽然这是不可避免的，但我们不能使这些错误始终存在于系统中，错误可能会造成无法估量的后果，如系统崩溃，安全信息泄露，系统无法正常启动等，为了避免这些问题，我们需要测试程序，再测试过程中发现问题，并纠正它们，从而使系统更长时间稳定成熟。

本章的作用是发现这些问题，并对其进行修改，虽然耗时费力，但对于长期使用而言是非常重要和必要系统的开发。 

软件在设计后必须进行测试，调试过程中使用的方法是软件测试方法。在开发新软件时，系统测试是检查软件是否合格的关键步骤，以及是否符合设计目标的参考。测试主要是查看软件中数据的准确性，正确的操作与否，以及操作的结果，还有哪些方面需要改进。 

酒店管理系统的实现，对于系统中功能模块的实现及操作都必须通过测试进行来评判系统是否可以准确的实现。在系统正式上传使用之前必须做的一步就是系统测试，对于测试发现的错误及时修改处理，保证系统准确无误的供给用户使用。 

**6.2系统测试方法** 

在对酒店管理系统进行测试的时候在找到问题的情况下必须在第一时间找到解决问题的办法，不要存在侥幸的心理，这样才能让酒店管理系统开发的质量可以过关，并且开发的周期会大大缩短，还有就是在测试时，不要出现重复性的错误，遇到一个错误问题，要将整个酒店管理系统开发所牵扯的该问题都必须一一解决，提高酒店管理系统的安全性、稳定性。 

白盒测试与黑盒测试是测试中比较常用的两种方法。 

①结构测试俗称白盒测试：这种测试是在对程序的处理过程与结构都有详尽谅解的前提下，顺从程序内部的逻辑而完成的系统测试，以确定系统中所有的通路都能够遵照设计要求正常工作，不出现任何偏差。 

②功能测试又成黑盒测试：主要是针对程序功能能够按照设计正常实现的一种检测，在程序接口处进行，检测程序手法数据是否正常，与外部信息的交换是否完整。

功能测试，主要是对系统的用户登录进行详细的测试，但是登录不可以是任何人都可以登录成功的，所以对登录进行详细测试。

用户登录测试： 

|模块名称|测试用例|预期结果|实际结果|是否通过|
| :-: | - | - | - | - |
|登录模块|用户名：001   密码：123  |弹出错误提示，提示密码错误|弹出错误提示，提示密码错误|通过|
|登录模块|<p>用户名：123   </p><p>密码：002   </p>|弹出错误提示，提示用户名错误|弹出错误提示，提示用户名错误|通过|
|登录模块|<p>用户名：001   </p><p>密码：001   </p>|管理员登录成功|管理员登录成功|通过|
删除分类测试：

|模块名称|测试用例|预期结果|实际结果|是否通过|
| :-: | - | - | - | - |
|删除分类模块|分类名：最新通知  |删除成功、页面自动跳转|删除成功、页面自动跳转|通过|
修改密码测试：

|模块名称|测试用例|预期结果|实际结果|是否通过|
| - | - | - | - | - |
|修改密码模块|<p>原密码：666</p><p>新密码：123</p><p>确认密码：123  </p>|弹出错误提示，提示原密码错误|弹出错误提示，提示原密码错误|通过|
|修改密码模块|<p>原密码：001   新密码：123</p><p>确认密码：333  </p>|弹出错误提示，提示确认密码不一致|弹出错误提示，提示确认密码不一致|通过|
|修改密码模块|<p>原密码：001   新密码：123</p><p>确认密码：123  </p>|密码修改成功|密码修改成功|通过|
通过对功能的测试，酒店管理系统的基本功能都是可行的，不管是系统里面的功能，还是界面的设计都是可值得推广宣传的。



**6.3 测试结果**

经过对一系列测试结果的有效分析，本平台开发系统符合用户的要求和需求。所有的基本功能相对齐全，操作起来简单方便，测试系统性能良好，作为用户化系统使用是比较值得推广宣传的。

**结论**

此时项目已经完成，即使实施的时间不是很长，但是在这个过程中需要准备很长的一段时间去对系统设计开发所实际用到的技术进行学习和巩固。在学习的过程中，我逐渐认识到了我自身存在的一些不足。对于一些控制是必要的应用技能，能够理解，整个过程中仅仅是掌握了常用的性能和控制方法，我觉得还是相对来说挺容易的。从该系统中，系统的分析和设计的调查数据，已经经历了几个月，并且努力了几个月，该系统现在已经完成。很显然，该系统仍有很多不成熟的地方，在系统设计过程中有许多技术缺陷存在。在设计的过程中也涉及到了很多自己无法解决的问题，主要通过找专业的网站和论坛来解决这些问题，对于圆满完成我的毕业设计，他们也贡献了很大一部分力量。

系统的开发环境和配置都是可以自行安装的，系统使用SSM框架开发工具，使用比较成熟的Mysql数据库进行对系统前台及后台的数据交互，根据技术语言结合需求对数据库进行修改维护，可以使得系统运行更具有稳定性和安全性，从而完成实现系统的开发。

在设计酒店管理系统的过程中还遇到了一个棘手的问题，那就是自己的英语水平还有待提高，很多关于网站技术开发的资料文献都是英文版的，关键词语以及技术性词汇不能很好的理解。只有在借助翻译软件的实时性翻译功能的辅助下才勉强看懂。显然英语水平的高低直接影响到系统的开发过程。

回顾毕业设计的整个过程，既付出了努力与汗水也收获了很多难以忘怀的美好经历。虽然在系统开发过程中经历了各种各样的困难，自己也在不断研究与探索，可是系统的实现仍有许多不足之处。但是经过系统编程工作的学习让我有了更多的信心，我相信在未来的路上，我会走的更好。



**致　谢**

毕业设计结束的同时也意味着四年的大学生活就要结束了。酒店管理系统的完成以及如何在系统运行过程中实现的更好，这其中付出了很大的努力，这段时光将会终身难忘。 

在毕业设计的这一段时间里，离不开导师的细心指导，还有同学们的热情帮助，有时候几个同学在一起讨论系统中的某个功能模块如何实现，如何实现的更好，或是问题没得到有效的解决，就会没有心思做其他的事情，让我们对学习充满了动力。

在毕业设计即将结束之时，首先要感谢我的指导老师，谢谢您在毕业设计和毕业论文中对我的指导。在您的细心指导下我才能快速的掌握系统的相关功能，在您的大力帮助下我才能将课本上的知识与自己的项目结合，真正的做到学以致用。感谢您经常牺牲自己的休息时间，利用其丰富的教学和项目经验对我进行指导。 课堂上，您教会我们如何学习、教会我们新的知识，在课下，您又像朋友一样亲切，教会了我很多道理，让我意识到先做人、后做事。感谢所有教过我的老师，为我倾注了大量的心血，正是你们的谆谆教诲、严谨教学才使我能顺利的完成学业，再此向你们表示深深的感谢。感谢大学里教过我的每一位老师，真心祝福您们。

在这里还得感谢我的战友们，也就是同学们对我的大力支持及帮助。正是因为有你们的不断帮助、鼓励，熬夜通宵，不停的调试、测试程序，给我带来了极大的动力，才能最终完成网站的运行。我们在一起交流、谈论的时光，都将是我们在通往未来道路上的宝贵财富。我要深深地感谢你们！

毕业在即，在今后的工作和生活中，我会铭记师长们的教诲、同学们的帮助，继续不懈努力和追求，来报答所有支持和帮助过我的人！

最后，耽误了你们的休息时间来对本文进行审阅，评议和参与论文答辩的各位老师表示深深的感谢。在此，衷心的谢谢您们！



**参考文献**

1. 范立峰，乔世全，程文彬 Java程序设计 人民邮电大学出版社 2018。
1. （美）Kevin Mukhar, Chris Zelenak , James L.Weaver,Jim Crume ，JavaEE 5 开发指南，机械工业出版社，2018。
1. 陈雄华 企业应用开发详解 电子大学出版社，2017。
1. 李宁Java Web开发技术大全--Java+Servlet清华大学出版社，2018。
1. 聂哲 Java动态WEB技术实例教程。
1. 李绪成，闫海珍 java Web开发教程—入门与提高篇(Java+Servlet) 清华大学出版社 2018 。
1. 史胜辉，王春明，沈学华 JavaEE基础教程 清华大学出版社 2017 。
1. 霍尔等著 Mysql与Java核心编程 北京 清华大学出版社 2019
1. Joyce Farrell著 Java编程(英文影印版) 科学出版社 2019郭克华编  JavaEE程序设计与应用开发  北京 清华大学出版社 2019埃克尔著，陈昊鹏译．Java编程思想[M]．（第4版）．北京:机械工业出版社，2019：17-690．
1. Robert W.Sebesta著，刘伟琴等译．Web程序设计[M]．(第4版)．北京：清华大学出版社，2019：9-450．
1. 赵强 编著．精通Java编程[M]．北京：电子工业出版社,2018：34-56．
1. 萨师煊，王珊．数据库系统概论[M]．北京:高等教育出版社，2019：10-180．
1. 陈刚．ECLIPSE 从入门到精通[M]．北京:清华大学出版社，2017：17-380．
1. `	`孙卫琴．精通Struts:基于MVC的Java Web设计与开发[M]．北京:电子工业出版社，2019：19-421．



39
![](/md/blog.032.png)











