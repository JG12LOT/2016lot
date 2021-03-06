#20160707
##UI交互设计：设计选择菜单
##四个方面：
###1.选择菜单
###2.选项数量
###3.标签
###4.默认选项
---
**好的选项菜单:**

- 可以节省屏幕空间，减少用户错误输入（只显示有效选项）；
- 输入引导，各平台完美适配；

**差的交互设计：**

- 填写流程长，下拉菜单多，长。尤其是在小屏幕的手机上体验更差。

---

###1.选择菜单和选项数量：

- 选项过多：当一个选择菜单的选项超过15个，浏览体验就非常差了；费时。

**总结：**当选项超过15个，别用选择菜单，考虑一下使用能让用户直接输入或可自动填写的输入框。
实时根据用户输入的第一个单词来自动给出最接近的猜测选项。


- 选项过少：当一个选择菜单的选项少于7个时，用选择菜单下拉框体验也很差。

**总结：**当选择菜单选项少于7个时，直接用单选框。

---

###2.选择菜单和标签：

- 在选框内和选框外显示提示信息，明确告知用户下一步，**例如：**下拉菜单框内告知用户此下拉菜单的作用，**如：**请选择国家。

---

###3.选择菜单和默认选项：

- 当不能确定大部分（90%）用户会选择哪一个选项时，不应该适用默认选项。
- 更安全的方法是：当用户某个问题未填写时警示遗漏了。

**例如：**性别选项，最好不要默认。

---
###4.选项菜单和移动设备：


**1.下拉菜单在手机是很糟糕，甚至是无法呈现的。**

**2.手机端：难点**

- 填写一个表格可能需要很多步；
- 屏幕空间有限。

#####解决方法：使用控件代替下拉列表

- 利用一组单选按钮或分隔式选项来显示类型相似但又彼此独立的选项（例如：**选择地区**）

- 数字步进器：可以被用于只能递增/递减其数量的选项。（例如：**淘宝商品选择数量——加减按钮**）

- 状态切换器：快速转换两种相反状态。（例如：**手机设置里wifi的开和关**）

- 滑动控制器：可以流畅控制数值，并告知可选范围。（例如：**调节屏幕亮度条、看电影的进度条**）


