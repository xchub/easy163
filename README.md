# easy163 安卓版网易云助手  

**一键可用，无须 ROOT**  

**播放 VIP 和下架歌曲**  

**任意歌曲下载到本地**  

**下架歌曲收藏**  

工作原理：  
在本地搭建 VPN 服务，拦截修改重定向网易云 APP 的 HTTP 请求，从其他音乐平台获取资源

特性：
1. 支持 VIP 和下架歌曲播放
2. 任意歌曲下载
3. 支持收藏（不支持 Like）
4. 高精度歌曲匹配算法

已知问题：   
1. Easy163 开启时无法登录网易云音乐，请先关闭时登录，登录完毕后再打开
2. 用户自身个人主页不可用，暂时无解
3. 下载时若长时间显示正在计算文件长度然后失败，点击重试即可

使用方式：    
开启本软件的 VPN 服务即可使用
如无法使用请重启网易云  
开启本软件后如遇到设备网络异常请关闭本软件  

说明：    
开启本软件后网易云 APP 所有的 HTTP 请求皆由本软件代理，如质疑其安全性欢迎审阅源码并自行编译 APK     
本软件为实验性项目，请勿用于非法用途      
目前版本未能测试各个版本的网易云 APP，欢迎经测试后反馈问题    


捐赠支持（支付宝）：

**捐赠链接 https://qr.alipay.com/fkx11633kcs1ezhpuvixc2b**

<img src="https://wx1.sinaimg.cn/mw690/00622KNxgy1gidsm87al4j30mx0mxad9.jpg" width="40%">

**你们的支持是我维护的动力，欢迎点赞项目，提交问题**

感谢 [https://github.com/nondanee/UnblockNeteaseMusic] 提供 NodeJS 版网易云助手 
本项目参考其大量业务逻辑，包括 APP 图标

感谢 [https://github.com/mightofcode/android-vpnservice] 实现了轻量易用的 Android VPN 代理程序
