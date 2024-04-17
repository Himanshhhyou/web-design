# Shrink & Expand

🖱️<a href="https://himanshhhyou.github.io/web-design/small-projects/shrink-expand/shrink-expand.html">Click here to see preview</a>


## HTML

<a href="shrink-expand.html">shrink-expand.html</a>

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Shrink & Expand</title>
  
  <!-- External Stylesheet -->
  <link rel="stylesheet" href="shrink-expand.css">
</head>

<body>
  <!-- Radio buttons for shrink and expand -->
  <input type="radio" name="btn" id="shrink">
  <label for="shrink">Shrink</label>
  <input type="radio" name="btn" id="expand">
  <label for="expand">Expand</label>
  <!-- Container div for the effect -->
  <div></div>
</body>

</html>
```
## CSS

<a href="shrink-expand.css">shrink-expand.css</a>

```css
   /* Hide the radio buttons */
   input {
     display: none;
   }

   /* Style for labels */
   label {
     display: inline-block;
     width: 100%;
     text-align: center;
     border: 1px solid #3F3F3F;
     padding: 20px 0;
     font-weight: 500;
     margin-bottom: 5px
   }

   /* Styling for the container */
   div {
     width: 100%;
     height: 500px;
     background-color: #585D70;
     transition: 2s;
   }

   /* Shrink effect when the #shrink radio is checked */
   #shrink:checked~div {
     height: 1px;
   }

   /* Expand effect when the #expand radio is checked */
   #expand:checked~div {
     height: 500px;
   }

   /* Button styling changes when #shrink radio is checked */
   #shrink:checked~label:nth-child(2) {
     background: #49B379;
     color: #fff;
   }

   /* Button styling changes when #expand radio is checked */
   #expand:checked~label:nth-child(4) {
     background: #49B379;
     color: #fff;
   }
```
Feel free to adjust the value of `transition: 2s;` on line 22 in the CSS to control the speed of the expand and shrink effects.
