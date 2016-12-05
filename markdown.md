# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

一级标题
====
二级标题  
----

***

>分割线最常使用就是三个或以上*，还可以使用-和_

段落一  

段落二  

>引用一  
>引用二  

>>段落、引用换行的方式是在一行末添加两个或两个以上的空格

---

#### 无序列表  
> 使用*、+或- 表示无序

* 1
+ 2
  + 1
  * 2
- 3
- 4

#### 有序列表
1. 1
2. 2
3. 3

___


[**Markdown** preference pane](#markdown-pane)

#### 插入链接
[百度](https://www.baidu.com/)

this is [百度][1] reference-style link

[1]: https://www.baidu.com/    "Optional Title Here"  

>Optional Title Here可以用""、‘’或（）引住

#### 插入图片
![MacDown logo](http://macdown.uranusjr.com/static/base/img/logo-160.png)


##### <a name="markdown-pane">hehe</a> 
The Markdown Preference Pane

***  

**这里是粗体**

*这里是斜体*

***

`Command-Q`          退出 app。

***

#### 代码区块
	void main()
	{
		printf("Hello, Markdown.");
	}
> 代码区块的建立是在每行开头加上4个空格或者一个制表符

```javascript
let _hello = "Hello, Markdown."
console.log(_hello)
```
>或者用`````` ``` ``````包裹，一些支持代码高亮的解析器可指定语言。

***

#### 表格

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| Left Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |         $1600 |
| col 2 is      | centered        |           $12 |
| zebra stripes | are neat        |            $1 |

> 左对齐，居中，右对齐


