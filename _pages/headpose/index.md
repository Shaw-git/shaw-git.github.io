---
title: "Accurate Head Pose Estimation Using Image Rectification and Lightweight Convolutional Neural Network"
subtitle: "Head Pose Estimation, Image Rectification, Convolutional Neural Networks"
summary: "Head Pose Estimation, Image Rectification, Convolutional Neural Networks"
layout: single
permalink: /headpose/
authors:
  - admin
  - Dong Zhang
date: "2020-07-20T00:00:00Z"
featured: false
draft: false

image:
  placement: 1
  focal_point: ""
  preview_only: false

projects: []
---

## Abstract

Head pose estimation is an important step for many human-computer interaction applications such as face detection, facial recognition, and facial expression classification. Accurate head pose estimation benefits these applications that require face image as the input. Most head pose estimation methods suffer from perspective distortion because users do not always align their face perfectly with the camera. This paper presents a new approach that uses image rectification to reduce the negative effect of perspective distortion and a lightweight convolutional neural network to obtain highly accurate head pose estimation. The proposed method calculates the angle between the camera optical axis and the projection vector of the face center. The face image is rectified using this estimated angle through perspective transformation. A lightweight network with the size of only 0.88 MB is designed to take the rectified face image as the input to perform head pose estimation. The output of the network, the head pose estimation of the rectified face image, is transformed back to the camera coordinate system as the final head pose estimation. Experiments on public benchmark datasets show that the proposed image rectification and the newly designed lightweight network remarkably improve the accuracy of head pose estimation. Compared with state-of-the-art methods, our approach achieves both higher accuracy and faster processing speed.

## Results

In order to evaluate the performance of our method, we adopted three commonly used head pose estimation datasets: the BIWI Dataset, the AFLW2000, and the 300W-LP Dataset. The experiment results show that our method outperformed the state-of-the-art methods in terms of accuracy.

{{< figure src="./result.png" caption="Size and Average Error Comparisons on the BIWI Dataset and the 300W-LP Dataset" numbered="true" >}}

<div class='paper-box'><div class='paper-box-image'><div><img src='_pages/headpose/result.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

**Appearance-Based Gaze Estimation from Full Face Image**

Gaze Estimation, Attention Analysis, Gaze-Computer Interaction

**Xiao Li**, Dong Zhang

[**Project Page**](https://shaw-git.github.io/eye-tracking/index)
</div>
</div>


To fully understand the performance of the proposed lightweight network, we conducted an experiment to test the processing speed of our network. We compared our network with three state-of-the-art networks with reasonably small model size.

{{< figure src="speed.png" caption="Model Size and Running Speed on NVIDIA GeForce GTX 1080Ti" numbered="true" >}}

## Demo

* Real-time test:  
  {{< video src="fast_headpose.mp4" controls="yes" >}}
