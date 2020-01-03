垂直对齐原理
===========

## 知识点

* vertical-align：垂直对齐

### 垂直对齐方式

* baseline
* top
* bottom
* middle
* 10px(baseline之上)
* -10px(baseline之下)

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
    <h1>垂直对齐原理</h1>
    <p class="css01">This is my <img src="bar.png"> page.</p>
</body>
</html>
~~~

### style.css

~~~css
p {
    font-size: 64px;
    line-height: 128px;
    background-color: bisque;
}

img {
    vertical-align: baseline;
}
~~~

## 课程文件

https://github.com/komavideo/LearnCSS3

## 小马视频频道

http://komavideo.com
