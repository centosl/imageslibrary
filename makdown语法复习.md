# makdown语法复习
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题


> This is a blockquote.
  this is <br/>
> 

>---html
	this is  new blockquote
	
	第二段块级内容

	<div className="App">
        <header className="App-header">
          <img src={logo} className="App-logo" alt="logo" />
          <h2 className="App-title">Welcome to React</h2>
        </header>
        <p className="App-intro">
          To get started, edit <code>src/App.js</code> and save to reload.
        </p>
    </div>


### Header 3

> This is a blockquote.
> 
> This is the second paragraph in the blockquote.
>


> ## This is an H2 in a blockquote

Some of these words *are emphasized*.
Some of these words _are emphasized also_.
Use two asterisks for **strong emphasis**.
Or, if you prefer, __use two underscores instead__.

### 无序列表
* Candy.
* Gum.
* Booze.

+ Candy.
+ Gum.
+ Booze.

- Candy.
- Gum.
- Booze.

##有序列表
1. Red
2. Green
3. Blue




###### 如果你在项目之间插入空行，那项目的内容会用 <p> 包起来，你也可以在一个项目内放上多个段落，只要在它前面缩排 4 个空白或 1 个 tab 。
* A list item.
With multiple paragraphs.

* Another item in the list.

#### 链接
This is an [example link](http://example.com/).

This is an [example link](http://example.com/ "With a Title").

I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

[1]: http://google.com/ "Google"
[2]: http://search.yahoo.com/ "Yahoo Search"
[3]: http://search.msn.com/ "MSN Search"

#### 图片
![alt text](/path/to/img.jpg "Title")


#### 代码块

If **you** want your page to *validate under* ***XHTML 1.0 Strict***,
you've got to put paragraph tags in your blockquotes:

<blockquote>
<p>For example.</p>
</blockquote>


##### 各种骚操作

**这是加粗的文字**

*这是倾斜的文字*
***
///
***这是斜体加粗的文字***

~~这是加删除线的文字~~


- 无序列表项目
- 无序列表项目
- 无序列表项目

* 无序列表项目
* 无序列表项目
* 无序列表项目

1. 有序列表项目
2. 有序列表项目
3. 有序列表项目

- 外层列表项目
 + 内层列表项目
 + 内层列表项目
 + 内层列表项目
- 外层列表项目

    四个空格

| ABCD | EFGH | IJKL |
| -----|:----:| ----:|
| a    | b    | c    |
| d    | e    |  f   |
| g    | h    |   i  |

ABCD | EFGH | IGKL
-----|------|----
a    | b    | c
d    | e    | f
g    | h    | i

> 引用的文字
> 引用的文字
> 引用的文字

---
> 引用的文字引用的文字引用的文字引用的文字引用的文字引用的文字引
用的文字引用的文字引用的文字引用的文字引用的文字引用的文字引用
的文字引用的文字引用的文字

---
> 引用的文字引用的文字引用的文字引用的文字引用的文字

---
 >> 引言内的引言引言内的引言引言内的引言

----
> 引用的文字引用的文字引用的文字引用的文字引用的文字

>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容


## 表格

表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略

```html
<!--这里面的是代码块哟-->
<div className="App">
    <header className="App-header">
      <img src={logo} className="App-logo" alt="logo" />
      <h2 className="App-title">Welcome to React</h2>
    </header>
    <p className="App-intro">
      To get started, edit <code>src/App.js</code> and save to reload.
    </p>
</div>
```
##### 单行代码块
`create database hero;`


### 流程图

~~markdow中划线~~


---------------------

