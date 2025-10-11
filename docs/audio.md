## 多种分类的音频格式

由于一些底层问题，目前 Raven 还不能播放所有类型的音频文件。目前支持的音频格式有：

- WAV
- OGG
## 如何添加音频？
```yaml
- character: "none"
  text: "控制台的蓝色光芒照亮了指挥官疲惫的面容，星舰已经在深空中航行了三百七十二个标准日。"
  portrait: "none"
  bgm: "bgm1"

- character: "艾拉"
  text: "舰长，我们收到了来自地球的最后一次信号...那是六个月前的事了。"
  portrait: "none"
  bgm: "bgm2"
```
对应的配置在main.yaml中：
```yaml
audio:
  audio:
    bgm:
      bgm1: "audio/one.ogg"
      bgm2: "audio/two.ogg"
    sfx:
      doorbell: "assets/audio/sfx/doorbell.mp3"
      explosion: "assets/audio/sfx/explosion.mp3"
    click_sound: "typing2.ogg"
    backclick_sound: "button.ogg"
```
其中，bgm是背景音乐，sfx是音效，click_sound是鼠标点击的声音，backclick_sound是鼠标点击返回的声音。