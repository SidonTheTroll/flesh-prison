# HTML
## Head 
### Headings 
```html 
<h1> Heading 1 </h1> 
<h2> Heading 2 </h2> 
<h3> Heading 3 </h3> 
<h4> Heading 4 </h4> 
<h5> Heading 5 </h5> 
<h6> Heading 6 </h6> 
```
## Styles 
1. Background color 
    - `<body style="background-color:powderblue;">`
2. Text color 
    - `<h1 style="color:blue;">`
    - `<p style="color:red;"`
3. Font style 
    - `<h1 style="font-family:papyrus;">`
    - `<p style="font-family:papyrus;">`
4. Font size 
    - `<h1 style="font-size:300%;">`
    - `<p style="font-size:150%;">`

### Style Tag 
- Used to insert style formatting in head tag 

```html 
<head>
    <style>
        body {background-color: powderblue;}
        h1 {color:red;}
        h2 {color:blue;}
        h3 {color:green;}
        h4 {color:yellow;}
        h5 {color:black;}
        h6 {color:cyan;}
    </style> 
<head>
```

## Formatting Elements 
- **Bold text:** `<b>`
- **Italic text:** `<i>`
- **Emphasized text:** `<em>`
- **Marked text:** `<mark>`
- **Smaller text:** `<small>`
- **Deleted text:** `<del>`
- **Inserted text:** `<ins>`
- **Subscript text:** `<sub>`
- **Superscript text:** `<sup>`

## Tables 
```html
<body>
    <table style="width:100%">
        <tr>
            <th>Name</th>
            <th>Branch</th>
            <th>Semister</th>
        </tr>
        <tr>
            <td>Alice</td>
            <td>Civil</td>
            <td>2nd</td>
        </tr>
        <tr>
            <td>Bill</td>
            <td>Mechanical</td>
            <td>4th</td>
        </tr>
    </table>
</body>
```

## List 
### Ordered List 
```html
<ol>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
</ol>
```

### Unordered List 
```html
<ul>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
</ul>
```

## Form 
```html 
<form action="/action_page.php">
    <label for="fname">First name:</label>
    <input type="text" name="fname" value="name"><br><br>
    <label for="Iname">Last name:</label>
    <input type="text" name="Iname" value="Iname"><br><br>
    <input type="submit" value="Submit">
</form>

<p>Click the "Submit" button and the form-data will be sent to a page on the server called "action_page.php"</p>
```

## Hyperlink 
```html
<a href="url">link text</a>
```

## Linking Image
```html 
<img src="./image.jpg">
```

# CSS
## Linking .css file to HTML 
```html 
<head>
    <link rel="stylesheet" href="styles.css">
</head>
```

## CSS File 
```css 
body {
    background-color: powderblue;
}
h1 {
    color: blue;
}
p {
    color: red;
}
```
