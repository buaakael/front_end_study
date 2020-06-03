# front_end_study
Front end learning notes.

## Web标准的构成
+ 结构Structure(HTML)  
+ 表现Presentation(CSS)  
+ 行为Behavior(JavaScript)  

# HTML
## HTML语法规范

**HTML标签是由尖括号包围的关键词**  
+ 开始标签<html>  
+ 结束标签</html>  
+ 单标签<br />  

**双标签关系**  
+ 包含关系  
+ 并列关系  

## HTML基本结构标签

|标签名|定义|说明|
|------|----|----|
|`<html></html>` |HTML标签|根标签|
|`<head></head>` |文档的头部|head标签中必须设置title标签|
|`<title></title>` |文档的标题|网页标题|
|`<body></body>` |文档的主体|页面内容基本都放在body里面|

+ `<!DOCTYPE html>`文档类型声明标签  
+ lang 语言种类  
+ meta charset=“UTF-8” 字符集  

## HTML常用标签

+ **标题标签**`<h1> - <h6>`
+ **段落标签**`<p> </p>`
+ **换行标签**`<br />` 强制换行
+ **文本格式化标签**

|语义|标签|说明|
|----|----|----|
|加粗|`<strong></strong>或者<b></b>`|更推荐使用`<strong>`标签 语义更强烈|
|倾斜|`<em></em>或者<i></i>`|更推荐使用`<em>`标签 语义更强烈|
|删除线|`<del></del>或者<s></s>`|更推荐使用`<del>`标签 语义更强烈|
|下划线|`<ins></inl>或者<u></u>`|更推荐使用`<ins>`标签 语义更强烈|

+ **`<div>`和`span`标签** 没有语义，就是一个装内容的盒子
   + `<div>`分割，独自占一行，是一个大盒子
   + `<span>`跨距，一行可以放多个盒子，小盒子
