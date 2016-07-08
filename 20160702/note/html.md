#20160702
##HTML

1. ```<pre> </pre>``` 预设样式化文本。

2. ```<address> </address>``` 地址。斜体

3. 缩写：

- ```<abbr tetle="">引号内的缩写</abbr>```
- ```<acronym tetle="">引号内的首字母缩写</acronym>```


4. ```<bdo dir="rtl"> </bdo>``` 定义文字方向，**rtl**方向从右到左。

5. ```<q></q>```  短引用
	
		<p>WWF's goal is to: 
		<q>Build a future where people live in harmony with nature.</q>
		We hope they succeed.</p>
浏览器效果：

`WWF's goal is to:` " `Build a future where people live in harmony with nature. ` " `We hope they succeed.`

###html文本格式化标签：
- ```<b>``` 文本加粗。
- ``<em>``  着重标签，斜体。
- `<strong>` 着重标签，粗体。


### html样式：

**内部样式：**在**标签内**使用`style属性`;

**内部样式表：**在**`<head>`中**使用`<style>标签`

**外部样式表：**在**`<head>`中**使用`<link>标签`

**example：**

	<head>
	<link rel="stylesheet" type="text/css" href="mystyle.css">
	</head>

###表格：

	<table>
	<tr>
	<th></th>
	<td></td>
	</tr>
	</table>

###列表：

1.无序列表：

	<ul>
	<li></li>
	</ul>
2.有序列表：

	<ol>
	<li></li>
	</ol>

###定义一个区域：

```<div></div>```

###表单：

	<form action="demo-form.php" >
	
	First name: <input type="text" name="FirstName" value="Mickey"><br />
	
	Last name: <input type="text" name="LastName" value="Mouse"><br />
	
	Password: <input type="password" name="pwd"><br />
	
	<input type="radio" name="sex" value="male">Male<br />
	
	<input type="radio" name="sex" value="female">Female<br />
	
	<input type="checkbox" name="vehicle" value="Bike">I have a bike<br />
	
	<input type="checkbox" name="vehicle" value="Car">I have a car <br />
	
	<select name="cars">
	<option value="volvo">Volvo</option>
	<option value="saab">Saab</option>
	<option value="fiat" selected>Fiat</option>
	<option value="audi">Audi</option>
	</select>
	
	<input type="submit" value="Submit">
		</form>
	
	<textarea rows="10" cols="30">
	我是一个文本框。
	</textarea>



<form action="demo-form.php" >

First name: <input type="text" name="FirstName" value="Mickey"><br />

Last name: <input type="text" name="LastName" value="Mouse"><br />

Password: <input type="password" name="pwd"><br />

<input type="radio" name="sex" value="male">Male<br />

<input type="radio" name="sex" value="female">Female<br />

<input type="checkbox" name="vehicle" value="Bike">I have a bike<br />

<input type="checkbox" name="vehicle" value="Car">I have a car <br />

<select name="cars">
<option value="volvo">Volvo</option>
<option value="saab">Saab</option>
<option value="fiat" selected>Fiat</option>
<option value="audi">Audi</option>
</select>

<input type="submit" value="Submit">
	</form>

<textarea rows="10" cols="30">
我是一个文本框。
</textarea>

