# base_html
 html语言，是不限制标签的大小写，一般用小写表示

#### 块级元素
生成一个元素框，他会填充父元素的内容区，旁边不能有其他元素。p，div

display：block

#### 行内元素
在文本行内生成元素框，不能打断这行文件，

display:inline

##### 外部css的引入使用
```html
<link rel="stylesheet" href="sheet1.css" type="text/css">
```

在css中引入，其他的css文件，使用@import url()

##### 内联css
就是在标签里面使用style

##### 内部css
html使用style标签

#### 元素选择器

##### 使用标签作为元素标识
比如p，a，h1

##### 使用通配选择器
```html
*{
    color:red;
}
```
让每个元素的color都是red。

##### 类选择器class selector 和 ID选择器 id selector
```html
*.warning{
    font-weight:bold
}

#lead-para{
    font-weight:bold
}
```
bold的样式会应用到class属性为warning的所有元素

#### 属性选择器
```html
h1[class] {
    color:silver;
}

a[href][title]{
    font-weight:bold
}

a[href="http://www.baidu.com"]{
    font-weight:bold
}
```
要选择带有class属性（值不限）的所有h1元素，使其文本为银色

同时将href和title属性的超链接的html文本为粗体

具体值href，的a标签文本为粗体

#### 父子关系

html是根元素

#### 





