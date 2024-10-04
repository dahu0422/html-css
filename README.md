# html-css

Build Responsive Real-World Websites with HTML and CSS

## 什么是 HTML

- HyperText Markup Language 超文本标记语言
- HTML is a markup language that web developers use to structure and describe the content of a webpage (not a programming language) HTML 是一门标记语言，web 开发者用它来搭建和描述一个网页的内容
- HTML consists of elements that describe different types of content: paragraphs, links, headings, images, video, etc. HTML 由描述不同类型内容的元素组成:段落、链接、标题、图像、视频等。
- Web browsers understand HTML and render HTML code as websites. 浏览器理解 HTML 并将 HTML 代码渲染成网站。

## HTML 结构

```html
<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>

  <body></body>
</html>
```

- DOCTYPE html: HTML5 文档类型声明，告诉浏览器使用 HTML5 规范来解析页面
- html 标签： 整个网页的根标签，包含网页的所有内容
- head 标签： 包含网页的元数据，比如标题、描述、关键词、作者、网页编码等
- body 标签： 包含网页的主内容，比如文本、图像、视频、音频、表单、链接等

## `<b>` vs `<strong>`

两者在网页中的显示效果是一样的。

- `<b>` 标签使得文本默认显示效果为加粗效果，是**样式标签**
- `<strong>` 标签使得文本默认显示效果为加粗效果，是**语义化标签**，标签的意思是加强，表示该文本比较重要，提醒读者/终端注意。

盲人使用屏幕阅读设备阅读网络资源时，`<strong>` 标签包裹的内容会被重读，而 `<b>` 标签包裹的内容不会被重读

## 使用 UTF-8 转义字符

## Live Server Extension 原理

## 什么是 CSS

- Cascading Style Sheets 层叠样式表
- CSS describes the visual style and presentation of the content written in HTML. CSS 描述了用 HTML 编写的内容的视觉样式和表示
- CSS consists of countless properties that developers use to format the content: properties about font, text, spacing, layout, etc. CSS 包含无数开发者用来格式化内容的属性:字体、文本、间距、布局等属性。

## 样式优先级

优先级从高到低：

1. !important 如果可以避免，尽量不要使用！
2. inline style 内联样式
3. ID selector ID 选择器
4. Class(.) or pseudo-class(::) selector 类选择器、伪类选择器
5. Element selector 元素选择器
6. Universal selector (\*) 全局选择器
