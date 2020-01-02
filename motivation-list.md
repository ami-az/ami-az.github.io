---
title: Motivation List
layout: page
icon: fa-book
order: 3
published: true
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.container {
  position: relative;
  width: 50%;
}

.image {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  text-align: center;
}

.container:hover .image {
  opacity: 0.3;
}

.container:hover .middle {
  opacity: 1;
}

.text {
  background-color: #D291BC;
  color: white;
  font-size: 16px;
  padding: 16px 32px;
}
</style>
</head>
  
<div class="row">
 <div class="container">
  <a href="https://ami-az.github.io/study.html"><img src="assets/images/study.jpg" alt="Avatar" class="image" style="width:100%">
  <div class="middle">
    <div class="text">Study</div>
  </div>
  
<div class="container">
  <a href="https://ami-az.github.io/study.html"><img src="assets/images/lifestyle.jpg" alt="Avatar" class="image" style="width:100%">
  <div class="middle">
    <div class="text">Lifestyle</div>
  </div>
