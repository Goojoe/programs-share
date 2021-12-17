1.软件名:qbittorrent-nox

2.版本:4.2.1

3.来源:[island](http://www.island42.net/rpms/cen77/qbittorrent.html)(好像挂掉了)

4.支持平台:Linux(Centos7)

5.介绍:

qBittorrent是一个用C++/Qt编程的bittorrent客户端，使用Arvid Norberg的libtorrent（有时称为libtorrent-rasterbar）。

它的目标是成为所有其他比特rent客户端的良好替代品。qBittorrent快速、稳定，并提供unicode支持以及许多功能。

DB-IP的免费IP to Country Lite数据库用于解决对等人的国家。该数据库在知识共享署名4.0国际许可证下授权。

6.评论:
编译套路深,我要回农村(rpm),农村路太滑(版本低),心情太复杂

centos7的epel7 的qbittorrent版本居然只有3.3.? 最新版都4.3.9了,然后我花了几个小时都没有编译成功,无奈只能找别人做好的rpm

别人制作的rpm就是版本更新太慢了,还有可能不太安全,不过这个是外国人做的,应该没啥问题

7.安装:
解压压缩包里的rpm文件

```bash
sudo yum install libtorrent-rasterbar-1.2.3-1.el7.x86_64.rpm qbittorrent-4.2.1-1.el7.x86_64.rpm
```

说明:安装qbittorrent需要先安装libtorrent 
yum 可以自动补全缺失的软件包还可以用下面的命令安装

````
sudo yum install libtorrent-rasterbar-1.2.3-1.el7.x86_64.rpm qbittorrent-4.2.1-1.el7.x86_64.rpm
````

8.标签:#qbittorrentnox #qbittorrent #nox

#Linux

9.[>>下载](https://t.me/GoojoeShare/44)

10.SHA256:
11603FFE160A5F30609FF74FBABE3AF71EE8F4FEB43CB02F0013730A05A90218