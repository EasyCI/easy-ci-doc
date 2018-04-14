# EasyCI 插件系统的部署

> 基于 Linux 的安装

## （一）准备

### 运行环境

- Python 3.5+

### 工具

- Git
- pip

## （二）配置

### 配置运行环境

保证系统中安装的 Python 版本为 3.5+，并安装 pip 工具，可以从这里查看 **[pip 安装方法](http://docs.python-guide.org/en/latest/starting/installation/)** 。

运行以下命令通过 pip 安装 Python 第三方库

```
pip install requests
pip install email
pip install secure-smtplib
```

### 获取插件脚本

通过以下命令，获取源代码

```
git clone -b master https://github.com/EasyCI/easy-ci-plugin.git
```

将获取的源码下 script/ 文件夹内容拷贝到 EasyCI 后端服务部署的同一台主机中，并按照 **[后端服务配置](./install_back_end.md)** 的 `custum.pluginScriptPath` 参数指定的插件路径下。



<br/><br/><br/>

<div id="bom">
    <a href="./install_front_end.md">上一节：EasyCI 前端程序的部署</a>
    &nbsp;&nbsp;|&nbsp;&nbsp;
    <a href="./quick_android.md">下一节：Android 项目构建</a>
</div>

<link rel="stylesheet" rev="stylesheet" href="./assets/css/easy-ci.css" type="text/css"/>