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
        <div class="inline-block-div">div-1</div>
        <div class="inline-block-div">div-2</div>
        <div class="inline-block-div">div-3</div>
        <br>
        <span>span-1</span>
        <span>span-2</span>
        <span>span-3</span>
        <br>
        <div class="block-div">
            123456789101112
        </div>
    </div>
</body>

</html>
```

## 要求

1.   包含`container`类的标签满足：
     -   `display`属性为`block`；
     -   宽度和高度均为`500px`；
     -   内边距为`10px`；
     -   外边距为`20px`；
     -   背景颜色为`lightblue`；
2.   包含`inline-block-div`类的标签满足；
     -   `display`属性为`inline-block`；
     -   宽度和高度均为`100px`；
     -   内边距为`10px`；
     -   外边距为`10px`；
     -   背景颜色为`blue`；
     -   字体颜色为`white`；
3.   所有`span`满足：
     -   display属性为`inline`；
     -   左右内边距为`10px`；
     -   左右外边距为`20px`；
     -   背景颜色为`bisque`；
     -   字体颜色为`green`；
4.   包含`block-div`类的标签满足；
     -   `display`属性为`block`；
     -   宽度和高度均为`100px`；
     -   内边距与外边距均为`10px`；
     -   背景颜色为`blue`；
     -   字体颜色为`white`；
     -   `overflow`属性为`hidden`；
     -   `text-overflow`属性为`ellipsis`；