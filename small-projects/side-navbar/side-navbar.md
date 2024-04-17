[Back to home](../README.md)

# Side Navigation bar

![side-navbar](side-navbar.png)

Here, I use `Font Awesome` for icons and `W3CSS` for styling to enhance visual appeal.

### CDN Link for Font Awesome
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
```

### CDN link for W3CSS
```html
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
```


## Source Code
### HTML

[side-navbar.html](side-navbar.html)

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <!-- Document metadata -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
 
  <!-- Title for the web page -->
  <title>Side Navigation</title>
  
  <!-- Font awesome icons CDN -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

  <!-- W3CSS CDN -->
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  
  <!-- External CSS -->
  <link rel="stylesheet" href="side-navbar.css">
</head>

<body>
  <!-- Sidebar container with W3CSS styling -->
  <div class="sidebar w3-green w3-container w3-padding">
    <!-- Font Awesome icons in the sidebar -->
    <i class="fa fa-home"></i>
    <i class="fa fa-star"></i>
    <i class="fa fa-rocket"></i>
    <i class="fa fa-globe"></i>
    <i class="fa fa-lightbulb"></i>
    <i class="fa fa-smile"></i>
  </div>
</body>

</html>
```

### CSS

[side-navbar.css](side-navbar.css)

``` css
/* Sidebar styling */
.sidebar {
  width: 50px;
  height: 100vh;
}

/* Font Awesome icon styling */
.fa {
  color: #fff;
  margin-bottom: 30px;
  font-size: 20px;
  display: block;
}
```

[Back to home](../README.md)
