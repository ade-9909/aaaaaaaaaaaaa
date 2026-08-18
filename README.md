<!DOCTYPE html>
<html>
<head>
<title>ADEDAPO</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/5/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1 {font-family: "Montserrat", sans-serif}
img {margin-bottom: -7px}
.w3-row-padding img {margin-bottom: 12px}
</style>
</head>
<body>

<!-- Sidebar -->
<nav class="w3-sidebar w3-black w3-animate-top w3-xxlarge" style="display:none;padding-top:150px" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-button w3-black w3-xxlarge w3-padding w3-display-topright" style="padding:6px 24px">
    <i class="fa fa-remove"></i>
  </a>
  <div class="w3-bar-block w3-center">
    <a href="#" class="w3-bar-item w3-button w3-text-grey w3-hover-black">About</a>
    <a href="#" class="w3-bar-item w3-button w3-text-grey w3-hover-black">Photos</a>
    <a href="#" class="w3-bar-item w3-button w3-text-grey w3-hover-black">Shop</a>
    <a href="#" class="w3-bar-item w3-button w3-text-grey w3-hover-black">Contact</a>
  </div>
</nav>

<!-- !PAGE CONTENT! -->
<div class="w3-content" style="max-width:1500px">

<!-- Header -->
<div class="w3-opacity">
<span class="w3-button w3-xxlarge w3-white w3-right" onclick="w3_open()"><i class="fa fa-bars"></i></span> 
<div class="w3-clear"></div>
<header class="w3-center w3-margin-bottom">
  <h1><b>LOVESTORY</b></h1>
  <p><b>A love story between Adedapo and Preye.</b></p>
  <p class="w3-padding-16"><button class="w3-button w3-black" onclick="myFunction()">Let's get the love started</button></p>
</header>
</div>

<!-- Photo Grid -->
<div class="w3-row" id="myGrid" style="margin-bottom:128px">
  <div class="w3-third">
    <img src="ade.jpg" style="width:100%">
    <img src="a8.jpg" style="width:100%">
    <img src="a13.png" style="width:100%">
    <img src="a3.jpg" style="width:100%">
    <img src="a16.png" style="width:100%">
    <img src="a5.jpg" style="width:100%">
  </div>

  <div class="w3-third">
    <img src="a2.jpg" style="width:100%">
    <img src="a6.jpg" style="width:100%">
    <img src="a4.jpg" style="width:100%">
    <img src="a9.jpg" style="width:100%">
    <img src="a10.jpg" style="width:100%">
    <img src="a20.jpg" style="width:100%">
  </div>

  <div class="w3-third">
    <img src="a15.png" style="width:100%">
    <img src="a11.jpg" style="width:100%">
    <img src="a14.png" style="width:100%">
    <img src="a17.jpg" style="width:100%">
    <img src="a7.jpg" style="width:100%">
    <img src="a21.jpg" style="width:100%">
  </div>
</div>

<h1 style="color: rgb(0, 0, 0); text-align: center;background-color:rgb(136, 177, 173);
   font-size: 200%; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; margin-bottom: 0;">
  Made with love for the person who makes my world a little brighter, every picture holds a memory, every moment with you is one i'll always treasure
</h1>

<!-- End Page Content -->
</div>

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin-top:128px"> 
  <i class="fa fa-facebook-official w3-hover-opacity"></i>
  <i class="fa fa-instagram w3-hover-opacity"></i>
  <i class="fa fa-snapchat w3-hover-opacity"></i>
  <i class="fa fa-pinterest-p w3-hover-opacity"></i>
  <i class="fa fa-twitter w3-hover-opacity"></i>
  <i class="fa fa-linkedin w3-hover-opacity"></i>
  <p class="w3-medium">Powered by <a href="https://sportybet.com" target="_blank" class="w3-hover-text-green">adedapooyewonola</a></p>
</footer>
 
<script>
// Toggle grid padding
function myFunction() {
  var x = document.getElementById("myGrid");
  if (x.className === "w3-row") {
    x.className = "w3-row-padding";
  } else { 
    x.className = x.className.replace("w3-row-padding", "w3-row");
  }
}

// Open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.width = "100%";
  document.getElementById("mySidebar").style.display = "block";
}

function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
</html>

