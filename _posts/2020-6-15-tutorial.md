

## Typora入门

### 常用快捷键

- **加粗**：Ctrl + B   

- *倾斜*：Ctrl + I

- 插入链接：Ctrl + K       [www.github.com]()

- 代码块：```+ Enter   并在后面选择一个语言名称即可语法高亮

  ```c#
  Console.WriteLine("Enjoy coding time!");
  ```

  ```python
  def helloworld():
      print 'hello, world'
  ```

- 行内代码：Ctrl + Shift + `       

  `helloworld`

- 插入图片：Ctrl + Shift + i

  ![冰, 冷, 凍結的, 史诗 的 免费素材图片](https://images.pexels.com/photos/417173/pexels-photo-417173.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500)

- 无序列表：- + Space + Enter

  - 第一行
  - 第二行
  - 第三行

- 有序列表：数字键 + . + Space + Enter

  1. 第一行

  2. 第二行

     1.嵌套

     2.嵌套第二行

     1. 三层嵌套

  3. 第三行

- 多行无序列表：Enter + Tab

  - 多行无序列表2
    - 多行无序列表3
      - 多行无序列表4
      - 多行无序列表5

- 撤销：Ctrl + Z

- 切换原文和语法：Ctrl + /

- N级标题：Ctrl + 数字键N

- <u>下划线</u>：Ctrl + U  

- ~~删除线~~：Alt + Shift + 5

### 块元素

#### 换行符

回车即可创建新段落

#### 标题级别

> #一级标题，快捷键为Ctrl + 1
>
> ######六级标题，快捷键为Ctrl + 6

#### 引用文字

> \> + 空格 + 引用文字

> >多层引用

#### 任务列表

>> -[ ] 不勾选
>
>> -[x]勾选

>- [ ] 
>
>- [x] 

#### 表

输入 |表头1|表头2|+ Enter，即可将创建一个包含两列的表，然后就像操作Word文档一样设置表格即可

| First Header | Second Header |
| ------------ | ------------- |
|              |               |

#### 脚注

>创建一个脚注，输入[^1]
>
>[^1]:这是上面的注释内容。
>
>[^1]. 创建脚注的输入内容
>
>注意：脚注标识可以为字母数字下划线，但是暂不支持中文。脚注内容可为任意字符，包括中文。

#### 分割线

输入***或--- 再按Enter即可绘制一条水平线

***



#### YAML Front Matter

Typora支持[YAML Front Matter](https://jekyllrb.com/docs/front-matter/),在文章开头输入---，按Enter即可。

#### 目录（TOC)

输入[toc]+Enter,即可创建一个目录。TOC从文档中提取所有标题，其内容将自动更新。

### 跨度元素

跨度元素及图片，网址，视频等，在Typora输入后，会立刻载入并呈现。

#### 超链接

> Typora允许用<括号括起来>，自动链接标准网址。<www.pseduos.site>
>
> 行内式链接    [文字]：网址（中间是英文的冒号）
>
> [百度]: https://www.baidu.com/
>
> 参考式链接   [文字] [网址]（中间无空格）
>
> [百度][https://www.baidu.com/]



#### 图片

>![显示的文字](/path/to/img.jpg)
>
>![显示的文字](/path/to/img.jpg "图片标题")



![blockchain](https://upload-images.jianshu.io/upload_images/6860761-fd2f51090a890873.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/550/format/webp "blockchain")



![dslr-camera-falt](E:\pics\dslr-camera-flat-lay-821652.jpg "dslr-camera-falt")

#### 倾斜

>左右两边加单个星号*或下划线_
>
>*单个星号*
>
>_单下划线_

#### 加粗

>左右两边加两个星号**或双下划线__
>
>**两个星号**
>
>__双下划线__

#### 代码标记

标记代码使用`,左右两边加上，效果如下：

`printf()`

#### 删除线

>左右两边加上~~，效果如下：

~~删除线~~

#### 下划线

> <u>下划线：Ctrl+U</u>

#### 文本居中/标题居中

```html
<div align = "center">文本居中</div>
```

<div align = "center">文本居中</div>

```html
<h1 align = "center">标题居中</h1>
```

<h1 align = "center">标题居中</h1>

#### 表情符号

>：smile：(英文的冒号)

:grinning:

#### 高亮

> 左右两边加==，效果如下：（需在设置中打开该功能）
>
> ==helloworld==

#### 设置文字颜色/大小/字体属性

```html
<span style='color:文字颜色;background:背景颜色;font-size:文字大小;font-family:字体;'>文字</span>
```

使用时将“文字”替换为需要修改的文本即可。

<span style='color:red;background:white;font-size:10;font-family:consolas;'>Consolas</span>

修改字体大小，注意不直接使用数字，格式为sizepx,例如20px

<span style='color:blue;background:yellow;font-size:20px;font-family:consolas;'>Consolas</span>

#### HTML

支持HTML

#### 上标

X^2^  (需在设置中打开该功能)

#### 下标

H~2~O (需在设置中打开该功能)

#### 嵌入内容

支持iframe-based嵌入代码

#### 视频

> < video src=”xxx.mp4” />

<video src="E:\pics\1.mp4"></video>

### 特殊符号

|  &copy；  |  &copy;  |   版权   |
| :-------: | :------: | :------: |
|  &reg；   |  &reg;   | 注册商标 |
| &trade；  | &trade;  |   商标   |
|  &nbsp；  |  &nbsp;  |   空格   |
|  &amp；   |  &amp;   |    和    |
|  &quot；  |  &quot;  |   引号   |
|  &apos；  |  &apos;  |   撇号   |
|   &lt；   |   &lt;   |   小于   |
|   &gt；   |   &gt;   |   大于   |
|           |   &ne;   |  不等号  |
|  &cent；  |  &cent;  |    分    |
| &pound；  | &pound;  |    磅    |
|  &euro；  |  &euro;  |   欧元   |
|  &yen；   |  &yen;   |    元    |
|  &sect；  |  &sect;  |    节    |
| &times；  | &times;  |   乘号   |
| &divide； | &divide; |   除号   |
| &plusmn； | &plusmn; |  正负号  |



