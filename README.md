# README 的写法

## 标题

# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题

## 字体

**这是加粗的文字**
<br/>
*这是倾斜的文字*`
<br/>
***这是斜体加粗的文字***
<br/>
~~这是加删除线的文字~~

## 引用

>这是引用的内容

## 分割线

---
----
***
*****

## 图片
[路飞](./images/timg.jpg "悬停显示")

## 超链接

[仿易公司](https://jinhuangmin.github.io/yifirm/)
<br/>

[仿QQ阅读](https://jinhuangmin.github.io/qqreadbook/)

## 列表

- 列表内容
+ 列表内容
* 列表内容

## 表格

表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

## 代码

`代码内容`

(```)
document.addEventListener('scroll',
		function(){
      var scrollTop=document.body.scrollTop||document.documentElement.scrollTop;
			document.getElementById("box")
					.style.bottom=scrollTop>600?"50px":"1000px";
			}
		);
(```)
