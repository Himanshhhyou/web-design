# Table Tag
### Example 1
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Table Tag</title>
    </head>
    <body>
        <table border="1">
            <tr>
                <td>A</td>
            </tr>
        </table>
    </body>
</html>
```
**Output**

<!DOCTYPE html>
<html>
    <body>
        <table border="1" width="100%">
            <tr>
                <td>A</td>
            </tr>
        </table>
    </body>
</html>

### Example 2
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Table Tag</title>
    </head>
    <body>
        <table border="1">
            <tr>
                <td>A</td>
                <td>B</td>
            </tr>
        </table>
    </body>
</html>
```
**Output**

<!DOCTYPE html>
<html>
    <body>
        <table border="1" width="100%">
            <tr>
                <td>A</td>
                <td>B</td>
            </tr>
        </table>
    </body>
</html>

## Rowspan
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Rowspan</title>
    </head>
    <body>
       <table>
            <tr>
                <td rowspan="2">A</td>
                <td>B</td>
            </tr>
            <tr>
                <td>C</td>
            </tr>
       </table>
    </body>
</html>
```

<!DOCTYPE html>
<html>
    <body>
       <table border="1" width= "100%" height="200px">
            <tr>
                <td rowspan="2">A</td>
                <td>B</td>
            </tr>
            <tr>
                <td>C</td>
            </tr>
       </table>
    </body>
</html>


