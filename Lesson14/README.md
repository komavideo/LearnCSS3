CSS箱体模型
===========

## 知识点

CSS箱体模型的要素和解释

* width
* height
* border
* padding
* margin

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
    <h1>CSS箱体模型</h1>
    <p class="p1">Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>
    <p class="p2">Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>
    <p class="p3">Cascading Style Sheets (CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG or XHTML). CSS describes how elements should be rendered on screen, on paper, in speech, or on other media.</p>
</body>
</html>
~~~

### style.css

~~~css
p {
    margin: 0;
}

.p1 {
    background-color: skyblue;
}

.p2 {
    background-color: bisque;
    margin: 20px;
    border: 1px solid red;
    padding: 30px;
}

.p3 {
    background-color: aquamarine;
}
~~~

## 课程文件

https://github.com/komavideo/LearnCSS3

## 小马视频频道

http://komavideo.com
