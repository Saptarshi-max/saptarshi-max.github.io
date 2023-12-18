---
title: My Artworks
description: 
  During my spare time, I love to try my hands on Digital illustrations and Concept Sketching. The software I use for designing are Affinity Designer, Affninty Photo, Sketchbook Pro, Blender, FreeCAD
no_third_column: false
---



<style>
* {
  box-sizing: border-box;
}
.row {
  display: flex;
}
/* Create three equal columns that sits next to each other */
.column {
  flex: 40.33%;
  padding: 5px;
}
.column img:hover {
  opacity: 1;
}
</style>
</head>
<body>

<h2>Sketches</h2>
<p></p>

<div class="row">
  <div class="column">
    <img src="/assets/img/gallery/plane.png" alt="Snow" style="width:100%">
  </div>

<div class="column column-1">
    <img src="/assets/blog_gallery/detective_conan.jpg" alt="Forest" style="width:100%">
  </div>
  <div class="column column-1-2">
    <img src="/assets/img/gallery/plane.png" alt="Mountains" style="width:100%">
  </div>
  <div class="column">
    <img src="/assets/img/gallery/plane.png" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="/assets/img/gallery/plane.png" alt="Mountains" style="width:100%">
  </div>
</div>

</body>
</html>

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;}

#myImg {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

/* Modal Content (image) */
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

/* Caption of Modal Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation */
.modal-content, #caption {  
  -webkit-animation-name: zoom;
  -webkit-animation-duration: 0.6s;
  animation-name: zoom;
  animation-duration: 0.6s;
}

@-webkit-keyframes zoom {
  from {-webkit-transform:scale(0)} 
  to {-webkit-transform:scale(1)}
}

@keyframes zoom {
  from {transform:scale(0)} 
  to {transform:scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
  .modal-content {
    width: 100%;
  }
}
</style>
</head>
<body>



<html>
<head>
<style>
body {margin:25px;}

div.polaroid {
  width: 80%;
  background-color: white;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  margin-bottom: 25px;
}

div.container {
  text-align: center;
  padding: 10px 20px;
}
</style>
</head>
<body>

<h2>Responsive Polaroid Images / Cards</h2>

<div class="polaroid">
  <img src="/assets/img/gallery/plane.png" alt="5 Terre" style="width:100%">
  <div class="container">
  <p>Cinque Terre</p>

  </div>
</div>

<div class="polaroid">
  <img src="/assets/img/gallery/plane.png" alt="Norther Lights" style="width:100%">
  <div class="container">
  <p>Northern Lights</p>

  </div>
</div>



</body>
</html>