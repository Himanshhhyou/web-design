[Back to home](../README.md)

# Colourful-text
Here, I'll show you how to change the color of individual letters in a word.
![colourful-text.png](colourful-text.png)

## HTML

> 🙋**Attention Here:**
 I utilize `Google Fonts` exclusively to switch the font family. Alternatively, you can select a different font or stick with the default one provided by your browser.

[colourful-text.html](colourful-text.html)
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <!-- Set character set and viewport for responsiveness -->
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Colourful Text</title>

  <!-- External Stylesheet -->
  <link rel="stylesheet" href="colourful-text.css">

  <!-- Preconnect to Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  
  <!-- Import and apply the 'Arizonia' font from Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Arizonia&display=swap" rel="stylesheet">
</head>

<body>
  <div>
    <!-- Individual spans for each letter with corresponding classes for colors -->
    <span class="l1">W</span>
    <span class="l2">E</span>
    <span class="l3">B</span><br>
    <span class="l4">D</span>
    <span class="l5">E</span>
    <span class="l6">S</span>
    <span class="l7">I</span>
    <span class="l8">G</span>
    <span class="l9">N</span>
  </div>
</body>
</html>
```

## CSS
[colourful-text.css](colourful-text.css)
``` css
/* Styling for the body */
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  font-family: arizonia, sans-serif;
  background: #01060A;
}

/* Styling for each individual letter */
span {
  font-size: 4em;
}

.l1 {
  color: #3142FF;
}

.l2 {
  color: #63DF0D;
}

.l3 {
  color: #FF31DC;
}

.l4 {
  color: #FF5C31;
}

.l5 {
  color: #F2F81D;
}

.l6 {
  color: #0C94DF;
}

.l7 {
  color: #31E9FF;
}

.l8 {
  color: #770CBC;
}

.l9 {
  color: #4FE316;
}
```

[Back to home](../README.md)
