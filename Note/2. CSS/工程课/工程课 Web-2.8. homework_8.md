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
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div>10</div>
</body>

</html>
```

## 要求

1.   `body`的高度设为`2000px`，外边距设为`0`。
2.   所有`div`标签的样式设置为：
     -   宽度与高度均为`200px`；
     -   背景颜色设置为`lightblue`；
     -   外边距设置为`20px`；
3.   第一个`div`的`position`属性为`static`。
4.   第二个`div`的样式设置为：
     -   `position`的值为`relative`；
     -   `left`的值为`50px`；
     -   `top`的值为`15px`；
5.   第三个`div`的样式设置为：
     -   `position`的值为`absolute`；
     -   背景颜色为`rgba(0, 0, 255, 0.5)`；
     -   `left`的值为`30px`;
     -   `top`的值为`30px`；
6.   第四个`div`的样式设置为：
     -   `position`的值为`fixed`；
     -   背景颜色为`rgba(0, 255, 0, 0.5)`；
     -   `left`的值为`100px`；
     -   `top`的值为`250px`；
7.   第十个`div`的样式为：
     -   `position`的值为`sticky`；
     -   背景颜色为`rgba(255, 0, 0, 0.5)`；
     -   `bottom`的值为`10px`；