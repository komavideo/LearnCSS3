CSS选择器
=========

## 知识点

* 标记选择(div, span, ...)
* id选择(#)
* class选择(.)

## 实战演习

### index.html

~~~html
<!DOCTYPE html>
<html lang="zh-cmn-Hans">
<head>
    <meta charset="utf-8" />
    <title>CSS3入门与理解 | 小马技术</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
</head>
<body>
    <h1>CSS选择器</h1>
    <p>Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>
    <p class="toRight">Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>
    <p>Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>
    <div class="toRight">
        <button id="btnRegister">注册</button>
        <button id="btnLogin">登陆</button>
    </div>
</body>
</html>
~~~

### style.css

~~~css
p {
    background-color: bisque;
    font-size: 24px;
    line-height: 48px;
    /* line-height: 2em; */
}

button {
    background-color: dodgerblue;
    width: 150px;
    height: 50px;
    font-size: 24px;
}

#btnRegister {
    color: whitesmoke;
}

#btnLogin {
    font-weight: bolder;
}

.toRight {
    text-align: right;
}

* {
    color: red;
}
~~~

## 课程文件

https://github.com/komavideo/LearnCSS3

## 小马视频频道

http://komavideo.com
