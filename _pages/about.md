---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- title: "About Me"
Hi, I am Hanzhong Tan (Hank), currently a Master's student majoring in Computer Science and Technology at Hubei Minzu University. I completed my undergraduate studies in Information Engineering, during which my coursework and projects primarily centered around embedded systems. My passion for Artificial Intelligence was sparked when I first worked with development boards integrated with Convolutional Neural Network (CNN) algorithms, which subsequently inspired me to pivot toward the AI field for my graduate studies.

Currently, my research interests focus on **Computer Vision**, **Multi-modal Learning**, **Brain-Computer Intelligence**, and **AI4S**. Outside of my academic pursuits, I am a sports enthusiast with a particular love for **basketball**.

---

News
======
* **[2026-08]** Our paper "Frequency-Gated Prompting for Enhancing Transformer-based EEG Decoding" has been accepted by *<font color="red">IEEE Journal of Biomedical and Health Informatics (SCI Q1 TOP, CCF-C, IF=7.7)</font>*!🎉
* **[2026-06]** Our paper "Competitive Fusion in Multi-Modal Networks for Enhanced Salient Object Detection" has been accepted by *<font color="red">The Visual Computer (CCF-C)</font>*!🎉
* **[2026-01]** Our paper "Multi-Modal Hierarchical Fusion with Cross-Agent for RGB-D Salient Object Detection" has been accepted by *<font color="red">IEEE ICASSP 2026 (CCF-B)</font>*!🎉
* **[2025-08]** Our paper "HEFT: Hierarchical Enhanced Fusion Transformer for RGB-D Salient Object Detection" was published in *<font color="red">IEEE ICARM 2025 (CAA-A)</font>* (Portsmouth, United Kingdom).🎉


Selected Publications
======

* **Competitive fusion in multimodal networks for enhanced salient object detection**
  <br>**H. Tan**, S. Wen, L. Zhang, etc.  
  *The Visual Computer*, CCF-C, 2026.

* **Multi-Modal Hierarchical Fusion with Cross-Agent for RGB-D Salient Object Detection**
  <br>**H. Tan**, Y. Zhang, L. Zhang, etc.  
  *The 51st International Conference on Acoustics, Speech, and Signal Processing (IEEE ICASSP 2026)*, CCF-B, 2026.

* **HEFT: Hierarchical Enhanced Fusion Transformer for RGB-D Salient Object Detection**
  <br>**H. Tan**, S. Wen, L. Zhu, etc.  
  *IEEE International Conference on Advanced Robotics and Mechatronics (ICARM)*, CAA-A, 2025.


Honors & Awards
======
* **National Invention Patent** (Grant No. CN202411262320.4) 
  <br>Cross-modal Image Fusion Method for Abnormal Driving Behavior Detection, *CNIPA*, 2025.

* **Academic Research & Publication Excellence Award**
  <br>Hubei Minzu University, 2025–2026.

* **National/Provincial Award in Mathematical Modeling Competition**
  <br>Applied Undergraduate Innovation & Modeling Contest, 2019.
-->

<!-- 引入 FontAwesome 图标库与 Academicons 学术图标库 -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

<style>
  /* 整体色彩体系定义 */
  :root {
    --primary-color: #2b5876;
    --accent-color: #4e4376;
    --badge-ccf-b: #ff6b6b;
    --badge-ccf-c: #4ecdc4;
    --badge-patent: #ff9f43;
    --bg-card: #f8f9fa;
    --text-main: #2d3436;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    color: var(--text-main);
    line-height: 1.6;
  }

  /* 标题与板块样式 */
  .section-title {
    font-weight: 700;
    color: var(--primary-color);
    border-bottom: 2px solid var(--primary-color);
    padding-bottom: 5px;
    margin-top: 35px;
    margin-bottom: 20px;
    display: flex;
    align-items: center;
    gap: 10px;
  }

  /* 彩色标签 Badge 样式 */
  .badge {
    display: inline-block;
    padding: 2px 7px;
    font-size: 11px;
    font-weight: 600;
    color: white;
    border-radius: 4px;
    margin-right: 6px;
    vertical-align: middle;
  }
  .badge-red { background-color: #e74c3c; }
  .badge-blue { background-color: #3498db; }
  .badge-green { background-color: #2ecc71; }
  .badge-orange { background-color: #e67e22; }
  .badge-purple { background-color: #9b59b6; }

  /* 按钮标签 [Paper] [Code] */
  .btn-link {
    display: inline-block;
    padding: 2px 10px;
    font-size: 12px;
    border: 1px solid var(--primary-color);
    color: var(--primary-color);
    border-radius: 12px;
    text-decoration: none;
    margin-right: 5px;
    transition: all 0.2s;
  }
  .btn-link:hover {
    background-color: var(--primary-color);
    color: white;
  }

  /* 卡片化列表容器 */
  .card-item {
    background: var(--bg-card);
    border-left: 4px solid var(--primary-color);
    padding: 15px;
    margin-bottom: 15px;
    border-radius: 0 8px 8px 0;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
  }

  .paper-title {
    font-weight: 600;
    font-size: 18px;
    color: #1a1a1a;
  }
  .paper-authors {
    color: #666;
    font-size: 14px;
  }
  .journal-conf {
    font-size: 15px;
  }
  .me {
    font-weight: bold;
    color: var(--primary-color);
    text-decoration: underline;
  }

  /* 滚动容器通用样式 */
  .scrollable-container {
    max-height: 520px; /* 设置固定最大高度，根据实际需要调整 260px*/
    overflow-y: auto;  /* 内部内容超出时自动出现纵向滚动条 */
    padding-right: 10px; /* 留出边距，防止内容贴近滚动条 */
    border-radius: 6px;
  }

  /* 自定义美化滚动条 (支持 Chrome/Safari/Edge/Opera) */
  .scrollable-container::-webkit-scrollbar {
    width: 6px; /* 细滚动条 */
  }

  .scrollable-container::-webkit-scrollbar-track {
    background: #f1f1f1; /* 滚动条轨道背景色 */
    border-radius: 4px;
  }

  .scrollable-container::-webkit-scrollbar-thumb {
    background: #c1c1c1; /* 滚动条滑块颜色 */
    border-radius: 4px;
  }

  .scrollable-container::-webkit-scrollbar-thumb:hover {
    background: #a8a8a8; /* 鼠标悬停时滑块颜色 */
  }

  /* 适配 Firefox 浏览器的滚动条 */
  .scrollable-container {
    scrollbar-width: thin;
    scrollbar-color: #c1c1c1 #f1f1f1;
  }
</style>

<!-- 个人基础信息与社交图标 -->
<!-- 
# Hanzhong Tan (谭寒钟)
<p>
  <span class="badge badge-blue"><i class="fa-solid fa-graduation-cap"></i> Master Student</span>
  <span class="badge badge-purple"><i class="fa-solid fa-microchip"></i> Computer Vision & BCI</span>
</p>

<p>
  <a href="mailto:your_email@domain.com" class="btn-link"><i class="fa-solid fa-envelope"></i> Email</a>
  <a href="https://github.com/your-github" class="btn-link"><i class="fa-brands fa-github"></i> GitHub</a>
  <a href="https://scholar.google.com" class="btn-link"><i class="ai ai-google-scholar"></i> Google Scholar</a>
</p>

---
Biography-->

<!--
<h2 class="section-title"><i class="fa-solid fa-user"></i> About Me</h2>

Hi, I am Hanzhong Tan (Hank), currently a Master's student majoring in Computer Science and Technology at Hubei Minzu University. I completed my undergraduate studies in Information Engineering, during which my coursework and projects primarily centered around embedded systems. My passion for Artificial Intelligence was sparked when I first worked with development boards integrated with Convolutional Neural Network (CNN) algorithms, which subsequently inspired me to pivot toward the AI field for my graduate studies.

Currently, my research interests focus on **Computer Vision**, **Multi-modal Learning**, **Brain-Computer Intelligence**, and **AI4S**. Outside of my academic pursuits, I am a sports enthusiast with a particular love for **basketball**.

---

<h2 class="section-title"><i class="fa-solid fa-newspaper"></i> News</h2>

* **[2026-08]** 🎉 Our paper *"Frequency-Gated Prompting for Enhancing Transformer-based EEG Decoding"* has been accepted by *<font color="red">IEEE Journal of Biomedical and Health Informatics</font>* (IF=7.7)! <span class="badge badge-red">SCI Q1 TOP</span> <span class="badge badge-green">CCF-C</span>
* **[2026-06]** 🎉 Our paper *"Competitive Fusion in Multi-Modal Networks for Enhanced Salient Object Detection"* has been accepted by *<font color="red">The Visual Computer</font>*! <span class="badge badge-red">SCI Q3</span> <span class="badge badge-green">CCF-C</span>
* **[2026-01]** 🎉 Our paper *"Multi-Modal Hierarchical Fusion with Cross-Agent for RGB-D Salient Object Detection"* has been accepted by *<font color="red">IEEE ICASSP 2026</font>*! <span class="badge badge-blue">CCF-B</span>
* **[2025-08]** 🎉 Our paper *"HEFT: Hierarchical Enhanced Fusion Transformer for RGB-D Salient Object Detection"* was published in *<font color="red">IEEE ICARM 2025</font>*. <span class="badge badge-purple">CAA-A</span>

---

<h2 class="section-title"><i class="fa-solid fa-book-bookmark"></i> Selected Publications</h2>

<div class="card-item">
  <div class="paper-title">Frequency-Gated Prompting for Enhancing Transformer-based EEG Decoding</div>
  <div class="paper-authors"><span class="me">Hanzhong Tan</span>, Shuangbing Wen, Tao Hu, et al.</div>
  <div class="journal-conf"><em>IEEE Journal of Biomedical and Health Informatics (JBHI)</em>, 2026. <span class="badge badge-green">CCF-C</span> <span class="badge badge-red">SCI Q1 TOP</span> <span class="badge badge-red">IF=7.7</span></div>
  <div style="margin-top: 8px;">
    <a href="https://liangjiaxiaoqi.github.io/files/2026-08-12-Frequency_Gated_Prompting_for_Enhancing_Transformer_based_EEG_Decoding.pdf" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Paper</a>
    <a href="https://github.com/liangjiaxiaoqi/FGPT" class="btn-link"><i class="fa-brands fa-github"></i> Code</a>
  </div>
</div>

<div class="card-item">
  <div class="paper-title">Competitive Fusion in Multimodal Networks for Enhanced Salient Object Detection</div>
  <div class="paper-authors"><span class="me">Hanzhong Tan</span>, Shuangbing Wen, Lingfeng Zhang, et al.</div>
  <div class="journal-conf"><em>The Visual Computer</em>, 2026. <span class="badge badge-green">CCF-C</span> <span class="badge badge-red">SCI Q3</span> <span class="badge badge-red">IF=3.4</span></div>
  <div style="margin-top: 8px;">
    <a href="https://liangjiaxiaoqi.github.io/files/2026-07-09-Competitive_fusion_in_multimodal_networks_for_enhanced_salient_object_detection.pdf" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Paper</a>
    <a href="https://github.com/liangjiaxiaoqi/MC2FNet" class="btn-link"><i class="fa-brands fa-github"></i> Code</a>
  </div>
</div>

<div class="card-item">
  <div class="paper-title">Multi-Modal Hierarchical Fusion with Cross-Agent for RGB-D Salient Object Detection</div>
  <div class="paper-authors"><span class="me">Hanzhong Tan</span>, Yedong Zhang, Lingfeng Zhang, et al.</div>
  <div class="journal-conf"><em>The 51st International Conference on Acoustics, Speech, and Signal Processing (ICASSP)</em>, 2026. <span class="badge badge-blue">CCF-B</span></div>
  <div style="margin-top: 8px;">
    <a href="https://liangjiaxiaoqi.github.io/files/Multi-Modal_Hierarchical_Fusion_with_Cross-Agent_for_RGB-D_Salient_Object_Detection.pdf" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Paper</a>
    <a href="https://github.com/liangjiaxiaoqi/HMaT-D" class="btn-link"><i class="fa-brands fa-github"></i> Code</a>
  </div>
</div>

<div class="card-item">
  <div class="paper-title">HEFT: Hierarchical Enhanced Fusion Transformer for RGB-D Salient Object Detection</div>
  <div class="paper-authors"><span class="me">Hanzhong Tan</span>, Shuangbing Wen, Li Zhu, et al.</div>
  <div class="journal-conf"><em>IEEE International Conference on Advanced Robotics and Mechatronics (ICARM)</em>, 2025. <span class="badge badge-purple">CAA-A</span></div>
  <div style="margin-top: 8px;">
    <a href="https://liangjiaxiaoqi.github.io/files/2-HEFT.pdf" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Paper</a>
  </div>
</div>

---

<h2 class="section-title"><i class="fa-solid fa-award"></i> Honors & Awards</h2>

<h3 style="color: var(--accent-color);"><i class="fa-solid fa-certificate"></i> Patents & Intellectual Property</h3>
* <span class="badge badge-orange">Granted Patent</span> **National Invention Patent**: *Method for detecting abnormal driving behavior based on cross-modal image fusion* (Grant No. `CN202411262320.4`), 2025.
* <span class="badge badge-orange">Granted Patent</span> **National Utility Model Patent**: *A sun umbrella that automatically adjusts the angle of shade* (Grant No. `CN202420634142.2`), 2025.
* <span class="badge badge-orange">Granted Patent</span> **National Utility Model Patent**: *A Fruit Inspection and Traceability System* (Grant No. `CN202021377980.4`), 2021.

<h3 style="color: var(--accent-color);"><i class="fa-solid fa-trophy"></i> Academic & Competition Honors</h3>
* <span class="badge badge-green">University</span> **Graduate Education Innovation Program** (Principal Investigator), 2025~2026
* <span class="badge badge-blue">Regional</span> **2st Prize in the Central China Regional Competition**, China Graduate Student Electronic Design Competition, 2025
* <span class="badge badge-purple">National</span> **National 3st Prize**, China Graduate Student Mathematical Modeling Competition, 2024
* <span class="badge badge-orange">Provincial</span> **3st Prize, Chongqing Municipality**, China College Students' Computer Design Competition, 2024
* <span class="badge badge-blue">Regional</span> **2st Prize in the Central and Southwest China Region**, National College Student Internet of Things Design Competition, 2024
* <span class="badge badge-purple">National</span> **National Award**, National 5G IoT Innovation Competition for College Students, 2019
* <span class="badge badge-orange">Provincial</span> **3st Prize, Chongqing Municipality**, Chongqing City Hetai Cup Microcontroller Application Design Competition, 2019
* <span class="badge badge-orange">Provincial</span> **1st Prize/2st Prize, Chongqing Municipality**, National College Students Mathematical Modeling Competition, 2019 & 2018  
*......*  
* <span class="badge badge-orange">Provincial</span> **1st Prize, Chongqing Municipality**, Chongqing Innovation Methods Competition, 2018
-->

<h2 class="section-title"><i class="fa-solid fa-user"></i> About Me</h2>

Hi, I am Hanzhong Tan (Hank), currently a Master's student majoring in Computer Science and Technology at Hubei Minzu University. I completed my undergraduate studies in Information Engineering, during which my coursework and projects primarily centered around embedded systems. My passion for Artificial Intelligence was sparked when I first worked with development boards integrated with Convolutional Neural Network (CNN) algorithms, which subsequently inspired me to pivot toward the AI field for my graduate studies.

Currently, my research interests focus on **Computer Vision**, **Multi-modal Learning**, **Brain-Computer Intelligence**, and **AI4S**. Outside of my academic pursuits, I am a sports enthusiast with a particular love for **basketball**.

---

<h2 class="section-title"><i class="fa-solid fa-newspaper"></i> News</h2>

<!-- News 滚动容器 180px-->
<div class="scrollable-container" style="max-height: 360px;">
  <ul style="padding-left: 20px; margin: 0;">
    <li><b>[2026-08]</b> 🎉 Our paper <em>"Frequency-Gated Prompting for Enhancing Transformer-based EEG Decoding"</em> has been accepted by <em><font color="red">IEEE Journal of Biomedical and Health Informatics</font></em> (IF=7.7)! <span class="badge badge-red">SCI Q1 TOP</span> <span class="badge badge-green">CCF-C</span></li>
    <li style="margin-top: 8px;"><b>[2026-06]</b> 🎉 Our paper <em>"Competitive Fusion in Multi-Modal Networks for Enhanced Salient Object Detection"</em> has been accepted by <em><font color="red">The Visual Computer</font></em>! <span class="badge badge-red">SCI Q3</span> <span class="badge badge-green">CCF-C</span></li>
    <li style="margin-top: 8px;"><b>[2026-01]</b> 🎉 Our paper <em>"Multi-Modal Hierarchical Fusion with Cross-Agent for RGB-D Salient Object Detection"</em> has been accepted by <em><font color="red">IEEE ICASSP 2026</font></em>! <span class="badge badge-blue">CCF-B</span></li>
    <li style="margin-top: 8px;"><b>[2025-08]</b> 🎉 Our paper <em>"HEFT: Hierarchical Enhanced Fusion Transformer for RGB-D Salient Object Detection"</em> was published in <em><font color="red">IEEE ICARM 2025</font></em>. <span class="badge badge-purple">CAA-A</span></li>
  </ul>
</div>

---

<h2 class="section-title"><i class="fa-solid fa-book-bookmark"></i> Selected Publications</h2>

<!-- Publications 滚动容器380px -->
<div class="scrollable-container" style="max-height: 620px;">
  <div class="card-item">
    <div class="paper-title">Frequency-Gated Prompting for Enhancing Transformer-based EEG Decoding</div>
    <div class="paper-authors"><span class="me">Hanzhong Tan</span>, Shuangbing Wen, Tao Hu, et al.</div>
    <div class="journal-conf"><em>IEEE Journal of Biomedical and Health Informatics (JBHI)</em>, 2026. <span class="badge badge-green">CCF-C</span> <span class="badge badge-red">SCI Q1 TOP</span> <span class="badge badge-red">IF=7.7</span></div>
    <div style="margin-top: 8px;">
      <a href="https://liangjiaxiaoqi.github.io/files/2026-08-12-Frequency_Gated_Prompting_for_Enhancing_Transformer_based_EEG_Decoding.pdf" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Paper</a>
      <a href="https://github.com/liangjiaxiaoqi/FGPT" class="btn-link"><i class="fa-brands fa-github"></i> Code</a>
    </div>
  </div>

  <div class="card-item">
    <div class="paper-title">Competitive Fusion in Multimodal Networks for Enhanced Salient Object Detection</div>
    <div class="paper-authors"><span class="me">Hanzhong Tan</span>, Shuangbing Wen, Lingfeng Zhang, et al.</div>
    <div class="journal-conf"><em>The Visual Computer</em>, 2026. <span class="badge badge-green">CCF-C</span> <span class="badge badge-red">SCI Q3</span> <span class="badge badge-red">IF=3.4</span></div>
    <div style="margin-top: 8px;">
      <a href="https://liangjiaxiaoqi.github.io/files/2026-07-09-Competitive_fusion_in_multimodal_networks_for_enhanced_salient_object_detection.pdf" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Paper</a>
      <a href="https://github.com/liangjiaxiaoqi/MC2FNet" class="btn-link"><i class="fa-brands fa-github"></i> Code</a>
    </div>
  </div>

  <div class="card-item">
    <div class="paper-title">Multi-Modal Hierarchical Fusion with Cross-Agent for RGB-D Salient Object Detection</div>
    <div class="paper-authors"><span class="me">Hanzhong Tan</span>, Yedong Zhang, Lingfeng Zhang, et al.</div>
    <div class="journal-conf"><em>The 51st International Conference on Acoustics, Speech, and Signal Processing (ICASSP)</em>, 2026. <span class="badge badge-blue">CCF-B</span></div>
    <div style="margin-top: 8px;">
      <a href="https://liangjiaxiaoqi.github.io/files/Multi-Modal_Hierarchical_Fusion_with_Cross-Agent_for_RGB-D_Salient_Object_Detection.pdf" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Paper</a>
      <a href="https://github.com/liangjiaxiaoqi/HMaT-D" class="btn-link"><i class="fa-brands fa-github"></i> Code</a>
    </div>
  </div>

  <div class="card-item">
    <div class="paper-title">HEFT: Hierarchical Enhanced Fusion Transformer for RGB-D Salient Object Detection</div>
    <div class="paper-authors"><span class="me">Hanzhong Tan</span>, Shuangbing Wen, Li Zhu, et al.</div>
    <div class="journal-conf"><em>IEEE International Conference on Advanced Robotics and Mechatronics (ICARM)</em>, 2025. <span class="badge badge-purple">CAA-A</span></div>
    <div style="margin-top: 8px;">
      <a href="https://liangjiaxiaoqi.github.io/files/2-HEFT.pdf" class="btn-link"><i class="fa-solid fa-file-pdf"></i> Paper</a>
    </div>
  </div>
</div>

---

<h2 class="section-title"><i class="fa-solid fa-award"></i> Honors & Awards</h2>

<!-- Honors 滚动容器 -->
<!-- <div class="scrollable-container" style="max-height: 300px;"> -->
  <h3 style="color: var(--accent-color); margin-top: 0;"><i class="fa-solid fa-certificate"></i> Patents & Intellectual Property</h3>
  <ul style="padding-left: 20px;">
    <li><span class="badge badge-orange">Granted Patent</span> <b>National Invention Patent</b>: <em>Method for detecting abnormal driving behavior based on cross-modal image fusion</em> (Grant No. <code>CN202411262320.4</code>), 2025.</li>
    <li style="margin-top: 5px;"><span class="badge badge-orange">Granted Patent</span> <b>National Utility Model Patent</b>: <em>A sun umbrella that automatically adjusts the angle of shade</em> (Grant No. <code>CN202420634142.2</code>), 2025.</li>
    <li style="margin-top: 5px;"><span class="badge badge-orange">Granted Patent</span> <b>National Utility Model Patent</b>: <em>A Fruit Inspection and Traceability System</em> (Grant No. <code>CN202021377980.4</code>), 2021.</li>
  </ul>

  <h3 style="color: var(--accent-color);"><i class="fa-solid fa-trophy"></i> Academic & Competition Honors</h3>
  <ul style="padding-left: 20px;">
    <li><span class="badge badge-green">University</span> <b>Graduate Education Innovation Program</b> (Principal Investigator), 2025~2026</li>
    <li style="margin-top: 5px;"><span class="badge badge-blue">Regional</span> <b>2st Prize in the Central China Regional Competition</b>, China Graduate Student Electronic Design Competition, 2025</li>
    <li style="margin-top: 5px;"><span class="badge badge-purple">National</span> <b>National 3st Prize</b>, China Graduate Student Mathematical Modeling Competition, 2024</li>
    <li style="margin-top: 5px;"><span class="badge badge-orange">Provincial</span> <b>3st Prize, Chongqing Municipality</b>, China College Students' Computer Design Competition, 2024</li>
    <li style="margin-top: 5px;"><span class="badge badge-blue">Regional</span> <b>2st Prize in the Central and Southwest China Region</b>, National College Student Internet of Things Design Competition, 2024</li>
    <li style="margin-top: 5px;"><span class="badge badge-purple">National</span> <b>National Award</b>, National 5G IoT Innovation Competition for College Students, 2019</li>
    <li style="margin-top: 5px;"><span class="badge badge-orange">Provincial</span> <b>3st Prize, Chongqing Municipality</b>, Chongqing City Hetai Cup Microcontroller Application Design Competition, 2019</li>
    <li style="margin-top: 5px;"><span class="badge badge-orange">Provincial</span> <b>1st Prize/2st Prize, Chongqing Municipality</b>, National College Students Mathematical Modeling Competition, 2019 & 2018</li>
    <li style="margin-top: 5px;"><span class="badge badge-orange">Provincial</span> <b>1st Prize, Chongqing Municipality</b>, Chongqing Innovation Methods Competition, 2018</li>
  </ul>
<!--</div>-->


<!--  这是注释
---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

我是**谭寒钟 (Hanzhong Tan)**，目前是湖北民族大学 (Hubei Minzu University) 计算机科学与技术专业的硕士研究生。我的主要研究方向为**计算机视觉 (Computer Vision)**、**多模态学习 (Multi-modal Learning)** 以及**显著性目标检测 (Salient Object Detection)**。

I am **Hanzhong Tan**, a Master's student at Hubei Minzu University. My research interests include Computer Vision, Multi-modal Learning, and Salient Object Detection.

---

最新动态 / News
======
* **[2026-03]** 论文 "Hierarchical Multi-attention Transformer with Cross-Agent for RGB-D Salient Object Detection" 被 <font color="red">IEEE ICASSP 2026</font>**IEEE ICASSP 2026** 录用！
* **[2025-07]** 论文 "Hierarchical Enhanced Fusion Transformer (HEFT)" 发表于 **IEEE ICARM 2025**（江苏常州）。

研究方向 / Research Interests
======
* **多模态信息融合 (Multi-modal Fusion):** 专注于 RGB-D 和 RGB-T 数据的特征融合，特别是基于 Transformer 架构与层次化注意力机制的设计。
* **脑电信号解码 (EEG Decoding):** 基于频域信息的脑机接口（BCI）研究，开发了 Frequency-Gated Prompting (FGPT) 等方法。
* **场景理解 (Scene Understanding):** 致力于将多模态协同表示学习和显著性目标检测技术应用于船舶航行场景理解中。

学术成果 / Selected Publications
======

* **Hierarchical Multi-attention Transformer with Cross-Agent for RGB-D Salient Object Detection** **H. Tan**, S. Wen, Y. Zhang, L. Zhu, etc.  
  *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*, 2026. (Accepted)

* **Hierarchical Enhanced Fusion Transformer (HEFT) for Multi-Modal Interaction** **H. Tan**, S. Wen, etc.  
  *IEEE International Conference on Advanced Robotics and Mechatronics (ICARM)*, 2025.
-->


<!--  这是注释
---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

-->


