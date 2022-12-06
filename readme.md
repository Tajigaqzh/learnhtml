# 笔记

## html+css+js

### day01 html(Hyper Text Markup Language)

这里只是简单总结，[详细内容](https://www.runoob.com/html/html-tutorial.html)

#### [标题h1~h6](./day01/test01.html)

```html
<h1>标题</h1>
```

#### [文字](./day01/test01.html)

```html
<em>斜体</em>
<u>带下划线</u>
<strike>带删除线</strike>
<!--strike html5已经移除 -->
<sup>上标</sup>
<sub>下标</sub>
```

#### 特殊符号

|特殊符号|实体名称|含义|
|---|---|---|
|"|```&quot;```|引号|
|<|```&lt;```|小于|
|>|```&gt;```|大于|
| | ```&nbsp;```|空格|

#### 段落

p标签自带空行样式

```html
<p>段落</p>
```

#### div

div 没有具体含义块标签可嵌套

#### 语义化标签

h1~h6、p、ul、li、ol、a、dl、dt、dd等

### 新特性

HTML5 中的一些有趣的新特性：

用于绘画的 canvas 元素
用于媒介回放的 video 和 audio 元素
对本地离线存储的更好的支持
新的特殊内容元素，比如 article、footer、header、nav、section
新的表单控件，比如 calendar、date、time、email、url、search

### 块元素、内联元素、内联块

#### 块元素

- 支持全部样式
- 如果没有设置宽度，继承父级
- 每个元素各占一行

div、p、ul、li、h1~h6、dl、dt、dd等

#### 内联元素

- 支持部分样式，不支持width、height、margin-top、margin-bottom、padding-top、padding-bottom
- 不设置宽高时，宽高由内容决定
- 盒子并在一行
- 代码换行盒子之间会产生间距
- 子元素如果是内联元素，父元素可以用text-align设置水平对齐方式，用line-height属性值设置垂直对齐方式

a、span、em、b、i、strong等

##### 解决内联元素间距

- 去掉内联元素之间的换行
- 将内联元素父级font-size设置为0，内联元素分别设置font-size

#### 内联块元素

内联块元素，也叫行内块元素，是新增的元素类型，现有元素没有归于此类别的，img和input元素的行为类似这种元素，但是也归类于内联元素，我们可以用display属性将块元素或者内联元素转化成这种元素。

- 支持全部样式
- 如果没有设置宽高，宽高由内容决定
- 盒子并在一行
- 代码换行，盒子会产生间距
- 子元素是内联块元素，父元素可以用text-align属性设置子元素水平对齐方式。
