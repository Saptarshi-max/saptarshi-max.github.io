---
layout: post
title: Wakabox

accent_color: '#ccc'
theme_color: '#ccc'
description: 
  Version 9.1 provides minor design changes, new features, and closes multiple issues.
invert_sidebar: true
---

- Table of Contents
{:toc}

## data 

<div class="img-hover-zoom">
  <img src="\assets\icons\icon-96x96.png" alt="This zooms-in really well and smooth">
</div>

/* [1] The container */
.img-hover-zoom {
  height: 300px; /* [1.1] Set it as per your need */
  overflow: hidden; /* [1.2] Hide the overflowing of child elements */
}
## some more data
/* [2] Transition property for smooth transformation of images */
.img-hover-zoom img {
  transition: transform .5s ease;
}

/* [3] Finally, transforming the image when container gets hovered */
.img-hover-zoom:hover img {
  transform: scale(1.5);
}

<style>
@import 'https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css';
</style>
