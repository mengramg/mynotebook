# html基本骨架

## 基本骨架

+ html：整个网页
+ head：网页头部，用来存放给浏览器看的信息，例如css
  + title：网页标题
+ body：网页主体，用来存放给用户看的信息

```html
<html>
	<head>
        <title>网页标题</title>
    </head>
    
    <body>
        网页主体内容
    </body>
</html>
```



## vscode快速生成骨架

在html文件中，!（叹号）配合tab或enter键



# 标签的关系

+ 父子关系（嵌套关系）：子级别标签换行且缩进（tap键）
+ 兄弟关系（并列关系）：兄弟标签换行要对齐



# html注释

+ 写法：

```html	
<!-- 很开心 -->
```

+ 快捷键：ctrl+/



# 标题标签

标题名：h1-h6,可以最多到六级标题

语法：

```html
<h1>标题标签</h1>
```

+ h1级别只能用一次，h2-h6没有次数限制

# 段落标签

+ 语法：

```html
<p>
    段落内容
</p>
```



# 换行与水平线标签

+ 换行：

```html
<br>
```

+ 水平线：

```html
<hr>
```

+ 两个都是单标签



# 文本格式化标签

+ 为文本添加特殊格式，例如加粗，倾斜，下划线，删除线等

```html
<strong>加粗</strong>
<br>
<em>倾斜</em>
<br>
<ins>下划线</ins>
<br>
<del>删除线</del>
```



# 图像标签

语法：

`<img src="图片的URL" 属性1 属性2>`

注意：若图片的文件夹或图片和html文件放在同一个文件夹里	图片的URL为 ==./图片文件路径==

图片的属性：

![image-20250428210818212](C:\Users\24517\AppData\Roaming\Typora\typora-user-images\image-20250428210818212.png)

宽和高的单位是像素，一般情况只改一个，另一个会跟着等比例缩放



# 路径

相对路径：./文件路径 表示当前文件夹里找文件

绝对路径：就是Windows中的路径属性



ctrl+d：一起选中一样的内容可以进行修改



# ==超链接==

语法： 

```html
<a href="https://www.baidu.com">跳转到百度</a>
<a href="#">井号代表空链接</a>
```

href属性值是跳转地址，是超链接的必须属性

属性：

超链接默认是当前窗口跳转页面，添加target="_blank"可以实现新窗口打开页面



# 音频标签

```html
<audio src="音频的URL"></audio>
```

![image-20250428215512154](C:\Users\24517\AppData\Roaming\Typora\typora-user-images\image-20250428215512154.png)



# 视频标签

![image-20250428215927510](C:\Users\24517\AppData\Roaming\Typora\typora-user-images\image-20250428215927510.png)

+ width属性也可以使用

