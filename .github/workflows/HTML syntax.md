# HTML

## Key combinations
Lorem text: enter **lorem#(number)**

Toggle word wrap: **ALT + Z**

Seeing all the proposed items: **CTRL + space**

Copying elemnts: **ALT + SHIFT + down arrow**

Sevetal cursors: hold **ALT** and left-click

Commentary (not visible on the actual webpage): **CTRL + /** (same for “disommenting”)
```
    <!-- Commentary -->
```

Developer tools in Chrome: **F12**

## General Tags

Template HTML page: enter **!**
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## Connecting tags

Tag **\<link>** for connecting outside files (CSS styles, fonts, JavaScript codes):
```
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
```

Tag **\<img>** for connecting images:
```
<img src="img/logo.png" alt="">
```

Tag **\<script>** for connecting scripts:
```
<script src="main.js"></script>
```

## List tags

Tag **\<ol>** for ordered lists:
```
<ol>
    <li>lorem</li>
    <li>lorem</li>
</ol>
```
![](img/ol.jpg)

Tag **\<ul>** for marked lists:
```
<ul>
    <li>lorem</li>
    <li>lorem</li>
</ul>
```
![](img/ul.jpg)

Tag **\<a>** for hyperlinks or other files:
```
<a href="http://youtube.com">Go to Youtube</a>
<a href="Markdown syntax.md">Go to Markdown</a>
```

## Table tags

```
    <table border="2">
        <caption>Name of the table</caption>
        <tr>
            <td>lorem</td>
            <td>lorem</td>
            <td>lorem</td>
        </tr>
        <tr>
            <td>lorem</td>
            <td>lorem</td>
            <td>lorem</td>
        </tr>
    </table>
```

![](img/table.jpg)

## Block, line, heading tags

Tag **\<div>** for separate blocks and creating paragraphs:
```
<div>Lorem ipsum dolor, <div>sit amet</div> consectetur adipisicing elit.</div>
```
![](img/div.jpg)

Tag **\<span>** for creating separate line sections:
```
<div>Lorem ipsum dolor, <span>sit amet</span> consectetur adipisicing elit.</div>
```
![](img/span.jpg)

Tag **\<hr>** for a separating line:
```
<div>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</div>
<hr>
```
![](img/hr.jpg)

Tag **\<p>** for paragraphs (with embedded spaces):
```
<div>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</div>
<div>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</div>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
```
![](img/p.jpg)

Tags **\<h1>**, **\<h2>**, **\<h3>**, **\<h4>**, **\<h5>**, **\<h6>** for titles:
```
<h1>Title</h1>
<h2>Title</h2>
<h3>Title</h3>
<h4>Title</h4>
<h5>Title</h5>
<h6>Title</h6>
```
![](img/h.jpg)

## Form tags

Tag **\<button>**:
```
<form action="">
    <button>Button</button>
</form>
```
![](img/button.jpg)

Tag **\<input>**:
```
<form action="">
    <input type="text">
    <input type="button">
    <input type="button" value="Button">
    <input type="checkbox" name="" id="">
    <input type="color" name="" id="">
    <input type="date" name="" id="">
    <input type="email" name="" id="">
    <input type="number" name="" id="">
    <input type="password" name="" id="">
    <input type="radio" name="" id="">
    <input type="range" name="" id="">
    <input type="time" name="" id="">
    <input type="file" name="" id="">
</form>
```
![](img/input.jpg)

Tag **\<textarea>**:
```
<form action="">
    <textarea name="" id="" cols="30" rows="10"></textarea>
</form>
```
![](img/textarea.jpg)

Tag **\<select>**:
```
<form action="">
    <select name="" id="">
        <option value="">Option</option>
        <option value="">Option</option>
        <option value="">Option</option>
    </select>
</form>
```
![](img/select.jpg)

## Universal attributes

Attribute **hidden**:
```
Lorem ipsum dolor sit amet consectetur, adipisicing elit. <div hidden>Tenetur possimus corrupti iste molestiae dolore blanditiis.</div>
Lorem ipsum dolor sit amet consectetur, adipisicing elit. <div hidden="hidden">Tenetur possimus corrupti iste molestiae dolore blanditiis.</div>
```
![](img/hidden.jpg)

Attribute **title** for hints:
```
Lorem ipsum dolor sit amet consectetur, adipisicing elit. <div title="Title">Tenetur possimus corrupti iste molestiae dolore blanditiis.</div>
```
![](img/title.jpg)

Attributes **class** and **id** (there can be many items of the same class, but ids are unique) (several classes can be written with spaces):
```
<div class="class1 class2" id="id1">Lorem ipsum dolor sit amet consectetur.</div>
<div class="class1" id="id2">Lorem ipsum dolor sit amet consectetur.</div>
```

## Special symbols
```
<div>&rarr; &larr; &uarr; &darr; &harr;</div>
<div>&bull; &ndash; &mdash; &sect; &copy; &times;</div>
```
![](img/special%20symbols.jpg)

## Colors
```
<body bgcolor="green">
<body bgcolor="#00ff00">
```