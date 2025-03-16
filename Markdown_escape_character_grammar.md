# Markdown 转义字符语法
要显示原本用于格式化 Markdown 文档的字符，请在字符前面添加反斜杠字符`\`。
```Markdown
* Without the backslash, this would be a bullet in an unordered list.

\* And use a backslash can escape that.
```
* Without the backslash, this would be a bullet in an unordered list.

\* And use a backslash can escape that.
## 可做转义的字符
* `\` backslash
* `` ` `` backtick (see also escaping backticks in code)
* `*` asterisk
* `_` underscore
* `{}` curly braces
* `[]` brackets
* `()` parentheses
* `#` pound sign
* `+` plus sign
* `-` minus sign (hyphen)
* `.` dot
* `!` exclamation mark
* `|` pipe (see also escaping pipe in tables)
## 特殊字符自动转义
在 HTML 文件中，有两个字符需要特殊处理：`<` 和 `&`。 `<` 用于起始标签， `&` 符号则用于标记 HTML 实体。如果你只是想要使用这些符号，你必须要使用实体的形式，像是 `&lt;` 和 `&amp;` 。

`&` 符号其实很容易让写作网页文件的人感到困扰，如果你要打 [AT&T] ，你就必须要写成 [AT&amp;T] ，还得转换网址内的 `&` 符号。不用说也知道这是很容易忘记的，这也可能是 HTML 标准检查所检查到的错误中，数量最多的。

Markdown 允许直接使用这些符号，它帮你自动转义字符。