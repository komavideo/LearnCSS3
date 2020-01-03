颜色指定方式
============

## 知识点

CSS颜色指定方式

* 颜色名：red, blue, green, ...
* rgb：rgb(255, 0, 128), #ff0080
* hsl：hsl(0, 50%, 50%)
  + Hue:色调,0(或360)表示红色,120表示绿色,240表示蓝色,也可取其他数值来指定颜色。取值:0 - 360
  + Saturation:饱和度,取值:0.0% - 100.0%
  + Lightness:亮度,取值:0.0% - 100.0%
* 透明度：rgba(255, 0, 0, 1), hsla(120, 50%, 50%, 1)

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
    <h1>颜色指定方式</h1>
</body>
</html>
~~~

### style.css

~~~css
h1 {
    line-height: 128px;
    color: white;
    background-color: red;
    /* background-color: rgb(255, 0, 128); */
    /* background-color: hsl(0, 50%, 50%); */
    /* background-color: rgba(255, 0, 128, 1); */
    /* background-color: hsla(0, 50%, 50%, 1); */
}
~~~

## 课程文件

https://github.com/komavideo/LearnCSS3

## 小马视频频道

http://komavideo.com
