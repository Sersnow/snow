# snow
snow
<!DOCTYPE html>
<html lang="en">
<head>
<style>
	.block{
		width:280px;
		height:105px;
		display:block;
		background:#66CC99;
		padding:20px;
		padding-left: 40px;
		outline-style:solid;
		outline-color:#66CC99;

	}

.para{
		color:#888888;
		width:340px;
		height:40px;
		display: block;
		outline-style:solid;
		outline-color:#888888;
		outline-width:0.4px;
		line-height: 40px;
	}

.para:hover{
		background:	#FFF5EE;
		cursor:pointer;
	}
	
.circle{
		background:grey;
		width:65px;
		height:65px;
		float:left;
		border-radius: 50%;
	}

.circleimg{
	border-radius: 50%;
	position:relative;
	left:2.5px;
	top:2.5px;
}
.large{
		font-size: 20px;
		padding-left:30px;
	}

.style{
		padding:20px;
		padding-left:50px;
	}

.small{
		font-size: 10px;
		padding-left:30px;
	}

</style>
     <meta charset="UTF-8">
     <title>Myweb</title>
     <link rel="stylesheet" href="style.css">
     <link rel="stylesheet" type="text/css" href="./iconfont.css">
     <script src="./iconfont.js"></script>
</head>
<body> 	
	<div class="block">
	  	<p class="circle"><img class="circleimg" src="D:\照片\1-140F4142445.jpg" width="60" height="60"></p>
	  	<div class="style">
	     	<div class="large" style="font-family:verdana">Jonathan Smith</div>
	       	<div class="small">jsmith@flatlab.com</div>
	    </div>
	</div>
	<div>
		<div class="para"> <i class="iconfont icon--sick"></i> Mailinbox</div> 
		<div class="para">Recent activity</div>
		<div class="para">Notification</div>
		<div class="para">Message</div>
	</div>
    <script type="text/javascript"></script>
</body>
</html>
