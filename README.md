# unity demo for puerts
> 本仓库master分支用到了unity package的能力，因此仅支持Unity2018+。如您在使用5.5和2017，请查看1.2.x或1.0.x分支（或[点此下载zip](https://github.com/chexiongsheng/puerts_unity_demo/archive/refs/heads/1.2.x.zip)）

## Demo Layout | 目录结构解释

* `package` code of PuerTS
* `projects/0_Basic_Demo` most basic example | 最基础的Demo示例
* `projects/1_Start_Template` a demo with some useful editor features. could be used as a starter template | 一些很有用的编辑器功能演示,甚至可用于作为你的项目启动模板

## How to run it? | 怎么跑这demo？

* git clone https://github.com/chexiongsheng/puerts_unity_demo.git 

* open `projects/0_Basic_Demo` or `projects/1_Start_Template`

## Changelog

### 2025-03-04

为了在Unity 2022.3.53上打开工程并且在iOS上运行， 使用全js/ts编程，做了如下修改：
* 对依赖的package进行升级
* 添加了20来个obsolete的数据类型
* 改进PuertsFilter.cs中对ref范型类的参数的支持
* 添加了几个UnityEditor相关的类到黑名单（不知道为什么会生成，待查）

## More example? | 更多的示例或者教程？
https://puerts.github.io/docs/puerts/unity/other/community
