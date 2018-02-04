# Awesome-iOS-Articles
A collection of the best articles that explaining topics on iOS.

# Inspiration

从头开始学习一个知识总是很难, 好在已经有前人为我们铺路, 通过别人记录的文章可以让我们更快的上手,但是要在茫茫大海里找到一篇质量上乘的文章却不那么容易,这个集合就是为了让我们能够更快的找到某个知识点的最佳入门文章, 而剩下的就需要靠你自己实践了.
(PS: 其实最好的老师还是官方文档加自己动手实验,别人的东西仅供我们学习和参考.)

# Content

- [Objective-C](#objective-c)
- [Swift](#swift)
- [iOS SDK](#ios-sdk)
- [Performance](#performance)
- [Library and Frameworks](#library-and-frameworks)
- [Architecture](#architecture)
- [Others](#others)

***

# Objective-C

### Code Style
* [Google Objective-C Style Guide](https://google.github.io/styleguide/objcguide.html)

### Runtime
* [Understanding the Objective-C Runtime](http://cocoasamurai.blogspot.jp/2010/01/understanding-objective-c-runtime.html)

### Copy & MutableCopy
* [iOS 集合的深复制与浅复制](https://www.zybuluo.com/MicroCai/note/50592)

### 预编译和宏
* [iOS预编译指令详解](http://www.jianshu.com/p/1c71a3c713a4)
* [宏定义的黑魔法 - 宏菜鸟起飞手册](https://onevcat.com/2014/01/black-magic-in-macro/)

### Retain Cycle
* [iOS 容易引起“循环引用”的几种场景](http://blog.csdn.net/hherima/article/details/39078545)
* [深入研究Block用weakSelf、strongSelf、@weakify、@strongify解决循环引用](http://www.jianshu.com/p/701da54bd78c)
* [Tip: Avoid retain cycles without doing the strong to weak dance](http://iosdevtips.co/post/118711491198/avoid-retain-cycles-weak-strong)

# Swift

### Method Dispatch
* [Method Dispatch in Swift](https://www.raizlabs.com/dev/2016/12/swift-method-dispatch/)

# iOS SDK

### Layout pass
* [Demystifying iOS Layout](http://tech.gc.com/demystifying-ios-layout/)

### Runloop
* [深入理解RunLoop](http://blog.ibireme.com/2015/05/18/runloop/)
* [RunLoop 总结：RunLoop的应用场景（一）](http://blog.csdn.net/u011619283/article/details/53433243)
* [【iOS程序启动与运转】- RunLoop个人小结](http://www.jianshu.com/p/37ab0397fec7)
* [iOS 事件处理机制与图像渲染过程](http://www.cnblogs.com/yulang314/p/5091894.html)
* [iOS刨根问底-深入理解RunLoop](http://www.cnblogs.com/kenshincui/p/6823841.html)

### Thread
* [iOS多线程到底不安全在哪里？](http://mrpeak.cn/blog/ios-thread-safety/)
* [从一道网易面试题浅谈OC线程安全](http://www.jianshu.com/p/cec2a41aa0e7)
* [深入理解 iOS 开发中的锁](http://blog.csdn.net/abc649395594/article/details/52747864)
* [pthread的各种同步机制](https://casatwy.com/pthreadde-ge-chong-tong-bu-ji-zhi.html)
* [libpthread 源码](https://opensource.apple.com/tarballs/libpthread/)

### GCD
* [Using dispatch groups to wait for multiple web services](http://commandshift.co.uk/blog/2014/03/19/using-dispatch-groups-to-wait-for-multiple-web-services/)

### Response Chain
* [史上最详细的iOS之事件的传递和响应机制-原理篇](http://www.jianshu.com/p/2e074db792ba)
* [iOS事件响应链中Hit-Test View的应用](http://www.jianshu.com/p/d8512dff2b3e)

### NSTimer
* [NSTimer和实现弱引用的timer的方式](http://blog.csdn.net/yohunl/article/details/50614903)

### NSDate
* [iOS时间那点事](https://my.oschina.net/yongbin45/blog/150114)
* [iOS关于时间的处理](http://mrpeak.cn/blog/ios-time/)
* [Cache NSDateFormatter](https://coderwall.com/p/yjnkwg/cache-nsdateformatter)

### NSNumber
* [Currency & High Precision Numbers With NSDecimalNumber](http://iosdevelopertips.com/data-file-management/currency-high-precision-numbers-with-nsdecimalnumber.html)
* [The Floating-Point Guide](http://floating-point-gui.de/)

### NSUserDefaults
* [A look at how to use, and not to use, NSUserDefaults in your programs](http://dscoder.com/defaults.html)

### Mask
* [关于使用CALayer中mask的一些技巧](http://joeshang.github.io/2014/12/19/calayer-mask/)
* [高级mask应用](http://www.cnblogs.com/YouXianMing/p/3788270.html)

### NSNotification
* [iOS NSNotificationCenter 使用姿势详解](http://www.ifelseboy.com/2015/08/20/ios-nsnotificationcenter-shi-yong-zi-shi-xiang-jie/)
* [Unregistering NSNotificationCenter Observers in iOS 9](http://useyourloaf.com/blog/unregistering-nsnotificationcenter-observers-in-ios-9/)

### Xib & StoryBoard
* [iOS 关于 xib 的那些事](https://gist.github.com/Josscii/cb700299ec8e4cf22af12a9344dd3bf2)

### Core Animation
* [iOS CoreAnimation专题——总览篇](http://blog.csdn.net/u013282174/article/details/50252455)

### UINavigationController && UINavigationBar
* [透明与半透明 NavigationBar 切换的三种方案](http://www.jianshu.com/p/e3ca1b7b6cec)
* [iOS NavigationBar 背景颜色设置方案探究](http://www.jianshu.com/p/6a5552ec5099)
* [一个丝滑的全屏滑动返回手势](http://blog.sunnyxx.com/2015/06/07/fullscreen-pop-gesture/)
* [AHKNavigationController](https://github.com/fastred/AHKNavigationController)

### UIStatusBar
* [在iOS7中修改状态栏字体的颜色](http://blog.csdn.net/gaoyp/article/details/38441723) / [补充](https://gist.github.com/Josscii/51d5154583e38fef24a5380abdb18a0c)

### Text
* [NSParagraphStyle Explained Visually](https://medium.com/@at_underscore/nsparagraphstyle-explained-visually-a8659d1fbd6f#.md3yj2pqw)
* [UIFont Explained Visually](https://medium.com/@at_underscore/uifont-explained-visually-7de1a9c9f7a1#.5llg1dtv0)

### ViewController Containing
* [Make `automaticallyAdjustsScrollViewInsets` Great Again](https://gist.github.com/steipete/5622e0a7e6dd60957a08)

### APNs
* [基于HTTP2的全新APNs协议](https://github.com/ChenYilong/iOS9AdaptationTips/blob/master/%E5%9F%BA%E4%BA%8EHTTP2%E7%9A%84%E5%85%A8%E6%96%B0APNs%E5%8D%8F%E8%AE%AE/%E5%9F%BA%E4%BA%8EHTTP2%E7%9A%84%E5%85%A8%E6%96%B0APNs%E5%8D%8F%E8%AE%AE.md)
* [iOS推送——本地推送与远程推送详解（一图看懂）](http://www.jianshu.com/p/bcece05517fc) `<= iOS 9`
* [iOS 开发中，怎样用好 Notifications？](http://www.jianshu.com/p/f20b00c1fc24) `iOS 10` 

### UIWebView & WKWebView
* [UIWebView Memory Leak Prevention](http://www.codercowboy.com/code-uiwebview-memory-leak-prevention/)
* [WKWebView 那些坑](https://zhuanlan.zhihu.com/p/24990222)
* [源码分享：仿微信的WebViewProgress](http://lzcuriosity.github.io/2016/07/16/%E6%BA%90%E7%A0%81%E5%88%86%E4%BA%AB%EF%BC%9A%E4%BB%BF%E5%BE%AE%E4%BF%A1%E7%9A%84WebViewProgress/)

### Assets Catalog
* [4 XCODE ASSET CATALOG SECRETS YOU NEED TO KNOW](https://krakendev.io/blog/4-xcode-asset-catalog-secrets-you-need-to-know)
* [Add a resizable area to an image](http://help.apple.com/xcode/mac/8.3/#/deve65bd8d0d)
* [resizableImageWithCapInsets:方法的探析](http://www.jianshu.com/p/a577023677c1)
* [补充](https://gist.github.com/Josscii/599c42c684b6ca8dc1831e0a4caed761)

### UIImage
* [Resize a UIImage the right way](http://vocaro.com/trevor/blog/2009/10/12/resize-a-uiimage-the-right-way/)
* [Image Resizing Techniques](http://nshipster.com/image-resizing/)

### UIView
* [Tint Color and Template Images](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/UIKitUICatalog/)

### UIWindow
* [UIWindow in iOS](http://www.fantageek.com/2014/08/28/uiwindow-in-ios/)
* [浅谈iOS的多Window处理](https://satanwoo.github.io/2016/09/17/uiwindow-iOS/)

### UIButton
* [理解UIButton的imageEdgeInsets和titleEdgeInsets](http://blog.intmaxdev.com/2016/04/10/uibutton-edgeinsets/)

### UITableview
* [Swift Image Cache](http://www.splinter.com.au/2015/09/24/swift-image-cache/)
* [Asynchronous downloaded images with caching](http://khanlou.com/2012/08/asynchronous-downloaded-images-with-caching/)
* [戏说CollectionView、TableView如何优雅应对变化的界面展示](http://zackzheng.info/2016/04/24/2016-04-24-handle-collectionview-tableview-with-grace/)
* 不浮动的 section header [[1](http://johnwong.github.io/mobile/2015/07/04/ios-quirks.html)] [[2](http://blog.csdn.net/hherima/article/details/51030113)]
* [深入reloadData](http://www.jianshu.com/p/b482ccaf8bba)

### URL Schemes & Universal Links
* [The Complete Tutorial on iOS/iPhone Custom URL Schemes](http://iosdevelopertips.com/cocoa/launching-your-own-application-via-a-custom-url-scheme.html)
* [Deferred Deep Linking in iOS](http://tech.glowing.com/cn/deferred-deep-linking-and-branch-sdk-in-ios/)
* [iOS: How to open Deep Links, Notifications and Shortcuts](https://medium.com/ios-os-x-development/ios-how-to-open-deep-links-notifications-and-shortcuts-253fb38e1696)

### InterfaceBuilder
* [Using Interface Builder at Lyft](http://scottberrevoets.com/2017/03/06/using-interface-builder-at-lyft/)

### Custom Transition
* [iOS 视图控制器转场详解](https://github.com/seedante/iOS-Note/wiki/ViewController-Transition)

### TextKit
* [iOS: 利用TextKit实现UILabel的高亮、可交互](http://www.jianshu.com/p/29a893531ab3)

### UI
* [如何设计一个 iOS 控件?(iOS 控件完全解析)](http://blog.csdn.net/zhangao0086/article/details/45622875)
* [iOS 文本对齐，如何像素般精确还原设计稿](https://zhuanlan.zhihu.com/p/27572662)

### 截图
* [我只是想要截个屏](http://blog.startry.com/2016/02/24/Screenshots-With-SwViewCapture/)
* [Getting a screenshot of a UIScrollView, including offscreen parts](https://stackoverflow.com/questions/3539717/getting-a-screenshot-of-a-uiscrollview-including-offscreen-parts)

### LaunchImage
* [Tips:获取APP的Launch Image](http://adad184.com/2015/10/15/tips-access-current-launch-image/)

# Performance

### Scroll
* [保持界面流畅的学习路径](https://gist.github.com/Josscii/22330cfdb3ec682e13e07b7ad4df56ca) 💥💥💥💥💥
* [iOS Scroll Performance Tutorial](https://tech.okcupid.com/ios-performance-tutorial-from-okcupid/) 💥💥💥💥💥

### Image
* [ImageCachingBenchmark](https://github.com/bpoplauschi/ImageCachingBenchmark/)

# Library and Frameworks

### Masonry
* [追求Masonry](http://www.jianshu.com/p/1841e6c69611)

# Architecture

### 网络层
* [与时俱进，HTTP/2下的iOS网络层架构设计](http://www.jianshu.com/p/a9bca62d8dab)
* [对比iOS网络组件：AFNetworking VS ASIHTTPRequest](http://www.infoq.com/cn/articles/afn_vs_asi)

# Others

### 切图
* [Pixel Density, Demystified(需翻)](https://medium.com/@pnowelldesign/pixel-density-demystified-a4db63ba2922#.z6k6c93ua)
* [从视觉到App：网易有钱iOS项目切图与适配实践](http://www.infoq.com/cn/articles/netease-ios-vision-to-app/)
* [The Ultimate Guide To iPhone Resolutions](https://www.paintcodeapp.com/news/ultimate-guide-to-iphone-resolutions)

### 打包
* [Using -exportArchive instead of Package Application to export an IPA](http://subathrathanabalan.com/2016/01/07/building-ipa-export-archive/)

### 证书
* [iOS Provisioning Profile(Certificate)与Code Signing详解](http://blog.csdn.net/phunxm/article/details/42685597/)

### 调试
* [小笨狼与LLDB的故事](http://www.jianshu.com/p/e89af3e9a8d7)
* [小笨狼的LLDB技巧:chisel](http://www.jianshu.com/p/afaaacc55460)

### Git
* [Become a git guru](https://www.atlassian.com/git/tutorials)
* [Learn Version Control with Git](https://www.git-tower.com/learn/git/ebook/en/command-line/introduction)
* [Pro Git book](https://git-scm.com/book/en/v2)

### 正则表达式
* [regular-expressions.info](http://www.regular-expressions.info/)

***

# Contribution

如果你也想参与其中, 或者对于某个主题有更好的推荐的文章, 欢迎提 issues 或者 pull request!
