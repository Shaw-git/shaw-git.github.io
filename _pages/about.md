---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Ph.D. student at the University of Florida under the supervision of [Prof. Sanjay Ranka](https://sanjayranka.com/) and [Prof. Anand Rangarajan](https://www.cise.ufl.edu/~anand/) . I got my bachelor's degree and master's degree at Sun Yat-Sen University in 2018 and 2020 respectively under the supervision of Prof. Dong Zhang. My research focuses on applying deep learning to solve practical problems. Currently, I am working on developing foundational diffusion models for lossy data compression and spatio-temporal data generation.

My research interest includes:
- Smart transportation
- Unsupervised learning
- Error bounded lossy data compression
- Generative AI


# 🔥 News
- *2024.12*: &nbsp;⭐⭐ Our work **"Guaranteed Conditional Diffusion: 3D Block-based Models for Scientific Data Compression"** has been submitted to PAKDD conference.
- *2024.12*: &nbsp;⭐⭐ Our work **"Foundation Model for Lossy Compression of Spatiotemporal Scientific Data"** has been submitted to PAKDD conference.
- *2024.12*: &nbsp;⭐⭐ Xiao Li presented the work **"Attention Based Machine Learning Methods for Data Reduction with Guaranteed Error Bounds"** at IEEE BigData 2024 in Washington DC, USA.
- *2024.10*: &nbsp;🎉🎉 Our paper **"Attention Based Machine Learning Methods for Data Reduction with Guaranteed Error Bounds"** has been accepted in **IEEE BigData 2024**.
- *2024.06*: &nbsp;⭐⭐ Xiao Li presented the work **"A Data-driven Approach for Probabilistic Traffic Prediction and Simulation at Signalized Intersections"** at 2024 IEEE Intelligent Vehicles Symposium (IV) in Jeju, Korea.
- *2024.04*: &nbsp;🎉🎉 Our paper **"An Efficient Semi-Automated Scheme for Infrastructure LiDAR Annotation" has been accepted"** has been accepted in **IEEE Transactions on Intelligent Transportation Systems**.
- *2024.03*: &nbsp;🥇🥇 Congratulations to Xiao Li on being selected as the Gartner Group Graduate Fellowship recipient at UFL!
- *2024.03*: &nbsp;⭐⭐ Xiao Li presented the work **"Hybrid Approaches for Data Reduction of Spatiotemporal Scientific Applications"** at the DCC Conference in Snowbird, Utah.
- *2024.01*: &nbsp;🎉🎉 Our work **"Hybrid Approaches for Data Reduction of Spatiotemporal Scientific Applications"** has been accepted in **Data Compression Conference**.
- *2023.07*: &nbsp;🎉🎉 Our paper  **"A Spatiotemporal Correspondence Approach to Unsupervised LiDAR Segmentation with Traffic Applications"** has been accepted in **IEEE Intelligent Transportation Systems Conference**.
- *2023.05*: &nbsp;🎉🎉 Our work **"Computer-aided autism spectrum disorder diagnosis with behavior signal processing"** has been accepted in **IEEE Transactions on Affective Computing**.
- *2023.03*: &nbsp;🎉🎉 Our paper  **"An Efficient Semi-Automated Scheme for LiDAR Annotation and A Benchmark Infrastructure Dataset"** has been accepted in **ICLR ML4IoT**.
- *2022.11*: &nbsp;🎉🎉 Our paper  **"Accurate Head Pose Estimation Using Image Rectification and A Lightweight Convolutional Neural Network"** has been accepted in **IEEE Transactions on Multimedia**.
- *2021.09*: &nbsp;🎉🎉 Our paper  **"Concurrent Two-factor Identify Verification Using Facial Identify and Facial Actions"** has been accepted in **Electronic Imaging**.

# 📖 Education

<div style="display: flex; align-items: center;">
    <img src="images/uflogo.png" alt="UF Logo" style="height: 60px; margin-right: 8px;"> 
    <span style="font-size: 1.25em;"><strong>University of Florida</strong></span>
</div>
<p style="margin: 0; padding-left: 60px;"><em>- Ph.D. Student in Computer Science</em></p>
<p style="margin: 0; padding-left: 60px;"><em>- Advisor: <a href="https://sanjayranka.com/">Prof. Ranka Sanjay</a>, Co-advised by <a href="https://www.cise.ufl.edu/~anand/">Prof. Anand Rangarajan</a></em></p>
<p style="padding-left: 60px;"><em>- 2021.08 - Present</em></p>

<div style="display: flex; align-items: center;">
    <img src="images/sysulogo.png" alt="SYSU Logo" style="height: 60px; margin-right: 8px;"> 
    <span style="font-size: 1.25em;"><strong>Sun Yat-sen University</strong></span>
</div>
<p style="margin: 0; padding-left: 60px;"><em>- M.S. in Electronics and Communication, Outstanding Graduate</em></p>
<p style="margin: 0; padding-left: 60px;"><em>- Prof. Dong Zhang</em></p>
<p style="padding-left: 60px;"><em>- 2018.08 - 2020.08</em></p>

<div style="display: flex; align-items: center;">
    <img src="images/sysulogo.png" alt="SYSU Logo" style="height: 60px; margin-right: 8px;"> 
    <span style="font-size: 1.25em;"><strong>Sun Yat-sen University</strong></span>
</div>
<p style="margin: 0; padding-left: 60px;"><em>- B.S. in Communication Engineering</em></p>
<p style="padding-left: 60px;"><em>- 2014.08 - 2018.08</em></p>




# 📝 Publications 



{% capture publication_content %}
{% include_relative publication.md %}
{% endcapture %}

{{ publication_content | markdownify }}


# 📝 Projects
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->

# 🎖 Honors and Awards
- *2024.05* Gartner Group Graduate Fellowship
- *2020.06* Outstanding Graduate
- *2019.09* First Class Scholarship
- *2018.09* Second Class Scholarship
- *2016.09* MCM/ICM Contest Meritorious Winner



# 👨‍💻 Professional Services
Paper Reviewer:
- IEEE Transactions on Neural Networks and Learning Systems (TNNLS) (2024)
- Machine vision and applications (2023)

  
# 💻 Professional Experience and Internships

- **2020.12 - 2021.08**: *CVTE (Software Development Engineer)*  
  - Worked on hand-computer interaction for XR headset.

- **2020.08 - 2020.12**: *Duke Kunshan University, China*  

- **2019.08 - 2019.12**: *Duke Kunshan University, China*  



# 📚 Teaching Experience
- CAP6610 Spring 2024 - Machine Learning
- COT5615 Fall 2023 - Math for Intelligent Systems
- COP3530 Fall 2021 - Data Structure and Algorithms
