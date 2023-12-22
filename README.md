# 默认 Headline

> An awesome project.

# Emoji

😄 😆 😊 😃 ☺️ 😏 😍 😘 😚

# Zoom image

<img id="zoom-default" src="https://medium-zoom.francoischalifour.com/image-2.ddbb59d5.jpg" data-zoom-src="https://upload.wikimedia.org/wikipedia/commons/e/e3/Animhorse.gif" >

<img id="zoom-margin" src="https://medium-zoom.francoischalifour.com/image-2.ddbb59d5.jpg" >

```javascript
<script>
  window.$docsify = {
    disqus: 'shortname'
  }
</script>
<script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/disqus.min.js"></script>
```

```bash
#!/bin/bash  
  
# 打印欢迎消息  
echo "欢迎来到Bash脚本示例！"  

# 定义变量  
name="John Doe"  
age=30  
```

```php
<?php  

// 打印欢迎消息  
echo "欢迎来到PHP代码示例！";  
  
// 定义变量  
$name = "John Doe";  
$age = 30;  
 
?>
```

# Tabs

<!-- tabs:start -->

#### **Tab1**

这是 Tab1

#### **Tab2**

这是 Tab2

<!-- tabs:end -->

# 文档助手

!> 强调内容

?> 普通提示

# 取消编译超链接

[link](/demo/ ":ignore")

[link](/demo/ ":ignore title")

# 设置超链接打开方式

[link](https://docsify.js.org/#/zh-cn/ ":target=_self")

[link](https://docsify.js.org/#/zh-cn/ ":target=_blank")

# 禁用超链接

[link](/demo ":disabled")

# 跨域链接

[example.com](https://example.com/ ":crossorgin")

# Github 任务列表

- [ ] 未完成的任务
- [X] 已完成的任务

# 图片处理

![logo](https://docsify.js.org/_media/icon.svg)
![logo](https://docsify.js.org/_media/icon.svg ":size=50x100")
![logo](https://docsify.js.org/_media/icon.svg ":size=100")

<!-- 支持按百分比缩放 -->

![logo](https://docsify.js.org/_media/icon.svg ":size=10%")

# 设置图片的 class 属性

![logo](https://docsify.js.org/_media/icon.svg ":class=someCssClass")

# 设置图片的 ID 属性

![logo](https://docsify.js.org/_media/icon.svg ":id=someCssId")

# 设置标题的 ID 属性

### 你好，世界！ :id=hello-world

# 在html 标签中写 Markdown

<details>
<summary>自我评价（点击展开）</summary>

- Abc
- Def

</details>

<div style='color: red'>

- listitem1
- listitem2
- listitem3

</div>

# 支持使用 Vue 语法

<ul>
  <li v-for="i in 3">Item {{ i }}</li>
</ul>

<p>2 + 2 = {{2+2}}</p> 

<p>
  <button @click="count -= 1">-</button>
  {{ count }}
  <button @click="count += 1">+</button>
</p>

# 文件嵌入

[logo](./logo.mp4 ':include')
