# CSS

## General

HTML file view:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Title</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Illum laboriosam perferendis temporibus fuga eos fugiat.</p>
    <div class="element">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque repellendus ullam pariatur commodi placeat temporibus?</div>
    <h4 id="title">Title 4</h4>
</body>
</html>
```

## Selectors

**\*** means for all tags:
```
* {
    color: blueviolet;
}
```
![](img/asterisk.jpg)

**h1**
```
h1 {
    color: blueviolet;
}
```
![](img/selector%20h1.jpg)

For a **class selector**, copy the name of the class and add a period in front:
```
.element {
    color: blueviolet;
}
```
![](img/selector%20class%20element.jpg)

For an **id selector**, copy the name of the id and add a hash in front:
```
#title {
    color: blueviolet;
}
```
![](img/selector%20id.jpg)

For a **tag**, copy the name of the tag (another div added):
```
div {
    color: blueviolet;
}
```
![](img/selector%20div.jpg)

For a **tag with specific attribute**, specify additionally the type of the attribute (or additionally its name) in brackets:
```
div[title] {
    color: blueviolet;
}
```
![](img/selector%20div%20title.jpg)

## Backgrounds

For a bachground color:
```
p {
    background-color: blueviolet;
}
```

For a background image:
```
<div class="logo"></div>
```
```
.logo {
    background-image: url(img/logo.png);
    background-repeat: no-repeat;
}
```
In order to go to a catalog higher, add **..** before slash.

To display the image, additional attributes are needed:
```
.logo {
    background-image: url(img/logo.png);
    background-repeat: no-repeat;
    height: 200px;
    width: 200px;
    border: 1px solid yellow;
}
```
![](img/logo%20background.jpg)



## Borders

Border creating:
```
p {
    color: black;
    border: 4px red dotted;
}
```
![](img/dotted%20background.jpg)

Border rounding:
```
p {
    color: black;
    border: 4px red dotted;
    border-radius: 10%;
}
```
![](img/dotted%20background%20rounded.jpg)

## Fonts
```
p {
    font-family: sans-serif;
    font-size: larger;
    font-weight: 800;
    line-height: 50px;
    text-align: end;
    text-decoration: underline;
    text-transform: capitalize;
}
```

![](img/font%20sans-serif.jpg)

For links, it is possible to remove the underline feature:
```
a {
    text-decoration: none;
}
```
![](img/link%20no%20decoration.jpg)

Text decoration for lists:
```
ul {
    list-style: square;
}
```
![](img/list%20decoration.jpg)





## Notes

In CSS, every active string ands with a semicolon.

The lower the string, the higher priority it has.

To view a list of items for choosing from: **CTRL + SPACE**.

To put multiple cursors at the same time: **ALT + left click**.

To create a UL with several links: **ul>li*3**.