## 文字替換
```
<!DOCTYPE HTML>
<HTML>
	<head>
		<meta charset="utf-8">
		<title>Java script</title>
		<script language="javascript">
		function test()
			{
			document.getElementById("demo").innerHTML = "changed.";
	
			}
		</script>
	</head>
	<body>
	<h1>test</h1>
	<p id="demo">123</p>
	<button type="button" onclick="test()">Try it</button>
	</body>
</HTML>
```
