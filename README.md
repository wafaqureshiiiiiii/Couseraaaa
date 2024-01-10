<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8"
<title>The Box Model</title>
<style>
* {
	box-sizing: border-box;
}

body {
    margin: 0;
    padding: 0;
	background-color: gray;
}
#box {
	background-color: blue;
	padding: 10px 10px 10px 10px;
	border: 3px solid black;
	margin: 40px;
	width: 300px;
	margin-top: 50px;  
}
#content {
	background-color: #90EE90; //green
}

h1 {
	margin-bottom: 30px;
}

</style>
</head>
<body>

<h1>Box Model</h1>
<div id= "box">
  <div id= "content"> Lorem ipsum dolor sit amet, consectuer adipisicing elit.
  </div>
</div>

</body>
</html>
