# StartPortable

## 准备部署代码

请准备一个目录，用于保存 Online Judge 将会用来缓存的所有文件内容，在此目录下开始执行下面的命令

```shell
git clone https://github.com/PortableOJ/portable-deploy.git
cd portable-deploy
```

## 授予权限并启动

请依次执行下列命令

```shell
sudo chmod +x start.sh
./start.sh
```

之后，你将可以看到一个选择框界面

在选择框页面中，当前选中选项的开头将会用一个红色的星号表示

你可以通过 w 键和 s 键来上下移动选项选择对应的操作，并敲击回车进行确认

下面是几个选项的简要介绍

> (re)Start a Server with a Judge. 在本机上(重新)启动完整的数据库服务和 server 服务，并启动一个本地的判题系统
> (re)Start a Server without Judge. 在本机上(重新)启动完整的数据库服务和 server 服务，但是不启动本地判题系统
> (re)Start a remote Judge. 在本机上(重新)启动一个判题系统
> Update deploy shell and restart. 更新部署脚本并重新回到此页面
> Do nothing and quit. 什么也不做并退出

## 修改配置文件

你可以在当前目录下的 `setup-env.sh` 文件内找到默认配置信息，但<span style="color:red">请不要随意随意修改此文件内的任何配置信息</span>，如果你希望更新其中的配置信息，请继续阅读本文档。

#
