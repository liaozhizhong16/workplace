# 需要创建python3虚拟环境，名字取pythonShadowVM3
首先安装epel扩展源：

　　yum -y install epel-release

　　更新完成之后，就可安装pip：

　　yum -y install python-pip

　　安装完成之后清除cache：

　　yum clean all

这是在root用户时使用的命令，当前用户如果不具有root权限，加上sudo

pip install virtualenv

virtualenv pythonShadowVM3
