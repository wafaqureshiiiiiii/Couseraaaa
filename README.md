<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Floating Elements</title>
<style>

div {
	background-color: #00FFFF;
}
p {
	width: 50px;
	height: 50px;
	border: 1px solid black;
}
#p1 {
	background-color: #A52A2A;
	float:left;
}
#p2 {
	background-color: #DEB887;
	float: right;
	height: 300;
}
#p3 {
	background-color: #5F9EA0;
	clear: right;

}
#p4 {
	background-color: #FF7F50;
}
section {
	clear: left;
}
</style>
</head>
<body>
<h1>Floating Elements</h1>

<div>
  <p id="p1"></p>
  <p id="p2"></p>
  <p id="p3"></p>
  <p id="p4"></p>
  <section>this is regular continuing after okkkk bye thnkou yours faithfully abc </section>

</div>
</body>
</html>
