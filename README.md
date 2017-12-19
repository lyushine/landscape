# Landscape

使用户在旋转手机屏幕切换为竖屏的时候给一个友好的小提示，移动端手机网页有时无法禁止用户旋转为竖屏，给一个友好的提示更能
不必考虑竖屏的布局减少开发维护成本提升用户体验。

## 用法

```html
<script src="landscape.min.js"></script>
<script>
    new landscape({
        mode:'portrait',
        prefix:'Shine'
    });
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

## Demo

打开 `demo.htm`, <kbd>F12</kbd> 打开开发工具手机预览, 切换横屏查看效果！
