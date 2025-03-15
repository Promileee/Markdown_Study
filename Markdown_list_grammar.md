# Markdown 列表语法
可以将多个条目组织成有序或无序列表。
## 有序列表
要创建有序列表，请在每个列表项前添加数字并紧跟一个英文句点。数字不必按数学排列，但是列表应当以数字`1`起始。
```Markdown
1. First item
2. Second item
3. Third item
4. Fourth item
```
1. First item
2. Second item
3. Third item
4. Fourth item
```Markdown
1. First item
1. Second item
1. Third item
1. Fourth item
```
1. First item
1. Second item
1. Third item
1. Fourth item
```Markdown
1. First item
8. Second item
3. Third item
5. Fourth item
```
1. First item
8. Second item
3. Third item
5. Fourth item
```Markdown
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item
```
1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item
## 无序列表
要创建无序列表，请在每个列表前面添加减号(`-`)、星号(`*`)或加号(`+`)。缩进一个或多个列表项可创建嵌套列表。
### 例子
```Markdown
- First item
- Second item
- Third item
- Fourth item
```
- First item
- Second item
- Third item
- Fourth item
```Markdown
* First item
* Second item
* Third item
* Fourth item
```
* First item
* Second item
* Third item
* Fourth item
```Markdown
+ First item
+ Second item
+ Third item
+ Fourth item
```
+ First item
+ Second item
+ Third item
+ Fourth item
```Markdown
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
```
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
## 在列表中嵌套其他元素
要在保留列表连续性的同时在列表中添加另一种元素，请将该元素缩进四个空格或一个制表符。
### 段落
```Markdown
- This is the first list item.
- Here's the second list item.

    I need to add another paragraph below the second list item.

- And here's the third list item.
```
- This is the first list item.
- Here's the second list item.

    I need to add another paragraph below the second list item.

- And here's the third list item.
### 引用块
```Markdown
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.
```
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.
### 代码块
代码块通常采用四个空格或一个制表符的缩进。当他们被放在列表中时，请将他们缩进八个空格或两个制表符。
```Markdown
1. Open the file.
2. Find the following code block on line 21:

        &lt;html>
          &lt;head>
            &lt;title>Test&lt;/title>
          &lt;/head>

3. Update the title to match the name of your website.
```
1. Open the file.
2. Find the following code block on line 21:

        &lt;html>
          &lt;head>
            &lt;title>Test&lt;/title>
          &lt;/head>

3. Update the title to match the name of your website.
### 图片
```Markdown
1. Open the file containing the Linus mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/tux.png)

3. Close the file.
```
1. Open the file containing the Linus mascot.
2. Marvel at its beauty.

    ![Tux, the Linux mascot](/tux.png)

3. Close the file.
### 列表
你可以在有序列表中嵌套无序列表，反之亦然。
```Markdown
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
```
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item