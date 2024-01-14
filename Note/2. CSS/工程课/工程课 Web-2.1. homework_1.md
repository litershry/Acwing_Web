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
    <div class="small-div">1</div>
    <div id="big-div">2</div>
    <div>3</div>
    <div class="small-div">4</div>
    <div class="small-div hover-div">5</div>
    <div>6</div>
    <div>7</div>
    <div class="hover-div">8</div>
    <div>9</div>
    <div>10</div>
</body>

</html>
```






## 要求

1.   所有`div`标签的字体颜色设置为`white`，宽度和高度均设置为`300px`。
2.   从前往后数，第奇数个`div`的背景颜色设置为：`#0000FF`。
3.   从前往后数，第偶数个`div`的背景颜色设置为：`rgba(255, 0, 0, 0.7)`。
4.   所有包含`small-div`类的`div`的宽度和高度均设置为`200px`。
5.   `id`为`big-div`的`div`的宽度和高度均设置为`400px`。
6.   对于所有包含`hover-div`类的`div`，当鼠标悬浮时，背景颜色变成`orange`。

