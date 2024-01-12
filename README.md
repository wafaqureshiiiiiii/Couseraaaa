<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"
<title>Media Queries</title>
<style>

h1 {
	margin-bottom: 15px;
}
p {
	border: 1px solid black;
	margin-bottom: 15px;
}
#p1 {
	background-color: #A52A2A;
	width: 300px;
	height: 50px;
}
#p2 {
	background-color: #5F9EA0;
	position: absolute;
	width: 150px;
	height: 150px;	
}
/********** Large devices only **********/
@media (min-width: 1200px) {
 #p1 {
 width: 80%;
 }
 #p2 {
 width: 150%;
 }
}
</style>
</head>
<body>
<h1> Media Queries</h1>
<div>
  <p id="p1"></p>
  <p id="p2"></p>
  <section>this is regular continuing after okkkk bye thnkou yours faithfully abc </section>

</div>
</body>
</html>
