<!doctype html>
<html lang="en-us">
<head>
	<meta charset="UTF-8">
	<title>V + P Advent Calendar</title>
	<link rel="icon" type="image/x-icon" href="images/favicon.ico">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
	body {
	background-image: url("images/bg.jpg");
	background-repeat: no-repeat;
	background-attachment: fixed;
	background-size: cover;
	}
	.button {
		background-color: #04AA6D;
		border: none;
		color: white;
		padding: 15px 32px;
		text-align: center;
		text-decoration: none;
		display: inline-block;
		font-size: 20px;
		margin: 4px 2px;
		transition-duration: 0.4s;
		cursor: pointer;
	}
	.button1 {
		background-color: white;
		color: black;
		border: 2px solid #04AA6D;
	}
	.button1:hover {
		background-color: #04AA6D;
		color: white;
	}
</style>

</head>

<body>

<div style="text-align:center">
	
<video id="door_24" width="100%">
	<source src="images/door_24.mp4" type="video/mp4">
	Browser not supported - Contact your boyfriend
</video>
<br><br>
<button id="button1" class="button button1" onclick="playPause()"10
>Open</button>
</div>

<script>
var myVideo = document.getElementById("door_24"); 

function playPause() { 
  if (myVideo.paused) 
    myVideo.play(); 
  else 
    myVideo.pause();
} 
</script>

-->

</body>
</html>
