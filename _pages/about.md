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
{% assign gsDataBaseUrl = "<https://cdn.jsdelivr.net/gh/>" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "<https://raw.githubusercontent.com/>" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi, I am an undergraduate student from the first session of [Guozhi Class](http://www.qingyuan.sjtu.edu.cn/c/Introductiongzb) (held by [Prof.Xiaoou Tang](https://www.ie.cuhk.edu.hk/faculty/Tang-Xiaoou-Sean/) and [Prof.Cewu Lu](https://www.mvig.org/)), Shanghai Jiao Tong University and major in **Artificial Intelligence**. 

Currently, I work as a research intern at [OpenDriveLab](https://opendrivelab.com), supervised by Prof. [Hongyang Li](https://lihongyang.info). Meanwhile, I also work as a research intern at [ReThinkLab](https://thinklab.sjtu.edu.cn), supervised by Prof. [Junchi Yan](https://thinklab.sjtu.edu.cn).

My research interest includes ***robotics, embodied AI, autonomous driving and computer vision***. <a href="https://scholar.google.com/citations?user=_LeSlzUAAAAJ"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fwbjsamuel%2Fwbjsamuel.github.io%40google-scholar-stats%2Fgs_data_shieldsio.json&amp;logo=Google%20Scholar&amp;labelColor=f6f6f6&amp;color=9cf&amp;style=flat&amp;label=citations"></a>

Recently, I have co-led a project related to human-oriented representation learning for robot manipulation.🦾

In my spare time, I enjoy playing tennis🎾, travelling🏝 and drilling my skills in both photography📷 and cinematography🎥 and I am also a big fan of jazz🎷 and classical music🎼 !


- My latest resume is available here: [CV](https://wbjsamuel.github.io/files/BangjunWang_Resume_20240120.pdf) [Updated on 20 Jan, 2024].
- I am seeking 2024 summer research position in the US. If you are interested in my research, please feel free to contact me via [email](mailto:wbjsamuel+001@gmail.com)

# 🔥 News
<!-- - 2024.03: &nbsp; Planning to collaborate with Prof.[Hao Dong](https://zsdonghao.github.io) of PKU-Agibot Lab on robot manipulation this spring semester. -->
- 2024.02: &nbsp; One paper on robot manipulation has been submitted to <span style="color:#090;background-color:#DAF7A6"><b>RSS 2024</b></span>.
- 2024.01: &nbsp; One paper(LaneSegNet) is accepted by  <span style="color:#00aeff;background-color:#e6f7ff"><b>ICLR 2024</b></span>.
- 2023.11: &nbsp; Going to serve as a reviewer for  <span style="color:#00aeff;background-color:#e6f7ff"><b>CVPR 2024</b></span>
- 2023.09: &nbsp; One paper(OpenLane-V2) is accepted by  <span style="color:#00aeff;background-color:#e6f7ff"><b>NeurIPS 2023</b></span>.
- 2023.07: &nbsp; Participate in [RACV 2023](https://mp.weixin.qq.com/s/xq5vVxIL27NLLQX9oFgv1w).
- 2023.03: &nbsp; Become a member of [OpenDriveLab](https://opendrivelab.com).
- 2023.02: &nbsp; Participate in MCM/ICM 2023, collaborating with Wenye Yu and Yunlin He.
- 2022.11: &nbsp; Become a member of  [ReThinkLab](https://thinklab.sjtu.edu.cn).
- 2022.08: &nbsp; Join Prof. [Nanyang Ye](https://ynysjtu.github.io)’s Laboratory in JHC, Shanghai Jiao Tong University.
- 2021.12: &nbsp; Enrolled in [Guozhi Class](http://www.qingyuan.sjtu.edu.cn/c/Introductiongzb).

# 💻 Internships
<div class='paper-box-right'><div class='paper-box-image'><div><a href="https://opendrivelab.com"><img src='images/odl_logo.png' alt="sym" width="100px" style="padding: 10px;"></a></div></div>
<div class='paper-box-text' markdown="1">
## OpenDriveLab

*2023.03 - (present)*, Supervisor: Prof. [Hongyang Li](https://lihongyang.info).
- **Robotics, Robot Learning**
- **Structural Understanding for Driving Scenes**

</div>
</div>

<div class='paper-box-right'><div class='paper-box-image'><div><a href="https://thinklab.sjtu.edu.cn"><img src='images/thinklab_logo.png' alt="sym" width="100px" style="padding: 10px;"></a></div></div>
<div class='paper-box-text' markdown="1">
## ReThinkLab, Shanghai Jiao Tong University

*2022.11 - (present)*, Supervisor: Prof. [Junchi Yan](https://thinklab.sjtu.edu.cn).
- **Image Retrieval, Image Matching**

</div>
</div>

<div class='paper-box-right'><div class='paper-box-image'><div><a href="https://ynysjtu.github.io/"><img src='images/sjtu_logo.png' alt="sym" width="100px" style="padding: 10px;"></a></div></div>
<div class='paper-box-text' markdown="1">
## Nanyang Ye’s lab, JHC, Shanghai Jiao Tong University

*2022.6 - 2022.11*, Supervisor: Prof. [Nanyang Ye](https://ynysjtu.github.io)
- **Causal Inference, OoD learning, OoD HDR Video Compression**
</div>
</div>

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/lane_segment.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Georgia, serif; font-size: 14px;">
[**LaneSegNet: Map Learning with Lane Segment Perception for Autonomous Driving**](https://arxiv.org/abs/2312.16108)

Tianyu Li$^\ast$, Peijin Jia$^\ast$, **Bangjun Wang$^\ast$**, Li Chen, Kun Jiang, Junchi Yan, Hongyang Li

[**Github**](https://github.com/OpenDriveLab/LaneSegNet)<strong><span class='show_paper_citations' data='_LeSlzUAAAAJ:u-x6o8ySG0sC'></span></strong>

- *We advocate Lane Segment as a map learning paradigm that seamlessly incorporates both map 🛣️ geometry and 🕸️ topology information.* <a href="https://github.com/OpenDriveLab/LaneSegNet"><img src="https://img.shields.io/github/stars/OpenDriveLab/LaneSegNet?style=social" alt="GitHub" style="opacity: .8"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeuraIPS 2023</div><img src='images/olv2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1" style="font-family:  Georgia, serif; font-size: 14px;">
[**OpenLane-V2: A Topology Reasoning Benchmark for Scene Understanding in Autonomous Driving**](https://openreview.net/pdf?id=OMOOO3ls6g)

Huijie Wang, Tianyu Li, Yang Li, Li Chen, Chonghao Sima, Zhenbo Liu, **Bangjun Wang**, Peijin Jia, Yuting Wang, Shengyin Jiang, Feng Wen, Hang Xu, Ping Luo, Junchi Yan, Wei Zhang, Hongyang Li

[**Project**](https://github.com/OpenDriveLab/OpenLane-V2) <strong><span class='show_paper_citations' data='_LeSlzUAAAAJ:u-x6o8ySG0sC'></span></strong>

- *The World's First Perception and Reasoning Benchmark for Scene Structure in Autonomous Driving.* <a href="https://github.com/OpenDriveLab/OpenLane-V2"><img src="https://img.shields.io/github/stars/OpenDriveLab/OpenLane-V2?style=social" alt="GitHub" style="opacity: .8"></a>
- [OpenLane Topology, AD Challenge 2023, CVPR 2023](https://opendrivelab.com/AD23Challenge.html#openlane_topology)
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations

- *2021.09 - Present*, Undergraduate, Artificial Intelligence, Guozhi Class, SEIEE, Shanghai Jiao Tong University.
- **TOEFL iBT**: 106(R:29, L:28, S:22, W:27)(first time), **CET6**: 638(first time)

# 🧑🏻‍💻 Service
- Reviewer for <span style="color:#00aeff;background-color:#e6f7ff"><b>CVPR 2024</b></span>
- Maintainer for [opendrivelab.com](https://opendrivelab.com) and [opendrivelab.sjtu.edu.cn](https://opendrivelab.sjtu.edu.cn)
- Administrator of Computing Cluster, Guozhi Class, SEIEE, Shanghai Jiao Tong University.
- Class monitor, Guozhi Class, SEIEE, Shanghai Jiao Tong University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

-  -->