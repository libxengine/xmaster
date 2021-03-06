# screen-recording-master

#### 介绍
使用C C++实现屏幕录制
屏幕录制大师,基于XEngine开发的一套屏幕录制软件.
可以录制屏幕,录制声音.打包成指定格式.

#### 软件架构
此程序是基于XEngine实现的一款屏幕和声音录制软件,可以为各位视频作者录制屏幕和声音,也可以推送桌面图像到流媒体服务器  
此程序需要下面的库才能使用  
XEngine:https://gitee.com/xyry/libxengine or https://github.com/libxengine/xengine  
此应用程序为开源,采用C++MFC实现

#### 编译方式
编译支持x86和x64编译,debug和release均可.

#### 安装教程

1.  下载XEngine完整包.
2.  配置环境
3.  下载代码
4.  使用VS打开
5.  直接编译
6.  拷贝dll到程序目录
7.  直接运行即可

#### 使用说明

1.  点击开始录制.即可录制电脑屏幕,根据你的桌面分辨率设置.位置坐标表示从屏幕的某一点开始到分辨率设置的位置
2.  如果没有选择音频设备,将只录制屏幕
3.  停止录制后会自动打包  
4.  某些时候如果没有找到音频,可能是因为驱动问题,你可以使用在virtual-audio-capturer.下载地址:https://github.com/rdp/screen-capture-recorder-to-video-windows-free/releases  

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request

#### 测试流媒体服务
推流:rtmp://app.xyry.org/live/你的识别码,比如 rtmp://app.xyry.org/live/qyt  
拉流:http://app.xyry.org:8088/live/你的识别码.flv 比如 http://app.xyry.org:8088/live/qyt.flv

#### 其他说明

1.  视频采用h264编码,你可以通过这个程序了解c c++ 实现h264编解码
2.  音频采用aac编码,你可以通过这个程序了解c c++ 实现aac编解码
3.  在录制完成后程序会自动打包为mp4文件,你也可以指定其他文件,系统会自动判断要打包的格式是否支持
4.  我们提供的SDK仅仅包含编解码与采集器相关,如果你想了解更多xengine的内容,请访问我们的网站
5.  此代码没有任何限制,可以随意传播,编译,商用
6.  如果有其他需求,欢迎与我们联系  
7.  如果打包完毕大小没有变化,可以关闭程序在看下,可能是句柄没有正确释放导致的  

##### 关于我们
你可以访问我们的网站了解更多 www.xyry.org