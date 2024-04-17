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
                <td>R1C1</td>
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
                <td>R1C1</td>
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
                <td>R1C1</td>
                <td>R1C2</td>
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
                <td>R1C1</td>
                <td>R1C2</td>
            </tr>
        </table>
    </body>
</html>

### Example 3
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Table Tag</title>
    </head>
    <body>
        <table border="1">
            <tr>
                <td>R1C1</td>
                <td>R1C2</td>
                <td>R1C3</td>
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
                <td>R1C1</td>
                <td>R1C2</td>
                <td>R1C3</td>
            </tr>
        </table>
    </body>
</html>


### Example 4
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Table Tag</title>
    </head>
    <body>
        <table border="1">
            <tr>
                <td>R1C1</td>
            </tr>
             <tr>
                <td>R2C1</td>
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
                <td>R1C1</td>
            </tr>
             <tr>
                <td>R2C1</td>
            </tr>
        </table>
    </body>
</html>

### Example 5
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Table Tag</title>
    </head>
    <body>
        <table border="1">
            <tr>
                <td>R1C1</td>
            </tr>
            <tr>
                <td>R2C1</td>
            </tr>
            <tr>
                <td>R3C1</td>
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
                <td>R1C1</td>
            </tr>
            <tr>
                <td>R2C1</td>
            </tr>
            <tr>
                <td>R3C1</td>
            </tr>
        </table>
    </body>
</html>

### Example 6
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Table Tag</title>
    </head>
    <body>
        <table border="1">
            <tr>
                <td>R1C1</td>
                <td>R1C2</td>
            </tr>
            <tr>
                <td>R2C1</td>
                <td>R2C2</td>
                </tr>
            <tr>
                <td>R3C1</td>
                <td>R3C2</td>
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
                <td>R1C1</td>
                <td>R1C2</td>
            </tr>
            <tr>
                <td>R2C1</td>
                <td>R2C2</td>
                </tr>
            <tr>
                <td>R3C1</td>
                <td>R3C2</td>
            </tr>
        </table>
    </body>
</html>

### Example 7
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Table Tag</title>
    </head>
    <body>
        <table border="1">
            <tr>
                <td>R1C1</td>
                <td>R1C2</td>
                <td>R1C3</td>
            </tr>
            <tr>
                <td>R2C1</td>
                <td>R2C2</td>
                <td>R2C3</td>
            </tr>
            <tr>
                <td>R3C1</td>
                <td>R3C2</td>
                <td>R3C3</td>
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
                <td>R1C1</td>
                <td>R1C2</td>
                <td>R1C3</td>
            </tr>
            <tr>
                <td>R2C1</td>
                <td>R2C2</td>
                <td>R2C3</td>
            </tr>
            <tr>
                <td>R3C1</td>
                <td>R3C2</td>
                <td>R3C3</td>
            </tr>
        </table>
    </body>
</html>


## Rowspan

### Example 1
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

**Output**

<!DOCTYPE html>
<html>
    <body>
       <table border="1" width= "100%">
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


### Example 2
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Rowspan</title>
    </head>
    <body>
       <table>
            <tr>
                <td>A</td>
                <td rowspan="2">B</td>
            </tr>
            <tr>
                <td>C</td>
            </tr>
       </table>
    </body>
</html>
```

**Output**

<!DOCTYPE html>
<html>
    <body>
       <table border="1" width= "100%">
            <tr>
                <td>A</td>
                <td rowspan="2">B</td>
            </tr>
            <tr>
                <td>C</td>
            </tr>
       </table>
    </body>
</html>

### Example 3
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Rowspan</title>
    </head>
    <body>
       <table>
            <tr>
                <td>A</td>
                <td rowspan="3">B</td>
            </tr>
            <tr>
                <td>C</td>
                <td>D</td>
                <td>E</td>
            </tr>
       </table>
    </body>
</html>
```

**Output**

<!DOCTYPE html>
<html>
    <body>
       <table border="1" width= "100%">
            <tr>
                <td>A</td>
                <td rowspan="2">B</td>
            </tr>
            <tr>
                <td>C</td>
            </tr>
       </table>
    </body>
</html>
