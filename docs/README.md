# 【狂】HTML5

# HTML5

## HTML基础认知

- [ ]  [P1HTML01：初识HTML12:01](https://www.bilibili.com/video/BV1x4411V75C?p=1)

### 前端基础了解

- JUE可以实现前后端分离，绑定
- html：网页最基本的结构
- CSS：美化网页
- JS动态页面，交互行为
- JS过于复杂，可以用封装JS的库JQuery

### 目录

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled.png)

### 什么是html

- hyper text markup language 超文本标记语言
- 标记语言：标签
- 超文本：包括文字，图片，音频，视频，动画
- 浏览器访问 源代码（html）

### html发展史

- 现在的发展史是css3+html5
- html5新特性：可以图形渲染，动画，图表，不需要插件就可以执行
- 早期动画还要flash，现在直接html5就可以了
- html5优势：
    - 所有浏览器都对html5支持
    - 纯天然跨平台
    - 市场需求-html5 统一了web，技术成熟，有自身标准化

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%201.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%201.png)

### W3C

- World Wide Web Consortium 万维网联盟
- 成立于1994，web技术领域最权威的国际中立性技术标准机构
- 网站(org表示开源)
    - http://www.w3.org/
    - http://www.chinaw3c.org/
- W3C标准
    1. 结构化standard语言：html, xml（配置文件）
    2. 表现standard语言：CSS
    3. 行为标准：DOM（文档对象模型），ECMAScript（JavaScript规范，ECMA6）

### 写前端的工具、IDE

- 早期
    - 记事本
    - Dreamweaver
- 现在
    - WebStorm
    - IntelliJ IDEA(集成了WebStorm，两家是同一个公司出的)

### 新建一个html项目

- 打开idea
- java开个项目
- 现在不需要src了，删掉，新建一个dir 叫html
- new一个html file
自动生产代码：

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Title</title>
    </head>
    <body>

    </body>
    </html>
    ```

- 右边有多个browser的标，可以依次打开browser查看效果
    - link样例：[http://localhost:63342/HTML/html/1.myFirstWebPage.html](http://localhost:63342/HTML/html/1.myFirstWebPage.html?_ijt=63vcnqnb0b83q4e5uu1fhm18r1)
- 可以调配浏览器的local程序地址
    - File-Settings-web

        ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%202.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%202.png)

### html基本结构

- 分为html - head - body - html结束
- 标签类型
    - 自闭和标签/**开放标签**：只有一个标签的，比如    `<meta charset="UTF-8">`
    - **闭合标签**：有开始和结束

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%203.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%203.png)

## 网页基本信息

- [ ]  [P2HTML02：网页基本信息05:24](https://www.bilibili.com/video/BV1x4411V75C?p=2)

### 页面基本信息

- DOCTYPE 声明：告诉浏览器，要是用什么规范
- title: 显示在tab上的文字

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%204.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%204.png)

- meta：描述性的，比如关键词，description(可以用来做SEO)

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%205.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%205.png)

- 可以通过browser查看源代码，和inspect

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%206.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%206.png)

### 注释

- IntelliJ中，`control`+`/` 是在html中添加注释的快捷键
- 格式如下

    ```html
    <!-- comment-->
    ```

### html基础代码，标签解读

```html
<!-- DOCTYPE: 告诉浏览器，要是用什么规范-->
<!DOCTYPE html>

<!-- html总标签，外面的不会显示-->
<html lang="en">
<!-- head 标签；网页header-->
<head>
    <!-- meta描述性标签，用来描述网站的一些信息 -->
    <meta charset="UTF-8">
    <meta name="keywords" content="SKT,html">
    <meta name ="description" content="学习html的第一个网页">

    <!-- 网页标题,显示在browser tab上 -->
    <title>My First Web Pae</title>
</head>

<!-- body标签：网页body-->
<body>
hello,world!
</body>
</html>
```

## 网页基本标签

- [ ]  [P3HTML03：网页基本标签11:51](https://www.bilibili.com/video/BV1x4411V75C?p=3)

### header

- 直接写`</`自动就补全出来了
- <h1> </h1>

    ```html
    <!--标题标签-->
    <h1>一级标签</h1>
    <h2>二级标签</h2>
    <h3>三级标签</h3>
    <h4>四级标签</h4>
    <h5>五级标签</h5>
    <h6>六级标签</h6>
    ```

### 段落标签`<p></p>`

- 如果不写段落标签，浏览器不会换行（空格，换行没用）

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%207.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%207.png)

- 快捷键：`p`+`tab`

    ```html
    <p>Inside those walls you are doing your time,
        Not being here with me is your only true crime.
        Others in your life will come and go,
        But my love is true, and i’m sure you know.
    </p>
    ```

### 换行标签`<br/>`

- 自闭和标签，最后要加上`/`
- 例子，紧凑，换行不换段

    ```html
    I may not be rich or the prettiest one,
    But I love you so much; you are my sun.<br/>
    You light up my life every time you call.
    When the time is up, I begin to fall.<br/>
    You are my stars, you are my moon,
    Being with you will come very soon.<br/>
    So when you sleep, take this to heart,
    No one or nothing will keep us apart.<br/>

    ```

### 水平线标签`<hr/>`

- `hr` + `tab`

### 字体格式

- 粗体：`<strong>I love you </strong>`
- 斜体：`<em>I love you</em>`

### 特殊符号

- 空格：
    - 正常来说，不管连续按多少个空格，html都只空一格
    - 要用`&nbsp;` 代表真正的空格

        ```html
        空   格： <br/>
        空&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;格
        ```

- 大于：`&gt;`
- 小于：`&lt;`
- 版权：`&copy;`
- 记忆方式

    ```html
    <!--
    特殊符号记忆方式
    &  ;
    google，或者直接 敲&和字母，有自动提示
    -->
    ```

### code-基本标签

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>基本标签学习</title>
</head>
<>

<!--标题标签-->
<h1>一级标签</h1>
<h2>二级标签</h2>
<h3>三级标签</h3>
<h4>四级标签</h4>
<h5>五级标签</h5>
<h6>六级标签</h6>

<!--段落标签-->
<p>I see you in my thoughts and dreams,
    When I awake, how real it seems.
    You aren’t here to comfort me,
    But soon I hope you will be.
    No one truly knows or understands;
    You have my heart in your hands.
    My love is what you truly own.
    Come soon and make our house a home.</p>

<p>Inside those walls you are doing your time,
    Not being here with me is your only true crime.
    Others in your life will come and go,
    But my love is true, and i’m sure you know.
</p>

<p>I may not be rich or the prettiest one,
    But I love you so much; you are my sun.
    You light up my life every time you call.
    When the time is up, I begin to fall.
    You are my stars, you are my moon,
    Being with you will come very soon.
    So when you sleep, take this to heart,
    No one or nothing will keep us apart.</p>

<!--换行标签-->
I may not be rich or the prettiest one,
But I love you so much; you are my sun.<br/>
You light up my life every time you call.
When the time is up, I begin to fall.<br/>
You are my stars, you are my moon,
Being with you will come very soon.<br/>
So when you sleep, take this to heart,
No one or nothing will keep us apart.<br/>

<!--水平线标签-->
<hr/>

<!--字体-->
<h1>字体样式标签</h1>

粗体： <strong>I love you </strong> <br/>
斜体： <em>I love you</em>

<!--特殊符号-->
<br/>
空   格： <br/>
空&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;格

<!--大于小于-->
<br/>
&gt;
<br/>
&lt;
<br/>
&copy;copy right:Kaitan

<!--
特殊符号记忆方式
&  ;
google，或者直接 敲&和字母，有自动提示
-->

</body>
</html>
```

## 图像标签

- [ ]  [P4HTML04：图像标签06:11](https://www.bilibili.com/video/BV1x4411V75C?p=4)

### 常见图像格式

- JPG： 使用多
- GIF
- PNG： 使用多
- BMP位图

### 如何嵌入图片

- alt：如果显示不出来图片的时候，显示什么文字

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%208.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%208.png)

- `img`+`tab`
- 编程习惯：可以增加一个resources的dir，然后里面添加一个image专门储存图片
- 推荐使用相对地址
- 空格一下，IntelliJ自动提示其他的关键词

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>图片标签学习</title>
    </head>
    <body>

    <!--img学习
    src:图片地址(必填)
        1.相对地址(推荐)
        2.绝对地址
    alt：文字（必填）
    -->
    <img src="..\resources\image\Code-Geass.jpg"
         alt="Luluxiu" title="Lulu Image" width="200">

    </body>
    </html>
    ```

## 超链接

- [ ]  [P5HTML05：超链接标签及应用11:44](https://www.bilibili.com/video/BV1x4411V75C?p=5)

### 超链接种类

- 页面间-链接
- 锚链接
- 功能性链接

### 页面间超链接`<a>`

- `a` + `tab`
- 参数
    - href：路径，必填
    - target：窗口如何打开，比如_blank是打开一个新的窗口
- 可以在a标签里放image，就是在图片上加了跳转链接，可以直接点击图片跳转

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%209.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%209.png)

### 锚链接

- 设定锚标签
    - 使用a标签，添加name作为锚的名字

    ```html
    <!--毛标签-标记
        使用name作为标记-->
    <a name="top">顶部</a>
    ```

    - 跳转的设定，用#标签名

    ```html
    <a href="#top">回到顶部</a>
    ```

    - 也可以跳转到别的界面的 锚链接

    ```html
    <a href="4.链接标签.html#down">调转link4最下面</a>
    ```

### 功能性链接-邮箱

- 点击下面link，user直接打开默认邮箱，收件人已填好

```html
<!--功能性链接
    邮件链接：mailto(收件人是谁)-->
<br>
<a href="mailto:sunkaitan123@163.com">点击联系我</a>
```

### 功能性链接：QQ

- 搜索QQ推广，登录QQ账号
- 点击-推广工具

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2010.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2010.png)

- 填写推广文字，得到代码

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2011.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2011.png)

```html
<a target="_blank" href="http://wpa.qq.com/msgrd?v=3&uin=&site=qq&menu=yes"><img border="0" src="http://wpa.qq.com/pa?p=2::52" alt="加我加我" title="加我加我"/></a>
```

### 代码

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>链接标签学习</title>
</head>
<body>

<!--毛标签-标记
    使用name作为标记-->
<a name="top">顶部</a>

<!--a标签
href: 必填，要跳转的页面
target：窗口在哪里打开
    _blank:新标签页打开
    _self:自己的网页中打开
-->
<a href="1.myFirstWebPage.html" target = "_blank">点击，跳转</a><br>
<a href="https://www.google.com">点击，跳转google</a><br>

<p>点击图片跳转：<br>
    <a href="1.myFirstWebPage.html">
        <!-- 点击图片-跳转超链接 -->
        <img src="..\resources\image\Code-Geass.jpg"
             alt="Luluxiu" title="Lulu Image" width="800">
    </a>
</p>

<p>点击图片跳转：<br>
    <a href="1.myFirstWebPage.html">
        <!-- 点击图片-跳转超链接 -->
        <img src="..\resources\image\Code-Geass.jpg"
             alt="Luluxiu" title="Lulu Image" width="800">
    </a>
</p>
<p>点击图片跳转：<br>
    <a href="1.myFirstWebPage.html">
        <!-- 点击图片-跳转超链接 -->
        <img src="..\resources\image\Code-Geass.jpg"
             alt="Luluxiu" title="Lulu Image" width="800">
    </a>
</p>
<p>点击图片跳转：<br>
    <a href="1.myFirstWebPage.html">
        <!-- 点击图片-跳转超链接 -->
        <img src="..\resources\image\Code-Geass.jpg"
             alt="Luluxiu" title="Lulu Image" width="800">
    </a>
</p>
<p>点击图片跳转：<br>
    <a href="1.myFirstWebPage.html">
        <!-- 点击图片-跳转超链接 -->
        <img src="..\resources\image\Code-Geass.jpg"
             alt="Luluxiu" title="Lulu Image" width="800">
    </a>
</p>

<!--锚链接
1. 需要一个锚标记（在最上面）
2. 跳转到标记 （#标记名称如top）
-->
<a href="#top">回到顶部</a><br>

<a name="down">down</a>

<!--功能性链接
    邮件链接：mailto(收件人是谁)-->
<br>
<a href="mailto:sunkaitan123@163.com">点击联系我</a>

<!--QQ推广-->

<a target="_blank" href="http://wpa.qq.com/msgrd?v=3&uin=&site=qq&menu=yes"><img border="0" src="http://wpa.qq.com/pa?p=2::53" alt="加我加我" title="加我加我"/></a>
</body>

</html>
```

## 块元素，行内元素

- [ ]  [P6HTML06：块元素和行内元素02:37](https://www.bilibili.com/video/BV1x4411V75C?p=6)

### 块元素

- 无论内容多少，元素独占一行
- 比如`p` , `h1`

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2012.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2012.png)

### 行内元素

- 可以把内容撑开，可以跟其他元素放在同一行（不用新起一行）

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2013.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2013.png)

- 比如`strong` `em`

## 列表

- [ ]  [P7HTML07：列表标签05:44](https://www.bilibili.com/video/BV1x4411V75C?p=7)

### 什么是列表

- 其实就是bullet points, 序号之类的

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2014.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2014.png)

### 有序列表

- ordered list
- <ol></ol>

    ```html
    <ol>
        <li>Java</li>
        <li>Python</li>
        <li>DevOps</li>
        <li>C</li>
    </ol>
    ```

    ```html
    1. Java
    2. Python
    3. DevOps
    4. C
    ```

### 无序列表

- `<ul></ul>`
- Un-ordered list

    bullet points：

    ```html
    <ul>
        <li>Java</li>
        <li>Python</li>
        <li>DevOps</li>
        <li>C</li>
    </ul>
    ```

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2015.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2015.png)

### 自定义列表

- `<dt></dt>`
    - dt: 列表名称
    - dd: 选项/内容

    ```html
    <!--自定义列表
    dl：标签
    dt：列表名称
    dd：列表内容-->
    <dl>
        <dt>学科</dt>
        <dd>Java</dd>
        <dd>Python</dd>
        <dd>Linux</dd>
        <dd>C</dd>

        <dt>位置</dt>
        <dd>西安</dd>
        <dd>北京</dd>
        <dd>新疆</dd>
        <dd>重庆</dd>
    </dl>
    ```

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2016.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2016.png)

- 应用场景:

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2017.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2017.png)

## 表格

- [ ]  [P8HTML08：表格标签05:39](https://www.bilibili.com/video/BV1x4411V75C?p=8)

### 使用表格

- 结构稳定
- 简单通用

### 基本结构

- 单元格
- 行，列
- 合并：跨行，跨列

### 例1

```html
<!--表格table
    行：tr (table row)
    列：td
    -->

<table border="1px">
    <tr>
        <td>1-1</td>
        <td>1-2</td>
        <td>1-3</td>
        <td>1-4</td>
        <td>1-5</td>
    </tr>
    <tr>
        <td>2-1</td>
        <td>2-2</td>
        <td>2-3</td>
        <td>2-4</td>
    </tr>
    <tr>
        <td>3-1</td>
        <td>3-2</td>
        <td>3-3</td>
        <td>3-4</td>
    </tr>
```

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2018.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2018.png)

### 例2

- 跨行，跨列

```html
<!--表格table
    行：tr (table row)
    列：td
    -->

<table border="1px">
    <tr>
        <!--跨列-->
        <td colspan = "3">1-1</td>
        <td>1-2</td>

    </tr>
    <tr>
        <!--跨行-->
        <td rowspan="2">2-1</td>
        <td>2-2</td>
        <td>2-3</td>
        <td>2-4</td>
    </tr>
    <tr>
        <td>3-1</td>
        <td>3-2</td>
        <td>3-3</td>
    </tr>
</table>
```

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2019.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2019.png)

## 视频，音频

- [ ]  [P9HTML09：媒体元素05:38](https://www.bilibili.com/video/BV1x4411V75C?p=9)

### 视频video

- 这样看不到视频：

    ```html
    <!--video-->
    <video src="../resources/video/sample_ted.mp4"></video>
    ```

    - open video in a new tab才能看视频
    - 这是因为没有添加控制、播放功能
- 添加controlers就能看到了
- 除此之外还可以设置autoplay (但是chrome默认禁止了auto play，所以还要设置一下)

    ```html
    <video src="../resources/video/sample_ted.mp4" controls autoplay></video>
    ```

### 音频audio

- 同理，需要controlers

    ```html
    <!--audio-->
    <audio src="../resources/audio/sample_song.mp3" controls autoplay></audio>
    ```

## 页面结构

- [ ]  [P10HTML10：页面结构分析04:34](https://www.bilibili.com/video/BV1x4411V75C?p=10)

### 页面结构

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2020.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2020.png)

- 最上面的导航栏
- 侧边栏
- 底部

### Example code

- 用这些结构标签，可以让webpage结构更清晰
- 例子

    ```html
    <header>
        <h2>网页header</h2>
    </header>

    <section><h2>网页section</h2></section>

    <footer><h2>网页footer</h2></footer>
    ```

## iframe内联框架

- [ ]  [P11HTML11：iframe内联框架06:25](https://www.bilibili.com/video/BV1x4411V75C?p=11)

### 内联框架

- 在一个网页里，嵌套另外一个网页
- code格式

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2021.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2021.png)

- 加一个iframe，显示百度这个网页

    ```html
    <!--baidu-->
    <!--格式：
        src:path
        w-h:宽度 高度
        name:名字-->
    <iframe src="https://www.baidu.com" frameborder="0" width="800px" height="1000px"></iframe>
    ```

### 例子：bilibili中

- 点击一个视频的 分享

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2022.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2022.png)

- 有内嵌代码

    ```html
    <iframe src="//player.bilibili.com/player.html?aid=55631961&bvid=BV1x4411V75C&cid=97257967&page=11" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>
    ```

### 例子: 在iframe中跳转

- 例子：点击跳转，可以在 一个空的iframe中显示指定网页
- 代码

    ```html
    <!--在iframe中打开指定网页-->
    <iframe src="" name="Hello" frameborder="0" width="300px" height="300px"></iframe>

    <a href="1.myFirstWebPage.html" target = "Hello">跳转page1</a>
    ```

## 表单

- [ ]  [P12HTML12：初识表单post和get提交09:28](https://www.bilibili.com/video/BV1x4411V75C?p=12)

### 语法

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2023.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2023.png)

### 例子：

- 用form设计一个登录界面

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>登陆注册</title>
    </head>
    <body>

    <h1>注册</h1>

    <!--表单form
        action:表单提交的位置，可以是网站，也可以是一个请求处理地址
        method: post，get提交方式
            get: 可以在url中看到信息，不安全，但是高效，不能传输大文件
            post:url中看不到信息，安全，可以传输大文件
        -->

    <form action="1.myFirstWebPage.html" method="post">
        <p>
            <!--文本输入框：
                input类似python的input，文本输入框-->
            名字: <input type="text" name="username">
        </p>
        <p>
            <!--密码框：
                password类，input自动变*-->
            密码: <input type="password" name="pwd">
        </p>

        <p>
            <!--提交表单，类型：submit，button形式-->
            <input type="submit">
            <!--清空表单，类型：reset，button形式-->
            <input type="reset">
        </p>

    </form>

    </body>
    </html>
    ```

    ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2024.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2024.png)

- 用get方式提交，进入的页面link会带着 input parameter，如下

    ```html
    http://localhost:63342/HTML/html/1.myFirstWebPage.html?username=zidiefeng&pwd=123456
    ```

- post提交，url就看不到param了，安全

    ```html
    http://localhost:63342/HTML/html/1.myFirstWebPage.html
    ```

### get post 对比

- get:
    - 可以在url中看到信息，不安全，但是高效
    - 不能传输大文件
- post
    - url中看不到信息，安全
    - 可以传输大文件
    - 如果不在url中，那form信息如何查看？可以进入inspect network，点击提交的时候，可以看到有个request，里面储存了各种request信息，包括form data

        ![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2025.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2025.png)

    - 这样也不是很安全，可以加密，即使在这里也看不到

### 表单元素格式

- [ ]  [P13HTML13：文本框和单选框05:55](https://www.bilibili.com/video/BV1x4411V75C?p=13)
- name 类似parameter name
- value 是 parameter input

![%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2026.png](%E3%80%90%E7%8B%82%E3%80%91HTML5%20e96b083441164191be63655774f0966d/Untitled%2026.png)

### 文本框例子-其他属性

- value: 默认初始填充值
- maxlength: 最多能输入的字符长度
- size: 输入框的长度

    ```html
    <p>名字: <input type="text" name="username" value="狂神好帅" maxlength="8" size = "30"></p>
    ```

### 单选框-`radio`

- 注意，name 一样的 才会设置为同一组单选关系
- 必须有value，要不提交不成功

```html
<!--单选框
    input type: radio
    value：单选框的值 （input value of a parameter）
    name: 组，不同组没有多选一的关系
    -->
    <p>性别：
        <input type="radio" value="boy" name = "sex"/>男
        <input type="radio" value="girl"  name = "sex"/>女
    </p>
```

- [ ]  [P14HTML14：按钮和多选框05:38](https://www.bilibili.com/video/BV1x4411V75C?p=14)

### 多选框

```html
<!-- 多选框
        默认选中：checked
      -->
    <p>爱好
        <input type="checkbox" value = "sleep" name="hobby" checked>睡觉
        <input type="checkbox" value = "coding" name="hobby">敲代码
        <input type="checkbox" value = "chat" name="hobby">聊天
        <input type="checkbox" value = "game" name="hobby">游戏
    </p>
```

### 按钮

- value：按钮上面的文字
- 图片也可以是个按钮
- 还有默认按钮：subit, reset

```html
<!--按钮
    input type = button
    input type = image
    input type = submit
    input type = reset
    -->
<p>按钮：
    <input type="button" name = "btn1" value="点击边长">
    <input type="image" src="../resources/image/Code-Geass.jpg" width="200">
</p>
```

- [ ]  [P15HTML15：列表框文本域和文件域08:32](https://www.bilibili.com/video/BV1x4411V75C?p=15)

### 下拉框

- 用select

```html
<!--下拉框
        value是param input
        selected：默认选中-->
    <p>国家：
        <select name="列表名称" >
            <option value="china" selected>中国</option>
            <option value="us">美国</option>
            <option value="选项的值">瑞士</option>
            <option value="选项的值">印度</option>
        </select>
    </p>
```

### 文本域

- 用textarea

```html
<!--文本域:
        多行文本输入-->
    <p>反馈：
        <textarea name="textarea" cols="30" rows="10">文本内容</textarea>
    </p>
```

### 文件域

- input type: file
- 下面，可以配合设置一个 确认上传button（目前还没有设置功能）

```html
<!--文件域
        -->
    <p>文件：
        <input type="file" name = "files">
        <input type="button" value = "上传" name = "upload">
    </p>
```

- [ ]  [P16HTML16：搜索框滑块和简单验证06:54](https://www.bilibili.com/video/BV1x4411V75C?p=16)

### 滑块

```html
<!--滑块-->
    <p>滑块
        <input type="range" name="voice" min="1" max="9">
    </p>
```

### 搜索框

```html
<!--搜索-->
    <p>搜索
        <input type="search" name="search">
    </p>
```

## 表单应用

- [ ]  [P17HTML17：表单的应用04:54](https://www.bilibili.com/video/BV1x4411V75C?p=17)

### 表单属性

- 隐藏：`hidden`
    - 虽然隐藏了，但是param还在（用于处理默认value）

    ```html
    <p>
    <!--密码框：
            password类，input自动变*-->
    密码: <input type="password" name="pwd" hidden>
    </p>
    ```

- 只读 - `readonly`

    ```html
    <p> 只读标签
            <input type="text" name="fixname" value="admin" readonly>
        </p>
    ```

- 禁用-`disabled`
    - 不能点击男

    ```html
    <p>性别：
            <input type="radio" value="boy" name = "sex" checked disabled/>男
            <input type="radio" value="girl"  name = "sex"/>女
        </p>
    ```

### 点击，可以指向某个输入框

- 点击“你点我试试”，自动能切换到id为mark的这个input框
- for代表目标input框

```html
<!--增强鼠标可用性
    for: id-->
    <label for="mark">你点我试试</label>
    <input type="text" id="mark">
```

## 表单初级验证

- [ ]  [P18HTML18：表单初级验证05:27](https://www.bilibili.com/video/BV1x4411V75C?p=18)

### 表单验证

- 高级需要js，现在就是初级验证
- 验证-为了缓解服务器压力（不要处理垃圾、错误请求）
- 保证数据安全性

### 常用验证方式

- placeholder

    输入框中的提示信息

    ```html
    <p> placeholder
        <input type="text" name="user"  placeholder="请输入用户名">
    </p>
    ```

- required

    不能为空

    ```html
    <p> required
      <input type="required" name="user1"  placeholder="请输入用户名" required>
    </p>
    ```

- pattern
正则表达式

    ```html
    <p>自定义邮箱
        <input type="text" name="diymail" pattern="^\w+([-+.]\w+)*@\w+([-.]\w+)*\.\w+([-.]\w+)*$">
    </p>
    ```

    - 常用正则：[https://www.cnblogs.com/zxin/archive/2013/01/26/2877765.HTML](https://www.cnblogs.com/zxin/archive/2013/01/26/2877765.HTML)

## 总结

- [ ]  [P19HTML19：HTML总结07:03](https://www.bilibili.com/video/BV1x4411V75C?p=19)
- html基本结构
- 网页基本标签
    - 标题h1
    - 段落p
    - 换行br
    - 水平线
    - 注释
    - 特殊符号
- 图像标签 - img
- 超链接
    - 锚链接
    - 功能性链接 （邮箱，QQ）
- 行内元素，块元素
- 列表
    - 有序列表
    - 无序列表
    - 自定义列表
- 表格：行，列，跨行，跨列
- 媒体元素：video，audio
- 网页简单布局：header, footer, section, ...
- 内联框架：iframe
- 表单：`form (post, get)`
    - 文本框，密码框
    - 单选，多选
    - 按钮
    - 下拉框
    - 滑块
    - ...
- 表单应用
    - 只读readonly
    - 禁用disabled
    - 隐藏hidden
- 表单初级验证
    - 用户提示placeholder
    - 非空判断required
    - 正则表达pattern