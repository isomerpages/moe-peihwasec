---
title: Example Title
permalink: /about-us/Departments/permalink/
description: ""
third_nav_title: Departments
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}


/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container"style="max-width: 1000px;
  position: relative;
  margin: auto;">

<div class="mySlides fade">
  <div class="numbertext" style="color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;">1 / 3</div>
  <img src="/images/eng1.png" style="width:100%">

</div>

<div class="mySlides fade">
  <div class="numbertext" style="color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;">2 / 3</div>
  <img src="/images/eng1.png" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext" style="color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;">3 / 3</div>
  <img src="/images/eng1.png" style="width:100%">
</div>

<a class="prev" style="cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;">❮</a>
<a class="next" style="cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;right: 0;
  border-radius: 3px 0 0 3px;">❯</a>

</div>
<br>

</body>
</html> 
