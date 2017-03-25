# lib-mp4v2
lib of mp4v2 resource

计划将H264与AAC文件合并为MP4，目前ios只有AVAssetWritter封装mp4但输入源为pcm 与yuv（rgb），
所以采取libmp4v2，源码地址为https://code.google.com/p/mp4v2

找到github地址https://github.com/Thinkerfans/lib-mp4v2这个朋友写过，非常开心 😀

但是编译不过去，所以简单改了改脚本，在此记录一下

IOS_BASE_SDK=8.2 改为 IOS_BASE_SDK=10.2 （xcode 8.2版本）

删除
export AR=$DEVROOT/usr/bin/ar 
export RANLIB=$DEVROOT/usr/bin/ranlib
