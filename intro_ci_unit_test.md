# 有关「CI」及「单元测试」

## 什么是「 CI 」

![Continuous Integration](./assets/img/what-ci.png)

- CI (Continuous Integration) —— 也就是「持续集成」
- 持续集成指的就是，频繁地（一天多次）将代码集成到主干

有关持续集成乃至持续交付、持续部署的介绍，这里引用一篇文章：
> [The Product Managers’ Guide to Continuous Delivery and DevOps](https://www.mindtheproduct.com/2016/02/what-the-hell-are-ci-cd-and-devops-a-cheatsheet-for-the-rest-of-us/)
*(“持续交付产品经理指南”和DevOps)*

## 何谓「单元测试」

> 在计算机编程中，单元测试（英语：Unit Testing）又称为模块测试, 是针对程序模块（软件设计的最小单位）来进行正确性检验的测试工作。程序单元是应用的最小可测试部件。在过程化编程中，一个单元就是单个程序、函数、过程等；对于面向对象编程，最小单元就是方法，包括基类（超类）、抽象类、或者派生类（子类）中的方法。

> 通常来说，程序员每修改一次程序就会进行最少一次单元测试，在编写程序的过程中前后很可能要进行多次单元测试，以证实程序达到软件规格书要求的工作目标，没有程序错误；虽然单元测试不是什么必须的，但也不坏，这牵涉到项目管理的政策决定。

> 每个理想的测试案例独立于其它案例；为测试时隔离模块，经常使用stubs、mock[1]或fake等测试马甲程序。单元测试通常由软件开发人员编写，用于确保他们所写的代码匹配软件需求和遵循开发目标。它的实施方式可以是非常手动的（通过纸笔），或者是做成构建自动化的一部分。

*以上有关单元测试的内容摘自：维基百科 - 单元测试*

所谓单元测试，是实践持续集成乃至敏捷开发的前提，有关单元测试的话题：这里引用三篇 **继承** 老师的三篇专栏文章：

> [聊聊单元测试](https://zhuanlan.zhihu.com/p/23844500)

> [聊聊如何写单元测试](https://zhuanlan.zhihu.com/p/23846487)

> [聊聊坚持单元测试编写](https://zhuanlan.zhihu.com/p/23974537)

<br/><br/><br/>

<div id="bom">
    <a href="./README.md">返回目录首页</a>
</div>
<br>
<div id="bom">
    <a href="./intro_framework.md">上一节：EasyCI 整体架构</a>
    &nbsp;&nbsp;|&nbsp;&nbsp;
    <a href="./install_back_end.md">下一节：EasyCI 后端服务的部署</a>
</div>

<link rel="stylesheet" rev="stylesheet" href="./assets/css/easy-ci.css" type="text/css"/>