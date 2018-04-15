# 常见问题

## 如何找到 FIR_API_TOKEN

- EasyCI 针对移动端开发项目集成了广受欢迎的移动内侧托管工具 **[fir.im](https://fir.im)**；

- **fir.im** 是一款方便移动开发人员对应用进行打包托管平台，同时提供了很多方便好用的工具；

- EasyCI 插件系统中集成了 fir.im 上传托管功能，只需要在项目配置时选择 **fir 上传插件**，并填写 **fir** 注册账户下的个人 API Token；

- fir Api Token 可以登录 **[fir.im](https://fir.im) 站点，在右上角的个人中心位置找到。

## 首次构建项目卡在「初始化环境」步骤

- 首次构建项目时，可能因为新项目中需要引进新版本 SDK 或其他第三方依赖库，根据网络状况需要等待较长时间；

- 首次构建成功后，后续 EasyCI 再次构建同一项目时，**初始化环境** 则会很快完成；

- 由于网络原因，依赖资源下载可能受限，可依据情况配置合适的代理工具。



<br/><br/><br/>

<div id="bom">
    <a href="./quick_android.md">上一节：Android 项目构建</a>
    &nbsp;&nbsp;|&nbsp;&nbsp;
    <a href="./other_about.md">下一节：关于</a>
</div>

<link rel="stylesheet" rev="stylesheet" href="./assets/css/easy-ci.css" type="text/css"/>