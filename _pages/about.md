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

I am currently an undergraduate student (Sep 2023 – Jun 2027 expected) pursuing a dual Bachelor of Engineering degree at **[Nanjing University of Information Science and Technology (NUIST)](https://www.nuist.edu.cn)** (Waterford Institute) and **[South East Technological University (SETU)](https://www.setu.ie)** (Computer Science and IT), ranking **1/34** in both programs with GPAs of **4.16/5.0** and **4.18/5.0**.

My research interests include **Machine Learning**, **Pattern Recognition**, **Image Processing**, **Remote Sensing Applications**, **Large Language Model Inference**, and **Model-Driven Deep Learning**.

Here is my [CV/Resume](CV_Weijie_Xu.pdf). If you are interested in my work or prospective research collaborations, please feel free to contact me via *[wjxu@nuist.edu.cn](mailto:wjxu@nuist.edu.cn)*.


# 🎯 Research Interests
- **Computer Vision & Remote Sensing**: Infrared Small Target Detection (ISTD), Image Processing, Object Segmentation.
- **Machine Learning & Edge Intelligence**: Model-Driven Deep Learning, Federated Learning, Edge-Cloud Systems, LLM Inference Optimization.


# 🔥 News
- *2026*: &nbsp;📄 1 paper submitted to **IEEE TMC** (CCF A), 1 paper under major revision at **Optics & Laser Technology**!
- *2025*: &nbsp;🎉🎉 1 first-author paper published online in **IEEE Transactions on Geoscience and Remote Sensing (TGRS)** (Q1 TOP, CCF B)!
- *2025*: &nbsp;🏆 Honored as **Person of the Year** and awarded **National Scholarship** at NUIST!
- *2025*: &nbsp;🥇 Awarded First Prize in **China Robotics and Artificial Intelligence Competition** & Honorable Mention in **MCM**!
- *2024*: &nbsp;🏆 Awarded **National Scholarship**, First Prize in **National College Student Mathematical Modeling Competition**, and First Prize in **Jiangsu Higher Math Competition**!


# 📝 Selected Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TGRS 2025</div><img src='images/paper_tgrs_1.png' alt="FSCFNet" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>Think Locally and Act Globally: A Frequency-Spatial Fusion Network for Infrared Small Target Detection</b></font>

<p style="margin: -1px 0;"><span style="font-weight: bold;"><u>Weijie Xu</u></span>#, Zhenglong Ding*, Ziheng Wang, Zhiqing Cui, Yifan Hu, Feng Jiang</p>

<em>IEEE Transactions on Geoscience and Remote Sensing (<b>IEEE TGRS</b>), 2025. <b><span style="color:#e74c3c">Q1 TOP, CCF B, IF: 8.6</span></b></em>

- Proposed **FSCFNet** for infrared small target detection under sparsity, low contrast, and blurred textures.
- Designed Frequency-Spatial Convolution, Asymmetric Cross-Domain Attention, and Multiscale Receptive Contextual Block to jointly model high-frequency details and low-frequency global structures.
- On IRSTD-1k, improved mAP@50 from 86.5% to 90.4% (+3.9%) with only +3.6% parameters; achieved leading performance against 16 SOTA models on IRSTD-1k, NUAA-SIRST, and NUDT-SIRST.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Optics & Laser Tech</div><img src='images/paper_olt_2.png' alt="PFDMNet" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>PFDMNet: Prior-Guided Frequency-Decoupled Mamba Network for Infrared Small Target Detection</b></font>

<p style="margin: -1px 0;">Yifan Hu#, <span style="font-weight: bold;"><u>Weijie Xu</u></span>, Zhenglong Ding*, Kao Zhang, Feng Jiang</p>

<em>Submitted to Optics and Laser Technology (<b>Major Revision</b>), <b><span style="color:#e74c3c">Q2, IF: 5.7</span></b>, 2026</em>

- Formulated a prior-guided frequency-decoupled Mamba network architecture to enhance infrared small target detection performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TMC Under Review</div><img src='images/paper_tmc_4.png' alt="TMC Paper" width="90%"></div></div>
<div class='paper-box-text' markdown="1">

<font size="3.5"><b>Budget-Aware Rank Scheduling for Efficient Federated LoRA in Edge-Cloud Systems</b></font>

<p style="margin: -1px 0;">Xinkang Fan, Shucun Fu, Xiaolong Xu, <span style="font-weight: bold;"><u>Weijie Xu</u></span>, Runze Chen, Muhammad Bilal</p>

<em>Submitted to IEEE Transactions on Mobile Computing (<b>IEEE TMC</b>), <b><span style="color:#e74c3c">Q1 TOP, CCF A, IF: 8.1</span></b>, 2026</em>

- Proposed a budget-aware rank scheduling framework for efficient federated LoRA in edge-cloud systems to optimize communication and computational resource utilization.
</div>
</div>


# 🎓 Educations
- *2023.09 - 2027.06 (expected)*, B.E. in Waterford Institute, **Nanjing University of Information Science and Technology (NUIST)**, Nanjing, China.
  - **GPA**: 4.16/5.0 | **Rank**: 1/34 | **Centesimal Average**: 91.45
- *2023.09 - 2027.06 (expected)*, B.E. in Computer Science and Information Technology, **South East Technological University (SETU)**, Munster, Ireland.
  - **GPA**: 4.18/5.0 | **Rank**: 1/34 | **Centesimal Average**: 91.60

### 📚 Selected Coursework
Linear Algebra (99), College Physics (99), Introduction to Engineering (99), Advanced Mathematics (99), Discrete Mathematics (98), Relational Databases (98), Computer Networks (97), Probability Theory and Statistics (97), Python and its Application Practice (96), Web Application Development (95).


# 📖 Publications

### 📄 Journal & Conference Papers
- <small>**<u>Weijie Xu#</u>**, Zhenglong Ding*, Ziheng Wang, Zhiqing Cui, Yifan Hu, Feng Jiang, "Think Locally and Act Globally: A Frequency-Spatial Fusion Network for Infrared Small Target Detection", *IEEE Transactions on Geoscience and Remote Sensing (TGRS)*, 2025. **[IF: 8.6, Rank: Q1 TOP, CCF B]**</small>
- <small>Zhenglong Ding#, Yifan Hu*, Yuanhong Du, **<u>Weijie Xu</u>**, Yamei Wei, Xuan Yao, "LESO-Net: A Lightweight and Efficient Small Object Segmentation Network", *Journal of Nanjing University of Information Science and Technology*, 2024. **[Rank: Core Technology]**</small>

### 📄 Papers Under Review & Working Papers
- <small>Yifan Hu#, **<u>Weijie Xu</u>**, Zhenglong Ding*, Kao Zhang, Feng Jiang, "PFDMNet: Prior-Guided Frequency-Decoupled Mamba Network for Infrared Small Target Detection", submitted to *Optics and Laser Technology* (in Major Revision), 2026. **[IF: 5.7, Rank: Q2]**</small>
- <small>Xinkang Fan, Shucun Fu, Xiaolong Xu, **<u>Weijie Xu</u>**, Runze Chen, Muhammad Bilal, "Budget-Aware Rank Scheduling for Efficient Federated LoRA in Edge-Cloud Systems", submitted to *IEEE Transactions on Mobile Computing (TMC)* (Under Review), 2026. **[IF: 8.1, Rank: Q1 TOP, CCF A]**</small>


# 🏆 Honors & Awards
- *2025*: **National Scholarship**, Ministry of Education, China
- *2025*: **Person of the Year**, NUIST
- *2025*: **Outstanding Student**, NUIST
- *2025*: **Outstanding Student Leader**, NUIST
- *2025*: **The Mathematical Contest in Modeling (MCM)**, Honorable Mention
- *2025*: **China Robotics and Artificial Intelligence Competition**, First Prize
- *2024*: **National Scholarship**, Ministry of Education, China
- *2024*: **College Student Innovation and Entrepreneurship Training Program of Jiangsu Province**
- *2024*: **National College Student Mathematical Modeling Competition**, First Prize
- *2024*: **Higher Mathematics Competition of Jiangsu Province**, First Prize
- *2024*: **Outstanding Volunteer**, NUIST


# 💻 Skills
- **Programming Languages & Frameworks**: Python, PyTorch, C++, Java, SQL, Shell, LaTeX
- **Operating Systems & Databases**: Linux, Docker, Git, MySQL, MongoDB
- **Software & Tools**: Office, Obsidian
