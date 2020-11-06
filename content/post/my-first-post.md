---
title: "My First Post"
date: 2020-10-16T15:07:43+08:00
description: "This is a description of markdown file"
image: "hutomo-abrianto-l2jk-uxb1BY-unsplash.jpg"
draft: false
tags: ["hugo"]
categories: ["杂技浅尝"]
---

`单行代码段`

``` csharp
Console.Writeline("多行代码段");
```

一级标题（等号）

=

二级标题（减号）

-
正常
**加粗**
*倾斜*
***粗体倾斜***
~~删除线~~

# 这是一级标题

## 这是二级标题

### 这是三级标题

#### 这是四级标题

##### 这是五级标题

###### 这是六级标题

>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容

分割线
- --
分割线
- --
分割线
***
分割线
*****
分割线

![图片下面的文字](https://www.baidu.com/img/baidu_jgylogo3.gif "鼠标移到图片上时显示的内容")

[<u>超链接</u>](https://www.baidu.com/ "百度")

无序列表（无序列表用 - + * 任何一种都可以）
- 列表内容
+ 列表内容
* 列表内容

注意：- + * 跟内容之间都要有一个空格


有序列表
1. 列表内容
5. 列表内容
10. 列表内容

注意：序号跟内容之间要有空格

- [x] 已勾选
- [ ] 未勾选

列表嵌套
* 一级无序列表
   - 二级无序列表
   - 二级无序列表
* 一级无序列表
   1. 二级有序列表
   3. 二级有序列表

表格

姓名|表情|排行
:-|:-:|-:
刘备|:-(|大哥
关羽|:-)|二哥
张飞|:-O|三弟

;-(  ;-) B-) X-) :D >:( </3 :/ :,( <3 ]:( o:) :') :-* :-| :@ ]:) :P ,:( ,:) :s  [emoji](https://github.com/markdown-it/markdown-it-emoji/blob/master/lib/data/shortcuts.js "emoji")

流程图
```flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
```

缩进

未缩进参照

&#160;缩进1/4中文

&nbsp;缩进1/4中文

&#8194;缩进半个中文

&ensp;缩进半个中文

&#8195;缩进一个中文

&emsp;缩进一个中文

特殊符号
\\ 反斜线
\* 星号
\_ 下划线
\{\}\[\]\(\)括号
\# 井号
\+ 加号
\- 减号
\. 点
\! 惊叹号
&#10084;
&#10003;
&#9728;
&#9733;
&#9730;
&#9775;
&#9762;
&#9742;
&#8734;
&#10052;
&#9835;

字体
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=#09f size=2 face="黑体">color=#09f size=2 face="黑体"</font>
<font color=#0ff size=3>color=#0ff</font>
<font color=gray size=4>color=gray</font>

$\sin a$

使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
\*\* 正常显示星号 \*\*

$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
$$