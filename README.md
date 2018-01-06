# Landscape

用户在旋转手机屏幕为横屏时给一个友好的提示，不必考虑横屏的布局，同时减少开发维护成本提升用户体验。

## Demo

[Live demo](https://ifyour.github.io/landscape/demo.htm)

## 用法

```html
<script src="landscape.js"></script>
<script>
    (function () {
        new landscape({
            mode: 'portrait',
            prefix: 'shine'
        });
    })()
</script>
```

## 参数

```text
pic     : 图片地址, 可以是图片 URL,
picZoom : 图片缩放比例 如 2,
mode    : [*必填] 页面模式, 'portrait': 横屏提示, 'landscape': 竖屏提示,
bgcolor : 背景色,如 '#000',
txt     : 提示文字, 如 '为了更好的体验，请将手机/平板竖过来',
txtColor: 提示文字颜色 如 '#ffd40a',
prefix  : 前缀 如 'Shine', 防止样式冲突
zIndex  : 层级覆盖 z-index 值
```
