iOS Tasks
=========

    ITEC学习iOS的同学的Github聚集地 =。=

	iOS开发的学习是个漫长而有趣的过程，加油吧~
	
## 提交说明
1. 自己建个Github的账号，fork一份到你自己本地。
2. 以自己的名字拼音全称创建文件夹，来存放你的Task代码。

熟悉熟悉Git怎么用，有个概念了以后可以用SourceTree客户端。
注意代码规范。
每次提交的时候记着Pull request一份到我这。

## 开发环境

### 硬件环境
有Mac，当然最好。</br>
没有。。。装个[黑苹果](http://zh.wikipedia.org/wiki/OSx86)吧，最大的[黑苹果论坛](http://bbs.pcbeta.com/forum.php?gid)，一个不错的[教程](http://bbs.feng.com/read-htm-tid-6296516.html)。

### IDE
Xcode 6.
Sublime Text。
当然，还有最神器的AppCode。


## 学习
### 编程语言
开发iOS的主要编程语言是Object-C（cocoa框架），当然还有C语言，C++等等。（最新的Swift暂时不考虑，不够成熟）C++大部分用来开发图像、音视频等性能敏感的库，一般的应用只会涉及到Object-C。

目前Object-C的开发、维护基本上也就是Apple在做，所以学习Object-C最好最权威的地方就是Apple developer官网->https://developer.apple.com/devcenter/ios/index.action

这里是几个比较好的官方教程：
* [Object-C基本教程。](https://developer.apple.com/library/mac/documentation/cocoa/conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
* [面向对象编程：Object-Oriented Programming with Objective-C](https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/OOP_ObjC/Introduction/Introduction.html#//apple_ref/doc/uid/TP40005149)。
* [Block专题教程。这个非常强大！](https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/Blocks/Articles/00_Introduction.html#//apple_ref/doc/uid/TP40007502)
* [线程: Threading Programming Guide。](https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/Multithreading/Introduction/Introduction.html#//apple_ref/doc/uid/10000057i)
* [字符串：String Programming Guide。](https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/Strings/introStrings.html#//apple_ref/doc/uid/10000035i)
* [异常处理：Exception Programming Topics。](https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/Exceptions/Exceptions.html#//apple_ref/doc/uid/10000012i)
* [并发编程：Concurrency Programming Guide。](https://developer.apple.com/library/ios/documentation/General/Conceptual/ConcurrencyProgrammingGuide/Introduction/Introduction.html#//apple_ref/doc/uid/TP40008091)
* [集合类：Collections Programming Topics。](https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/Collections/Collections.html#//apple_ref/doc/uid/10000034i)

当然，还有许多非常好的第三方教程，如：[tutorialspoint](http://www.tutorialspoint.com/objective_c/index.htm)

### 书
推荐一些电子书

* [Programming iOS 7, 4th Edition](http://it-ebooks.info/book/3138/)
* [Beginning iOS 5 Development](http://it-ebooks.info/book/508/)
* [iOS 7 Programming Fundamentals](http://it-ebooks.info/book/3084/)
* [Learn iOS 7 App Development](http://it-ebooks.info/book/3143/)
* [More iOS 6 Development](http://www.it-ebooks.info/book/1973/)
* [Beginning iOS 7 Development](http://www.it-ebooks.info/book/3901/)
* [The Core iOS Developer's Cookbook, 5th Edition](http://www.it-ebooks.info/book/3675/)
* [Beginning iOS Programming](http://www.it-ebooks.info/book/3663/)
* [Application Development in iOS 7](http://www.it-ebooks.info/book/3545/)
* [Learning Cocoa with Objective-C, 4th Edition](http://www.it-ebooks.info/book/3323/)
* [Professional iOS Programming](http://www.it-ebooks.info/book/3834/)
* [iOS Components and Frameworks](http://www.it-ebooks.info/book/3684/)
* [iOS Drawing](http://www.it-ebooks.info/book/3683/)
* [iOS Auto Layout Demystified, 2nd Edition](http://www.it-ebooks.info/book/3681/)
* [Learn iOS 7 App Development](http://www.it-ebooks.info/book/3143/)
* [iOS 7 Programming Cookbook](http://www.it-ebooks.info/book/3083/)

### iOS开发
有了一定的OC基础以后，就可以着手做几个小东西玩玩，练练手。iOS的体系很庞大，所以一开始最好先按照简单的教程来做一些Demo。当然，[官方的教程](https://developer.apple.com/library/ios/navigation/#)是非常全面的，但是未免有些吓人=。=，太多了。。。所以在此推荐一个非常好的网站：[www.raywenderlich.com](http://www.raywenderlich.com/)，新手可以按照里面的教程，做些Demo应用，攒点成就感~~

当然，大神们的博客是要多多阅读的：[中文 iOS/Mac 开发博客列表](https://github.com/tangqiaoboy/iOSBlogCN).

**遇到问题多Google（不许用Baidu =。= ），stackoverflow是你最好的伙伴**

## 任务
1. Task1: 按照教程[iOS Tutorial: How To Create A Simple iPhone App](http://www.raywenderlich.com/1797/ios-tutorial-how-to-create-a-simple-iphone-app-part-1)，完成教程中的Demo应用。
2. Task2: 按照教程[iOS 7 Best Practices; A Weather App Case Study: Part 1](http://www.raywenderlich.com/55384/ios-7-best-practices-part-1)，完成一个静态数据的天气应用。
3. Task3: 做一个简单的笔记应用。
要求：1). 只用记录文字，有标题、正文、创建时间等基本信息。2). 一共两个页面，首页是所有笔记的列表，点击一条笔记进入笔记的详细内容页面，可以编辑笔记。3). 笔记可以创建、修改、删除、加星标记等。4). 用SQLite数据库保存笔记数据（可以用FMDB第三方库）。5). 发挥你的创造力！
4. Task4: 仿照青桔音乐的iOS客户端，实现歌曲榜、歌手帮的功能（不要求实现播放器，以本地歌曲代替，重点是AFNetworking库的使用，Json，异步更新UI，动画等等）。。。待续。。。

## 第三方库
很多时候，我们可以减少重复的制造轮子，多用用别人的库，可以很大的提升效率。当然，阅读别人的优质代码也是一种学习。

第三方库管理工具：强烈简易[CocoaPods](http://cocoapods.org/)。（当然，它还是有些弊端的=。=）。

这是冰岩的酷站推荐的一个iOS的常用[第三方库合集](http://github.ibireme.com/github/list/ios/)。

列举几个好用、常用的。
* [AFNetworking](https://github.com/AFNetworking/AFNetworking)。一个优秀的网络请求库。
* [FMDB](https://github.com/ccgus/fmdb)。一个封装了iOS的SQLite的库，可以方便的操作数据库，事务、并发什么的，都不在话下。
* [SVPullToRefresh](https://github.com/samvermette/SVPullToRefresh)。一个UITableView的Category扩展，超级方便的增加下拉刷新、上拉加载更多的功能。
* [SVSegmentedControl](https://github.com/samvermette/SVSegmentedControl)。不错的Tab switch控件。
* [SVProgressHUD](https://github.com/TransitApp/SVProgressHUD)。iOS风格的简易提醒对话框。
* [SDWebImage](https://github.com/rs/SDWebImage)。简单强大的，带有内存、文件缓存的图片加载库。
* [CRToast](https://github.com/cruffenach/CRToast)。漂亮的Status栏Notification。
* [KLCPopup](https://github.com/jmascia/KLCPopup)。炫酷的Popup弹出UIView。

另外，[Facebook](https://github.com/facebook)的开源库也是炫酷的不行啊，太多了。