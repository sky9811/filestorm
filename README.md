# Filestorm


Filestorm 官方    https://github.com/tudousi/FileStorm/releases

根据官方的源码，写的一键脚本

<b>2019年2月28日更新一键脚本，适合 CENTOS 7.4 完整版系统安装</b>
 
 
第一步，安装 Centos7.6 X64位 完整版 教程如下

<code> https://www.jianshu.com/p/2cdc3ea850b7 </code>

第二步，执行一键安装脚本，用 SSH 工具连接 LINUX，执行如下命令

<code>yum -y install wget</code>

<code>wget -N --no-check-certificate https://tudousi.org/download/document/install.sh && chmod +x install.sh && bash install.sh</code>

我在 filestorm 目录下面，直接放了一个 restart.sh 脚本，大家直接执行命令

<code>./restart.sh</code>


安装完以后，要修改Filestorm/userconfig.json这个文件，修改一下里面的收益地址，也就是你的墨客钱包地址

第三步，矿机需要在官网注册一下，教程如下

https://www.jianshu.com/p/7103026dfb87
