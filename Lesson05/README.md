CSS样式继承
==========

## 知识点

* CSS样式的父子继承

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
    <h1>CSS3入门与理解</h1>
    <p>东南西北东南西北东南西北东南西北东南西北东南西北东南西北东南西北东南西北</p>
</body>
</html>
~~~

### style.css

body 设置的样式单可以继承给 h1 和 p 标记 。 

~~~css
body {
    color: red; /* 可继承 */
    border: 3px solid green; /* 不可继承 */
}
~~~

但是只有 `color` 样式被继承了 ， `border` 样式并没有被继承 ， 这是为什么呢？

## 样式参考网页

### color

https://developer.mozilla.org/zh-CN/docs/Web/CSS/color

### border

https://developer.mozilla.org/zh-CN/docs/Web/CSS/border

**强制继承**

~~~css
h1 {
    border: inherit;
}
~~~

## 课程文件

https://github.com/komavideo/LearnCSS3

## 小马视频频道

http://komavideo.com
