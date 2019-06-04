# Shenbijiaochen

##  V2RAY使用方法
###  新版UI下载客户端和查看订阅链接方法
点击用户中心
![](https://image.nuccombat.cn/images/2019/06/04/UI.jpg)
左下角即可看到订阅链接和软件下载
![](https://image.nuccombat.cn/images/2019/06/04/UI2.jpg)

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

####  Android端设置方法

Android端V2RAY基本同Shadowsocks

在站点下载apk

![](https://image.nuccombat.cn/images/2019/06/02/Android.jpg)

安装完成后启动，先在站点复制订阅链接，然后回到V2Ray右上角+号，进入自定义配置

![](https://image.nuccombat.cn/images/2019/06/02/100df00c0f629ac1cfc4efb98bd8b5c3.jpg)

之后选择剪贴板URL导入自定义配置即可。

Android下面V2ray设置中可以设置分应用代理，非常方便

####  Android端应用分流方法
应用左上角打开菜单界面 进入Setting（设置）
![](https://image.nuccombat.cn/images/2019/06/04/2f4f17f341689fac30151ec32a841681.jpg)
设置选择第一个Per-app proxy
![](https://image.nuccombat.cn/images/2019/06/04/2.jpg)
进入后可以选择模式（第一个是选中的应用流量走V2，第二个是选中的流量不走V2） 我们以Youtube设置流量走V2为例，在搜索框中搜索Youtube 勾选即可，这个功能用处是在于可以让客户端通过应用方式来决定是否将流量转发到V2
![](https://image.nuccombat.cn/images/2019/06/04/3.jpg)

###  IOS端
以Kitsunebi为例，IOS端也可用使用QUANT
~~感谢不具名大佬的协助~~
进入应用后，点击右上角加号，将会弹出弹窗，选择订阅
![](https://image.nuccombat.cn/images/2019/06/04/IOS1.jpg)
进入订阅，URL填写站点获取的订阅地址，备注任意填写即可，填写完成后点击存储，存储后点击从URL获取更新即可更新到最新服务器信息
![](https://image.nuccombat.cn/images/2019/06/04/IOS2.jpg)
