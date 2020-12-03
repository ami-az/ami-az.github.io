---
title: Machine Learning Project
date: 2019-12-07 00:00:00 Z
author: Ami-AZ
layout: post
---

<h3>Bicycle Detection using Haar Cascade in OpenCV</h3>

<font color="black"><br>This segment will explain the specific procedures and techniques of my mini project which titled Bicycle Detection by using Haar Cascades features in OpenCV and how to implement it in the real-world environment.

Below are the steps and configurations in Ubuntu System including OpenCV and Python3 binding which have been installed properly.
1) Three folders were created which named data, positives and negatives in a directory.

2) 391 images of bicycles were put into positives folder, 4719 images of non-related to bicycle were put into negatives folder, while data folder was set empty.

3) Then train the cascade using the provided commands and annotate the positive images.

4) The sample was created and trained (Figure 1.0).

5) Cascade.xml which was created by the training process is put in the directory of the python program file.

<span class="image center"><img src="{{ 'assets/images/opencv/levelofstages.png' | relative_url }}" alt="Figure 1.0: Level of Stages" /></span>
Figure 1.0: Level of Stages

<br>In this mini project program, there are three different source code files in order to produce outputs from three different sources which are from images, video and webcam that is real world environment. Below are the figures of the source code files.
<br>
<span class="image center"><img src="{{ 'assets/images/opencv/imageofsourcecodes.png' | relative_url }}" alt="Figure 2.0: Image Source Codes" /></span>
Figure 2.0: Image Source Codes
<br>
<span class="image center"><img src="{{ 'assets/images/opencv/videosourcecodes.png' | relative_url }}" alt="Figure 3.0: Video Source Codes" /></span>
Figure 3.0: Video Source Codes
<br>
<span class="image center"><img src="{{ 'assets/images/opencv/webcamsourcecodes.png' | relative_url }}" alt="Figure 4.0: Webcam Source Codes" /></span>
Figure 4.0: Webcam Source Codes
