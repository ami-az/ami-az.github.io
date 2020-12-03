---
title: Machine Learning Project
date: 2019-12-07 00:00:00 Z
author: Ami-AZ
layout: post
---

<h3>Bicycle Detection using Haar Cascade in OpenCV</h3>

<br><font color="black">This segment will explain the specific procedures and techniques of my mini project which titled Bicycle Detection by using Haar Cascades features in OpenCV and how to implement it in the real-world environment.</font>

Below are the steps and configurations in Ubuntu System including OpenCV and Python3 binding which have been installed properly.

1) Three folders were created which named data, positives and negatives in a directory.

2) 391 images of bicycles were put into positives folder, 4719 images of non-related to bicycle were put into negatives folder, while data folder was set empty.

3) Then train the cascade using the provided commands and annotate the positive images.

4) The sample was created and trained (Figure 1.0).

5) Cascade.xml which was created by the training process is put in the directory of the python program file.

<span class="image center"><img src="{{ 'assets/images/opencv/levelofstages.png' | relative_url }}" alt="Figure 1.0: Level of Stages" /></span>
<br>Figure 1.0: Level of Stages

In this mini project program, there are three different source code files in order to produce outputs from three different sources which are from images, video and webcam that is real world environment. Below are the figures of the source code files.

<span class="image center"><img src="{{ 'assets/images/opencv/imageofsourcecodes.png' | relative_url }}" alt="Figure 2.0: Image Source Codes" /></span>
<br>Figure 2.0: Image Source Codes

<span class="image center"><img src="{{ 'assets/images/opencv/videosourcecodes.png' | relative_url }}" alt="Figure 3.0: Video Source Codes" /></span>
<br>Figure 3.0: Video Source Codes

<span class="image center"><img src="{{ 'assets/images/opencv/webcamsourcecodes.png' | relative_url }}" alt="Figure 4.0: Webcam Source Codes" /></span>
<br>Figure 4.0: Webcam Source Codes

   <hr />
  <h3 align="center">Results Demonstration</h3>
  <br>
  <span class="image center"><img src="{{ 'assets/images/opencv/1.png' | relative_url }}" alt="" /></span>
  <span class="image center"><img src="{{ 'assets/images/opencv/2.png' | relative_url }}" alt=" /></span>
  <span class="image center"><img src="{{ 'assets/images/opencv/3.png' | relative_url }}" alt="" /></span>

  <br>
  <style>
  @media only screen and (max-width: 767px) {

.video-container {
position: relative;
padding-bottom: 56.25%;
padding-top: 30px; height: 0; overflow: hidden;
}
 
.video-container iframe,
.video-container object,
.video-container embed {
position: absolute;
top: 0;
left: 0;
width: 100%;
height: 100%;
}
  }
</style>

<div class="video-container"><iframe width="560" height="315" src="https://www.youtube.com/embed/hdWmrjy6T3s" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe></div>

