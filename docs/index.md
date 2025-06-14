# 欢迎来到Raven的 参考文档

<img
  src="https://imgs.freeimg.cn/s/68309e7895514.png"
  alt="Clock"
  width="400px">

## 引擎介绍
Raven 是一款基于 Rust 语言开发的现代化视觉小说/文字冒险游戏引擎，专注于为开发者提供简洁高效的叙事工具链。凭借 Rust 的内存安全性与高性能特性，Raven 能够流畅运行于多平台，同时通过声明式脚本语法和模块化设计，大幅降低视觉小说的开发门槛。

更多的信息请访问官网：raven.rs 

或者GitHub的地址：https://github.com/E72UJ/Raven

```yaml linenums="1"
  - character: "黛安娜"
    label: "one"
    text: "你好，欢迎使用Raven Engine V0.1"
    portrait: "protagonist"

  - character: "黛安娜"
    text: "Raven是一个使用rust编写的视觉小说引擎，它拥有两个开发模式"
    portrait: "protagonist"
    jump: "one"
```

## 引擎特性

* `双模开发` -  引擎拥有两种开发模式，既可以简单配置使用yaml文件进行开发 也可以使用专有DSL（Sadscript）进行专有的开发
* `模块化设计` - 引擎拥有独特的插件机制，每个插件就是一份程序，自由插入
* `无损动画渲染` - 引擎支持原生swf和svg渲染，助力视觉小说视觉表现。
* `多平台兼容` - 引擎默认兼容Windows和mac

## 致谢

本文档图文外链使用 https://www.freeimg.cn/ 图床

<img
  src="https://imgs.freeimg.cn/s/682c1c9ca0965.png"
  alt="Clock"
  width="400px">
