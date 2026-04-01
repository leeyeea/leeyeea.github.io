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

# ✨ About Me
I am a Ph.D student in the School of Computer Science and Technology, Zhejiang Normal University, China, advised by Prof. [Xinzhong Zhu](https://xinzhongzhu.github.io/). My research lies at the intersection of Deep Learning and Pattern Recognition, with a primary focus on Object Detectoin. My current work focuses on low-altitude UAV-based object detection, aiming to develop lightweight and efficient models that integrate multi-modal image fusion techniques for robust perception in complex environments. 

# 🔥 News
- *2026.03*: &nbsp;🎉🎉 Our paper entitled "IPeDet: An end-to-end fine-grained feature aggregation network for UAV infrared pedestrian detection" was accepted by AEI.
- *2025.11*: &nbsp;🎉🎉 Our paper entitled "BTDet:Towards Lightweight and Enhanced Feature Aggregation Network for Brain Tumor Detection" was accepted by BSPC.  
- *2025.10*: &nbsp;🎉🎉 Our paper entitled "KSCNet:Exploring KAN and State Space Model Collaboration Network for Small Object Detection from UAV Imagery" was accepted by ESWA.

# 📝 Publications 
<!-- text start 2026 ipedet -->
<div class='paper-box'>
<!-- <div class='paper-box-image'><div><div class="badge">AEI 2026</div><img src='images/papers/202603/ipedet.png' alt="sym" width="80%"></div></div> -->
<div class='paper-box-image' style="align-self:flex-start; margin-top:5px;"><div><div class="badge">AEI 2026</div><img src='images/papers/202603/ipedet.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

IPeDet: An end-to-end fine-grained feature aggregation network for UAV infrared pedestrian detection. <span style="color:#2E8B57;">Advanced Engineering Informatics.</span>  [SCI 1区 TOP] [PDF](https://www.sciencedirect.com/science/article/pii/S1474034626003319)

**YiLi**<sup>#</sup>, Huiying Xu<sup>#*</sup>, Xinzhongzhu, Hongbo Li<sup>*</sup>, Yiming Sun, Ruidong Wang, Lingling Xu

- This paper proposes IPeDet, a robust infrared pedestrian detector for UAV scenarios that enhances fine-grained feature aggregation to overcome the limitations of traditional visible light methods. The approach combines a lightweight backbone, Large Separable Kernel Attention, Online Convolutional Re-parameterization, and a novel Multi-Path Coordinate Attention mechanism to reduce feature redundancy and improve efficiency. IPeDet establishes a new state-of-the-art for infrared pedestrian detection.
</div>
</div>

<!-- text end -->

<!-- text start 2025 btdet-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">BSPC 2025</div><img src='images/papers/202511/btdet.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

BTDet: Towards lightweight and enhanced feature aggregation network for brain tumor detection. <span style="color:#2E8B57;">Biomedical Signal Processing and Control.</span> [SCI 2区] [PDF](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**YiLi**, Huiying Xu<sup>*</sup>, Xinzhongzhu, Xiao Huang, Hongbo Li

- This paper proposes BTDet, an efficient and lightweight detection framework for accurate brain tumor detection in MRI that balances performance with computational efficiency. The framework incorporates a Reparameterized C2f GELAN backbone with Fast Spatial Pyramid Pooling Fusion, C2f Squeeze and Excitation attention, General Depthwise Separable Convolution, and a lightweight dual-head to enhance feature extraction and multi-scale fusion. BTDet offers a practical and resource-efficient solution suitable for real-world medical imaging applications.
</div>
</div>
<!-- text start -->


<!-- text start 2025 kscnet-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA 2025</div><img src='images/papers/202510/kscnet.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

KSCNet: Exploring KAN and state space model collaboration network for small object detection from UAV imagery. <span style="color:#2E8B57;">Expert System with Applications.</span> [SCI 1区 TOP] [PDF](https://www.sciencedirect.com/science/article/abs/pii/S0957417425038552)

**YiLi**, Huiying Xu<sup>*</sup>, Yiming Sun, Pengfei Zhu, Lingling Xu, Xinzhongzhu 

- This paper proposes KSCNet, a collaboration network that integrates Kolmogorov–Arnold Networks (KAN) and State Space Model (SSM) to improve small target detection in UAV aerial imagery. The framework employs a KAN-based backbone for efficient feature extraction, a Semantic Aggregation Network (SAN) with SSM modules for global multiscale feature fusion, and a Depthwise Channel Attention (DCA) mechanism to mitigate aliasing effects. KSCNet provides an effective solution for UAV-based small object detection under complex background conditions.
</div>
</div>
<!-- text start -->


<!-- text start 2024 THDet-->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DSP 2024</div><img src='images/papers/202409/thdet.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

THDet: A Lightweight and Efficient Traffic Helmet Object Detector based on YOLOv8. <span style="color:#2E8B57;">Digtial Signal Processing.</span> [SCI 3区] [PDF](https://www.sciencedirect.com/science/article/abs/pii/S1051200424003907)

**YiLi**, Huiying Xu<sup>*</sup>, Xinzhongzhu, Xiao Huang, Hongbo Li

- This paper presents THDet, an efficient traffic helmet detector based on YOLOv8n that achieves a balance between detection accuracy and model efficiency through feature enhancement and lightweight design. The framework incorporates coordinate attention with softmax activation in C2f blocks, Focal_CIoU loss for precise bounding box regression, a lightweight dual-head detection architecture, and an Attention Refined Features Module (ARFM) for multi-scale feature calibration. THDet provides an effective solution for traffic helmet detection under varying object sizes and challenging visual conditions.
</div>
</div>
<!-- text start -->




# 📖 Educations
- *2023.09 - Now*, Ph.D, Zhejiang Normal University, School of Computer Science and Technology. 
- *2018.09 - 2021.06*, M.S., Zhejiang Normal University, School of Computer Science and Technology. 
- *2013.09 - 2017.06*, B.E, TaiShan University.


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->




<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->
<!--
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->