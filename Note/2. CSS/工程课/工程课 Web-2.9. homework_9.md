## 导航：[2. CSS](../../2. CSS.md)

编写一个完整的HTML页面，标签内容为：

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
    <div class="container">
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="next-line"></div>
    </div>
</body>

</html>
```

## 要求

1.   包含`container`类的标签满足：
     -   宽度与高度均为`500px`；
     -   背景颜色为`lightblue`；
2.   包含`item`类的标签满足：
     -   宽度和高度均为`100px`；
     -   外边距为`10px`；
     -   背景颜色为`lightcoral`；
     -   `float`属性的值为`left`；
3.   包含`next-line`类的标签满足：
     -   宽度和高度均为`150px`；
     -   背景颜色为`rgba(0, 0, 255, 0.5)`；
     -   必须移动到之前的浮动元素的下面（使用`clear`属性）；