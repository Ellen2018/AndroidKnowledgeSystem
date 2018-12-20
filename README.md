
# Android知识体系总结(全方面覆盖Android知识结构，面试&进阶 Version-1.0.1 时间:2018.09) #

>**基本内容** ：
>- ***Android基础知识***:基本涵盖Android所有知识体系，四大组件，Fragment,WebView,事件分发，View绘制...
>- ***Java基础知识&高阶知识点***:基础部分不谈了，高阶部分：泛型，反射，Java虚拟机...
>- ***算法与数据结构***:链表，堆，栈，树...
>- ***Android常用框架***：异步，网络，图片加载，内存优化，依赖注入，数据库等框架
>- ***Android前沿技术***：Android组件化，热更新，插件化，消息推送，AOP面向切面编程,Flutter(谷歌的移动UI框架)...
>- ***源码分析***：Android源码分析,启动一个app的源码分析,常用框架源码分析，Java源码分析，集合源码分析...
>- ***网络基础***：五层网络模型，三次握手&四次挥手，请求头&响应头，Socket&WebSocket......
>  ***内容实在太多，这里列不完，请接着往下看吧 -_-***
>---------------------------------------------------------------------------------------------------
>版本1.0.1更新日志：
>**更新内容**：这一次更新改动非常大，Java高阶知识点，Android几乎涵盖所有知识点，算法与数据结构变得更加完善了，详细内容请下载文章中2018年9月份更新的脑图。  
**更新说明**:笔者正在更新升级当中，请耐心等待笔者的这一次升级，希望不会让你失望！谢谢你的关注。如果对你有帮助，请您点个赞，谢谢！还有些内容还没有更新，但知识体系图已经更新完毕，这需要笔者有空余的时间进行整理，请体谅，欢迎持续关注。你或许感到很疑惑，面试会问这么多吗？为了不断完善自己的Android知识体系，笔者也只能这么干了，我也考虑到对于一些即将面试的同学而言这份面试总结内容过多，但是木有关系，笔者会在每一个知识点后面加上是否属于面试范围的标记，其实笔者写这篇文章的初衷确实是为了面试，但是在版本1.0.0中有很多学者反映，只把总结的结论丢在那里，真的是摸不着头脑，有点懵逼，所以为了让这一份总结容易理解，适应面试，适应学习，适应进阶，所以笔者索性把Android知识体系全部概括出来，对于面试者，不只是把结论放在那里，重在理解，才能流畅答出面试官问的内容，对于学习进阶Android的学者，争取将知识点概括完善，当然那是不可能的，但是尽量做吧。对于那些要面试的知识点，笔者会带上面试的标记，不带面试的标记，那么就是属于学习和进阶的知识点。下个版本(Version-1.0.2)，笔者将针对面试的知识点在末尾列举出高频率面试题，这需要很多时间，要看很多博主的面试经历总结整理出来，估计今年过年的时候整理吧。


&emsp;&emsp;本篇文章有以下目的：

>【1】Android程序猿的面试(初级，中级，高级，资深)，拿到满意的offer。  
>【2】Android程序猿学习进阶。  
>注意：因为笔者是列出所有的Android知识点，因此面试不需要看那么多内容，如果是面试的知识点。笔者会加上标记Face，而如果不是面试的知识点，笔者会加上No标记，它是要学的东西；然后笔者将Android面试者或者面试者分为4个等级，初级A1，中级A2，高级A3，资深A4，如果这个知识点是所有等级的范围，那么笔者将会以all标记上。因此进阶路线就是A1->A2->A3->A4。也是面试者挑选的复习范围，假如你是中级程序员，那么你面试要看的内容就是包含A2&Face的标记。如果笔者觉得文章更新的还不够完善，笔者会添加Update标记，当然，这是给笔者自己的，目的是快速定位此Android知识总结中的要改进的地方，但是那些Update标记还是会值得一看，你也可以查查类似的资料看看，不一定非得看笔者的；笔者给的一份脑图应该是涵盖Android基本上所有的知识点，如果你觉得笔者总结很辛苦，那么你去下载笔者上传到CSDN的那份脑图，给笔者积分作为奖励，当然你还可以去百度云下载，自由选择。
>- all : 所有的Android工程师都看。
>- A1: 初级Android工程师。
>- A2: 中级Android工程师。
>- A3: 高级Android工程师。
>- A4: 资深Android工程师。
>- Face: 是面试的知识点。
>- No: 面试基本遇不到。
>- Update: 还可以总结的更加完善，不过得等到下个版本。

以下是Android面试系列文章知识体系图以及文章的具体链接：  
Android面试系列文章知识体系图： 
2018年3月份(Version-1.0.0)： 
- 链接：https://pan.baidu.com/s/1qoyOI14bAjn2lMRr-toAag 密码：4qv9、
- CSDN下载链接：http://download.csdn.net/download/clandellen/10277364  
既然选不了0积分下载，最低需要2积分下载，CSDN官方规定最少2积分，对不起读者了

2018年9月份(Version-1.0.1)：
- 链接：https://pan.baidu.com/s/1g7WE-FoXXqr8-dPXLjjTLA 提取码：mg78
- CSDN下载链接：https://download.csdn.net/download/clandellen/10698579 (5积分，这次积分高了些，就算对笔者辛苦整理的奖励吧，但是你没有积分的话，去百度云下载吧，就在上面)

>&emsp;&emsp;当然这次升级添加了很多东西，你可能疑问面试为什么会有这么多东西，其实笔者的这份不仅仅可以用来面试，当作是进阶路线也是可以的，理论上讲这份完全是可以应付面试的，希望对你有所帮助。关于这份面试知识体系的说明请看后面。

以下是知识体系图的部分：  
![在这里插入图片描述](https://img-blog.csdn.net/20181008131221292?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NsQW5kRWxsZW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![在这里插入图片描述](https://img-blog.csdn.net/20181008131245124?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NsQW5kRWxsZW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![在这里插入图片描述](https://img-blog.csdn.net/2018100813131466?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NsQW5kRWxsZW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![在这里插入图片描述](https://img-blog.csdn.net/2018100813132646?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NsQW5kRWxsZW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![在这里插入图片描述](https://img-blog.csdn.net/20181008131344831?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NsQW5kRWxsZW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![在这里插入图片描述](https://img-blog.csdn.net/20181008131359427?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NsQW5kRWxsZW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![在这里插入图片描述](https://img-blog.csdn.net/20181008131413413?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NsQW5kRWxsZW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![在这里插入图片描述](https://img-blog.csdn.net/20181008131425320?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NsQW5kRWxsZW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

![在这里插入图片描述](https://img-blog.csdn.net/20181008131436652?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0NsQW5kRWxsZW4=/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

**脑图非常大，这里列不完，请读者下载笔者给的脑图链接，然后在详细看每一个知识体系结构。**

详细内容，读者可以下载上述百度云分享链接的那个文件，并使用Xmind8打开。

>&emsp;&emsp;注意：对于正在入门学习Android的同学，请看笔者另外一篇文章：https://blog.csdn.net/clandellen/article/details/78258187  （里面介绍了如何去自学Android,有Java视频教程，Android Studio版本的Android视频教程），Android基础部分对你来说可以去看一看，对于1到2年开发经验的读者，基础部分，必须掌握和明白，而有些部分，你可以选择性去看和掌握，比如：Android源码部分，你不必去弄清android系统的启动过程，只需要了解init进程什么，Zygote进程是什么，AMS是什么，作用是啥即可，而常用框架源码部分呢，如果你面的公司是有严格要求的，我指的是类似于BAT，你要选择其中3，4甚至5，6个着重去学习，其它的作为了解粗略看一下就行了，http自然不用我说了吧，Java设计模式等，数据结构与算法部分，也不必太耗时间去整明白，知道多线程环境下最安全的单例模式，而且知道一些框架中采用了何种设计模式，比如RxJava采用的观察者设计模式等，能手写冒泡，二分法，最好会快排，知道堆和栈，链表，队列等的特性即可，也要注意合理安排时间，有些链接里文字过多的，粗略的看看，达到能自己说出来重点即可，比如:Android基础部分，对于Context的理解，你需要知道Android中有几种上下文，它们的作用分别是什么即可，而对于3年经验甚至更多的读者，对我而言你已经是个大佬了，首先我要跟你打声招呼：大佬你好，基础部分，经验部分对你而言已经不再是难题，你应该去明白Android系统的启动流程的源码分析，一个app是如何启动等，常用框架的源码至少得弄懂大半，深入源码，并有自己的一套分析思维模式。最后总结：如果你对自己有严格要求，希望你找到offer后，把这篇文章里你不懂的部分还是去好好学习，只有不停的学，才可以让自己更加去胜任平时的工作。


## [1]Android基础部分

1.Android知识体系总结之Android部分之Activity篇(已更新，all&Face) 
http://blog.csdn.net/clandellen/article/details/79257489

2.Android知识体系总结2之Android部分之Broadcast篇(已更新，all&Face)  
http://blog.csdn.net/clandellen/article/details/79279416

3.Android知识体系总结之Android部分之ContentProvider篇(已更新，all&Face)  
https://blog.csdn.net/ClAndEllen/article/details/82765220

4.Android知识体系总结之Android部分之Service篇(已更新，all&Face)  
http://blog.csdn.net/clandellen/article/details/79276411

5.Android知识体系总结之Android部分之Fragment篇(已更新，all&Face)  
http://blog.csdn.net/clandellen/article/details/79269680  

6.Android知识体系总结之Android部分之WebView篇 (已更新，all&Face)   
http://blog.csdn.net/ClAndEllen/article/details/79287020

7.Android知识体系总结之Android部分之Binder机制篇 (已更新，A3&A4&Face) 
http://blog.csdn.net/ClAndEllen/article/details/79343389

8.Android知识体系总结之Android部分之Handler机制篇(已更新，all&Face)   
http://blog.csdn.net/ClAndEllen/article/details/79343538

9.Android知识体系总结之Android部分之AsyncTask篇(已更新，all&Face)  
http://blog.csdn.net/ClAndEllen/article/details/79346383

10.Android知识体系总结之Android部分之HandlerThread篇(已更新，all&Face)   
http://blog.csdn.net/ClAndEllen/article/details/79346492

11.Android知识体系总结之Android部分之IntentService篇(已更新，all&Face)    
http://blog.csdn.net/ClAndEllen/article/details/79346624

12.Android知识体系总结之Android部分之View绘制机制篇(已更新，all&Face&Update)  
http://blog.csdn.net/ClAndEllen/article/details/79365250

13.Android知识体系总结之Android部分之事件分发机制篇(已更新，all&Face)  
http://blog.csdn.net/ClAndEllen/article/details/79365369

14.Android知识体系总结之Android部分之ListView篇(已更新，all&Face&Update)    
http://blog.csdn.net/ClAndEllen/article/details/79365499

15  Android知识体系总结之Android部分之RecyclerView篇(已更新，all&Face&Update)    
https://blog.csdn.net/ClAndEllen/article/details/82859578

16 Android面知识体系总结之Android部分之ViewPager篇(已更新，all&Face&Update)  
https://blog.csdn.net/ClAndEllen/article/details/82862804

17 Android知识体系总结之Android部分之动画机制篇(待更新...，all&Face)  
http://blog.csdn.net/ClAndEllen/article/details/79411999

18  Android知识体系总结之Android部分之自定义View篇(待更新...，A2&A3&A4&Face)  
http://blog.csdn.net/ClAndEllen/article/details/79412399

19 Android知识体系总结之Android部分之Android中的布局篇(已更新，all&Face)  
https://blog.csdn.net/ClAndEllen/article/details/82979812

20 Android知识体系总结之Android部分之网络数据解析篇(已更新，all&Face)  
https://blog.csdn.net/ClAndEllen/article/details/82980593

21 Android知识体系总结之Android部分之Android中的序列化篇(已更新，all&Face)  
https://blog.csdn.net/ClAndEllen/article/details/82980677

22 Android知识体系总结之Android部分之Android系统版本特性篇(已更新，all&Face)  
https://blog.csdn.net/ClAndEllen/article/details/82982518

23 Android知识体系总结之Android部分之JNI和NDK篇(已更新，A2&A3&A4&Face)
https://blog.csdn.net/ClAndEllen/article/details/82966507

24 Android知识体系总结之Android部分之Android本地存储篇(已更新，all&Face)
https://blog.csdn.net/ClAndEllen/article/details/82997955

25 Android知识体系总结之Android部分之Intent篇(已更新，all&Face)
https://blog.csdn.net/ClAndEllen/article/details/83000920

26 Android知识体系总结之Android部分之对话框篇(已更新,all&No)  
https://blog.csdn.net/ClAndEllen/article/details/82966342

27 Android知识体系总结之Android部分之通知篇(已更新，all&No)
https://blog.csdn.net/ClAndEllen/article/details/83001281

28 Android知识体系总结之Android部分之Application类篇(已更新，A2&A3&A4&Face)
https://www.jianshu.com/p/f665366b2a47

29 Android知识体系总结之Android部分之Context的理解篇(已更新，A2&A3&A4&Face)  
https://www.jianshu.com/p/94e0f9ab3f1d

30 Android知识体系总结之Android部分之Window的理解篇(已更新，A2&A3&A4&Face)  
https://blog.csdn.net/yhaolpz/article/details/68936932

31 Android知识体系总结之Android部分之系统结构与系统源码目录篇(已更新，all&Face)
https://blog.csdn.net/itachi85/article/details/54695046/

32 Android知识体系总结之Android部分之冷启动&热启动篇(已更新，A2&A3&A4&Face)
https://blog.csdn.net/ClAndEllen/article/details/79383005

33 Android知识体系总结之Android部分之Andrid中的锁屏篇(已更新，all&No&Update)
https://www.jianshu.com/p/6c3a6b0f145e
https://blog.csdn.net/zrf1335348191/article/details/54377042

34 Android知识体系总结之Android部分之悬浮窗篇(已更新，all&No)  
https://blog.csdn.net/ClAndEllen/article/details/82966403

35 Android知识体系总结之Android部分之蓝牙&相机篇(已更新，all&No&Update)
[Android部分之蓝牙](https://blog.csdn.net/VNanyesheshou/article/details/51554852)
[Android部分之相机](https://blog.csdn.net/feiduclear_up/article/details/51968975)
[如何获取手机本地图片](https://www.jianshu.com/p/498c9d06c193)

36 Android知识体系总结之Android部分之音视频开发篇(已更新，all&No)
https://blog.csdn.net/ClAndEllen/article/details/83023573

37 Android知识体系总结之Android部分之手机定位篇(已更新，all&No)
https://blog.csdn.net/qq_33689414/article/details/54136922

[Android Studio地图开发（百度地图）](https://blog.csdn.net/wl1710582732/article/details/73466031)

38 Android知识体系总结之Android部分之点九切图篇(已更新，all&No)
https://blog.csdn.net/leeccncdl/article/details/7303635

39 Android知识体系总结之Android部分之Material Design篇(待更新...，all&No)
[Material+design非官方中文指导手册1.0](https://pan.baidu.com/s/1E1XbNqO1G1VVndg_8vpLlw)  提取码：uqex

40 Android知识体系总结之Android部分之Android Drawable篇(已更新，all&No)
https://www.cnblogs.com/sharecenter/p/5620967.html
[RecyclerView水波纹点击效果](https://blog.csdn.net/REIGE/article/details/68957994)
[Android:为Button添加圆角黑色边框及透明底色](https://blog.csdn.net/wangyanguiyiyang/article/details/49780005)

41 Android知识体系总结之Android部分之内存优化&布局优化篇(已更新，all&Face&Update)
https://blog.csdn.net/carson_ho/article/details/79708444?from=singlemessage

42 Android知识体系总结之Android部分之屏幕相关知识&屏幕适配篇(已更新，all&Face&Update)
https://blog.csdn.net/carson_ho/article/details/51234308

43 Android知识体系总结之Android部分之进程间通信篇(已更新，A2&A3&A4&&Face)
https://blog.csdn.net/u011240877/article/details/72863432

44 Android知识体系总结之Android部分之图片开发&Bitmap&高清大图显示篇(待更新...，all&Face)
https://blog.csdn.net/ClAndEllen/article/details/79382123

45 Android知识体系总结之Android部分之Toast篇(已更新，all&Face)
https://blog.csdn.net/ClAndEllen/article/details/83038021

46 Android知识体系总结之Android部分之AIDL篇(已更新，all&Face)
https://blog.csdn.net/u011240877/article/details/72765136

## [2]Java部分

1.Android知识体系总结之Java部分I/O流篇  
http://blog.csdn.net/ClAndEllen/article/details/79429328  

2.Android知识体系总结之Java部分多线程流篇  

3.Android知识体系总结之Java部分异常篇  
http://blog.csdn.net/ClAndEllen/article/details/79389561

4.Android知识体系总结之Java部分注解篇  
http://blog.csdn.net/ClAndEllen/article/details/79392453

5.Android知识体系总结之Java部分类加载器篇  
http://blog.csdn.net/ClAndEllen/article/details/79392630

6.Android知识体系总结之Java部分反射机制篇  
http://blog.csdn.net/ClAndEllen/article/details/79393029

7.Android知识体系总结之Java部分泛型篇 

8.Android知识体系总结之Java部分集合框架篇 

9.Android知识体系总结之Java部分设计模式篇(已更新，all&Face)   
https://blog.csdn.net/ClAndEllen/article/details/82966697

10.Android知识体系总结之Java部分Java虚拟机篇

## [3]算法和数据结构部分（注意面试的时候回答不上来，千万别放弃，因为Android对算法的要求是次要的，也就是说算法能力并不能决定你拿不拿得到offer,当然也必须具备一些基本的算法能力，比如：冒泡，选择排序，二分查找啊等）

1.Android知识体系总结之算法与数据结构部分之算法的效率篇

2.Android知识体系总结之数据结构之链表篇  
https://blog.csdn.net/lishuzhai/article/details/50972779

3.Android知识体系总结之数据结构之队列篇(已更新，all&Face)  
https://blog.csdn.net/javazejian/article/details/53375004

4.Android知识体系总结之数据结构之栈篇  
https://blog.csdn.net/javazejian/article/details/53362993

5.Android知识体系总结之数据结构之堆篇  
https://blog.csdn.net/wypblog/article/details/8076324

6.Android知识体系总结之算法之排序算法    
http://blog.csdn.net/happy_wu/article/details/51841244

7.Android知识体系总结之算法之查找算法  
http://blog.csdn.net/three_man/article/details/46799659

8.Android知识体系总结之数据结构之树篇  
https://blog.csdn.net/u011240877/article/details/53193877

9.Android知识体系总结之算法与数据结构部分之其它算法篇(待更新)


## [4]操作系统

1.什么是进程？什么是线程？进程和线程之间的区别

2.Windows剪切板的和Android的进程间通讯是不是类似

## [5]实战经验部分：

1.Android知识体系总结之实战经验部分之Android Stdio目录结构篇  
http://blog.csdn.net/ClAndEllen/article/details/79368343  

2.Android知识体系总结之实战经验部分之代码版本控制篇
http://blog.csdn.net/ClAndEllen/article/details/79369538

3.Android知识体系总结之实战经验部分之Android构建流程篇  
http://blog.csdn.net/ClAndEllen/article/details/79369302

4.Android知识体系总结之实战经验部分之gradle篇  
http://blog.csdn.net/ClAndEllen/article/details/79369643

5.Android知识体系总结之实战经验部分之proguard混淆篇  
http://blog.csdn.net/ClAndEllen/article/details/79369761

6.Android知识体系总结之实战经验部分之Android屏幕适配篇(已更新，all&Face)
https://blog.csdn.net/ClAndEllen/article/details/82977894

7.Android知识体系总结之实战经验部分之Android多渠道打包与apk签名篇
https://blog.csdn.net/ClAndEllen/article/details/83383127

## [6]实战经验部分之常用框架部分

1.Android知识体系总结之常用框架之网络框架篇  
http://blog.csdn.net/clandellen/article/details/79373303

2.Android知识体系总结之常用框架之异步框架篇  
http://blog.csdn.net/ClAndEllen/article/details/79373350

3.Android知识体系总结之常用框架之图片加载框架篇  
http://blog.csdn.net/ClAndEllen/article/details/79375228

4.Android知识体系总结之常用框架之依赖注入框架篇  
http://blog.csdn.net/clandellen/article/details/79375249

5.Android知识体系总结之常用框架之内存优化框架篇  
http://blog.csdn.net/ClAndEllen/article/details/79375317

6.Android知识体系总结之常用框架之数据库存储框架篇(已更新，all&Face)  
https://blog.csdn.net/ClAndEllen/article/details/82967459

## [7]实战经验部分之网络理论基础

1.Android知识体系总结之Android所具备的网络基础篇  
http://blog.csdn.net/ClAndEllen/article/details/79379691

## [8]实战经验部分之调试能力  

1.Android知识体系总结之异常处理ANR异常篇  
http://blog.csdn.net/ClAndEllen/article/details/79381399

2.Android知识体系总结之异常处理OOM异常篇  
http://blog.csdn.net/ClAndEllen/article/details/79381656

3.Android知识体系总结之内存管理之Bitmap的加载篇  
http://blog.csdn.net/ClAndEllen/article/details/79382123

4.Android知识体系总结之内存管理之UI卡顿篇    
http://blog.csdn.net/ClAndEllen/article/details/79382430

5.Android知识体系总结之内存管理之内存泄漏篇  
http://blog.csdn.net/ClAndEllen/article/details/79382815    

6.Android知识体系总结之内存管理篇  
http://blog.csdn.net/ClAndEllen/article/details/79382919

7.Android知识体系总结之内存管理之冷启动过优化及其他优化篇  
http://blog.csdn.net/ClAndEllen/article/details/79383005

http://blog.csdn.net/ClAndEllen/article/details/79383058

8.Android知识体系总结之Android代码分析工具：Lint检查  
http://blog.csdn.net/ClAndEllen/article/details/79400555

9.Android知识体系总结之Android代码编程规范

10.Android知识体系总结之实战经验部分之调试能力之测试篇


## [9]实战经验部分之架构搭建篇

1.Android知识体系总结之之架构搭建之MVC模式篇  
http://blog.csdn.net/ClAndEllen/article/details/79396116

2.Android知识体系总结之之架构搭建之MVP模式篇  
http://blog.csdn.net/ClAndEllen/article/details/79396527  

3.Android知识体系总结之之架构搭建之MVVM模式篇  
http://blog.csdn.net/ClAndEllen/article/details/79396831  

4.Android知识体系总结之之架构搭建之谷歌官方推荐架构TODO-MVP篇  
https://www.jianshu.com/p/8b81493d1297

## [10]前沿的技术篇

1.Android知识体系总结之前沿的技术之Android组件化开发篇(待更新，A2&A3&A4&Face)

2.Android知识体系总结之之Android插件化&热更新篇   
[插件化](http://blog.csdn.net/ClAndEllen/article/details/79397207)   
[热更新](http://blog.csdn.net/ClAndEllen/article/details/79397900)  

3.Android知识体系总结之前沿的技术之进程保活篇(待更新，A2&A3&A4&Face)  
http://blog.csdn.net/ClAndEllen/article/details/79398132

4.Android知识体系总结之Kotlin语言面试篇  
http://blog.csdn.net/ClAndEllen/article/details/79400968

5.Android知识体系总结之Android消息推送篇：    
https://www.jianshu.com/p/b61a49e0279f

6.Android知识体系总结之面向切面编程AOP篇：  
http://blog.csdn.net/innost/article/details/49387395

7.Android知识体系总结之谷歌最新跨平台UI框架Flutter篇  
[谷歌的移动UI框架Flutter](https://flutterchina.club/flutter-for-android/)


>由于笔者没有写源码分析文章的习惯，只是看源码的时候，自己大脑转了一遍，但没关系，我这里会贴出一些高质量大神写的源码分析的文章，希望读者被面试官问道的时候能够从容应答。

## [11]Java源码篇

1.Android知识体系总结之LRU算法有关的集合LinkedHashMap的源码探究
http://blog.csdn.net/justloveyou_/article/details/71713781

2.Android知识体系总结之Java常用集合源码探究
ArrayList:  
http://blog.csdn.net/gulu_gulu_jp/article/details/51456969  
http://blog.csdn.net/chun0801/article/details/51481877
http://blog.csdn.net/u014136713/article/details/52089156


...不止这些，还有很多，请读者耐心等待笔者总结

## [12]Android源码篇
1.启动一个app的源码分析

2.Android中的main()方法在哪里？

......

弄懂Android源码，你需要理解什么是init进程，什么是Zygote进程，SystemServer,AMS等等，这是需要时间去理解的：

http://blog.csdn.net/itachi85/article/details/54695046

init进程的启动流程：  
http://blog.csdn.net/itachi85/article/details/54783506

Zygote(受精卵进程)的启动流程：  
http://blog.csdn.net/itachi85/article/details/55047104

SyetemServer进程启动过程：  
http://blog.csdn.net/itachi85/article/details/55053356

Launcher启动过程与系统启动流程：
http://blog.csdn.net/itachi85/article/details/56669808

程序启动的流程：

http://blog.csdn.net/itachi85/article/details/64123035  
http://blog.csdn.net/itachi85/article/details/64243223

>&emsp;&emsp;源码分析也不能完全按照大神的角度去看，有时候自己尝试去理解，就会发现不一样的地方，觉得世界一下被打开了，笔者在研究广播机制的源码的时候，就有这样的感觉，研究的时候，笔者终于知道为什么系统广播不安全，而本地广播那么安全高效，因为系统广播的通信机制使用的Binder,而Binder是走的系统，通过AMS注册的传播广播信号，而本地广播是通过Handler机制实现的通信，这就意味着，本地广播的信号肯定不会发送到应用之外，由于采用的Handler机制，所以高效就不足为奇了。
>&emsp;&emsp;笔者曾被一个学弟提问道，研究源码有什么好处？除了平时能装逼，应付面试，还有什么？其实研究源码好处不止有这些，因为源码是比我们还要厉害的大神写出来的，我们可以学习这些源码里的一些实现逻辑，把这些实现逻辑搬到自己的代码中，这就厉害啦，有时候我们碰到难以实现的模块，我想源码或许会无形当中会提供一些解决方案，GitHub上那些Star比较多的项目的博主，我想他们肯定有看源码的习惯。

## [13]Android框架源码篇

1.Android知识体系总结之网络框架OkHttp源码分析篇  
https://www.jianshu.com/p/27c1554b7fee

2.Android知识体系总结之网络框架Retrofit源码分析篇  
https://www.jianshu.com/p/0c055ad46b6c

3.Android知识体系总结之图片框架Glide源码分析篇  
http://blog.csdn.net/yulyu/article/details/60331803

4.Android知识体系总结之图片框架Picasso源码分析篇  
http://blog.csdn.net/woliuyunyicai/article/details/51417839

5.Android知识体系总结之内存分析框架LeakCanary源码分析篇  
http://blog.csdn.net/cloud_huan/article/details/53081120

6.Android知识体系总结之依赖注入Butterknife源码分析篇  
http://blog.csdn.net/ta893115871/article/details/52497297

7.Android知识体系总结之依赖注入Dragger2源码分析篇  
https://www.jianshu.com/p/eef7fa8136e7

8.Android知识体系总结之异步框架EventBus源码分析篇
http://blog.csdn.net/ljd2038/article/details/51470734  

9.Android知识体系总结之异步框架RxJava源码分析篇  
http://gank.io/post/560e15be2dca930e00da1083

10.Android知识体系总结之图片框架ImageLoader框架源码分析  
http://blog.csdn.net/xiaanming/article/details/26810303
  
http://blog.csdn.net/xiaanming/article/details/27525741
  
http://blog.csdn.net/xiaanming/article/details/39057201

## [14]程序员所要掌握的图

1.Android知识体系总结之UML图(待更新...，all&No)
https://www.cnblogs.com/jiangds/p/6596595.html

2.Android知识体系总结之泳道图(待更新...，all&No)

> 以上就是Android知识体系总结的所有内容，下次更新时间预计于2019年3月左右，也就是每次跳槽最佳时间都会去更新一遍文章，即金三银四，金九银十，再次谢谢大家的阅读，觉得不错，就点个赞吧！

---------------------------------------------------------------------------------------

[一个GitHub受欢迎的Android第三方库整理的网站，读者可以收藏一下，高效率开发](https://hndeveloper.github.io/2017/github-android-ui.html)

笔者上面没能将Java,Kotlin,算法与数据结构总结完善，当然这也在笔者的规划之中。  
[Java知识体系](https://blog.csdn.net/ClAndEllen/article/details/82754931)  
[算法与数据结构知识体系](https://blog.csdn.net/ClAndEllen/article/details/82828765)  
[Kotlin知识体系(待整理)]()  
[Python知识体系(待整理)]()  


