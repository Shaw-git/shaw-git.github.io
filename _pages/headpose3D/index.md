---
title: '3D Face Modeling and Head Pose Tracking with Comsumer RGB-D Cameras'
subtitle: Point Cloud, 3D Geometry, Face Modeling, Head Pose Estimation
summary: Point Cloud, 3D Geometry, Face Modeling, Head Pose Estimation
permalink: /headpose3D/
layout: single
authors:
- admin
- Dong Zhang
# tags:
# - Academic
# - 开源
# categories:
# - Demo
# - 教程
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
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
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

We propose a method to address the issue of face modeling and head pose estimation from a depth image. We calculate head poses by aligning face point cloud acquired by a consumer depth camera with a 3D face model. However, due to the uniqueness of each individual’s biometrics, the pre-defined face model may not completely fit the real face of each person, which leads to errors in the estimated head pose. In order to address this problem, we use a deformable model to characterize the biometric differences of the face. The deformable face model has been proven to be effective. The method is used for automatic head pose annotation for RGB face images.

## Demo

* Raw 3D Face Scanning
{{< video src="face_scan.mp4" controls="yes" >}}
* Non-Rigid 3D Model Fitting and Face Model Deformation
{{< video src="face_deformation.mp4" controls="yes" >}}
* Accurate Head Pose Tracking with A Comsumer RGB-D Camera
{{< video src="headpose_tracking.mp4" controls="yes" >}}
