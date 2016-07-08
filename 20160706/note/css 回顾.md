#20160706
---

###1. css背景：

- `background-position`：
值；如果仅指定一个关键字，其他值将会是"center"。例如：top

完整值：

	left top
	left center
	left bottom
	right top
	right center
	right bottom
	center top
	center center
	center bottom

- `background-attachment：fixed；` *固定背景（图片）*

---

###2. css文本：

- 控制文本中的字母：`text-transform`值：

		none	        默认。定义带有小写字母和大写字母的标准的文本。
		capitalize		文本中的每个单词以大写字母开头。
		uppercase		定义仅有大写字母。
		lowercase		定义无大写字母，仅有小写字母。
		inherit	        规定应该从父元素继承 text-transform 属性的值。

- 缩进文本： `text-indent：50px;`

- 文本方向： `direction：rlt；`

- 元素空白处理： `white-space`

规定文本不换行：

		p
		{
		white-space:nowrap;
		}

- 垂直对齐： `vertical-align：text-top；`

---

###3. css字体：

- 设置字体粗细： `font-weight：bold；`


- 设置字体的异体： `font-variant：normal；`  *small-caps等值*

---

###4. css列表：

- 设置作为**列表标记项的图像**： `list-style-image：url（sqpurple.gif）;`

- 跨浏览器（crossbrowser）方法**设置列表标记项图像：**

		<head>
		
		<style>
		ul
		{
		list-style-type:none;
		padding:0px;
		margin:0px;
		}
		ul li
		{
		background-image:url(sqpurple.gif);
		background-repeat:no-repeat;
		background-position:0px 5px; 
		padding-left:14px;
		}
		</style>
		
		</head>
		
		<body>
		<ul>
		<li>Coffee</li>
		<li>Tea</li>
		<li>Coca Cola</li>
		</ul>
		</body>

---

###5. css表格:

- 合并表格边框： `border-collapse：collapse；`

- 表格标题位置： `caption {caption-side：bottom；}`

---

###6. css外边距： `margin`

###7. css填充（内边距）： `padding`

---

###8. css尺寸：
- `width`、`height`用**百分数表示**时，宽度、高度为包含它额**块级对象（父元素）**的百分之几宽度、高度。

---

###9. css显示：display、visibility

- 隐藏一个元素： `visibility：hidden；` *使用visibility属性，占着原来的 空间*

- 不显示元素：`display：none；` *不占用原来的空间*

- 将一个块元素显示为内联元素： `display：inline；`
- 将一个内联元素显示为块元素： `display：block；`
- 隐藏表格单元格（一行、一列)： `visibility：collapse；`（利用表格的collapse属性）

---

###10. css定位（positioning）：

- `fixed` 定位（固定定位）：

`Fixed` 定位使元素的位置与文档流无关，因此不占据空间。Fixed定位的元素和其他元素重叠。
	
	  p.pos_fixed
	 { 
	 position:fixed;
	 top:30px;
	 right:5px;
	 }


- `relative` 定位（相对定位）：

 相对定位元素的定位是相对其正常位置。它原来所占的空间不会改变。

	h2.pos_left
	{
	 position:relative;
	 left:-20px;
	 }
	h2.pos_right
	{
	position:relative;
	left:20px;
	}

注意：**相对定位元素经常被用来作为绝对定位的容器块（父元素）。**


- `absolute` 定位（绝对定位）：

注意： **绝对定位的元素的位置相对于最近的已定位父元素，如果元素没有已定位的父元素，那么它的位置相对于<html>。**
 
		h2.pos_left
		{
		position:relative;
		left:-20px;
		}
		h2.pos_right
		{
		position:relative;
		left:20px;
		}

- 重叠的元素 `z-index` ：-1、 1

- 设置元素的形状：`clip：rect=（top，right，bottom，left）;`


 注意： **right的数值相对左侧边框，bottom的数值相对于顶部的边框。**

		<html>
		<head>
		<style>
		img 
		{
		position:absolute; /*  原图为103* 142  */
		clip:rect(0px,60px,200px,0px);/* 剪成60*200（142） */
		}
		</style>
		</head>
		
		<body>
		<img src="w3css.gif" width="100" height="140" />
		</body>
		</html>

- 溢出处理 `overflow `：

 `overflow `属性为: `visible`, `hidden`, `scroll`, `inherit` 。

---



