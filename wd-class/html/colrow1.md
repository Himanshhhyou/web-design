## Colspan & Rowspan 1
[colrow1.html](colrow1.html)
```html



<!Doctype HTML>
<html>
	<head>
		<title>colrow1</title>
		<style>
			td{
				height: 100px;
				width: 100px;
			}
		</style>
	</head>
	<body>
		<table border="1">
			<tr>
				<td>A</td>
				<td rowspan="2">B</td>
				<td>C</td>
			</tr>
            		<tr>
				<td>D</td>
				<td>E</td>
			</tr>
            		<tr>
				<td>F</td>
				<td colspan="2">G</td>		
			</tr>
		</table>
	</body>
</html>
```

## Output
![](img/colrow1.png)
