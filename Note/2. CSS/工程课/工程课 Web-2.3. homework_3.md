## 导航：[2. CSS](../../2. CSS.md)

编写一个完整的HTML页面，标签内容如下：

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <div></div>
    <div></div>
    <div></div>
    <div></div>
</body>

</html>
```

## 要求

1.   所有`div`标签的宽度和高度均设置为`300px`，外边距设置为`10px`。
2.   第一个`div`的背景颜色设置为`lightblue`。
3.   第二个`div`的背景图片设置为`url('/static/images/mountain.jpg')`，背景图片大小设置为`100% 100%`，背景图片不重复。
4.   第三个`div`的背景图片设置为`url('/static/images/mountain.jpg'), url('/static/images/logo.png')`，背景图片大小设置为`50% 100%, 50% 100%`，两张背景图片均不重复，两张背景图片的位置设置为`top left, 150px 0`。
5.   第四个`div`的背景图片设置为`url('/static/images/mountain.jpg')`，背景图片大小设置为`100% 100%`，背景图片不重复，背景图片的位置在视口内固定。