---
title: Appearance-Based Gaze Estimation from Full Face Image
subtitle: Gaze Estimation, Attention Analysis, Deep Learning
summary: Gaze Estimation, Attention Analysis, Deep Learning
authors:
- admin
- Dong Zhang
# tags:
# - Academic
# - 开源
# categories:
# - Demo
date: "2019-09-20T00:00:00Z"
# lastmod: "2019-04-17T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 1
# caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## Abstract

In this work, We propose a method for estimating eye gaze direction from full face image with convolutional neural network. The majority of gaze estimation methods are based on optical phenomena like corneal reflection, which requires high resolution IR cameras to capture eye images. Instead of using high resolution IR cameras, we introduce an appearance-based gaze estimation method which can predict eye direction from face image captured by a webcam. Experimental results show that our method is robust to eye occlusion and different head poses. Compared with IR-based eye tracking methods, our method is easier to setup and has a larger detection range. We also present SYSUGaze, a RGB-D eye tracking dataset collected from 105 participants. Both 3D gaze annotations and head pose annotations are provided in this dataset. 


## Dataset
Appearance-based gaze estimation requires a rich dataset containing different face appearances and accurate gaze annotations. However, existing eye-tracking datasets are limited by either the variation of face appearance or the accuracy of gaze annotations. In this work, we present the SYSUGaze dataset we collected from 105 participants by RGB-D Cameras. The participants are asked to fix their gazes on a small point randomly shown on a computer monitor. The location of gaze points and face images are recorded. We provide gaze directions and head poses of each face image, which are automatically annotated by depth image. 
{{< figure src="datacollector.jpg" caption="Samples of SYSUGaze Dataset (left) and Data Collection (right)" numbered="true" >}}


## Demo
We test the proposed appearance-based eye tracking method in different cases. A white arrow is used to show the predicted eye gaze direction. Our prediction model shows good performance in case of eye occlusion and low image resolution. We design an interesting game where a space shooter is controlled by eye gaze. Besides, We also design an application which allows a user to insert password by eye gaze.

* Demo 1 (Eye Occulsion Case)
{{< video src="freegaze.mp4" controls="yes" >}}
* Demo 2 (Low Resolution Case)
{{< video src="low_resolution.mp4" controls="yes" >}}
* Demo 3 (Control Space Shooter by Eye Gaze)
{{< video src="game.mp4" controls="yes" >}}
* Demo 4 (Insert Password by Eye Gaze)
{{< video src="password.mp4" controls="yes" >}}