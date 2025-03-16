# Markdown 链接语法
链接文本放在中括号(`[]`)内，链接地址放在后面的括号(`()`)中，链接 title 可选。
超链接对应的 Markdown 语法代码：`[超链接显示名](超链接地址 "超链接title")`
### 例子
```Markdown
这是一个链接 [Markdown 语法](https://markdown.com.cn)。
```
这是一个链接 [Markdown 语法](https://markdown.com.cn)。
## 给链接增加 title
链接 title 是当鼠标悬停在链接上时会出现的文字，这个 title 是可选的，它放在圆括号中链接地址后面，跟链接地址之间以空格分割。
### 例子
```Markdown
这是一个链接 [Markdown语法](https://markdown.com.cn "最好的 markdown 教程")
```
这是一个链接 [Markdown语法](https://markdown.com.cn "最好的 markdown 教程")
## 网址和 Email 地址
使用尖括号可以很方便地把 URL 或者 email 地址变成可点击的链接。
### 例子
```Markdown
<https://markdown.com.cn>

<fake@example.com>
```
<https://markdown.com.cn>

<fake@example.com>
## 带格式化的链接
强调链接，在链接语法前后增加星号。要将链接表示为代码，请在方括号中添加反引号。
### 例子
```Markdown
I love supporting the **[EFF](https://rff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the session on [`Markdown 链接语法`](#user-content-markdown-链接语法).
```
I love supporting the **[EFF](https://rff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the session on [`Markdown 链接语法`](#user-content-markdown-链接语法).
### Note
`Github` 中，Markdown 会自动将标题设置为一个锚点，格式为 `user-content-heading`。需要注意的是，需要用减号(`-`)替代空格。

不同的 Markdown 应用程序处理 URL 中间空格的方式不一样。为了兼容性，请尽量使用`%20`代替空格。