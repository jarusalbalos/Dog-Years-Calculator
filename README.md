# Dog-Years-Calculator
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<meta name=viewport" content="initial-scale=1, maximum-scale=1, user-scalable=no, width= device-width">
		<title>Dog Years Calculator</title>
		<script>
		window.onload=function()
		{
			document.getElementById('btnCalc').addEventListener('click', calcAge);
		}
	function calcAge(e)
	{
		   var age=document.getElementById('dogAge').value;
		   age = age *7;
		   var result="In dog years, your dog is: " + age;
		   	document.getElementById('result').innerHTML = result;
	}
	
		</script>
		
	</head>
	<body bgcolor="yellow">
			<script type="text/javascript" src="cordova.js"></script>
			<h1>Dog Years Calculator</h1>
			<label for="dogAge">Dog Age in Human Years:</label>
			<input id="dogAge" type="number" />
			<button id="btnCalc">Calculate</button>
			<div id="result"></div>
			

	</body>
</html>
