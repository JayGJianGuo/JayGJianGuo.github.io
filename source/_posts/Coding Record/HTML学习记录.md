---
title: 170122-HTML学习笔记
tags: Coding Record
---
```
引用链接
<a href="http://www.w3school.com.cn">This is a link</a>
```

```
引用图片~编辑图片大小
<img src="w3school.jpg" width="104" height="142" />
```
####

#### 空的 HTML 元素

没有内容的 HTML 元素被称为空元素。空元素是在开始标签中关闭的。

<br> 就是没有关闭标签的空元素（<br> 标签定义换行）。

在 XHTML、XML 以及未来版本的 HTML 中，所有元素都必须被关闭。

在开始标签中添加斜杠，比如 <br />，是关闭空元素的正确方法，HTML、XHTML 和 XML 都接受这种方式。

即使 <br> 在所有浏览器中都是有效的，但使用 <br /> 其实是更长远的保障。





| 标签         | 描述                       |
| ---------- | ------------------------ |
| <p>段落 </p> | 定义段落。多个<p>， 只需要一个</p>结尾。 |
| <br> 换行    | 插入单个折行（换行）。              |

## HTML 水平线

<hr /> 标签在 HTML 页面中创建水平线。

hr 元素可用于分隔内容。

居中对齐|长度为50|宽度为100|不带阴影的水平线：

```
<hr align="center" width="50%" size="100px" noshade="noshade" />
[align 不适用于div中，在HTML4.0]
```

![](https://ww3.sinaimg.cn/large/006tKfTcgy1fbzdq8yymhj31do0iejuq.jpg)



![](https://ww1.sinaimg.cn/large/006tKfTcgy1fbzdqfhg91j31dy0rqjwm.jpg)



## HTML 变量格式化

HTML ** 元素定义*数学变量*：

###### 实例

```
<p>Einstein wrote:</p>

<p><var>E = m c<sup>2</sup></var></p>
```



HTML全局属性：http://www.w3school.com.cn/tags/html_ref_standardattributes.asp

HTML事件属性：http://www.w3school.com.cn/tags/html_ref_eventattributes.asp

######

###### [target="_blank"]在新的窗口中打开连接

#### [target="_self"]在本窗口打开连接

![](https://ww1.sinaimg.cn/large/006tNbRwgy1fc21uut1dbj30yi1pc1kx.jpg)





###### 给图片加上超链接

![](https://ww3.sinaimg.cn/large/006tNbRwgy1fc22bz8kiaj30yi12uwjw.jpg)



##### table

row——行

column——列

tr——table row——横行

td——table column——竖列

th——table header

span——块

colspan——列块数

border——边框（0-无；1-有）
