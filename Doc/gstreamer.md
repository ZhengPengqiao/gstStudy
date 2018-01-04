# gstreamer记录

## ubuntu 安装 gstreamer1.0

* sudo apt-get install libgstreamer1.0-0 libgstreamer1.0-dev gstreamer1.0-tools gstreamer1.0-plugins-base libgstreamer-plugins-base1.0-dev gstreamer1.0-plugins-good gstreamer1.0-plugins-ugly gstreamer1.0-plugins-bad
  * 具体的安装位置为/user/share/doc/和/user/lib
* sudo apt-get install libgstreamer1.0-dev gstreamer-tools gstreamer1.0-tools gstreamer1.0-doc
  * 具体的安装位置为/user/share/doc/

## ubuntu 安装 gstreamer0.10

* sudo apt-get install libgstreamer0.10-dev gstreamer-tools gstreamer0.10-tools gstreamer0.10-doc
* sudo apt-get install gstreamer0.10-plugins-base gstreamer0.10-plugins-good gstreamer0.10-plugins-ugly gstreamer0.10-plugins-bad gstreamer0.10-plugins-bad-multiverse

## ubuntu 安装 gstreamer的gstreamer-ffmpeg支持插件  （都没有成功）

* (可能需要添加源）
  * apt-get install gstreamer0.10-ffmpeg
  * 具体的安装位置为/user/share/doc/
* 也可以直接下载：
  * 下载链接：<http://ubuntu.mirror.cambrium.nl/ubuntu/pool/universe/g/gstreamer0.10-ffmpeg/>
  * 下载gstreamer0.10-ffmpeg_0.10.13-5_amd64(i386).deb, 手动安装即可。（安装时依赖0.10版本的gstreamer相关库）
* gst-ffmpeg源码：
  * 源码地址：<https://gstreamer.freedesktop.org/src/gst-ffmpeg/>