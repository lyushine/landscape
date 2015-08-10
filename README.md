/**
 * 移动端竖屏切换提示
 * @author lyushine
 * @create 2014/08/05 update 2015/06/18
 */
 
使用户在旋转手机屏幕切换为竖屏的时候给一个友好的小提示，移动端手机网页有时无法禁止用户旋转为竖屏，给一个友好的提示更能
不必考虑竖屏的布局减少开发维护成本提升用户体验。

##使用方式：
	<script src="http://ossweb-img.qq.com/images/js/landscape/landscape.min.js"></script>
	<script>
		var landscape = new landscape({
		    mode:'portrait',//portrait,landscape
		    prefix:'Shine',
		});
	</script>
## 具体参数说明（标红为必填，其他为选填）：

pic:图片地址 如'http://ossweb-img.qq.com/images/js/landscape/landscape.png',

picZoom:图片缩放比例 如 2,

mode:页面模式，如'portrait'或'landscape',

bgcolor:背景色,如 '#000',

txt:提示文字, 如 '为了更好的体验，请将手机/平板竖过来',

txtColor: 提示文字颜色 如'#ffd40a',

prefix:前缀 如 'Shine'
zIndex:层级覆盖z-index值 

##例子：

http://hyrz.qq.com/cp/a20150717test/index.html

请把手机移动到横屏，查看其横屏提示效果！

