## PC端如何通过SwitchyOmega插件来增强代理稳定性

**第一步：安装SwitchyOmega插件**：

- 【推荐】Edge浏览器安装方法：[点此跳转](https://microsoftedge.microsoft.com/addons/detail/proxy-switchyomega/fdbloeknjpnloaggplaobopplkdhnikc?hl=zh-CN)插件页面并点击安装
- Chrome浏览器安装方法：[点此打开](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif?hl=zh-CN)应用商店点【添加至Chrome】；如果无法访问应用商店，[点此下载离线安装包](https://dl.ssrss.club/SwitchyOmega_Chromium.zip)，然后参考百度经验教程安装（**注意插件后缀名是zip，解压后跳到百度经验里面的步骤4**）:[点此跳转到教程](https://jingyan.baidu.com/article/219f4bf7a0b737de442d38e8.html)

**第二步：设置proxy模式**

- 如图先设置全局代理模式：【SOCKS5--127.0.0.1--端口】

> 注意：
> - Clash的代理端口是7890
> - v2rayN的代理端口：windows上是10808，其他系统要到软件设置里面看socks5端口号或上网查

![图片2.png](https://yiy.one/upload/image/20210518/1621324184740842.png "1621324184740842.png")

**第三步，切换代理模式即可上网（一定要切换不然用不了）**：
在浏览器地址栏右侧找到圆圈状的SwitchyOmega插件图标，左键点击后出现以下菜单，然后点【系统代理]】或者【Proxy】：

![image.png](https://yiy.one/upload/image/20210723/1627050489338408.png "1627050489338408.png")

> **模式说明：**
> 【系统代理】开启VPN并打开VPN的系统代理模式时，浏览器走代理，关闭时直连。
> 【proxy】强行开启代理（代理更稳定，但VPN没启动时无法上网）
> 【直接连接】关闭代理（如果无法上网，显示代理服务器有问题，可以用这个恢复国内上网功能）

**此时点击切换到[Proxy]或者[系统代理]模式应该可以上外网了，如果还不行就重启一下浏览器**
