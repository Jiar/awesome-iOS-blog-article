# awesome-iOS-blog-article
iOS学习与开发过程中，发现的比较好的一些博客和文章之类的内容，收集着，利人利己，持续更新。

○表示博文内容与语法无关，★表示博文内容与Swift语言相关，■表示博文内容与Objective-C语言相关，🂡🂢🂣🂤🂥表示为博文内容难度等级，⦿表示访问链接可能需要翻墙，❖表示博文内容为外文。

------

## 目录

- [iOS开发相关](#iOS开发相关)
    - [iOS Base](#iOS Base)
    - [UITableView、UICollectionView](#UITableView、UICollectionView)
    - [AutoLayout](#AutoLayout)
    - [Async UI](#Async UI)
    - [Media](#Media)
    - [UINavigationController](#UINavigationController)
    - [CoreText](#CoreText)
    - [CoreData](#CoreData)
    - [Cache](#Cache)
    - [Block、Closure](#Block、Closure)
    - [GCD、NSOperationQueue、NSRunLoop、多线程安全、锁](#GCD、NSOperationQueue、NSRunLoop、多线程安全、锁)
    - [MVVM/RAC/RxSwift](#MVVM/RAC/RxSwift)
    - [Runtime](#Runtime)
    - [iOS Animation、UIBezierPath、CAShapeLayer](#iOS Animation、UIBezierPath、CAShapeLayer)
    - [CocoaPods](#CocoaPods)
    - [LLDB](#LLDB)
    - [调试打包日志测试持续集成](#调试打包日志测试持续集成)
    - [证书推送上架](#证书推送上架)
    - [Blog](#Blog)
    - [iOS代码库](#iOS代码库)
    - [XCode插件](#XCode插件)
    - [Bug Fix](#Bug Fix)
    - [其他](#其他)

- [iOS逆向工程](#iOS逆向工程)
    - [Reveal](#Reveal)
    
- [Git相关](#Git相关)
    - [git教程](#git教程)

- [Emacs相关](#Emacs相关)
    - [emacs教程](#emacs教程)

- [Vim相关](#Vim相关)
    - [vim教程](#vim教程)

- [Markdown相关](#Markdown相关)
    - [markdown相关](#markdown相关)
  
- [Mac相关](#Mac相关)
    - [mac配置](#mac配置)
    - [mac工具](#mac工具)

- [资源](#资源)
    - [图标资源](#图标资源)
  
## 内容


### iOS开发相关

#### iOS Base
* [OC语法基础](http://blog.csdn.net/jiangwei0910410003/article/category/2745191)■🂢
* [Objective-C代码规范](http://www.jianshu.com/p/4ef06ec81414)■🂢
* [Objective-C的@property的详细解读](http://blog.talisk.cn/blog/2016/03/05/iOS-@property/)■🂢
* [@weakify, @strongify](http://www.jianshu.com/p/3d6c4416db5e)■🂤
* [@synthesize和@dynamic区别](http://www.cnblogs.com/xiaodao/archive/2012/10/09/2716244.html)■🂡
* * [iOS应用程序的生命周期](http://www.jianshu.com/p/aa50e5350852)○🂢

#### UITableView、UICollectionView
* [UITableView和UITableViewCell的几种样式](http://blog.sina.com.cn/s/blog_4669f1cd0101qyp9.html)○🂢
* [UITableView使用详解](http://blog.sina.com.cn/s/blog_9693f61a01016lv5.html)■🂢
* [UITableView优化技巧](http://longxdragon.github.io/2015/05/26/UITableView%E4%BC%98%E5%8C%96%E6%8A%80%E5%B7%A7/) ■🂤
* [iOS 保持界面流畅的技巧](http://blog.ibireme.com/2015/11/12/smooth_user_interfaces_for_ios/)■🂥
* [iOS 程序性能优化](http://www.samirchen.com/ios-performance-optimization/)■🂤
* [iOS 高性能异构滚动视图构建方案](http://pingguohe.net/2016/01/31/lazyscroll.html)■🂤
* [UICollectionView + UIKit Dynamics](http://objccn.io/issue-5-2/)■🂤
* [iOS 10 UICollectionView新特性](http://www.jianshu.com/p/e97780a24224)■🂣

#### AutoLayout
* [开始iOS 7中自动布局教程(一)](http://www.cocoachina.com/industry/20131203/7462.html)■🂤
* [开始iOS 7中自动布局教程(二)](http://www.cnblogs.com/zer0Black/p/3977288.html)■🂤
* [iOS中AutoLayer自动布局流程及相关方法](http://www.th7.cn/Program/IOS/201406/213977.shtml)○🂢
* [使用Autolayout实现UITableView的Cell动态布局和高度动态改变](http://codingobjc.com/blog/2014/10/15/shi-yong-autolayoutshi-xian-uitableviewde-celldong-tai-bu-ju-he-ke-bian-xing-gao/index.html)■🂣
* [iOS 8 Auto Layout界面自动布局系列5-自身内容尺寸约束、修改约束、布局动画](http://www.itnose.net/detail/6309814.html)■🂤
* [iOS进阶指南试读之UI篇](http://www.jianshu.com/p/c4f3303c63d8)■🂣
* [AutoLayout中的Content Hugging 和 Content Compression Resistance](http://blog.csdn.net/yongyinmg/article/details/39526207)■🂤
* [优化UITableViewCell高度计算的那些事](http://blog.sunnyxx.com/2015/05/17/cell-height-calculation/)■🂥
* [深入理解Auto Layout 第一弹](http://zhangbuhuai.com/beginning-auto-layout-part-1/)■🂤
* [TableViewCellWithAutoLayout](https://github.com/smileyborg/TableViewCellWithAutoLayout)■🂤❖
* [TableViewCellWithAutoLayoutiOS8](https://github.com/smileyborg/TableViewCellWithAutoLayoutiOS8)■🂤❖

#### Async UI
* [AsyncDisplayKit 教程：达到 60 FPS 的滚动帧率](http://www.cocoachina.com/swift/20141124/10298.html)★🂤
* [AsyncDisplayKit 2.0 Tutorial: Getting Started](https://www.raywenderlich.com/124311/asyncdisplaykit-2-0-tutorial-getting-started)■🂤⦿
* [AsyncDisplayKit 2.0 Tutorial: Automatic Layout](https://www.raywenderlich.com/124696/asyncdisplaykit-2-0-tutorial-automatic-layout)■🂤⦿

#### Media
* [Swift AVPlayer 播放网络视频之基础篇](http://www.jianshu.com/p/d35980045c2b)★🂡
* [AVPlayer 本地、网络视频播放相关](http://www.jianshu.com/p/de418c21d33c)■🂡
* [基于 AVPlayer 自定义播放器](http://www.jianshu.com/p/195687ca80f5)■🂡
* [iOS 无限循环小视频播放](http://www.jianshu.com/p/43b29e121793)■🂡

#### UINavigationController
* [iOS-给push出来的控制器添加全局滑动(返回)手势](http://www.jianshu.com/p/158d68a730d3)■🂢
* [iOS 实现NavigationController的titleView动态缩放效果](http://www.jianshu.com/p/bcf3d692f99d)■🂣
* [iOS利用Runtime自定义控制器POP手势动画](http://www.jianshu.com/p/d39f7d22db6c)■🂤
* [iOS全屏右滑返回详解](http://www.jianshu.com/p/2e8d332c60ff)■🂣
* [用Reveal分析网易云音乐的导航控制器切换效果](http://jerrytian.com/2016/01/07/%E7%94%A8Reveal%E5%88%86%E6%9E%90%E7%BD%91%E6%98%93%E4%BA%91%E9%9F%B3%E4%B9%90%E7%9A%84%E5%AF%BC%E8%88%AA%E6%8E%A7%E5%88%B6%E5%99%A8%E5%88%87%E6%8D%A2%E6%95%88%E6%9E%9C/)■🂤

#### CoreText
* [CoreText笔记 Part 1](http://longxdragon.github.io/2015/03/14/CoreText-Notes-Part-1/)■🂢
* [CoreText入门](http://geeklu.com/2013/03/core-text/)■🂤

#### CoreData
* [iphone数据存储之－－ Core Data的使用](http://www.cnblogs.com/xiaodao/archive/2012/10/08/2715477.html)■🂣
* [Core Data 概述](http://objccn.io/issue-4-1/)■🂣
* [初识Core Data](http://yulingtianxia.com/tags/Core-Data/)■🂤
* [[Cocoa]深入浅出 Cocoa 之 Core Data（1）- 框架详解](http://blog.csdn.net/kesalin/article/details/6739319)■🂢
* [[Cocoa]深入浅出 Cocoa 之 Core Data（2）- 手动编写代码](http://blog.csdn.net/kesalin/article/details/6746117)■🂣
* [iOS Core Data 数据迁移 指南](http://www.jianshu.com/p/b3b764fc5191)■🂤
* [手把手教你从Core Data迁移到Realm](http://www.jianshu.com/p/d79b2b1bfa72)■🂤

#### Cache
* [iOS 网络缓存扫盲篇](https://www.v2ex.com/t/252955?from=singlemessage&isappinstalled=1)■🂤
* [缓存、缓存算法和缓存框架简介](http://blog.jobbole.com/30940/)■🂣

#### Block、Closure
* [Block简介与用法](http://blog.csdn.net/enuola/article/details/8674063)■🂣
* [iOS 闭包中的[weak self]在什么情况下需要使用，什么情况下可以不加?](https://www.zhihu.com/question/34593410)■🂣

#### GCD、NSOperationQueue、NSRunLoop、多线程安全、锁
* [关于GCD开发的一些事儿](http://www.jianshu.com/p/f9e01c69a46f)■🂣
* [GCD 深入理解：第一部分](https://github.com/nixzhu/dev-blog/blob/master/2014-04-19-grand-central-dispatch-in-depth-part-1.md)■🂤
* [GCD 深入理解：第二部分](https://github.com/nixzhu/dev-blog/blob/master/2014-05-14-grand-central-dispatch-in-depth-part-2.md)■🂤
* [iOS中GCD的使用小结](http://www.jianshu.com/p/ae786a4cf3b1)■🂣
* [Swift 3必看：从使用场景了解GCD新API](http://www.jianshu.com/p/fc78dab5736f)★🂢
* [NSOperation and NSOperationQueue Tutorial in Swift](http://www.raywenderlich.com/76341/use-nsoperation-nsoperationqueue-swift)★🂤⦿❖
* [Cocoa深入学习:NSOperationQueue、NSRunLoop和线程安全](https://blog.cnbluebox.com/blog/2014/07/01/cocoashen-ru-xue-xi-nsoperationqueuehe-nsoperationyuan-li-he-shi-yong/)■🂤
* [深入理解RunLoop](http://blog.ibireme.com/2015/05/18/runloop/)■🂥
* [不再安全的 OSSpinLock](http://blog.ibireme.com/2016/01/16/spinlock_is_unsafe_in_ios/?utm_source=tuicool&utm_medium=referral)○🂤
* [多种常见的加锁方式性能对比测试工程OC版本](https://github.com/ibireme/tmp/blob/master/iOSLockBenckmark/iOSLockBenckmark/ViewController.m)■🂣
* [多种常见的加锁方式性能对比测试工程Swift3版本](https://gist.github.com/steipete/36350a8a60693d440954b95ea6cbbafc)★🂣⦿
* [iOS多线程到底不安全在哪里？](http://mrpeak.cn/blog/ios-thread-safety/)■🂤
* [正确使用多线程同步锁@synchronized()](http://mrpeak.cn/blog/synchronized/)■🂤

#### MVVM/RAC/RxSwift
* [干货集中营-ReactiveCocoa+RXSwift+MVVM](http://www.jianshu.com/p/f32a4824797e)○🂡
* [RAC/MVVM个人学习资源汇总](http://www.jianshu.com/p/2cfed74789db)○🂡
* [[翻译]ReactiveCocoa 4 最佳实践](http://www.jianshu.com/p/da392a685a92)○🂡
* [最快让你上手ReactiveCocoa之基础篇](http://www.jianshu.com/p/87ef6720a096)■🂤
* [iOS——教你如何使用ReactiveCocoa和MVVM为代码解耦构建清爽APP](http://zhoulingyu.com/2016/05/20/iOS%E2%80%94%E2%80%94%E6%95%99%E4%BD%A0%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8ReactiveCocoa%E5%92%8CMVVM%E4%B8%BA%E4%BB%A3%E7%A0%81%E8%A7%A3%E8%80%A6%E6%9E%84%E5%BB%BA%E6%B8%85%E7%88%BDAPP/)■🂣
* [Swift MVVM 你喜欢哪种？](http://www.jianshu.com/p/1a61b3af1a88)★🂤

#### Runtime
* [Objective-C Runtime](http://justsee.iteye.com/blog/2163777)■🂤
* [Runtime 学习笔记(一)](http://lastdays.cn/2016/02/20/runtime1/)■🂤
* [Runtime 学习笔记(二)](http://lastdays.cn/2016/02/20/runtime2/)■🂤
* [Swift Runtime分析：还像OC Runtime一样吗？](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=403153173&idx=1&sn=c631f95b28a0eb4b842a9494e43a30e5)★🂤
* [iOS --- 如何在Swift项目中使用runtime?](http://icetime17.github.io/2016/07/03/2016-07/iOS-%E5%A6%82%E4%BD%95%E5%9C%A8Swift%E9%A1%B9%E7%9B%AE%E4%B8%AD%E4%BD%BF%E7%94%A8runtime)★🂣
* [从AOP框架学习iOS Runtime](http://yq.aliyun.com/articles/3063)■🂣

#### iOS Animation、UIBezierPath、CAShapeLayer
* [iOS Animation](https://github.com/yixiangboy/IOSAnimationDemo)■🂣
* [Facebook POP 进阶指南](http://www.cocoachina.com/industry/20140704/9034.html)■🂣
* [iOS自定义转场动画实战讲解](http://www.jianshu.com/p/ea0132738057)■🂤
* [iOS使用Quartzcode设计动画，快速得到Object-C 和 Swift 代码](http://www.jianshu.com/p/90d6cd355b14)■🂣
* [碎片动画](http://sindrilin.com/animate/2016/05/12/%E7%A2%8E%E7%89%87%E5%8A%A8%E7%94%BB.html)■🂤
* [关于App的一些迷思以及一些动画效果开源库的推荐](http://www.jianshu.com/p/69449e6bdc14)○🂡
* [iOS动画和特效（一）UIView动画和CoreAnimation](http://liuyanwei.jumppo.com/2015/10/30/iOS-Animation-UIViewAndCoreAnimation.html)★🂣
* [下雪的粒子效果、帧动画](http://www.jianshu.com/p/86d414ec8f3a)★🂣
* [右拉的3D抽屉效果](http://www.jianshu.com/p/77386607fd32)★🂣
* [Layer Animations的进阶使用](http://www.jianshu.com/p/a539a5fd3000)★🂣
* [Layer Animations的基本使用](http://www.jianshu.com/p/1d5a528053aa)★🂣
* [View Animations](http://www.jianshu.com/p/6af8a7a8a15a)★🂣
* [放肆地使用UIBezierPath和CAShapeLayer画各种图形](http://www.cocoachina.com/ios/20160214/15251.html)■🂤
* [关于CAShapeLayer的一些实用案例和技巧](http://www.jianshu.com/p/a1e88a277975)■🂣

#### CocoaPods
* [借助GitHub托管Category,利用CocoaPods集成到项目中](https://github.com/Damonvvong/DWCategory/blob/master/README.md)○🂣
* [深入理解 CocoaPods](http://objccn.io/issue-6-4/)○🂤
* [CocoaPods pod install/pod update更新慢的问题](http://blog.csdn.net/ralbatr/article/details/39082937)○🂡

#### LLDB
* [The LLDB Debugger](http://lldb.llvm.org/lldb-gdb.html)○🂡
* [iOS 开发者旅途中的指南针 - LLDB 调试技术](http://www.jianshu.com/p/75a2b63106ff)○🂣
* [LLDB调试命令初探](http://www.starfelix.com/blog/2014/03/17/lldbdiao-shi-ming-ling-chu-tan/)○🂣
* [Chisel-LLDB命令插件，让调试更Easy](https://blog.cnbluebox.com/blog/2015/03/05/chisel/)○🂣
* [教你如何使用Chisel增强LLDB调试](http://www.jianshu.com/p/79468a2eb6db)○🂢
* [小笨狼的LLDB技巧：chisel](http://ios.jobbole.com/83589/)○🂣

#### 调试打包日志测试持续集成
* [CocoaLumberjack和XcodeColors的安装和使用](http://www.jianshu.com/p/7eb7725c933c)■🂢
* [CocoaLumberjack的ios应用开发使用指南](http://blog.csdn.net/jia12216/article/details/44412697)■🂣
* [iOS开发中的单元测试](http://www.infoq.com/cn/articles/ios-unit-test-1)■🂣
* [Xcode7中你一定要知道的炸裂调试神技](http://www.jianshu.com/p/70ed36cf8a98)○🂣
* [如何使用Instruments诊断App(Swift版):起步](http://www.cocoachina.com/swift/20150623/12237.html)○🂣
* [OCLint 安装与使用](https://segmentfault.com/a/1190000005150573)○🂢
* [iOS 自动化测试框架 Google EarlGrey 尝鲜](https://testerhome.com/topics/4137)■🂢
* [敲一下enter键，完成iOS的打包工作](http://www.jianshu.com/p/a6cc6d9346ed)○🂣
* [iOS 平台如何使用 TestFlight 进行 Beta 测试](http://mp.weixin.qq.com/s?__biz=MzA4Mzg4ODE1NQ==&mid=2650417976&idx=1&sn=bb511a31c8c55413b4c531f1ab795f39&scene=0#wechat_redirect)○🂢
* [解放程序猿（媛）的双手—iOS UI自动化测试](http://tmq.qq.com/2016/06/uitestingiosautomation/)■🂣
* [使用Jenkins搭建iOS/Android持续集成打包平台](http://debugtalk.com/post/iOS-Android-Packing-with-Jenkins)○🂢
* [MLeaksFinder：精准 iOS 内存泄露检测工具](http://wereadteam.github.io/2016/02/22/MLeaksFinder/)○🂢
* [iOS内存泄漏自动检测工具PLeakSniffer](http://mrpeak.cn/blog/leak/)■🂢
* [Xcode 7 UI 测试初窥](https://onevcat.com/2015/09/ui-testing/)★🂡
* [iOS 性能优化：Instruments 工具的救命三招](https://blog.leancloud.cn/2835/)○🂢
* [手把手教你利用Jenkins持续集成iOS项目](http://www.jianshu.com/p/41ecb06ae95f)○🂣

#### 证书推送上架
* [iOS远程推送原理及实现过程(证书、iOS端代码、Java服务器代码)](http://blog.tingyun.com/web/article/detail/571)○🂣
* [细说 iOS 消息推送](http://www.cocoachina.com/industry/20140528/8582.html)○🂢
* [个推推送证书配及描述文件制作流程置](http://docs.getui.com/mobile/ios/apns/)○🂡
* [apicloud推送证书配及描述文件制作流程](http://docs.apicloud.com/Dev-Guide/iOS-License-Application-Guidance)○🂡
* [iOS消息推送之APNS](http://blog.csdn.net/jiajiayouba/article/details/39926017)○🂢
* [ios 如何判断是点击推送信息进入还是点击app图标进入程序](http://zhidao.baidu.com/link?url=QuZ9WZqZdHngaTSnao6-oZggHIw_f2KoSBj1-wu7cRZg2S7ytMATyGp-PnwtQOp90QgqKJ_Lk7e6lSmhf03tb-GIKgWmW9Zsu6sG2chMk3O)○🂡
* [史上最用心的iOS App上架流程](http://www.jianshu.com/p/16fa56eacb5e)○🂡

#### Blog
* [OneV's Den](https://onevcat.com/)
* [ObjC中国](https://objccn.io/issues/)
* [SwiftGG](http://swift.gg/)
* [唐巧的技术博客](http://blog.devtang.com/)
* [ibireme的技术博客](http://blog.ibireme.com/)
* [sunnyxx](http://blog.sunnyxx.com/)
* [bang's blog](http://blog.cnbang.net/)
* [WeRead团队博客](http://wereadteam.github.io/)
* [掘金翻译计划](https://github.com/xitu/gold-miner)
* [没故事的卓同学](http://www.jianshu.com/users/88a056103c02/)
* [一缕殇流化隐半边冰霜](http://www.jianshu.com/users/12201cdd5d7a/latest_articles)
* [MrPeak杂货铺](http://mrpeak.cn/)
* [WeRead团队博客](http://wereadteam.github.io/)
* [Andy矢倉](http://www.rockerhx.com/)
* [fir.im 飞行日志](http://blog.fir.im/)
* [美团点评技术团队](http://tech.meituan.com/)
* [玉令天下的博客](http://yulingtianxia.com/)
* [nixzhu/dev-blog](https://github.com/nixzhu/dev-blog)
* [老谭笔记](http://www.tanhao.me/)
* [叶孤城___ 的微博主页](http://weibo.com/u/1438670852/)
* [ChenYilong的Github主页](https://github.com/ChenYilong)
* [geeklu.com](http://geeklu.com/)
* [Top 100 Best Blogs for iOS Developers](http://www.softwarehow.com/best-blogs-for-ios-developers/)
* [我常常浏览的博客和网站](http://www.jianshu.com/p/e5353a1a752c)
* [斯坦福大学更新 iOS 9 编程开发新课程](https://itunes.apple.com/us/course/developing-ios-9-apps-swift/id1104579961)
* [swift.org](https://swift.org/)
* [swift中文文档](https://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/index.html)
* [SwiftGuide](https://github.com/ipader/SwiftGuide)
* [Swift开发者周刊](http://swiftweekly.cn/archive.html)
* [Swift精选内容](https://github.com/ipader/SwiftGuide/blob/master/Featured.md)
* [Auto Layout Club](https://autolayout.club)
* [nixzhu](https://github.com/nixzhu/dev-blog)
* [AloneMonkey](http://www.alonemonkey.com/)

#### iOS代码库
* [apple官方sample](https://developer.apple.com/library/ios/samplecode/)
* [apple-ios-samples](https://github.com/robovm/apple-ios-samples)
* [awesome-ios](https://github.com/search?utf8=%E2%9C%93&q=awesome-ios)
* [vsouza's awesome-ios](https://github.com/vsouza/awesome-ios)
* [awesome-ios-cn](https://github.com/jobbole/awesome-ios-cn)
* [awesome-swift](https://github.com/matteocrippa/awesome-swift)
* [ios_top_1000](https://github.com/iamdaiyuan/ios_top_1000)
* [TimLiu-iOS](https://github.com/Tim9Liu9/TimLiu-iOS#%E4%B8%8B%E6%8B%89%E5%88%B7%E6%96%B0)
* [cocoachina](http://code.cocoachina.com/)
* [code4app](http://code4app.com/category)
* [iOS走马观花](http://ios.b2mp.cn/)
* [iOS开源库](http://www.douban.com/note/276160185/?plg_nld=1&plg_uin=1&plg_auth=1&plg_usr=1&plg_dev=1&plg_vkey=1&plg_nld=1&type=like#!/i!/ckDefault)
* [Facebook Paper使用的第三方库](http://blog.rpplusplus.me/blog/2014/02/11/facebook-paper-used-3rd/)
* [适合新人学习的iOS官方Demo](http://www.jianshu.com/p/da65e54a55fc)
* [iOS完整App资源收集](http://www.henishuo.com/ios-app-fully-code/)
* [iOS学习资源汇总(开源项目、第三方库、技术博客等等)](http://www.jianshu.com/p/b7c4a787a597)
* [27个iOS开源库，让你的开发坐上火箭吧](http://www.jianshu.com/p/228535226656)
* [可以免费自学编程的12个网站](http://www.jianshu.com/p/9f094ce31075)

#### XCode插件
* [那些不能错过的Xcode插件](http://www.cocoachina.com/industry/20130918/7022.html)
* [iOS开发大神必备的Xcode插件](http://www.jianshu.com/p/ac8ac991d77b)

#### Bug Fix
* [Stripping Unwanted Architectures From Dynamic Libraries In Xcode](http://ikennd.ac/blog/2015/02/stripping-unwanted-architectures-from-dynamic-libraries-in-xcode/)

#### 其他
* [iOS-Source-Code-Analyze](https://github.com/Draveness/iOS-Source-Code-Analyze)
* [Limboy：自学 iOS 开发的一些经验](http://www.cocoachina.com/cms/wap.php?action=article&id=10823)
* [TSS](http://api.ineal.me/tss/status)
* [Big Nerd Ranch Books](http://forums.bignerdranch.com/)
* [AppCode](https://www.jetbrains.com/objc/)
* [使用j2objc实现iOS调java](http://blog.csdn.net/xyxjn/article/details/46049313)
* [VC之间的数据传递方式小结](http://www.jianshu.com/p/8edc728a0444)
* [获取当前AppDelegate 正在显示的UIViewController](http://blog.csdn.net/shaobo8910/article/details/47789027)
* [iOS图像处理](http://www.cnblogs.com/zanglitao/p/4036667.html)
* [iOS KVC & KVO](http://blog.jobbole.com/61044/)
* [能产生粒子效果的CAEmitterLayer](http://www.cnblogs.com/YouXianMing/p/3785876.html)
* [一文让你彻底了解iOS字体相关知识](http://www.cnblogs.com/dsxniubility/p/4699352.html)
* [iOS静态库的制作](http://www.jianshu.com/p/d70a51be5af1)
* [itunes](https://itunesconnect.apple.com)
* [2015年最新苹果开发者账号注册流程详解](http://www.niaogebiji.com/article-5703-1.html)
* [高斯模糊算法](http://www.ruanyifeng.com/blog/2012/11/gaussian_blur.html)
* [iOS静态库制作](http://www.jianshu.com/p/df0548780cd0)
* [解决常见的masksToBounds离屏渲染带来的性能损耗](http://zyden.vicp.cc/zycornerradius/)
* [逆向分析网络协议iOS篇](https://mp.weixin.qq.com/s?__biz=MzIwMTYzMzcwOQ==&mid=403204191&idx=1&sn=514664cc05597f8b76730cbf9f3a57f5)
* [Objective-C和Swift混编的一些经验](http://www.jianshu.com/p/a5e6e574145b)
* [用OCLint给iOS代码做静态分析](http://blog.csdn.net/uxyheaven/article/details/50818107)
* [如何在Cell中有不定数量个带图Button的情况下,保持性能和代码可读性?](http://reviewcode.cn/article.html?hmsr=toutiao.io&reviewId=15&utm_medium=toutiao.io&utm_source=toutiao.io)
* [Apple Pay接入详细教程](http://www.jianshu.com/p/738aee78ba52)
* [iOS实现简单的抽屉式侧栏——MMDraweController的使用](http://www.jianshu.com/p/940568a36e2c)
* [HTTPS科普扫盲帖](https://segmentfault.com/a/1190000004523659?f=tt&hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
* [在LLDB中一键打开模拟器sandbox路径](http://openfibers.github.io/blog/2016/03/04/open-sandbox-folder-in-lldb/)
* [iOS代码规范自动化](http://jwdev.cn/2016/02/29/iOS%E4%BB%A3%E7%A0%81%E8%A7%84%E8%8C%83%E8%87%AA%E5%8A%A8%E5%8C%96/)
* [让你爱上用代码自动布局——SDAutoLayout](http://blog.talisk.cn/blog/2016/03/03/iOS-SDAutoLayout/)
* [使用 Chrome 扩展程序 JSON Viewer 进行调试](http://blog.jayxhj.com/2016/01/using-json-viewer-for-debugging/)
* [UIKit性能调优实战讲解](http://www.jianshu.com/p/619cf14640f3)
* [你应当了解，但有可能不知道的Swift技巧](http://geek.csdn.net/news/detail/58593)
* [《招聘一个靠谱的iOS》面试题参考答案](https://github.com/ChenYilong/iOSInterviewQuestions/tree/master/01%E3%80%8A%E6%8B%9B%E8%81%98%E4%B8%80%E4%B8%AA%E9%9D%A0%E8%B0%B1%E7%9A%84iOS%E3%80%8B%E9%9D%A2%E8%AF%95%E9%A2%98%E5%8F%82%E8%80%83%E7%AD%94%E6%A1%88)
* [iOS7使用原生API进行二维码和条形码的扫描](http://my.oschina.net/u/2340880/blog/405847?fromerr=TWrCF6HG)
* [iOS 原生扫 QR 码的那些事](http://c0ming.me/qr-code-scan/)
* [iOS应用间跳转](http://www.jianshu.com/p/732c5e1720d0)
* [实现 iOS App 在线安装(局域网OTA)](http://www.jianshu.com/p/0546968b2d91)
* [iOS一分钟学会环形进度条](http://www.jianshu.com/p/e70a6068174f)
* [iOS10个实用小技巧](http://www.jianshu.com/p/a3156826c27c)
* [在 OC 项目中使用基于 Swift 的 CocoaPods 库](http://davidleee.com/2016/05/12/Use-Swift-framework-in-OC-project/)
* [检测iOS的APP性能的一些方法](http://www.starming.com/index.php)
* [一步一步实现iOS微信自动抢红包(非越狱)](http://www.jianshu.com/p/189afbe3b429)
* [iOS冰与火之歌 – 利用XPC过App沙盒](http://drops.wooyun.org/papers/14170)
* [iOS 视图控制器转场详解](https://github.com/seedante/iOS-Note/wiki/ViewController-Transition)
* [ios NSURLSession后台传输](http://www.cnblogs.com/trying/p/3790501.html)
* [UIButton的响应事件 UIControlEvents 类型说明](http://my.oschina.net/shede333/blog/509777?fromerr=MdBjGaCh)

* [移动端图片格式调研](http://blog.ibireme.com/2015/11/02/mobile_image_benchmark/)
* [WKWebView的使用和各种坑的解决方法（OC＋Swift）](http://www.jianshu.com/p/403853b63537)
* [iOS 9新特性、泛型、__kindof的使用](http://www.jianshu.com/p/3f73e696dd4d)
* [iOS 监听键盘伸缩调整输入框位置](http://www.jianshu.com/p/17b703b452cb)
* [iOS图片圆角的裁剪优化](http://www.jianshu.com/p/b91fea25c892)
* [const修饰全局变量取代宏定义](http://www.jianshu.com/p/ee4471b1a05d)
* [UIStackView 基础介绍](http://www.jianshu.com/p/ed981a87080b)
* [教你快速拿到iOS应用中所有图片资源](http://www.jianshu.com/p/78dea31f2109)
* [Xcode 8：如何创建 iMessage 动图](http://swift.gg/2016/07/14/xcode-8-create-an-animated-imessage-sticker/)
* [实现类似QQ微信视频的iOS小窗口自由拖动](http://www.jianshu.com/p/42c5f608349b)
* [iOS仿微信小视频功能开发优化记录](http://www.jianshu.com/p/6d35bb53f4ac)
* [详解 SiriKit - SiriKit 教程（Part 2）](http://swift.gg/2016/07/18/sirikit-swift-3-resolutions-sirikit-tutorial-part-2/)
* [iOS-状态栏设置](http://www.jianshu.com/p/5aa05983b445)
* [让UIWebview拥有超强的图片处理能力](http://www.jianshu.com/p/a46297f2ce70)
* [iOS 利用 framework 进行动态更新](http://yq.aliyun.com/articles/3024)
* [Xcode 8.0 Beta发布，详解Swift语言的重大变化](http://blog.csdn.net/gf771115/article/details/51682728)
* [Xcode 8 Auto Layout新特性](http://www.jianshu.com/p/2521c610fac3)
* [iOS 10  推送Notification新特性](http://www.jianshu.com/p/9b720efe3779)
* [关于IB_DESIGNABLE / IBInspectable的那些需要注意的事](http://www.jianshu.com/p/a5351d270ac1)
* [Launch Page让Logo"飞"出屏幕](http://www.jianshu.com/p/3fe831108001)
* [iOS如何优雅的处理“回调地狱Callback hell”(二)——使用Swift](http://www.jianshu.com/p/deb65d0a6b8c)
* [iOS如何优雅的处理“回调地狱Callback hell”(一)——使用PromiseKit](http://www.jianshu.com/p/f060cfd52f17)
* [搞定RSA（公钥、私钥）](http://blog.csdn.net/yi_zz32/article/details/50097325)
* [iPhone/iOS开启个人热点的纵向适配小结](http://blog.csdn.net/phunxm/article/details/42967035)
* [iOS UIDevice & iOS检测屏幕旋转实例](https://my.oschina.net/wolx/blog/387315)
* [Swift3.0 - 真的很简单](http://www.jianshu.com/p/a10afa7f9ce2)
* [在iOS 8中使用UIAlertController](http://www.cocoachina.com/ios/20141126/10320.html)
* [iOS UILabel 边框出现黑线问题](http://blog.csdn.net/dashudeshu/article/details/49784251)
* [iOS开发——创建你自己的Framework](http://blog.csdn.net/u013604612/article/details/43197465)
* [合并生成模拟器和真机通用的framework](http://msching.github.io/blog/2014/05/05/custom-framework-merging/)
* [Swift如何打印一个对象的地址](http://www.jianshu.com/p/84f244ec49dd)
* [关于Autolayout和Masonry自动布局的几个坑](http://ibloodline.com/articles/2016/03/02/autolayout-questions.html)
* [iOS编译过程的原理和应用](http://www.kuqin.com/shuoit/20160114/350029.html)
* [写给 iOS 开发者看的 HTTPS 指南](https://autolayout.club/2016/12/22/%E5%86%99%E7%BB%99-iOS-%E5%BC%80%E5%8F%91%E8%80%85%E7%9C%8B%E7%9A%84-HTTPS-%E6%8C%87%E5%8D%97/)
* [微信,QQ这类IM app怎么做——谈谈Websocket](http://www.jianshu.com/p/bcefda55bce4)
* [API Design Guidelines](https://swift.org/documentation/api-design-guidelines/)
* [Swift 3 新特性一览](https://realm.io/cn/news/appbuilders-daniel-steinberg-whats-new-swift-3/?utm_source=tuicool&utm_medium=referral)
* [Swift 3 中的函数参数命名规范指北](http://www.open-open.com/lib/view/open1476063231290.html)
* [iOS 异步图片加载优化与常用开源库分析](https://segmentfault.com/a/1190000002776279)
* [重定义你的XCode Console](http://hyyy.me/2017/01/16/RemoteConsole/?from=timeline&isappinstalled=0&nsukey=DqsZpkVB4xLdkdDg6FW63qvumOkdmKjqj1a9ekbFXz4y6%2F9b%2FzPsgNIz33SWp2jG6Pjg%2Bs4q3SkKYaPzqiZUYttn47vuBhDv6dcrYMP051VPnSnq7YGADIyGVSfBYocyrvjUtdgJtepiwme4t65Pc1tRISeykfmH77LpbUA7TdKGXYcJm7NfPTiRzV5n8PhW)
* [iOS开发--一步步教你彻底学会『iOS应用间相互跳转』](http://www.jianshu.com/p/b5e8ef8c76a3)
* [谈谈 iOS 中图片的解压缩](http://blog.leichunfeng.com/blog/2017/02/20/talking-about-the-decompression-of-the-image-in-ios/)
* [iOS开发中当TableView遇到导航栏自动下移的解决方案](http://www.code4app.com/blog-826368-806.html)


### iOS逆向工程

#### Reveal
* [iOS开发中集成Reveal](http://git.devzeng.com/blog/ios-reveal-integrating.html)
* [Reveal:分析iOS UI的利器](http://security.ios-wiki.com/issue-3-4/)
* [Reveal查看任意app的高级技巧](http://c.blog.sina.com.cn/profile.php?blogid=cb8a22ea89000gtw)
* [iOS Debug 速查表](https://everettjf.github.io/2016/05/25/my-ios-debug-cheatsheet)


### Git相关

#### git教程
* [廖雪峰git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
* [awesome-github](https://github.com/AntBranch/awesome-github)


### Emacs相关

#### emacs教程
* [从零开始——Emacs 安装配置使用教程 2015](http://www.jianshu.com/p/b4cf683c25f3)
* [一年成为Emacs高手(像神一样使用编辑器)](https://github.com/redguardtoo/mastering-emacs-in-one-year-guide/blob/master/guide-zh.org)


### Vim相关

#### vim教程
* [简明Vim练级攻略](http://coolshell.cn/articles/5426.html)
* [Vim新手节省时间的10多个小技巧](http://9iphp.com/linux/time-saving-tips-for-unix-vim-beginners.html)
* [用Vim来打造自己心仪的IDE](http://v2ex.com/t/235055)
* [vim快速上手](http://www.jianshu.com/p/33100d3fa173)
* [程序员的编辑器-VIM(爱就是爱)](http://www.jianshu.com/p/216811be226b)


### Markdown相关

#### markdown相关
* [Markdown——入门指南](http://www.jianshu.com/p/1e402922ee32)


### Mac相关

#### mac配置
* [如何配置一个高效的 Mac 工作环境](https://github.com/macdao/ocds-guide-to-setting-up-mac)
* [如何大幅度提高 Mac 开发效率](https://bestswifter.com/efficient-mac/)
* [让你用 Chrome 上网快到想哭：Vimium](http://sspai.com/27723/)


#### mac工具
* [awesome-mac](https://github.com/jaywcjlove/awesome-mac)
* [Homebrew](http://brew.sh/index_zh-cn.html)
* [apple.com/downloads](https://developer.apple.com/downloads/)
* [Java for OS X 2015-001](https://support.apple.com/kb/DL1572?viewlocale=en_US&locale=en_US)
* [iTerm](http://swiftcafe.io/2015/07/25/iterm/)
* [iOS程序员必备常用工具](http://mozhenhau.com/2016/01/11/%E7%A8%8B%E5%BA%8F%E5%91%98%E5%BF%85%E5%A4%87%E5%B8%B8%E7%94%A8%E5%B7%A5%E5%85%B7%E8%AE%B0%E5%BD%95---MAC/)
* [Network Link Conditioner(Xcode插件,网络调节工具)](http://nshipster.com/network-link-conditioner/)


### 资源

#### 图标资源
* [iconfont.cn](http://www.iconfont.cn/)
