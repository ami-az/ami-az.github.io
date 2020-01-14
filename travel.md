---
title: Travel Trip
layout: post
icon: fa-book
order: 9
hide: true
published: true
---
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 10px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
.img {
  display: block;
  margin-left: auto;
  margin-right: auto;}
}
</style>
</head>
<body>

<h2>Images Side by Side</h2>
<p>How to create side-by-side images with the CSS float property:</p>

<div class="row">
  <div class="column">
    <img src="https://ami-az.github.io/assets/images/hpwall/aesthetic_road.jpg" style="width:100%" align="middle">
  </div>
  <div class="column">
    <img src="https://ami-az.github.io/assets/images/hpwall/aesthetic_road.jpg" style="width:100%">
  </div>
  <div class="column">
    <img src="https://ami-az.github.io/assets/images/hpwall/aesthetic_road.jpg" style="width:100%">
  </div>
</div>

</body>
</html>
