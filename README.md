# awesome-dev-blog-article
学习与开发过程中，发现的比较好的一些博客和文章之类的内容，收集着，利人利己，持续更新。

-----------------

## 目录

- [iOS开发相关](#iOS开发相关)
    - [iOS基础](#iOS基础)
    - [UITableView](#UITableView)
    - [UICollectionView](#UICollectionView)
    - [UINavigationController](#UINavigationController)
    - [CoreText](#CoreText)
    - [证书及推送](#证书及推送)
    - [缓存](#缓存)
    - [Block](#Block)
    - [GCD](#GCD)
    - [RAC/MVVM](#RAC/MVVM)
    - [Runtime](#Runtime)
    - [iOS Animation](#iOS Animation)
    - [扫码](#扫码)
    - [Swift](#Swift)
    - [CocoaPods](#CocoaPods)
    - [iOS代码库](#iOS代码库)
    - [调试](#调试)
    - [XCode插件](#XCode插件)
    - [Blog](#Blog)
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

#### iOS基础
* [OC语法基础](http://blog.csdn.net/jiangwei0910410003/article/category/2745191)
* [Objective-C代码规范](http://www.jianshu.com/p/4ef06ec81414)
* [从零开始学iOS开发的15条建议](http://www.jianshu.com/p/8472ba0f2bb6)
* [浅谈 Objective - C 内存管理（上）](http://www.jianshu.com/p/52f136a3df1a)
* [浅谈 Objective - C 内存管理（中）](http://www.jianshu.com/p/1d9f6fc2a1b7)
* [浅谈 Objective - C 内存管理（下）](http://www.jianshu.com/p/36d5d98c9d3a)
* [Objective-C的@property的详细解读](http://blog.talisk.cn/blog/2016/03/05/iOS-@property/)
* [iOS应用程序的生命周期](http://www.jianshu.com/p/aa50e5350852?utm_campaign=maleskine&utm_content=note&utm_medium=writer_share&utm_source=weibo)
* [@weakify, @strongify](http://www.jianshu.com/p/3d6c4416db5e)
* [开始iOS 7中自动布局教程(一)](http://www.cocoachina.com/industry/20131203/7462.html)
* [开始iOS 7中自动布局教程(二)](http://www.cnblogs.com/zer0Black/p/3977288.html)

#### UITableView
* [UITableView和UITableViewCell的几种样式](http://blog.sina.com.cn/s/blog_4669f1cd0101qyp9.html)
* [UITableView使用详解](http://blog.sina.com.cn/s/blog_9693f61a01016lv5.html)
* [UITableView优化技巧](http://longxdragon.github.io/2015/05/26/UITableView%E4%BC%98%E5%8C%96%E6%8A%80%E5%B7%A7/) 
* [iOS 保持界面流畅的技巧](http://blog.ibireme.com/2015/11/12/smooth_user_interfaces_for_ios/)
* [iOS 异步图片加载优化与常用开源库分析](https://segmentfault.com/a/1190000002776279)
* [AsyncDisplayKit 教程：达到 60 FPS 的滚动帧率](http://www.cocoachina.com/swift/20141124/10298.html)
* [优化UITableViewCell高度计算的那些事](http://blog.sunnyxx.com/2015/05/17/cell-height-calculation/)
* [iOS 程序性能优化](http://www.samirchen.com/ios-performance-optimization/)
* [iOS 高性能异构滚动视图构建方案](http://pingguohe.net/2016/01/31/lazyscroll.html)

#### UICollectionView
* [UICollectionView + UIKit Dynamics](http://objccn.io/issue-5-2/)
* [UICollectionView的数据预加载及图片加载逻辑的优化](http://blog.vars.me/blog/2015/04/26/UICollectionView-Optimizing/)

#### UINavigationController
* [用Reveal分析网易云音乐的导航控制器切换效果](http://jerrytian.com/2016/01/23/yong-revealfen-xi-wang-yi-yun-yin-le-de-dao-hang-kong-zhi-qi-qie-huan-xiao-guo/)
* [iOS-给push出来的控制器添加全局滑动(返回)手势](http://www.jianshu.com/p/158d68a730d3)

#### CoreText
* [CoreText入门](http://geeklu.com/2013/03/core-text/)
* [CoreText笔记 Part 1](http://longxdragon.github.io/2015/03/14/CoreText-Notes-Part-1/)

#### 证书及推送
* [iOS远程推送原理及实现过程(证书、iOS端代码、Java服务器代码)](http://blog.tingyun.com/web/article/detail/571)
* [iOS证书及描述文件制作流程](http://docs.apicloud.com/APICloud/%E6%8A%80%E6%9C%AF%E4%B8%93%E9%A2%98/iOS-License-Application-Guidance)
* [创建Apple应用并创建APNS推送证书](http://docs.getui.com/pages/viewpage.action?pageId=1934165#id-创建Apple应用并创建APNS推送证书-APNSPush证书创建)
* [细说 iOS 消息推送](http://www.cocoachina.com/industry/20140528/8582.html)
* [iOS消息推送之APNS](http://blog.csdn.net/jiajiayouba/article/details/39926017)
* [ios 如何判断是点击推送信息进入还是点击app图标进入程序](http://zhidao.baidu.com/link?url=QuZ9WZqZdHngaTSnao6-oZggHIw_f2KoSBj1-wu7cRZg2S7ytMATyGp-PnwtQOp90QgqKJ_Lk7e6lSmhf03tb-GIKgWmW9Zsu6sG2chMk3O)

#### 缓存
* [iOS 网络缓存扫盲篇](https://www.v2ex.com/t/252955?from=singlemessage&isappinstalled=1)
* [缓存、缓存算法和缓存框架简介](http://blog.jobbole.com/30940/)

#### Block
* [Block简介与用法](http://blog.csdn.net/enuola/article/details/8674063)
* [Block深入问答](https://www.zhihu.com/question/34593410)

#### GCD
* [GCD 深入理解：第一部分](https://github.com/nixzhu/dev-blog/blob/master/2014-04-19-grand-central-dispatch-in-depth-part-1.md)
* [GCD 深入理解：第二部分](https://github.com/nixzhu/dev-blog/blob/master/2014-05-14-grand-central-dispatch-in-depth-part-2.md)
* [关于GCD开发的一些事儿](http://www.jianshu.com/p/f9e01c69a46f)
* [iOS中GCD的使用小结](http://www.jianshu.com/p/ae786a4cf3b1)
* [NSOperation and NSOperationQueue Tutorial in Swift](http://www.raywenderlich.com/76341/use-nsoperation-nsoperationqueue-swift)

#### RAC/MVVM
* [RAC/MVVM个人学习资源汇总](http://www.jianshu.com/p/2cfed74789db)
* [ReactiveCocoa 4 最佳实践](http://www.jianshu.com/p/da392a685a92)

#### Runtime
* [Objective-C Runtime](http://justsee.iteye.com/blog/2163777)
* [Runtime 学习笔记(一)](http://lastdays.cn/2016/02/20/runtime1/)
* [Runtime 学习笔记(二)](http://lastdays.cn/2016/02/20/runtime2/)

#### iOS Animation
* [iOS Animation](https://github.com/yixiangboy/IOSAnimationDemo)
* [Facebook POP 进阶指南](http://www.cocoachina.com/industry/20140704/9034.html)
* [iOS自定义转场动画实战讲解](http://www.jianshu.com/p/ea0132738057)
* [iOS使用Quartzcode设计动画，快速得到Object-C 和 Swift 代码](http://www.jianshu.com/p/90d6cd355b14)

#### 扫码
* [iOS7使用原生API进行二维码和条形码的扫描](http://my.oschina.net/u/2340880/blog/405847?fromerr=TWrCF6HG)
* [iOS 原生扫 QR 码的那些事](http://c0ming.me/qr-code-scan/)

#### Swift
* [swift.org](https://swift.org/)
* [swift中文文档](https://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/index.html)
* [SwiftGuide](https://github.com/ipader/SwiftGuide)
* [Swift开发者周刊](http://swiftweekly.cn/archive.html)
* [SwiftGG](http://swift.gg/)

#### CocoaPods
* [CocoaPods官网](https://cocoapods.org/)
* [借助GitHub托管Category,利用CocoaPods集成到项目中](https://github.com/Damonvvong/DWCategory/blob/master/README.md)
* [深入理解 CocoaPods](http://objccn.io/issue-6-4/)
* [ CocoaPods pod install/pod update更新慢的问题](http://blog.csdn.net/ralbatr/article/details/39082937)

#### iOS代码库
* [apple官方sample](https://developer.apple.com/library/ios/samplecode/)
* [awesome-ios](https://github.com/search?utf8=%E2%9C%93&q=awesome-ios)
* [vsouza's awesome-ios](https://github.com/vsouza/awesome-ios)
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

#### 调试以及日志
* [oneapm.com](http://www.oneapm.com/)
* [BugHD](http://bughd.com/)
* [CocoaLumberjack和XcodeColors的安装和使用](http://www.jianshu.com/p/7eb7725c933c)
* [CocoaLumberjack的ios应用开发使用指南](http://blog.csdn.net/jia12216/article/details/44412697)
* [iOS开发中的单元测试](http://www.infoq.com/cn/articles/ios-unit-test-1)
* [iOS 开发者旅途中的指南针 - LLDB 调试技术](http://www.jianshu.com/p/75a2b63106ff)
* [Xcode7中你一定要知道的炸裂调试神技](http://www.jianshu.com/p/70ed36cf8a98?utm_campaign=maleskine&utm_content=note&utm_medium=writer_share&utm_source=weibo)
* [如何使用Instruments诊断App(Swift版):起步](http://www.cocoachina.com/swift/20150623/12237.html)

#### XCode插件
* [那些不能错过的Xcode插件](http://www.cocoachina.com/industry/20130918/7022.html)

#### Blog
* [fir.im 飞行日志](http://blog.fir.im/)
* [唐巧的技术博客](http://blog.devtang.com/)
* [ibireme的技术博客](http://blog.ibireme.com/)
* [美团点评技术团队](http://tech.meituan.com/)
* [百度知道技术团队](http://blog.sunnyxx.com/)
* [王巍的技术博客](http://onevcat.com/)
* [玉令天下的博客](http://yulingtianxia.com/)
* [nixzhu/dev-blog](https://github.com/nixzhu/dev-blog)
* [叶孤城___ 的微博主页](http://weibo.com/u/1438670852/)
* [ChenYilong的Github主页](https://github.com/ChenYilong)
* [geeklu.com](http://geeklu.com/)

#### 其他
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
* [可以免费自学编程的12个网站](http://www.jianshu.com/p/9f094ce31075)
* [我常常浏览的博客和网站](http://www.jianshu.com/p/e5353a1a752c)
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
* [使用 Jenkins+Github+Xcode 对 iOS 项目做自动打包与持续集成，并将最终的 IPA 发布到 fir.im 上供下载](http://www.zengxianhua.com/2016/02/16/ti-gao-kai-fa-xiao-lu/)


### iOS逆向工程

#### Reveal
* [iOS开发中集成Reveal](http://git.devzeng.com/blog/ios-reveal-integrating.html)
* [Reveal:分析iOS UI的利器](http://security.ios-wiki.com/issue-3-4/)
* [Reveal查看任意app的高级技巧](http://c.blog.sina.com.cn/profile.php?blogid=cb8a22ea89000gtw)


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


### Markdown相关

#### markdown相关
* [Markdown——入门指南](http://www.jianshu.com/p/1e402922ee32)


### Mac相关

#### mac配置
* [如何配置一个高效的 Mac 工作环境](https://github.com/macdao/ocds-guide-to-setting-up-mac)

#### mac工具
* [Homebrew](http://brew.sh/index_zh-cn.html)
* [apple.com/downloads](https://developer.apple.com/downloads/)
* [Java for OS X 2015-001](https://support.apple.com/kb/DL1572?viewlocale=en_US&locale=en_US)
* [iTerm](http://swiftcafe.io/2015/07/25/iterm/)
* [iOS程序员必备常用工具](http://mozhenhau.com/2016/01/11/%E7%A8%8B%E5%BA%8F%E5%91%98%E5%BF%85%E5%A4%87%E5%B8%B8%E7%94%A8%E5%B7%A5%E5%85%B7%E8%AE%B0%E5%BD%95---MAC/)
* [Network Link Conditioner(Xcode插件,网络调节工具)](http://nshipster.com/network-link-conditioner/)


### 资源

#### 图标资源
* [iconfont.cn](http://www.iconfont.cn/)


