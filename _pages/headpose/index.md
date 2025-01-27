---
# title: An Ultra-Lightweight Convolutional Neural Network for Head Pose Estimation
title: Accurate Head Pose Estimation Using Image Rectification and Lightweight Convolutional Neural Network
subtitle: Head Pose Estimation, Image Rectification, Convolutional Neural Networks
summary: Head Pose Estimation, Image Rectification, Convolutional Neural Networks
permalink: /headpose/
authors:
- admin
- Dong Zhang
# tags:
# - Academic
# - 开源
# categories:
# - Demo
date: "2020-07-20T00:00:00Z"
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

Head pose estimation is an important step for many human-computer interaction applications such as face detection, facial recognition, and facial expression classification. Accurate head pose estimation benefits these applications that require face image as the input. Most head pose estimation methods suffer from perspective distortion because the users do not always align their face perfectly with the camera. This paper presents a new approach that uses image rectification to reduce the negative effect of perspective distortion and a lightweight convolutional neural network to obtain highly accurate head pose estimation. The proposed method calculates the angle between the camera optical axis and the projection vector of the face center. The face image is rectified using this estimated angle through perspective transformation. A lightweight network with the size of only 0.88 MB is designed to take the rectified face image as the input to perform head pose estimation. The output of the network, the head pose estimation of the rectified face image, is transformed back to the camera coordinate system as the final head pose estimation. Experiments on public benchmark datasets show that the proposed image rectification and the newly designed lightweight network remarkably improve the accuracy of head pose estimation. Compared with state-of-the-art methods, our approach achieves both higher accuracy and faster processing speed.

## Results

In order to evaluate the performance of our method, we adopted three commonly used head pose estimation datasets, the BIWI Dataset, the AFLW2000 and the 300W-LP Dataset. The experiment results show that our method outperformed the state-of-the-art methods in terms of accuracy.
{{< figure src="result.png" caption="Size and Average Error Comparisons on the BIWI Dataset and the 300W-LP Dataset" numbered="true" >}}
In order to fully understand the performance of the proposed lightweight network, we conducted an experiment to test the processing speed of our network. We compared our network with three state-of-the-art networks with reasonably small model size.
{{< figure src="speed.png" caption="Model Size and Running Speed on NVIDIA GeForce GTX 1080Ti" numbered="true" >}}


## Demo

* Real-time test 
{{< video src="fast_headpose.mp4" controls="yes" >}}

