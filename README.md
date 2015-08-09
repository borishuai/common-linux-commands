# common-linux-commands
Some useful linux commands

## Ubuntu PPA管理
* sudo add-apt-repository ppa:LP-BENUTZER/PPA-NAME, 添加一个ppa源，通常是官方的仓库中没有我们需要的软件
* sudo apt-get update, 更新所有PPA中的资源列表,通常在安装新软件之前执行

## Ubuntu软件管理
* sudo apt-get install package, 安装软件包，例如：sudo apt-get install redis-server
* sudo apt-get remove package， 删除包,但是不删除配置文件，例如：sudo apt-get remove redis-server
* sudo apt-get purge package, 删除包以及配置文件

## 磁盘空间查看
* df -h，查看磁盘使用情况，-h表示使用方便理解的单位进行显示
* du -f，该命令的功能是逐级进入指定目录的每一个子目录并显示该目录占用文件系统数据块（1024字节）的情况。若没有给出指定目录，则对当前目录进行统计，-h同上
