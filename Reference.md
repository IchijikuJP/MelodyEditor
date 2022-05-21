# 参考资料

## READING

### `Markdown`是什么

- 一种轻量级标记语言
- 以纯文本格式编写文档, 然后转换成有效的`HTML`语言

> `Markdown`和`HTML`都是标记语言, 但`Markdown`是书写格式,`HTML`是发布格式,`Markdown`最终会转为`HTML`格式在网页上显示



### 为什么使用`Markdown`

- `MS Word`中的加粗,倾斜,增大字号等在`Markdown`中用相应的特殊符号替代,`Markdown`用于解放鼠标, 仅仅用键盘就能排版出漂亮的博客
- 无需像`HTML`费时排版, 易读
- 让人专注于输入而非格式调整, 易写
- 语法简单, 提高写作效率, 易更改

> 其实浏览器并不能识别 Markdown 的语法，但许多 blog、wiki 平台以及 github 都内置了 Markdown 编辑器，编辑器会先把 Markdown 文本转换成 HTML 格式的网页，然后再把 HTML 网页交给浏览器来显示。除了上述的内置编辑器外，还有许多能解析 Markdown 语法的编写工具，这些工具一般都提供浏览器预览和导出成 HTML 或 PDF 文件的功能。
>
> Markdown 的语法由一些符号定义，这些符号夹杂在文本中，用于控制文本的显示方式。比如两个星号可以给文字加粗**加粗**，这两个星号在 Markdown 编辑器处理后就变成了 HTML 中的**加粗**标签。



### 跨平台使用(待添加)

- 线上
  - [微信 Markdown 编辑器](https://github.com/doocs/md)
  - [⭐⭐⭐Vditor](https://github.com/Vanessa219/vditor)
- Windows
  - Typora
  - Atom



### 怎么做

> Markdown 的语法需要编辑器才能实现，因此编辑器可以按照自己的需求添加或者修改某个语法的含义。因此，基本上所有编辑器解析 Markdown 语法的方式都有些许差异，但大体上可以分成三类：
>
> 1. Classic Markdown：最基础的 Markdown 语法，所有的编辑器都支持
> 2. Extra Markdown：扩展的 Markdown 语法，增加了表格等元素，不一定都能支持
> 3. Github Markdown：github 文档使用的 Markdown 语法，包含 Extra Markdown 的所有内容，还增加了代码高亮、emoji表情等语法，目前许多 blog 平台（cnblogs，csdn）都支持这种语法

#### 基本标签

- 标题: `=`或`-`或`#`
- 段落: 段落前后要有空行,强制换行使用两个以上空格加回车
- 区块引用: 每行使用`>`,可以添加嵌套引用`>>`
- 代码块: `行内代码`



 [12:02 2022年5月21日（星期六）](https://segmentfault.com/a/1190000022933916)