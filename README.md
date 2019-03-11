# calculatrice
code de calculatrice
<!DOCTYPE html>
<html>
 <meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width,initial-scale=1">

	<link rel="stylesheet" type="text/css" href="css/bootstrap.css">
    <link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
    <lin rel="stylesheet" type="text/css" href="css/bootstrap-theme.css">
    <link rel="stylesheet" type="text/css" href="css/bootstrap-theme.min.css">
    <link href="https://fonts.googleapis.com/css?family=Holtwood+One+SC" rel="stylesheet" type="test/css">
    <link rel="stylesheet" type="text/css" href="calculatrice.css">
<head>
	<title>calculatrice</title>
</head>
<h1 class="calculatrice"><i>caculatrice</i></h1>
<body class="calcul">
	<div class="calculator">
	 <div class="wrap">
		<form name="cal">
			<input type="text" name="display" class="saisir">
			<br></br>
			<input class="number" type="button" value="9" onclick="cal.display.value+='9'"><!-- cal.display.value+='9' permet de mettre le chiffre sur lequel on clique dans la barre d'ecriture du input-->
			<input class="number" type="button" value="8" onclick="cal.display.value+='8'">
			<input class="number" type="button" value="7" onclick="cal.display.value+='7'">
			<input class="number" type="button" value="+" onclick="cal.display.value+='+'">
			<br></br>
			<input class="number" type="button" value="6" onclick="cal.display.value+='6'">
			<input class="number" type="button" value="5" onclick="cal.display.value+='5'">
			<input class="number" type="button" value="4" onclick="cal.display.value+='4'">
			<input class="number" type="button" value="-" onclick="cal.display.value+='-'">
			<br></br>
			<input class="number" type="button" value="3" onclick="cal.display.value+='3'">
			<input class="number" type="button" value="2" onclick="cal.display.value+='2'">
			<input class="number" type="button" value="1" onclick="cal.display.value+='1'">
			<input class="number" type="button" value="*" onclick="cal.display.value+='*'">
			<br></br>
			<input class="number" type="button" value="0" onclick="cal.display.value+='0'">
			<input class="number" type="button" value="/" onclick="cal.display.value+='/'">
			<input class="number" type="button" value="%" onclick="cal.display.value+='%'">
			<input class="number" type="button" value="=" onclick="cal.display.value =eval(cal.display.value)"><!--cal.display.value =eval(cal.display.value) permet d'afficher le resultat de l'operation lorsqu'on click sur '='-->
			<br></br>
			<input class="number" type="button" value="DELETE" onclick="cal.display.value= ''"  id="del">
			<!--cal.display.value= '' est le delete permettant d'efface les valeurs-->
		</form>
	 </div>
	</div>

</body>
   <script scr="js/boostrap.js"></script>
   <script src="js/boostrap.min.js"></script>
   <script src="js/npm.js"></script>
   <script src="js/jquery.js"></script>
</html>
