---
title: "测试页"
date: 2020-10-24T15:07:43+08:00
description: "为测试而写，不做任何其他用途"
tags: ["markdown", "测试"]
categories: ["备忘录"]
summary: "<p>不是所有的成功都是可以一步就达到的，大多数情况下，你需要学会打滚。</p><p>失败的多了，也许就知道该放弃了，然后放下了一切，绕道而行。</p><p>放弃了之后，又会发现其实离成功只有一步之遥了，但这时往往已经没机会了。</p>"
katex: true
---

### `可以用来标识单行代码段哟

``` markdown
`fmt.Println("最喜欢go语言")`
```

`fmt.Println("最喜欢go语言")`

### ``` 可以用来写多行代码

```` markdodwn
``` csharp
   public void Main(String[] args)
   {
      Console.WriteLine("写的最多的还是csharp");
   }
```
````

``` csharp
   public void Main(String[] args)
   {
      Console.WriteLine("写的最多的还是csharp");
   }  
```

### 不普通的字体

``` markdown
正常
**加粗**
*倾斜*
***粗体倾斜***
~~删除线~~
```

正常
**加粗**
*倾斜*
***粗体倾斜***
~~删除线~~

### 标题（就只写代码吧，展示效果会乱）

``` markdown
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```

### 引用

``` markdown
> 这是引用的内容
>> 这也是引用的内容
>>>>>>>>>> 这还是引用的内容
```

> 这是引用的内容
>> 这也是引用的内容
>>>>>>>>>> 这还是引用的内容

### 论分割线的实现方法

``` markdown
分割线1
- --
分割线2
***
```

分割线1
- --
分割线2
***

### 图片和超链接

``` markdown
![图片下面的文字](https://www.baidu.com/img/baidu_jgylogo3.gif "鼠标移到图片上时显示的内容")

[<u>超链接</u>](https://www.baidu.com/ "百度")
```

![图片下面的文字](https://www.baidu.com/img/baidu_jgylogo3.gif "鼠标移到图片上时显示的内容")

[<u>超链接</u>](https://www.baidu.com/ "百度")

### 列表

###### 无序列表（无序列表用 - + * 任何一种都可以，- + * 跟内容之间都要有一个空格

``` markdown
- 列表内容
+ 列表内容
* 列表内容
```

- 列表内容
+ 列表内容
* 列表内容


###### 有序列表（序号跟内容之间要有空格）

``` markdown
1. 列表内容
5. 列表内容
10. 列表内容
```

1. 列表内容
5. 列表内容
10. 列表内容


###### 列表嵌套

``` markdown
* 一级无序列表
   - 二级无序列表
   - 二级无序列表
* 一级无序列表
   1. 二级有序列表
   3. 二级有序列表
```

* 一级无序列表
   - 二级无序列表
   - 二级无序列表
* 一级无序列表
   1. 二级有序列表
   3. 二级有序列表

### 勾选框

``` markdown
- [x] 已勾选
- [ ] 未勾选
```

- [x] 已勾选
- [ ] 未勾选

### 表格（简单表情不支持）

``` markdown
姓名|表情|排行
:-|:-:|-:
刘备|:-(|大哥
关羽|:-)|二哥
张飞|:-O|三弟
```

姓名|表情|排行
:-|:-:|-:
刘备|:-(|大哥
关羽|:-)|二哥
张飞|:-O|三弟

;-(  ;-) B-) X-) :D >:( </3 :/ :,( <3 ]:( o:) :') :-* :-| :@ ]:) :P ,:( ,:) :s  [emoji](https://github.com/markdown-it/markdown-it-emoji/blob/master/lib/data/shortcuts.js "emoji")

### 流程图(暂不支持)

``` mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

### 缩进和特殊符号的转义

###### 缩进

``` markdown
未缩进参照

&#160;缩进1/4中文

&nbsp;缩进1/4中文

&#8194;缩进半个中文

&ensp;缩进半个中文

&#8195;缩进一个中文

&emsp;缩进一个中文
```

未缩进参照

&#160;缩进1/4中文

&nbsp;缩进1/4中文

&#8194;缩进半个中文

&ensp;缩进半个中文

&#8195;缩进一个中文

&emsp;缩进一个中文

###### 特殊符号

``` markdown
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
```

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

### 字体

``` markdown
<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=#09f size=2 face="黑体">color=#09f size=2 face="黑体"</font>
<font color=#0ff size=3>color=#0ff</font>
<font color=gray size=4>color=gray</font>
```

<font face="黑体">我是黑体字</font>
<font face="微软雅黑">我是微软雅黑</font>
<font face="STCAIYUN">我是华文彩云</font>
<font color=#09f size=2 face="黑体">color=#09f size=2 face="黑体"</font>
<font color=#0ff size=3>color=#0ff</font>
<font color=gray size=4>color=gray</font>
