## 导航：[2. CSS](../../2. CSS.md)

编写一个HTML页面，标签内容为：

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
        <div>1</div>
        <div>2</div>
        <div>3</div>
        <div>4</div>
        <div>5</div>
        <div>6</div>
    </div>

    <div class="container">
        <div>1</div>
        <div>2</div>
        <div>3</div>
        <div>4</div>
        <div>5</div>
        <div>6</div>
    </div>
</body>

</html>
```

## 要求

1.   所有包含`container`类的标签满足：
     -   `display`属性为`flex`；
     -   宽度为`50%`；
     -   高度为`500px`；
     -   背景颜色为`lightblue`；
     -   外边距为`10px`；
2.   所有`container`类标签的子标签满足：
     -   宽度与高度均为`120px`；
3.   所有`container`类标签的第奇数个子元素满足：
     -   背景颜色为：`lightsalmon`；
4.   所有`container`类标签的第偶数个子元素满足：
     -   背景颜色为`lightgreen`；
5.   第一个`container`类标签满足：
     -   `flex-wrap`属性为`wrap`；
     -   `justify-content`属性为`space-between`；
     -   `align-content`属性为`flex-start`；
6.   第二个`container`类标签满足：
     -   `flex-direction`属性为`row-reverse`；
     -   `flex-wrap`属性为`nowrap`；
7.   第二个`container`类标签的所有第奇数个子标签满足：
     -   `flex-grow`属性为`3`；
     -   `flex-shrink`属性为`3`；
8.   第二个`container`类标签的所有第偶数个子标签满足：
     -   `flex-grow`属性为`1`；
     -   `flex-shrink`属性为`1`；