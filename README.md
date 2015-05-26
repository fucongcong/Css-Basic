# CSS
访问[php.xitongxue.com观看课程](http://xitongxue.com)
关注我们的ＱＱ群：390536187

##CSS简介
###CSS是什么？
CSS是Cascading Style Sheets（级联样式表）的缩写。

###CSS做什么？
CSS是一种样式表语言，用于为HTML文档定义布局。例如，CSS涉及字体、颜色、边距、高度、宽度、背景图像、高级定位等方面。

###CSS有哪些好处？
－通过单个样式表控制多个文档的布局；
－更精确的布局控制；
－响应式布局；

##CSS的工作原理
````
selector { property : value }

选择器　　　属性　　　　　值

````
如:
````
body {background-color: #FF0000;}

````
但是把CSS代码放在哪里呢？

－方法1：行内样式表（style属性）

````
	<html>
	  <head>
	  <title>例子</title>
	  </head>
	  <body style="background-color: #FF0000;">
	  </body>
	</html>
````
－方法2：内部样式表（style元素）
````
	<html>
	  <head>
	  <title>例子</title>
	  <style>
		  body {background-color: #FF0000;}
	  </style>
	  </head>
	  <body>
	  </body>
	</html>
````	
－方法3：外部样式表（引用一个样式表文件）

````
	<html>
	  <head>
	<title>我的文档</title>
		<link rel="stylesheet" type="text/css" href="style/style.css" />
	  </head>
	  <body>
````

##CSS样式
###颜色与背景
- color
- background-color
- background-image
- background-repeat
- background-attachment
- background-position
- background