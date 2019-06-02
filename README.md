# Shenbijiaochen

##  V2RAY使用方法

###  Windows端

登录站点，进行下载

![](https://image.nuccombat.cn/images/2019/06/02/--Windows.jpg)

解压之后打开客户端

![](https://image.nuccombat.cn/images/2019/06/02/93700a34460bdc1cdc4164134014c5de.jpg)

点击订阅-订阅管理

![](https://image.nuccombat.cn/images/2019/06/02/1.jpg)

点添加，之后在如图界面输入备注和在网站获取的订阅链接

![](https://image.nuccombat.cn/images/2019/06/02/2141a5c999af13f13.jpg)

确定，然后再点击订阅-更新订阅，即可获取节点

![](https://image.nuccombat.cn/images/2019/06/02/392e958c1d64b6536b03c038370911e9.jpg)

获取成功后，右键托盘区V2RAY图标，启动代理即可（类似shadowsocks）

![](https://image.nuccombat.cn/images/2019/06/02/f975f30f625b37513cfec4bf9ff27ea3.jpg)

Http代理模式一般只使用前两种，服务器用于切换节点服务器

![](https://image.nuccombat.cn/images/2019/06/02/51cec3048f1c59f79d2781d14d0a189c.jpg)

V2RAY的客户端使用需要配合浏览器的代理设置（Chrome下的SwitchOmega插件等），这里我推荐另一种比较方便的方法：配合SSTAP使用。由于V2Ray会提供一个默认端口为10808的本地Socks5代理（端口设置如下图所示，一般不用修改  参数设置-基本设置），我们可以利用这个把V2Ray转换成全局代理（SSTAP在站点-SSR-游戏端-下载客户端处下载）

![](https://image.nuccombat.cn/images/2019/06/02/socks5.jpg)

SSTAP中我们添加一个Socks5代理

![](https://image.nuccombat.cn/images/2019/06/02/socks5a4f073991ece036d.jpg)

如果没有修改端口，那么按照如图填写即可，修改了默认端口则在端口位置填写自己修改后的端口

![](https://image.nuccombat.cn/images/2019/06/02/socks51.jpg)

保存，之后我们会在SSTAP中看到这个代理，我们先启动V2RAY代理，然后再启动SSTAP，你将会获得一个类似VPN的全局代理体验（SSTAP一般选择只代理非中国IP或者绕过局域网和中国IP，这个根据自己情况选择）

###  Android端使用方法

Android端V2RAY基本同Shadowsocks

在站点下载apk

![](https://image.nuccombat.cn/images/2019/06/02/Android.jpg)

安装完成后启动，先在站点复制订阅链接，然后回到V2Ray右上角+号，进入自定义配置

![](https://image.nuccombat.cn/images/2019/06/02/100df00c0f629ac1cfc4efb98bd8b5c3.jpg)

之后选择剪贴板URL导入自定义配置即可。

Android下面V2ray设置中可以设置分应用代理，非常方便

###  IOS端

（待填坑）

