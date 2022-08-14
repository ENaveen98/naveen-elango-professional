---
slides: example
url_pdf: ""
summary: Industrial Research Project in collaboration with Advanced
  Manufacturing Technology Development Centre (AMTDC), IIT Madras Research Park.
url_video: ""
date: 2022-08-14T11:09:23.113Z
external_link: ""
url_slides: ""
title: Vision based Framework for Conversion of Engineering Drawings to Vector
  based Format for CAD Applications
tags:
  - CV
links:
  - icon: fa-accessible-icon
    icon_pack: null
    name: Poster
    url: https://drive.google.com/file/d/1groMt1-iApnMq7fW6wz9pVO2rya4o5VW/view?usp=sharing
image:
  caption: ""
  focal_point: ""
url_code: ""
---
The conversion of manual engineering drawing images to vectorized computer aided design format is a problem that has been hugely tackled using traditional approaches in the 1990s that are considered locally optimal. In this work a Computer Vision based framework is proposed, as opposed to traditional methods, that is both highly efficient in run-time and precise in representation of the overall drawing, as opposed to being compute intensive and highly local optimal solutions.

The conversion is done through a series of preprocessing morphological operations such as Median & Bilateral filtering, Erosion, Dilation and Skeletonization for cleaning the image, followed by novel algorithms such as FAST line detection, Hough Circle Transform and Elliptic & Line Segment Detection along with our improvements for detecting features such as lines, circles and arcs that represent the drawing.

Through this project a new 2-stage Improved Hough Circle Transform Algorithm is introduced that performs significantly better than the vanilla version in detection of Circles with minimal hyperparameter tuning. An evaluation metric called Root Mean Squared in Distance (RMSD) is defined in the Image Space for quantifying the performance of the conversion results and how various factors such as noise and complexity of the drawing affect the conversion process is discussed. The framework is tested on several engineering drawing images and the results along with aspects such as efficacy and efficiency are reported and the run-times of the algorithms are presented.

Given an image of a drawing with an orthographic view, the Framework converts it into a vector-based format which is compatible with any CAD software. The benefits for doing this include the capability to edit and modify the drawing in any CAD system. Also, when three such orthographic views are given in an image, they could all be converted to vector-based format using the same Framework. After doing so, several of the 3D CAD applications can be directly applied on these such as 3D modelling, surface and mesh modelling, finite element analysis and so on.