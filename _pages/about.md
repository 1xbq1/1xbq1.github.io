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

I am currently a Research Fellow at <a href='https://www.asintelligence.xyz/'>The Artificial Scientific Intelligence Lab (ASI Lab)</a> at the National University of Singapore, under the supervision of <a href='https://scholar.google.com/citations?user=kGSzBpMAAAAJ&hl=en'>Prof. Leo Dianbo Liu</a>. Before that, I received my Ph.D. from Nanjing University of Science and Technology, where I was affiliated with the <a href="https://shuxb104.github.io/team/">Visual Intelligence and Multimedia (VIM)</a> and <a href="https://imag-njust.net/">Intelligent Media Analysis Group (IMAG)</a> under the supervision of <a href='https://shuxb104.github.io/'>Prof. Xiangbo Shu</a>.

Previously, I was a visiting Ph.D. student at A*STAR and NUS for two years, working with <a href='https://cde.nus.edu.sg/ece/staff/shou-zheng-mike/'>Prof. Mike Z. Shou</a> and <a href='https://basurafernando.github.io/'>Dr. Basura</a>.

My research interests include Computer Vision, Action Recognition, Federated Learning, and AI Agents. 
<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!-- # 🔥 News
- *2026-01-26*: &nbsp;🎉🎉 Published a paper in IEEE TIP! 
- *2025-09-19*: &nbsp;🎉🎉 YOCO is accepted by NeurIPS 2025!
- *2025-06-26*: &nbsp;🎉🎉 Te-LoRA is accepted by ICCV 2025! 
- *2024-09-26*: &nbsp;🎉🎉 DoFIT is accepted by NeurIPS 2024! 
- *2023-03-10*: &nbsp;🎉🎉 Published a paper in IEEE TNNLS! 
- *2022-11-17*: &nbsp;🎉🎉 Published a paper in IEEE TPAMI! 
- *2022-05-26*: &nbsp;🎉🎉 Published a paper in IEEE TIP!  -->

# 🔥 News

<!-- <div style="height: 250px; overflow-y: auto; border: 1px solid #eee; padding: 15px; border-radius: 8px; background-color: #f9f9f9; margin-bottom: 20px;">
  <ul style="list-style-type: none; margin-left: 0; line-height: 1.6;"> -->
  <div style="max-height: 120px; overflow-y: auto; padding: 10px;">
  <ul style="margin: 0; padding-left: 20px;">
    <li><b>2026-01-26</b>: 🎉🎉 Published a paper in IEEE TIP!</li>
    <li><b>2025-09-19</b>: 🎉🎉 YOCO is accepted by NeurIPS 2025!</li>
    <li><b>2025-06-26</b>: 🎉🎉 Te-LoRA is accepted by ICCV 2025! Congrats to co-authors!</li>
    <li><b>2024-09-26</b>: 🎉🎉 DoFIT is accepted by NeurIPS 2024!</li>
    <li><b>2023-03-10</b>: 🎉🎉 Published a paper in IEEE TNNLS!</li>
    <li><b>2022-11-17</b>: 🎉🎉 Published a paper in IEEE TPAMI!</li>
    <li><b>2022-05-26</b>: 🎉🎉 Published a paper in IEEE TIP!</li>
  </ul>
</div>

<!-- # 📝 Selected Publications (*co-first author) -->
<!-- <div id="selected-publications"></div>
# 📝 Selected Publications (*co-first author) -->
<span class='anchor' id='selected-publications'></span>
# 📝 Selected Publications (*co-first author)

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">NeurIPS 2025</div>
      <img src='images/YOCO_1.PNG' alt="YOCO" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[You Only Communicate Once: One-shot Federated Low-Rank Adaptation of MLLM](https://openreview.net/pdf?id=FoVF3iL6o3)

**Binqian Xu**, Haiyang Mei, Zechen Bai, Jinjin Gong, Rui Yan, Guo-Sen Xie, Yazhou Yao, Basura Fernando, Xiangbo Shu

*The Thirty-ninth Annual Conference on Neural Information Processing Systems* (**NeurIPS**), 2025

<!-- [**[pdf]**](https://openreview.net/pdf?id=FoVF3iL6o3) | [**[code]**](https://github.com/1xbq1/FedMLLM)  -->
<a href="https://openreview.net/pdf?id=FoVF3iL6o3"><strong>[pdf]</strong></a> | <a href="https://github.com/1xbq1/FedMLLM"><strong>[code]</strong></a>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">ICCV 2025</div>
      <img src='images/TeLoRA.PNG' alt="TeLoRA" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[Tensor-aggregated LoRA in Federated Fine-tuning](https://openaccess.thecvf.com/content/ICCV2025/papers/Li_Tensor-aggregated_LoRA_in_Federated_Fine-tuning_ICCV_2025_paper.pdf)

ZhiXuanLi*, **Binqian Xu\***, Xiangbo Shu, Jiachao Zhang, Yazhou Yao, Guo-Sen Xie, Jinhui Tang

*International Conference on Computer Vision* (**ICCV**), 2025

<!-- [**[pdf]**](https://openaccess.thecvf.com/content/ICCV2025/papers/Li_Tensor-aggregated_LoRA_in_Federated_Fine-tuning_ICCV_2025_paper.pdf) | [**[code]**](#) -->
<a href="https://openaccess.thecvf.com/content/ICCV2025/papers/Li_Tensor-aggregated_LoRA_in_Federated_Fine-tuning_ICCV_2025_paper.pdf"><strong>[pdf]</strong></a> | <a href="#"><strong>[code]</strong></a>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">arXiv 2025</div>
      <img src='images/FedMLLM.png' alt="FedMLLM" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[FedMLLM: Federated Fine-tuning MLLM on Multimodal Heterogeneity Data](https://arxiv.org/pdf/2411.14717)

**Binqian Xu**, Xiangbo Shu, Haiyang Mei, Guo-Sen Xie, Basura Fernando, Jinhui Tang

*arXiv preprint arXiv:2411.14717*, 2025

<!-- [**[pdf]**](https://arxiv.org/pdf/2411.14717) | [**[code]**](https://github.com/1xbq1/FedMLLM)  -->
<a href="https://arxiv.org/pdf/2411.14717"><strong>[pdf]</strong></a> | <a href="https://github.com/1xbq1/FedMLLM"><strong>[code]</strong></a>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">NeurIPS 2024</div>
      <img src="images/DoFIT.PNG" alt="DoFIT" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[DoFIT: Domain-aware Federated Instruction Tuning with Alleviated Catastrophic Forgetting](https://openreview.net/pdf?id=FDfrPugkGU)

**Binqian Xu**, Xiangbo Shu, Haiyang Mei, Zechen Bai, Basura Fernando, Mike Zheng Shou, Jinhui Tang

*The Thirty-eighth Annual Conference on Neural Information Processing Systems* (**NeurIPS**), 2024

<!-- [**[pdf]**](https://openreview.net/pdf?id=FDfrPugkGU) | [**[code]**](https://github.com/1xbq1/DoFIT) -->
<a href="https://openreview.net/pdf?id=FDfrPugkGU"><strong>[pdf]</strong></a> | <a href="https://github.com/1xbq1/DoFIT"><strong>[code]</strong></a>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">IEEE TPAMI 2023</div>
      <img src="images/MAC_Learning.PNG" alt="MAC-Learning" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[Multi-Granularity Anchor- Contrastive Representation Learning for Semi-Supervised Skeleton-Based Action Recognition](https://ieeexplore.ieee.org/abstract/document/9954217)

Xiangbo Shu, **Binqian Xu**, Liyan Zhang, Jinhui Tang

*IEEE Transactions on Pattern Analysis and Machine Intelligence* (**IEEE TPAMI**), 2023

<!-- [**[pdf]**](https://ieeexplore.ieee.org/abstract/document/9954217) | [**[code]**](https://github.com/1xbq1/MAC-Learning) -->
<a href="https://ieeexplore.ieee.org/abstract/document/9954217"><strong>[pdf]</strong></a> | <a href="https://github.com/1xbq1/MAC-Learning"><strong>[code]</strong></a>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">IEEE TNNLS 2023</div>
      <img src="images/SDS-CL.PNG" alt="SDS-CL" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[Spatiotemporal Decouple- and-Squeeze Contrastive Learning for Semi-Supervised Skeleton-based Action Recognition](https://arxiv.org/abs/2302.02316)

**Binqian Xu**, Xiangbo Shu, Jiachao Zhang, Guangzhao Dai, and Yan Song

*IEEE Transactions on Neural Networks and Learning Systems* (**IEEE TNNLS**), 2023

<!-- [**[pdf]**](https://arxiv.org/abs/2302.02316) | [**[code]**]((#)) -->
<a href="https://arxiv.org/abs/2302.02316"><strong>[pdf]</strong></a> | <a href="#"><strong>[code]</strong></a>

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image' style="flex: 0.3; min-width: 200px;">
    <div>
      <div class="badge">IEEE TIP 2022</div>
      <img src="images/X-CAR.PNG" alt="X-CAR" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1" style="flex: 0.7; padding-left: 20px;">

[X-invariant Contrastive Augmentation and Representation Learning for Semi-Supervised Skeleton-Based Action Recognition](https://ieeexplore.ieee.org/abstract/document/9782720)

**Binqian Xu**, Xiangbo Shu, and Yan Song

*IEEE Transactions on Image Processing* (**IEEE TIP**), 2022

<!-- [**[pdf]**](https://ieeexplore.ieee.org/abstract/document/9782720) | [**[code]**]((#)) -->
<a href="https://ieeexplore.ieee.org/abstract/document/9782720"><strong>[pdf]</strong></a> | <a href="#"><strong>[code]</strong></a>

  </div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 🎖 Honors and Awards
- **National Scholarship for PhD Students**, 2025
- **Excellent Doctoral Candidate Training Program**, 2025
- **National Scholarship for Studying Abroad**, 2023
- **Third Prize**, 10th LanQiao Cup National Finals, 2019
- **Bronze Medal**, ICPC Xuzhou Site, 2018
- **Bronze Medal**, CCPC Jilin Site, 2018
- **Third Prize**, Hunan Collegiate Programming Contest, 2018
- **Third Prize**, 9th LanQiao Cup National Finals, 2018

  <!-- 访客地图 -->
<div style="text-align: center; margin-top: 30px; margin-bottom: 30px;">
  <a href="https://mapmyvisitors.com/web/1bzj9" title="Visit tracker">
    <img src="https://mapmyvisitors.com/map.png?cl=080808&w=500&t=tt&d=WOHftRxg9_a8EYuzD8Z_uAxyntu3Sk8OoiZfxOkMdSo&co=ffffff&ct=808080"
         style="width: 50%; max-width: 600px; height: auto;" />
  </a>
</div>

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->