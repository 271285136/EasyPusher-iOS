# EasyPusher-iOS

A simple, robust, low latency RTSP video&audio&screen stream pusher and recorder on iOS. 精炼、稳定、高效的iOS前/后摄像头/手机桌面屏幕采集、编码、RTSP直播推送工具，充分秉承了RTP在即时通信领域中的技术特点，网络条件满足的情况下，延时控制在300ms~500ms，非常适合于应急指挥、4G执法、远程遥控与直播等行业领域；

EasyPusher是EasyDarwin流媒体团队开发的一个RTSP/RTP流媒体音/视频直播推送产品组件，全平台支持(包括Windows/Linux(32 & 64)，ARM各平台，Android、iOS)，通过EasyPusher我们就可以避免接触到稍显复杂的RTSP/RTP/RTCP推送流程，只需要调用EasyPusher的几个API接口，就能轻松、稳定地把流媒体音视频数据推送给RTSP流媒体服务器进行转发和分发，尤其是与EasyDarwin开源RTSP流媒体服务器、EasyPlayer-RTSP播放器可以无缝衔接，EasyPusher经过长时间的企业用户和项目检验，稳定性非常高;

## 功能点支持 ##

- [x] 多分辨率选择；
- [x] `音视频`推送<!--、`纯音频`推送、`纯视频`推送-->；
<!--- [x] 支持`边采集、边录像`；-->
- [x] 稳定的录像、推流分离模式;<!--**支持推流过程中随时开启录像，录像过程中，随时推流；**-->
- [x] 采集过程中，前后摄像头切换；
<!--- [x] android完美支持`文字水印、实时时间水印`；-->
<!--- [x] 支持`推送端实时静音/取消静音`；-->
- [x] 支持软硬编码设置；
<!--- [x] android支持后台service推送摄像头或屏幕(推送屏幕需要5.0+版本)；-->
<!--- [x] 支持gop间隔、帧率、bierate、android编码profile和编码速度设置；-->
- [x] [音频]iOS支持噪音抑制功能；
- [x] [音频]iOS支持自动增益控制；
- [x] 结合UVCCamera (https://github.com/saki4510t/UVCCamera) 开源工程,支持**UVC摄像头视频推送\以及UVC摄像头本地录像**
- [x] 配套免费开源的EasyDarwin流媒体服务器；

## 工作流程 ##

![EasyPusher Work Flow](http://www.easydarwin.org/github/images/easypusher/easypusher_android_workfolw.png)

## 版本下载 ##

- iOS [https://itunes.apple.com/us/app/easypusher/id1211967057](https://itunes.apple.com/us/app/easypusher/id1211967057 "EasyPusher_iOS")

![EasyPusher_iOS](http://www.easydarwin.org/skin/bs/images/app/EasyPusher_iOS.png)

- Android [https://fir.im/EasyPusher ](https://fir.im/EasyPusher "EasyPusher_Android")

![EasyPusher_Android](http://www.easydarwin.org/skin/bs/images/app/EasyPusher_AN.png)


## 技术支持 ##

- 邮件：[support@easydarwin.org](mailto:support@easydarwin.org) 

- QQ交流群：465901074

## 获取更多信息 ##

**EasyDarwin**开源流媒体服务器：[www.EasyDarwin.org](http://www.easydarwin.org)

Copyright &copy; EasyDarwin Team 2012-2019

![EasyDarwin](http://www.easydarwin.org/skin/easydarwin/images/wx_qrcode.jpg)
