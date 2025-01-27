---
title: Real-Time 3D Hand Pose Estimation with Deep Heatmap-Based Network.
subtitle: Hand-Computer Intection, Deep Learning, Hand Pose Estimation.
summary: Hand-Computer Intection, Deep Learning, Hand Pose Estimation.
permalink: /hand-computer-interaction/
authors:
- admin
- Hui Hu
# tags:
# - Academic
# - 开源
# categories:
# - Demo
date: "2021-07-20T00:00:00Z"
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

Gesture-based interaction holds a great potential for VR applications and robotics. 3D hand pose estimation from images is a long-standing and challenging problem. This work aims to obtain 3D reconstruction of hands and manipulate objects in VR by 3D hands. We propose a two-step approach to estimate 3D mesh of a hand, given egocentric images. Step one tackles the problem of estimating hand keypoints from egocentric hand images. We design a deep heatmap-based convolutional neural network to extract features from hand images, generating 3D hand skeleton. The hand skeleton is utilized in step two which converts hand skeleton to 3D hand mesh. We build a hand keypoints dataset with the size of 800K+ images, which we call XRhand. All images in XRHand are labelled with 21 hand keypoints. Our method shows accurate estimation and smooth tracking of hand gestures.

## Dataset
Training computers to understand human gesture requires a rich dataset containing complex hand pose and shape. We capture the motion of human hands with 10 synchronized gray cameras and 2 depth cameras (Kinect Azure) and build a large scale hand keypoints dataset. In order to label the keypoints of hand images, we reconstruct the 3D structure of human hands by depth images. 21 hand keypoints are extracted from 3D hand mesh and further projected to the image plane of each camera. Some samples of the XRHand dataset are shown in the following video.
{{< video src="xrhand.mp4" controls="yes" >}}

## Demo

In order to demonstrate the performance of our method, we design an interactive virtual environment by Open3d. Users are allowed to manipulate 3D objects in VR with their hands. In our method, only two grey cameras are required. Users don't need any wearable sensors on their hands. Our method shows good performance in tracking human hands and strong robustness to finger occlusion. 
{{< video src="Cyberpunk_bili.mp4" controls="yes" >}}
