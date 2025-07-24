> 场景就是一些背景立绘，音频的抽象集合。

在Raven中，场景是非常常用的。
在Raven中一般把具备必要字段 + **background**字段的Yaml代码视为一个场景。

每个场景之间以 **-** 分割

```yaml
- character: "Raven"
  text: "我是场景1"
  portrait: "none"
  background: "bg2"

- character: "Raven"
  text: "我是场景2"
  portrait: "none"
  background: "bg2"
```
Raven 在切换背景的时候，默认给程序添加了渐变效果。

## 背景系统
调用代码为**background**:
```yaml
- character: "Raven"
  text: "我是场景2"
  portrait: "none"
  background: "bg2"
```