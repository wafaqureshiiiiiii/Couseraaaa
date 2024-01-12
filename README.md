<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>
<style>

/********** Base styles **********/
* {
	box-sizing: border-box;
}
h1 {
	margin-bottom: 15px;
}
p {
	border: 1px solid black;
	background-color: #A52A2A;
	width: 90%;
	height: 150px;
	margin-right: auto;
	margin-left: auto;
	font-family: Helvetica;
	color: white;
}
/* Simple Responsive Framework. */
.row {
	width: 100%;
}
/********** Large devices only **********/
@media (min-width: 1200px) {
	.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5 {
	float: left;
	border: 1px solid green;
	}
	.col-lg-1 {
	width: 25%;
	}
	.col-lg-2 {
	width: 25%;
	}
	.col-lg-3 {
	width: 25%;
	}
	.col-lg-4 {
	width: 35%;
	}
	.col-lg-5 {
	width: 41%;
	}
	.col-lg-6 {
	width: 58%;
	}
}

/*********** Medium devices only**********/
@media (min-width: 950px) and (max-width: 1199px) {.col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-mmd-6 {
	float: left;
	border: 1px solid green;
}
.col-md-1 {
	width: 8.33%;
}
.col-md-2 {
	width: 16.66%;
}
.col-md-3 {
	width:25%;
}
.col-md-4 {
	width: 33%;
}
.col-md-5 {
	width: 41.66%;
}
.col-md-6 {
	width: 50%;
}
}
</style>
</head>
<body>
<h1> Responsive Layout </h1>

<div class="row">
  <div class="col-lg-3 col-md-6"><p>item 1 </p></div>
  <div class="col-lg-3 col-md-6"><p>item 2 </p></div>
  <div class="col-lg-3 col-md-6"><p>item 3 </p></div>
  <div class="col-lg-3 col-md-6"><p>item 4 </p></div>
  <div class="col-lg-3 col-md-6"><p>item 5 </p></div>
  <div class="col-lg-3 col-md-6"><p>item 6 </p></div>
</div>

</body>
</html>
