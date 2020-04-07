<!doctype html>
 <html>
 <head>
 <meta charset="utf-8">
 <title>MEDIA QUERIES</title>
 <style>
 h1
 {
 margin-bottom:15px
 }
 p {border:1px solid black;
 	margin-bottom: 15px
 }
 #p1 {
 	background-color: #FF0000;
 	width:300px;
 	height:300px;

 }
#p2{background-color:#39ff14 ;
 	width:70px;
 	height:70px;

}
@media (min-width: 1200px){
	#p1{width:80%;
	}
	#p2{width:150px; 
		height:150px;
	}
}



</style>
</head>
<body>
<h1>MEDIA QUERIES</h1>
<p id="p1"></p>
<p id="p2"></p>
</body>
</html>
