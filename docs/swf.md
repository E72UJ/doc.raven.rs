SWF 渲染功能是Raven引擎所特有的一种动画支持功能，因为这类技术过于古早，大部分视觉小说引擎已经不再迭代。

渲染功能特性如下：

- 原生swf渲染，无需转换，完全直读swf

- 天然矢量支持，无需额外配置，即可无损渲染

## 语法

```yaml
- character: "none"
  text: "这是一个swf动画"
  portrait: "none"
  swf: "assets/swf/animation.swf"
```

地址也在main.yaml中配置。例如：

```yaml
swf:
  animation: "assets/swf/animation.swf"
```
