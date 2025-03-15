# Markdown 换行语法
在一行的末尾加两个或多个空格，然后按回车键，即可创建一个换行`<br>`。
```Markdown
This is the first line.   
And this is the second line.
```
This is the first line.   
And this is the second line.
## 换行用法的最佳实践
几乎每个 Markdown 应用程序都支持两个或多个空格进行换行，称为`结尾空格(trailing whitespace)`的方式，但这是有争议的，因为很难在编辑器里看到空格，
并且很多人在每个句子后面都会有意或无意地添加两个空格。由于这个原因，你可能要使用结尾空格以外的其它方式来换行。幸运的是，计划每个 Markdown
应用程序都支持另一种换行的方式：HTML的`<br>`标签。

为了兼容性，请在行尾添加“结尾空格”或 HTML 的`<br>`标签来实现换行。

还有另外两种方式不推荐使用。 CommonMark 和其他几种轻量级标记语言支持在行尾添加反斜杠(`\`)的方式实现换行，但是并非所有的 Markdown
应用程序都支持这种方式，因此从兼容性的角度出发，不推荐使用。并且至少有两种轻量级标记语言支持无须在行尾添加任何内容，只需键入回车键(`return`)即可实现换行。
