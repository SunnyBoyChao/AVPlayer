# AVPlayer
视频播放
##按时发生
撒旦法
---
GCPlayer使用说明
1、本播放器继承自UIView（以单例形式存在）

2.使用方法：
拖入（其中Images可于自己工程的图片合并，里面是视频的一些图片）

拖入以后请在需要播放的页面引入头文件，将本类创建成对象，并且在viewWillDisappear方法中写一段代码：
在ViewDidLoad中使用本类开辟空间，给它一个frem ，再用本类调用自己的方法 给它一个Url 加入视图，步骤就完成了
