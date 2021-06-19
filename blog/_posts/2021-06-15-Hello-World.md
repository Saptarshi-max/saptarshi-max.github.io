---
layout: post
title: Hello World

accent_color: '#ccc'
theme_color: '#ccc'
description: 
  Version 9.1 provides minor design changes, new features, and closes multiple issues.
invert_sidebar: true
---

Just to check ...
this is some texts.
This one is blog
Hello world post 
While this tutorial was written with Windows in mind, the only difference per platform is how you install Jekyll and file paths. {:.note}

<button class="btn btn-sm btn-primary" onclick=" window.open('https://github.com/TsekNet/PowerShell-Profile','_blank')" value="View Source on Github">
  <small class="icon-github"></small> View Source on Github
</button>

<div class="card" style="width: 18rem;">
  <img class="card-img-top" src="..\assets\img\nse-4597171921142844804-2106.jpg" alt="Card image cap">
  <div class="card-body">
    <h5 class="card-title">Card title</h5>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="btn btn-primary">Go somewhere</a>
  </div>
</div>

 <style>
  
.zoom {
  padding: 50px;
  background-color: red;
  <img src="C:\\Users\\sapta\\OneDrive\\Desktop\\Ccodes\\saptarshi-max.github.io\\saptarshi-max.github.io\\assets\\img\\me.jpg" alt="Avatar" style="width:100%">
  transition: transform .2s; /* Animation */
  width: 300px;
  height: 300px;
  margin: 0 auto;
}

.zoom:hover {
  transform: scale(1.5); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
}
</style>

<div class="zoom"></div> 

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {box-sizing: border-box;}

.img-zoom-container {
  position: relative;
}

.img-zoom-lens {
  position: absolute;
  border: 1px solid #d4d4d4;
  /*set the size of the lens:*/
  width: 40px;
  height: 40px;
}

.img-zoom-result {
  border: 1px solid #d4d4d4;
  /*set the size of the result div:*/
  width: 300px;
  height: 300px;
}
</style>
<script>
function imageZoom(imgID, resultID) {
  var img, lens, result, cx, cy;
  img = document.getElementById(imgID);
  result = document.getElementById(resultID);
  /*create lens:*/
  lens = document.createElement("DIV");
  lens.setAttribute("class", "img-zoom-lens");
  /*insert lens:*/
  img.parentElement.insertBefore(lens, img);
  /*calculate the ratio between result DIV and lens:*/
  cx = result.offsetWidth / lens.offsetWidth;
  cy = result.offsetHeight / lens.offsetHeight;
  /*set background properties for the result DIV:*/
  result.style.backgroundImage = "url('" + img.src + "')";
  result.style.backgroundSize = (img.width * cx) + "px " + (img.height * cy) + "px";
  /*execute a function when someone moves the cursor over the image, or the lens:*/
  lens.addEventListener("mousemove", moveLens);
  img.addEventListener("mousemove", moveLens);
  /*and also for touch screens:*/
  lens.addEventListener("touchmove", moveLens);
  img.addEventListener("touchmove", moveLens);
  function moveLens(e) {
    var pos, x, y;
    /*prevent any other actions that may occur when moving over the image:*/
    e.preventDefault();
    /*get the cursor's x and y positions:*/
    pos = getCursorPos(e);
    /*calculate the position of the lens:*/
    x = pos.x - (lens.offsetWidth / 2);
    y = pos.y - (lens.offsetHeight / 2);
    /*prevent the lens from being positioned outside the image:*/
    if (x > img.width - lens.offsetWidth) {x = img.width - lens.offsetWidth;}
    if (x < 0) {x = 0;}
    if (y > img.height - lens.offsetHeight) {y = img.height - lens.offsetHeight;}
    if (y < 0) {y = 0;}
    /*set the position of the lens:*/
    lens.style.left = x + "px";
    lens.style.top = y + "px";
    /*display what the lens "sees":*/
    result.style.backgroundPosition = "-" + (x * cx) + "px -" + (y * cy) + "px";
  }
  function getCursorPos(e) {
    var a, x = 0, y = 0;
    e = e || window.event;
    /*get the x and y positions of the image:*/
    a = img.getBoundingClientRect();
    /*calculate the cursor's x and y coordinates, relative to the image:*/
    x = e.pageX - a.left;
    y = e.pageY - a.top;
    /*consider any page scrolling:*/
    x = x - window.pageXOffset;
    y = y - window.pageYOffset;
    return {x : x, y : y};
  }
}
</script>
</head>
<body>

<h1>Image Zoom</h1>

<p>Mouse over the image:</p>

<div class="img-zoom-container">
  <img id="myimage" src="/assets/img/me2.jpg" width="300" height="240">
  <div id="myresult" class="img-zoom-result"></div>
</div>

<p>The image must be placed inside a container with relative positioning.</p>
<p>The result can be put anywhere on the page, but must have the class name "img-zoom-result".</p>
<p>Make sure both the image and the result have IDs. These IDs are used when a javaScript initiates the zoom effect.</p>

<script>
// Initiate zoom effect:
imageZoom("myimage", "myresult");
</script>

</body>
</html>
