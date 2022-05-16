<p align="center">
  <a href="https://github.com/vuejs/vue">
    <img src="https://img.shields.io/badge/CSDN-年度征文-brightgreen.svg" alt="ubuntu">
  </a>
  <a href="https://github.com/vuejs/vue-router">
    <img src="https://img.shields.io/badge/内容-嵌入式科技竞赛-brightred.svg" alt="vue-router">
  </a>
  <a href="https://github.com/vuejs/vuex">
    <img src="https://img.shields.io/badge/查看方式-在线阅读-brightgreen.svg" alt="vuex">
  </a>
</p>


朝花夕拾，旧事重提之意。恰逢本科毕业，所以写作本文为年终总结，`实为大学四年的总结，和CSDN一起成长参与各类竞赛的回忆`。

四年里和小伙伴们一起辛苦奋斗做了那么多比赛，当比赛结束，那些作品便无人问津了，放在学校的犄角旮旯里随着时间风化，也许并没有那么完善，但是对于当时付出时间和精力的我们来说，尤为珍贵，因此今天将它们一一回顾，作为纪念。
本文要介绍：
> 解魔方机器人、四旋翼飞行器、循迹小车、树莓派魔镜、Robomaster机甲大师、物料搬运机器人、手势识别装置、液位测量器、半自动腐蚀箱、平衡车、FPGA……

<font color=#999AAA >（想要探讨交流可以直接私信我）</font>

<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">

<font color=#999AAA >提示：以下是本篇文章正文内容，下面案例仅供参考

如果您对这段经历感兴趣，可以在CSDN上查看我所做的[所有嵌入式项目](https://sanfengcs.blog.csdn.net/article/details/111880548)，现在本站该文章的排版还不是很好。

##  解魔方机器人

[video(video-I4yiKAX9-1609296467638)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=885827039)(image-https://ss.csdn.net/p?http://i0.hdslb.com/bfs/archive/fd6c88faccda50c3c9313476c80a836759bc2545.jpg)(title-解魔方机器人-气动二指)]



<font color=#999AAA >开发时间：2019.03-2019.05

解魔方机器人是所有作品中，从观赏性、功能的完整度、投入的精力以及演示效果上来说都比较优秀的作品了，因此把它放在第一个。
正如视频里所看到的，在22秒内，这个机器人便可以成功解出来一个魔方，不需要对魔方进行任何破坏性的操作。作为相对来说比较复杂的一个自动控制系统，从机械电控到视觉都需要做很多工作。

基本方案是利用摄像头识别魔方六个面的颜色，然后通过气动控制爪子开合，步进电机控制爪子旋转，完成整个步骤。

当时处在保研的关键时间大三下，我已经有了放弃的念头，是`阿政`苦苦支撑，一个人完成了机械部件的选购以及装配工作。之后我才去做了一些微不足道的电控的工作，在视觉方面因为Linux不够熟悉，我也没有完成预定的Python程序移植的工作。
可以说没有阿政不会有这么漂亮的机器人。而在比赛完成之后，也是阿政，在学业紧张的时刻，带着这个机器人去云南完成了为期3天的展览活动，他付出良多，我永远感激。`有这样一个朋友，和你志趣相投，境遇相同，彼此理解，他是你触手可及的榜样，是一件很幸运的事情。`

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201230111326798.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MjA4OTE5MA==,size_16,color_FFFFFF,t_70)

##  RoboMaster机甲大师赛


[video(video-jAUkLWxl-1609212771426)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=65688721&page=11)(image-https://ss.csdn.net/p?http://i1.hdslb.com/bfs/archive/8399d57fe4478eadb3a45a3448cf5efe51f53212.jpg)(title-RoboMaster2019总决赛【8强争夺赛】合集)]

上面是bilibili上关于RM的比赛视频，机器人通过摄像头识别对方兵种的装甲板，喷射弹丸击中对方机器人。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201230142202237.gif)
<font color=#999AAA >开发时间：2019.10-2020.08

在RM中，我参加了视觉组，主要是在Linux平台上使用C++以及Open CV库完成视觉处理的工作。对于Robomaster这个我真的是吹爆啊！

从对技术的锻炼程度上来说，我觉得这可能是本科生能够接触的最高赛事。100人左右的大队伍，多个大型机器人兵种，机械电控视觉等团队互相协做，论坛上不断沉淀的技术资料……正是视觉组一年多的学习中，我认识了马哥叶师傅英平老师等计算机专业的学生，从Linux指令到固态硬盘的选购，我都向他们请教一翻，算是真正踏上了CS的学习道路。

另外在学习CMake的过程中，我和英平建了CMake-examples的[github仓库](https://github.com/SFUMECJF/cmake-examples-Chinese)，star数不断增长，算是我们开源想法的小小实践。

##  工程训练综合能力竞赛

[video(video-tUlf8zTa-1609316080456)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=885860203)(image-https://ss.csdn.net/p?http://i1.hdslb.com/bfs/archive/08f1a94c69669352cc15f65551dfebe3a484b0bc.jpg)(title-工程训练综合能力竞赛-物料搬运机器人)]

<font color=#999AAA >开发时间：2018.09-2018.11

两个半月的时间，阿政、栋仔和我三个人，牺牲了所有的业余时间，终于从0开始完成了这个机器人的所有功能，循迹识别黑线以及激光测距定位小车位置，摄像头识别物料色块和二维码，机械臂抓取并放置物块到制定地点。我们三个人齐心协力，完成了3D打印、激光雕刻、电路板绘制、贴片元件焊接等所有步骤。不过电机和轮胎是买的。

我们为这个比赛付出了很多，但是没有人带，在陷入瓶颈时也没有多向老师询问，所以三个人踩了很多坑。传感器选择上没有考虑到比赛现场体育场灯光的因素，这个破TCRT5000循迹模块真是害人不浅……所以这个比赛我记忆最深的就是，但凡涉及到类似摄像头、循迹等功能，一定要考虑光线的影响。

后来领快递的时候，发现有的快递员会将包裹放到黑布包裹的黑箱子里，识别那个码。箱子里只有内部光线，可以很好地和传感器搭配，看来屏蔽光线对摄像头影响的思想其实在工业界相当普遍。

2018年，我将这次比赛的经历放到了CSDN上，有了8000多的阅读量，也有很多网友陆陆续续加了微信和qq群，我因此认识了不少朋友。

相比于机械来说，电子设计以及计算机方向的知识分享起来是如此方便有效！

##  东北地区光电设计竞赛（二）
[video(video-sjL8P9jb-1609211579592)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=75047867)(image-https://ss.csdn.net/p?http://i2.hdslb.com/bfs/archive/f2def13621d4e05e2949a41e7e402cc8072ebb0e.jpg)(title-【个人回顾】2th东北地区光电竞赛.14th恩智浦室外越野.19电赛)]



当时时间紧张没有来得及拍我们自己的视频，上面的视频前2分钟是当时比赛速度最快的小车。当时还问这老哥借了一下螺丝刀……这个比赛任务是小车需要在每个客站，根据红外频率放下对应数量的圆珠铁球。

我们的小车效果如下，速度无法比拟智能车，人家专业的：

[video(video-RG0rkVih-1609298993696)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=415819357)(image-https://ss.csdn.net/p?http://i0.hdslb.com/bfs/archive/91a59f388da80d69395c009442150c6c5642af7c.jpg)(title-第二届东北地区光电设计竞赛-放客公交车)]

<font color=#999AAA >开发时间：2018.11-2018.12</font>
在上面那个工程训练综合能力竞赛的物料搬运小车上改了一下，机械臂换成圆盘状，加了一个红外频率读取模块。虽然完成了所有的功能，不过速度终究比不了人家做智能车的，所以最后只拿了二等奖。因为有之前的铺垫，所以这个比赛没有花费太多时间，可能这也是做好一件事情的重要性，之后在各种比赛以及大创环节可以对一个作品进行不断的完善。
参加这个比赛也很辛苦了，在寒冷的研教楼，三个人在木有暖气的教室里睡了一晚上～

##  东北地区光电设计竞赛（三）
[video(video-8wcZraq7-1609309681417)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=713275563)(image-https://ss.csdn.net/p?http://i0.hdslb.com/bfs/archive/8c4be19f91afa773f738fcf8c4626c5cd9c534de.jpg)(title-第三届东北地区光电设计竞赛-紫外线消毒机器人)]

<font color=#999AAA >开发时间：2019.05-2018.06

参加第三届光电比赛的时候，没有了对作品的指标比较，纯靠创意，当时想到了光和电结合的东西，同时也是为了准备2019年电子设计竞赛，因此做了一个紫外线消毒机器人。

一个四旋翼飞机，搭载紫外线灯，不断循环往复便可以实现对家庭进行消毒的目的。
也许有人问：紫外线不是看不见吗？emmmm，因为还装了一些紫灯～

##  循线机器人-2019全国电子设计竞赛

[video(video-cHY6hbWn-1609319913746)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=885766140)(image-https://ss.csdn.net/p?http://i2.hdslb.com/bfs/archive/b364d986a471c92e757a59066f20b52f541c9043.jpg)(title-2019年全国大学生电子设计竞赛四旋翼题准备-跟踪小车)]
<font color=#999AAA >开发时间：2018.09-2019-08

这个比赛要求一个四旋翼机器人，能够巡查黑线，途中识别二维码，再返回原地。b站上有很多分享的老铁，大家有兴趣可以去看看人家的。我们的飞机使用了Open MV进行图像识别，但是在距离过远的时候无法识别二维码，可能以后树莓派/jetson namo等Linux平台加摄像头进行图像处理才能够应付更多的视觉任务吧，Open MV还是有些逊色。

虽然我们的飞机完成的功能不多，基本上就是绕着飞了一圈再稳稳回来。但是已经是整个省唯一 一个在四旋翼题目上拿到国奖的队伍了。从这里大概就能知道四旋翼题有多难。另外不得不说，南北方存在着四旋翼实力的差距。获得国一的队伍大多是上海等有传承的队伍。

为电赛四旋翼的题目，一年中断断续续也准备了不少时间。我现在认为当时又陷入了做比赛的一个坑点，那就是完全没有人指导的情况下，去做比赛。当时也做了一些姿态解算的代码以及向老师进行ppt汇报，但是进展缓慢。啃公式实在是太难了。做四旋翼一定要多借鉴开源代码。


##  金属循迹小车-2016年电子设计竞赛
[video(video-2SAuiYVw-1609314353353)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=543255057)(image-https://ss.csdn.net/p?http://i0.hdslb.com/bfs/archive/7d23d3b67b135d9c94d323c4e7bfd16de2eb1388.jpg)(title-2016电子设计竞赛-LDC1314循迹机器人)]
<font color=#999AAA >开发时间：2018.04-2018.06

为了备战2018年电子设计竞赛省赛，我和栋仔一起做校电子设计竞赛，题目来源于2016年省赛题目，利用msp430和TI的芯片LDC1314做I2C通信，完成测速、数字识别、小车状态显示、摄像头识别数字等功能，比赛细节写在了[这篇文章](https://blog.csdn.net/weixin_42089190/article/details/80558272)
上面视频是小车第一次完成除摄像头之外的全部功能，但是速度太慢了。为了提高速度，在比赛前一周，我和栋仔住在了实验室里，每天晚上两点睡觉，想要将速度调得更快些，不过当时不会pid只会硬调速度，做了很多没用的工作，不过确实是已经尽力了，在没人指导的情况下，只能做到这样，而且受限于点击和电池的硬件，无法带动这么重的车。
为了给自己回一些本，我们把自己做的一些程序放在闲鱼上售卖，恰逢TI杯，这些程序被卖了几百元，后面还陆陆续续被一些做毕设的人买了一些。


 <img src="https://img-blog.csdnimg.cn/20201230170055547.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MjA4OTE5MA==,size_16,color_FFFFFF,t_70" style="zoom:15%;" alt=""/>

##  手势识别装置-2018年省电子设计竞赛

[video(video-xrHnwvUT-1609309778530)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=843366350)(image-https://ss.csdn.net/p?http://i0.hdslb.com/bfs/archive/41c6061a43ba5d90ef65b1bf1bf8e836bdf7d379.jpg)(title-2018年辽宁省电子设计竞赛-手势识别装置)]

<font color=#999AAA >开发时间：2018.06-2018.07

手势识别装置主控是msp430g2553，单片机和FDC2214通信，通过读取数据来判断是哪个手势。
准备完毕校赛之后，我和栋仔通过了选拔，开始准备省电赛。比赛要求FDC2214，我当时翻阅了很多2214的手册，手册上写明了2214可用于测液位和手势识别，当时就想会不会出这种题目，所以在一个月的时间内，我又买了一些大小不一的试管，开始做测液位的工作。

但是当时自己实在猜不出来手势能怎么用这一个传感器测量？？所以没做，没想到题目真的是手势识别装置，就像本篇开头的视频所演示的那样，把剪刀石头布放到传感器的铜板上后，传感器寄存器里面的数值会有连续的变化 ，通过这点就可以判断到底是什么手势。
##  智能魔镜


[video(video-0XDHHtTq-1609320062102)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=330844291)(image-https://ss.csdn.net/p?http://i1.hdslb.com/bfs/archive/6ec369868a1fe072b42ed15119c956da69b0eefb.jpg)(title-树莓派魔镜演示效果-基于自美智能系统的轮子)]




<font color=#999AAA >开发时间：2019.11-2020.06

为女朋友做的生日礼物，2018.12就想做了，为女友2019年的生日礼物，可惜拖拖拉拉各种压力，又因为疫情，直到2020年才送出去……作为一个智能家居，主要显示天气等出行信息，主人还可以通过微信等远程控制，插上鼠标键盘那就是一个电脑。
当时用了网上一个公司（智美智能系统）的开源代码，还买了他们的控制板，基本上使用的是他们的轮子，我自己做的工作是自己购买元件以及把人家的轮子应用好，前端的知识正没有学到多少。
##  FPGA
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201230113120420.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MjA4OTE5MA==,size_16,color_FFFFFF,t_70)

<font color=#999AAA >开发时间：2018.11-2018.11

这个作品只用了一个月的时间开发，因为当时把大部分时间都用在了物料搬运机器人上。主要是使用PYNQ-Z2（一种fpga）外接激光传感器和红外传感器，通过齿轮震动，检测震动引起的激光变化，接收频率判断齿轮有没有磨损。

也是在这里使用Python开发的时候 ，第一次感觉到了ipython和jupyter notebook的强大之处，强大的交互功能是开发代码原型的最佳选择，等代码成功了，再整体移植到pycharm等ide中开发是不错的选择。
另外，个人感觉做无限制的fpga作品竞赛的时候，最好能将fpga的高速计算的能力和摄像头的图像处理结合起来，这样可展示性也会很好。

##  半自动腐蚀箱

[video(video-rqkHvg33-1609319979610)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=245772676)(image-https://ss.csdn.net/p?http://i2.hdslb.com/bfs/archive/1cec05028796866548a0f10af0e9181307b2ab21.jpg)(title-半自动PCB腐蚀箱腐蚀单层板效果)]

<font color=#999AAA >开发时间：2018.12-2019.1

实验室的电路板腐蚀箱一直是利用氧化剂腐蚀铜板做单层板，直接接了个电机和抽水的喷头就没事了，我改进了一下，加入了单片机、加热棒和摄像头，能够更细致控制腐蚀过程，最后写了一篇专利，一年啊，我都快毕业了，才审批下来。不得不说，专利审批速度实在是太慢了。
##  平衡车
[video(video-jdaANuUW-1609317238316)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=800857307)(image-https://ss.csdn.net/p?http://i1.hdslb.com/bfs/archive/57c7efad893a55a256872c51b173a3232a3c7eef.jpg)(title-平衡车)]
<font color=#999AAA >开发时间：2018.05-2018.06

这个玩的人应该比较多吧，基本上是想做小车的同学必须要玩的东西，可以好好学学pid，我们后来做物料搬运机器人的时候，使用的就是从这里拆的直流减速点击，而不是之前性能很差的小黄电机了。
淘宝店160元，你值得拥有。
##  摇摇棒
[video(video-xMsJI5gZ-1609312973524)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=543259542)(image-https://ss.csdn.net/p?http://i0.hdslb.com/bfs/archive/8870ab3196b3ee261a89f480fd59b4e61669b1e5.jpg)(title-电子制作-摇摇棒演示)]

<font color=#999AAA >开发时间：2016.04-2016.06

本来想做手写绘图板，然后通过校赛参加全国电子设计竞赛的，奈何，太菜了。学长轻飘飘一句“百度照资料慢慢做就好啦”，萌新真的百度找到了都不知道怎么做……
最后无奈，做了个摇摇棒交差了。丑陋本体如下：
[video(video-24cinGMM-1609313015177)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=288329662)(image-https://ss.csdn.net/p?http://i1.hdslb.com/bfs/archive/ab5a266f27a95f65ee125aa2b63045a66e3dbe1b.jpg)(title-电子制作-摇摇棒本体)]

##  chrome小恐龙游戏


[video(video-kgkxlbeV-1609320042652)(type-bilibili)(url-https://player.bilibili.com/player.html?aid=928327220)(image-https://ss.csdn.net/p?http://i2.hdslb.com/bfs/archive/2d9ed3e93c8fdbcc117c803def18ee13208cf333.jpg)(title-esp8266实现谷歌浏览器小恐龙游戏)]


<font color=#999AAA >开发时间：2020.03-2020.03

知乎答主cr4fun在esp8266上做了chrome小恐龙的游戏，因此萌生了复刻该游戏的想法。
1. ESP8266开发板（NodeMcu）30元
2. 一个可以传输数据的USB数据线（注意有些USB数据线只能够充电，无法通讯） 需要利用数据线下载程序
3. 2个大按键     5元
4. 母对母杜邦线若干
5. I2C接口的oled     25元
写了一个知乎文章讲述如何应用的。[esp8266实现小恐龙游戏](https://zhuanlan.zhihu.com/p/107581280)

##  功放

功放是梦开始的地方，第一次用烙铁，什么都不懂焊接了一个什么玩意儿，插上手机才发现是个喇叭……学了电工学才知道功率放大电路原来是这样啊……

##  尾声
大学生的主业当然是学习，回想我自己的大学生涯，学习貌似只占了比较少的一部分。很多时间都用来参加各种科技竞赛。在制作这些电子控制系统的时候，越发讨厌在等待学校的激光切割机、3D打印机、腐蚀电路箱等机器上所花费的时间，而且每每受限于经费和实物的制约。感受到了纯粹的软件开发的优点：只要一台电脑就可以。
此外，回忆这些比赛，实际比赛场地的光线是我记忆最深刻的，因为很多时候哪怕你自己在学校里费了很大功夫调试，到了比赛的时候，还是有可能gg，因为水土不服。对于有摄像头和光电类传感器的作品犹为重要。
<hr style=" border:solid; width:100px; height:1px;" color=#000000 size=1">

最后，引用我偶像胡津铭的话作为结语：
如果我能回到旅程之前，我也许会对过去的自己说：“`你会经历一段难以置信、跌宕起伏的旅程。你会遇到很多志同道合的好友，以及你十分尊敬的师长。虽然你也会走很多弯路，碰到很多困难与挫折，但是不要担心，你一直兢兢业业、勤勉刻苦，你的努力最终都会得到回报。`”

总之，我希望这篇文章里所写的自己的一些经历、思考、心得、总结等能对后来者起到一些帮助。如果你在阅读了这篇文章之后觉得有一些收获，那本文的目的也就达到了。

各位同学，我们江湖上见。

## 微信公众号
欢迎大家关注我的个人公众号，现阶段主要总结为进入互联网大厂学习的知识。

公众号名称：三丰杂货铺
![在这里插入图片描述](https://img-blog.csdnimg.cn/20200310102322775.jpg)
