# CSS 总结
2019-8-27

### 1、设置浏览器标签图标
* favicon.ico<br>
* 在线制作连接：[http://www.faviconico.org/]()
  
```
<!--
href="favicon.ico",favicon.ico为图标名称
在线制作网站：[http://www.faviconico.org/]()
-->
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">

```
<hr>

### 2、background重点属性值
#### background-size


* background-size:100px 100px;

	- 设置背景图像的高度和宽度。
	- 第一个值设置宽度，第二个值设置高度。
	- 如果只设置一个值，则第二个值会被设置为 "auto"。

* background-size:200px;

* background-size:50%;
	- 以父元素的百分比来设置背景图像的宽度和高度。
	- 第一个值设置宽度，第二个值设置高度。
	- 如果只设置一个值，则第二个值会被设置为 "auto"。
	
* background-size:100% 100%;

* background-size:cover;
	- 把背景图像扩展至足够大，以使背景图像完全覆盖背景区域。
	- 背景图像的某些部分也许无法显示在背景定位区域中。
	
* background-size:contain;
	- 把图像图像扩展至最大尺寸，以使其宽度和高度完全适应内容区域。
	
#### background-repeat
* repeat

	- 默认。背景图像将在垂直方向和水平方向重复。
* repeat-x
	- 背景图像将在水平方向重复。	
	
* repeat-y

	- 背景图像将在垂直方向重复。

* no-repeat

	- 背景图像将仅显示一次。
	
#### background-position

	top left
	top center
	top right
	center left
	center center
	center right
	bottom left
	bottom center
	bottom right

#### background-origin	规定背景图片的定位区域。
	padding-box
		背景图像相对于内边距框来定位。
	border-box
		背景图像相对于边框盒来定位。
	content-box
		背景图像相对于内容框来定位。

#### background-attachment	规定背景图像是否固定或者随着页面的其余部分滚动。
	scroll
		默认值。背景图像会随着页面其余部分的滚动而移动。
	fixed
		当页面的其余部分滚动时，背景图像不会移动。

#### background属性连写
	background: [background-color] [background-image] [background-repeat] [background-attachment] [background-position] / [ background-size] [background-origin] [background-clip];
	
<hr>

### 3、标签居中《后面还需要补充》
####标签居中（方式一）
	水平居中
		行内标签   行内-块级标签
			text-align:center
		块级标签
			margin:0 auto
	垂直居中
		line-height == height
		定位
### 4、高度塌陷解决方案
```
有待补充。。。
```
### 5、字体图标

```
有待补充。。。
```

### 6、伸缩布局<font color="red">---重点</font>
```
有待补充。。。
```
### 7、 常用CSS3属性
* translateX(x, y)
	- 移动
		
* scale(x, y)
	- x 水平缩放 y垂直缩放 如果只写一个参数， 宽度和高度都缩放
* transform: rotate(度数); 
	- 改变变形中心点
	  - transform-origin: 水平位置 垂直位置;
* skew(x, y);
	- 倾斜
* perspective
	- 透视
		- 视距 距离 眼睛到屏幕的距离
			- 视距越大,  效果越不明显 
			- 视距越小，透视效果越明显
* 自定义动画




	
	
