### 实验3.1：安装Docker

###### （1）查看操作系统内核信息：

![](../image/3.1.png)

######           查看Linux的版本号：

![](../image/3.2.png)

######           更新应用程序数据库：

![](../image/3.3.png)

###### （2）安装curl：

![](../image/3.4.png)

###### （3）下载最新的Docker并安装：

![](../image/3.5.png)

###### （4）验证Docker是否成功启动：

![](../image/3.6.png)

###### （5）查看Docker的版本信息：

![](../image/3.7.png)

### 实验3.2：拉取CentOS镜像，并基于该镜像运行容器，在容器实例上完成WordPress的安装，并推送到Docker Hub

###### （1）拉取官方版本(OFFICIAL)的镜像：

![](../image/3.8.png)

###### （2）使用run命令：

![](../image/3.9.png)

###### （3）查看一下当前系统中存在的镜像：

![](../image/3.10.png)

###### （4）连接ssh后使用yum安装：

![](../image/3.11.png)

###### （5）测试：

![](../image/3.12.png)

###### （6）修改数据库用户名、密码、数据库名：

![](../image/3.13.png)

###### （7）注册并登录wordpress：

![](../image/3.14.png)

###### （8）注册登录dockerhub并创建仓库：

![](../image/3.15.png)

###### （9）将带有wordpress的容器制作成镜像：

![](../image/3.16.png)

###### （10）将镜像推送到dockerhub的仓库中：

![](../image/3.17.png)

### 实验3.3：利用Dockerfile创建一个完成WordPress安装的镜像并推送到Docker Hub

###### （1）dockerfile：

![](../image/3.18.png)

###### （2）安装apache、php、mysql:

![](../image/3.19.png)

###### （3）配置数据库:

![](../image/3.20.png)

###### （4）启动apache和mysql：

![](../image/3.21.png)

###### (5)运行dockerfile：

![](../image/3.22.png)

###### （6）生成容器：

![](../image/3.23.png)

###### （7）安装wordpress：

![](../image/3.24.png)

![](../image/3.25.png)