# Welcome to ACMD (Australian Chinese Mobile Developers)!

## 微信聊天精华
### 08/03/2015 - 14/03/2015
* 关于Swift
	* 目前还缺[reflection](http://en.wikipedia.org/wiki/Reflection_%28computer_programming%29)特性（respondsToSelector, confromsToProtocol, NSClassFromString等），从而导致无法用[ocmock](http://ocmock.org/)
	* IDE不稳定，经常崩溃
	* IDE不支持refactor
	* 不支持C++，得用[objc wrapper](http://stackoverflow.com/questions/24042774/can-i-mix-swift-with-c-like-the-objective-c-mm-files)，造成项目文件巨大

* 关于WatchKit
	* Xcode 6.2暂时还没有AppleWatch的模拟器，目前用Resiable ipad模拟器
	* AppleWatch只是附属，算是iOS app的一个远程屏幕（类比：view在手表上，viewcongtroller在iPhone上）
	* 明年可能会有native watch app

	
* 关于Android
	* 美国Android需求超过iOS，除了tablet app，很多公司的移动应用开始优先考虑Android 
	* 4.0开始和iOS缩小差距，5.0强制[ART(Android Runtime)](http://en.wikipedia.org/wiki/Android_Runtime)，摈弃[dalvik](http://en.wikipedia.org/wiki/Dalvik_%28software%29)虚拟机，性能已经好于iOS（简单说从安装的时候就是编译后的机器语言）
	* 对移动开发者来说，Android开发可发挥的余地更大，薪资行情还是iOS好一些

* 关于[Test Automation](http://en.wikipedia.org/wiki/Test_automation)
	* iOS不太需要automation，只需要unit test和integration test，毕竟设备大小就那几种
	* Android则必须要automation，自带的[test framework](http://developer.android.com/tools/testing/testing_ui.html)就挺好

* 关于Mobile Web App
	* 门槛低，对startup更适合
	* framework [ionic](http://ionicframework.com/): phonegap ＋ angularjs。有自己的lib，但是和angularjs结合很好。性能不错。
	* 也有直接用[phonegap](http://phonegap.com/) ＋ [angularjs](https://angularjs.org/)

* 关于backend
	* [azure](http://azure.microsoft.com/en-us/)：heroku类似，但是能做更多的东西，比如vm、数据库服务、cache。
	* [parse](https://www.parse.com/)：权限管理和admin界面亲切。可以当NoSQL用，随便加字段。Push notificaiton服务也不错。scale好于heroku

* 问题：设备上唯一id是ad id吗，用户关闭ad tracking后会出问题吗？
	* 貌似没有绝对唯一的id，vendor id删除app后就没了。advertiser则是reset系统后才被reset。
	* 如何保证唯一id：系统login之后由服务器分配token，没有试过“同一用户不同设备需要不同id”的需求。另外GA的tracking是自己有advertiser id 

* 关于animation
	* facebook的[pop](https://github.com/facebook/pop)
	* facebook的[AsyncDisplayKit](http://asyncdisplaykit.org/)
	
* 关于prototype
	* facebook的[origami](https://facebook.github.io/origami/)，支持输出iOS、Android和js。2.0支持导出code
	* relativewave的[form](www.relativewave.com/form)

### 15/03/2015 - 21/03/2015
