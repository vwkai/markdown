         * [目录](#\xE7\x9B\xAE\xE5\xBD\x95)
         * [标题](#\xE6\xA0\x87\xE9\xA2\x98)
         * [分割线](#\xE5\x88\x86\xE5\x89\xB2\xE7\xBA\xBF)
         * [块引用](#\xE5\x9D\x97\xE5\xBC\x95\xE7\x94\xA8)
         * [列表](#\xE5\x88\x97\xE8\xA1\xA8)
            * [1、无序列表](#1\xE6\x97\xA0\xE5\xBA\x8F\xE5\x88\x97\xE8\xA1\xA8)
            * [2、有序列表](#2\xE6\x9C\x89\xE5\xBA\x8F\xE5\x88\x97\xE8\xA1\xA8)
            * [3、任务列表](#3\xE4\xBB\xBB\xE5\x8A\xA1\xE5\x88\x97\xE8\xA1\xA8)
         * [代码块](#\xE4\xBB\xA3\xE7\xA0\x81\xE5\x9D\x97)
            * [1、多行代码](#1\xE5\xA4\x9A\xE8\xA1\x8C\xE4\xBB\xA3\xE7\xA0\x81)
            * [2、内联代码](#2\xE5\x86\x85\xE8\x81\x94\xE4\xBB\xA3\xE7\xA0\x81)
         * [表格](#\xE8\xA1\xA8\xE6\xA0\xBC)
         * [字体格式](#\xE5\xAD\x97\xE4\xBD\x93\xE6\xA0\xBC\xE5\xBC\x8F)
            * [1、加粗](#1\xE5\x8A\xA0\xE7\xB2\x97)
            * [2、斜体](#2\xE6\x96\x9C\xE4\xBD\x93)
            * [3、下划线](#3\xE4\xB8\x8B\xE5\x88\x92\xE7\xBA\xBF)
            * [4、删除线](#4\xE5\x88\xA0\xE9\x99\xA4\xE7\xBA\xBF)
            * [5、高亮](#5\xE9\xAB\x98\xE4\xBA\xAE)
         * [注释](#\xE6\xB3\xA8\xE9\x87\x8A)
         * [超链接](#\xE8\xB6\x85\xE9\x93\xBE\xE6\x8E\xA5)
         * [插入图片](#\xE6\x8F\x92\xE5\x85\xA5\xE5\x9B\xBE\xE7\x89\x87)
            * [1、本地图片](#1\xE6\x9C\xAC\xE5\x9C\xB0\xE5\x9B\xBE\xE7\x89\x87)
            * [2、网络图片](#2\xE7\xBD\x91\xE7\xBB\x9C\xE5\x9B\xBE\xE7\x89\x87)
            * [3、图片缩放](#3\xE5\x9B\xBE\xE7\x89\x87\xE7\xBC\xA9\xE6\x94\xBE)
### 目录

```
[TOC]
```

### 标题

在标题前面加上#（#与标题之间存在一个空格[非必须]，一到六个级别，从一到六依次递减）

```
# 这是一级标题

## 这是二级标题

####### 这是六级标题
```

### 分割线

格式如下：
```
---
或
***
```

### 块引用

Markdown使用电子邮件风格的`>`符来创建块引用。（>与引用内容之间存在一个空格[非必须]）如下：

```
> 这是第一段。这是含有两个段落的块引用
> 
> 这都是第一段里的

> 这是含有一个段落的另一个块引用。两个代码块间可以用一空行来分隔。
>

> 这是第三段
>> 这是引用块内的引用效果如下：
```

> 这是第一块。这是含有两个段落的块引用
> 
> 这都是第一块里的

> 这是含有一个段落的第二块引用。两个代码块间可以用一空行来分隔。
> 

> 这是第三块
> 
>> 这是引用块内的引用

- 在Typora中，输入符’`>`‘加上所用引用的内容会生成一个引用块。
- Typora在随后的输入过程中会自动为你添加`>`和行间隔。
- 引用块内的引用也是被允许的，只需要在引用块内同样使用`>`即可。


### 列表

#### 1、无序列表
格式如下：
```
* 清单事项
（注：* 可以用 - 或 + 代替，符号与文字之间有一个空格）
```
举例：
```
* 红色
* 绿色
* 蓝色
```
* 红色
* 绿色
* 蓝色

#### 2、有序列表

格式如下：
```
1. 清单事项
（注：符号与文字之间有一个空格）
```
举例：
```
1. 红色
2. 绿色
3. 蓝色
```
1. 红色
2. 绿色
3. 蓝色

#### 3、任务列表

格式如下：
```
- [ ] 任务清单1 	#未完成
- [x] 任务清单2		#已完成
(注：连接号和两个方括号，每个符号之间要有一个空格)
```
举例：
```
- [ ] 任务清单1
- [x] 任务清单2
- [ ] 任务清单3
```

- [ ] 任务清单1 
- [x] 任务清单2
- [ ] 任务清单3

### 代码块

 #### 1、多行代码

（1）普通代码块

```
​```
# code block
​```
```

（2）带语法高亮的代码块

```
​```php
<?php
	echo "hello world";
?>
​```
```

举例：

```php
<?php
	echo "hello world";
?>
```

#### 2、内联代码

```
`Inline code`
```

举例：

```
内联`代码块`文本
```

内联`代码块`文本

### 表格

使用 **|** 来分隔不同的单元格，使用 **-** 来分隔表头和其他行。

（1）格式如下：

```
| titile1 | title2 | title3 |
| ------- | ------ | ------ |
| cell1   | cell2  | cell3  |
```

| titile1 | title2 | title3 |
| ------- | ------ | ------ |
| cell1   | cell2  | cell3  |

（2）设置表格的对齐方式：

- **-:** 设置内容和标题栏居右对齐。
- **:-** 设置内容和标题栏居左对齐。
- **:-:** 设置内容和标题栏居中对齐。

```
| 左对齐 | 居中对齐 | 右对齐 |
| :----- | :------: | -----: |
| 单元格 |  单元格  | 单元格 |
| 单元格 |  单元格  | 单元格 |
```

| 左对齐 | 居中对齐 | 右对齐 |
| :----- | :------: | -----: |
| 单元格 |  单元格  | 单元格 |
| 单元格 |  单元格  | 单元格 |


### 字体格式

#### 1、加粗

```
四个星号间插入文本为加粗：**加粗**
或
四个下划线间插入文本为加粗：__加粗__
```

#### 2、斜体

```
两个星号间插入文本为斜体: *斜体*
或
两个下划线间插入文本为斜体: _斜体_
```

#### 3、下划线

```
<u>下划线</u>
```

#### 4、删除线

```
四个波浪线间插入文本为加删除线：~~删除线~~
```

#### 5、高亮

```
四个等号间插入文本为高亮：==高亮==
```

### 注释

```
<!---->
```

举例：

```
<!--注释的内容-->
```

<!--注释的内容-->

### 超链接

```
[显示的文字]（实际的链接地址）
或
[显示的文字]（实际的链接地址  "悬停文字"）
```

举例：

```
[网址](http://www.vwkai.com)
[网址(带标题)](http://www.vwkai.com "Blog")
```

[网址](http://www.vwkai.com)
[网址(带标题)](http://www.vwkai.com "Blog")

### 插入图片

```
![alt 属性文本](图片地址)
或
![alt 属性文本](图片地址 "悬停文字")
```

- 第一部分：感叹号 !
- 第二部分：方括号，里面放上图片的替代文字（非必须，作用就是当图片无法显示时，浏览器会把alt的文本内容显示出来）
- 第三部分：普通括号，里面包含图片路径或网址，还有悬停文字（非必须）

#### 1、本地图片

```
![blog-favicon](assets/favicon-32-32-a.png)
![blog-favicon](assets/favicon-32-32-a.png "favicon")

注：图片路径可以是【相对路径】或【绝对路径】
```

#### 2、网络图片

```
![blog-favicon](https://www.vwkai.com/images/favicon-32-32-a.png)
![blog-favicon](https://www.vwkai.com/images/favicon-32-32-a.png "favicon")
```

举例：

![blog-favicon](https://www.vwkai.com/images/favicon-32-32-a.png)

![blog-favicon](https://www.vwkai.com/images/favicon-32-32-a.png "favicon")

#### 3、图片缩放

Markdown 目前是使用原始的 <img> 标签来实现图片的缩放功能。

```
<img src="assets/favicon-32-32-a.png" alt="blog-favicon" title="favicon" style="width: 20%;" />
```

