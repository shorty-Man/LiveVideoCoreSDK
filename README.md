# LiveVideoCoreSDK 
基于IOS的手机视频直播SDK.
============================
视频直播时代来临了，手机视频直播国内已经非常火爆，并且手机美颜视频直播也已经兴起。

LiveVideoCoreSDK是基于IOS的视频直播SDK(支持IOS8.1以上)
--------------------------------------------------------
如果觉得本SDK对你的项目有用，接收捐赠. 接收捐赠的支付宝帐号:xiaoq_bj@126.com
-----------------------------------------------------------------------------
包含一下功能:

####1, 提供IOS苹果手机的RTMP推流；####

填写RTMP服务地址，直接就可以进行推流。

####2，美颜直播####

美不美都能装的直播，IOS OPENGL美艳加速，手机完全不发烫。

####3，前后摄像头随时切换####

####4，提供RTMP连接状态的回调####
<br>
SDK代码结构简介：
----------------------------------
####一，如何马上使用？####
下载代码后，直接用xcode打开LiveVideoCoreSDK.xcworkspace。(注意是xcworkspace，不是xcodeproj)

需要注意的是，视频直播不支持xcode的虚拟机，请用iphone真机进行调试和试用。


####二，代码结构####
1) LiveVideoCoreDemo就是Demo例子，你抄代码的地方，你懂的。

2) LiveVideoCoreSDK是SDK接口，视频直播的接口都在这里；

3) RtmpLivePushSDK: 核心代码，基于videocore进行了修改，希望自己研究和改进代码的，来这里。

备注：本客户端支持Wowza, nginx-rtmp，Edgecast，RED5，FMS几种类型的RTMP服务器. >还未确认支持的有crtmpserver和python rtmp server。
--------------------------------------------------------
如果有问题，可以在我的问题区提问，欢迎交流。

[RTMP mac下nginx服务器搭建](http://www.cnblogs.com/damiao/p/5231221.html)

