<!DOCTYPE html>
<html>
<head>
<script src="Script.js"></script>
<meta charset="UTF-8">
<link rel="stylesheet" type="text/css" href="style.css">
<title>Gra - 2048</title>

<h1>Gra - 2048</h1>
<p1> Twoja liczba punkt�w: </p1>
<p1 id="Points"> 4 </p1>
<br>
<p2> Czas gry: </p2>
<p2 id="PlayTime"> 0 s.</p2>
<button id= "Restart" type="button" style="width: 100px; height: 40px; position: absolute; top: 540px; left:10px" onclick="Restart()">Od nowa</button>
</head>
<body>

<input id="1x1" class="box row1" style="row1; left: 5px" disabled><br>
<input id="1x2" class="box row1" style="left: 105px" disabled><br>
<input id="1x3" class="box row1" style="left: 205px" disabled><br>
<input id="1x4" class="box row1" style="left: 305px" disabled><br>
<input id="2x1" class="box row2" style="left: 5px" disabled><br>
<input id="2x2" class="box row2" style="left: 105px" disabled><br>
<input id="2x3" class="box row2" style="left: 205px" disabled><br>
<input id="2x4" class="box row2" style="left: 305px" disabled><br>
<input id="3x1" class="box row3" style="left: 5px" disabled><br>
<input id="3x2" class="box row3" style="left: 105px" disabled><br>
<input id="3x3" class="box row3" style="left: 205px" disabled><br>
<input id="3x4" class="box row3" style="left: 305px" disabled><br>
<input id="4x1" class="box row4" style="left: 5px" disabled><br>
<input id="4x2" class="box row4" style="left: 105px" disabled><br>
<input id="4x3" class="box row4" style="left: 205px" disabled><br>
<input id="4x4" class="box row4" style="left: 305px" disabled><br>
</body>
</html>
<script>
document.getElementById("1x1").value=2;
document.getElementById("1x2").value=2;
document.onkeydown = checkKey;
</script>