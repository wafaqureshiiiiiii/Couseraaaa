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
	padding: 10px;
	border: 3px solid black;
	margin: 40px;
	width: 300px;
	height: 50px;
	margin-top: 50px;  
	overflow: visible;
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
  <div id= "content"> Lorem ipsum dolor sit amet, consectuer adipisicing elitfff ok ok fine i love myself im wafa qureshi. and i know that im fine ill be fine soon in sha allah.
  </div>
</div>

</body>
</html>
