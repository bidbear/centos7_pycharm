# centos7_pycharm
1.下载pycharm软件包

   curl直接下载：`curl https://download.jetbrains.8686c.com/python/pycharm-professional-2018.1.4.tar.gz >> pycharm-professional-2018.1.4.tar.gz`

2.解压软件包

   `tar -xf pycharm-professional-2018.1.4.tar.gz`
3.进入解压后的bin目录执行安装命令

   ./pycharm.sh 

4.序列号验证界面选择License server

填入：https://jetlicense.nss.im/

然后点activate即可

如果无效则参照此处获取注册码

https://blog.csdn.net/zengraoli/article/details/80554798

5.添加软连接：

命令行模式中输入命令：

`ln -s /root/pycharm-2018.1/bin/pycharm.sh /usr/sbin/pycharm`

6.启动pycharm 

`pycharm`
