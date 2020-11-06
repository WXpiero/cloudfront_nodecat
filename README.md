# cloudfront_nodecat
A python script to catch aws cloudfront ghost nodes in china.
---

# usage

https://vicho.me/87.html
教程
之前的脚本只能运行在python2环境下，且将zmap扫描端口存活和是否cloudfront节点两个分开,需要人工再去运行一下命令,目前这个脚本可以运行在python3下，只需要输入x.x.x.0/24格式的ip段即可输出可用节点。废话不多说，上教程。

1.安装运行环境
#安装Zmap运行环境
sudo apt-get install bison ed gawk gcc libc6-dev make
#安装Zmap
sudo apt install zmap
#安装python模块
pip install numpy
pip install requests
2.运行扫描程序
python scan.py iplist.txt 10
#解释：
scan.py = 文件名
iplist.txt = 包含IP段的文件
10 = 线程数 (尽力而为)
3.改进
其实可以改进一些内容，比如 Zmap默认的扫描速度是30MBps改成自定义，加一个进度条，可以自行修改。

4.改进脚本下载
https://github.com/madlifer/cloudfront_nodecat

链接：https://pan.vicho.me/s/juxsXDW9aeia 提取码：efT2G
