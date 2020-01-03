列表样式
========

## 知识点

* 列表标记：ul, ol, li
* 列表样式：list-style-*

### 参考网站

https://developer.mozilla.org/en-US/docs/Web/CSS/list-style

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
    <h1>列表样式指定</h1>
    <ul>
        <li>新闻</li>
        <li>体育</li>
        <li>军事</li>
    </ul>
    <ol>
        <li>Python</li>
        <li>Javascript</li>
        <li>Ruby on Rails</li>
    </ol>
</body>
</html>
~~~

### style.css

~~~css
ul {
    /* list-style-type: circle; */
    /* list-style-position: inside; */
    /* list-style-image: url(listicon.png); */
    /* list-style: circle inside url(listicon.png); */
}

ol {
    /* list-style-type: upper-alpha; */
    /* list-style-type: lower-greek; */
    /* list-style-type: lower-roman; */
    /* list-style-type: none; */
}
~~~

## 课程文件

https://github.com/komavideo/LearnCSS3

## 小马视频频道

http://komavideo.com
