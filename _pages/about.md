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

I am currently a first-year Ph.D. student in the Individualized Interdisciplinary Program at **The Hong Kong University of Science and Technology (HKUST)**, advised by [Prof. Anyi Rao](https://anyirao.com/) and [Prof. Huamin Qu](http://www.huamin.org/index.htm). I received my B.Eng. and M.Eng. degrees from **Beihang University (BUAA)**, where I was advised by [Prof. Si Liu](https://iai.buaa.edu.cn/info/1013/1096.htm). <a href='https://scholar.google.com/citations?user=yQ0CXqUAAAAJ'><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Frefkxh%2Frefkxh.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

I was fortunate to have interned at several leading tech companies, including **Alibaba Group**, **Baidu Inc.**, and **Meituan**, where I gained valuable industry experience and insights into real-world applications of computer vision and AI technologies.

My current research interest includes visual content generation and editing, visual creativity, and visual storytelling. I am passionate about exploring how to leverage advanced AI techniques to enhance human creativity and storytelling through visual media.

# 🔥 News

- *Dec. 2025*: &nbsp;🎉🎉 Excited to introduce [BiCo](https://refkxh.github.io/BiCo_Webpage/) that enables flexible concept composition from images and videos!

# 📝 Selected Papers

*: equal contribution, †: corresponding author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv Preprint</div><img src='images/bico.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Composing Concepts from Images and Videos via Concept-prompt Binding](https://arxiv.org/abs/2512.09824)

**Xianghao Kong**, Zeyu Zhang, Yuwei Guo, Zhuoran Zhao, Songchun Zhang, Anyi Rao

[**Project**](https://refkxh.github.io/BiCo_Webpage/) [**Code**](https://github.com/refkxh/bico)
<!-- <strong><span class='show_paper_citations' data='yQ0CXqUAAAAJ:A_FxGoFyzp5QC'></span></strong> -->

- We introduce Bind & Compose (BiCo), a one-shot method that enables flexible visual concept composition by binding visual concepts with the corresponding prompt tokens and composing the target prompt with bound tokens from various sources.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv Preprint</div><img src='images/ifv2v.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Taming Flow-based I2V Models for Creative Video Editing](https://arxiv.org/abs/2509.21917)

**Xianghao Kong**, Hansheng Chen, Yuwei Guo, Lvmin Zhang, Gordon Wetzstein, Maneesh Agrawala, Anyi Rao

<!-- [**Code**](https://github.com/refkxh/C-Instructor) -->
<!-- <strong><span class='show_paper_citations' data='yQ0CXqUAAAAJ:A_FxGoFyzp5QC'></span></strong> -->

- We propose IF-V2V, an Inversion-Free method that can adapt off-the-shelf flow-matching-based I2V models for video editing without significant computational overhead.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv Preprint</div><img src='images/profashion.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ProFashion: Prototype-guided Fashion Video Generation with Multiple Reference Images](https://arxiv.org/abs/2505.06537)

**Xianghao Kong**, Qiaosong Qi, Yuanbin Wang, Anyi Rao, Biaolong Chen, Aixi Zhang, Si Liu, Hao Jiang

<!-- [**Code**](https://github.com/refkxh/C-Instructor) -->
<!-- <strong><span class='show_paper_citations' data='yQ0CXqUAAAAJ:AWF5omc3nYNoC'></span></strong> -->

- ProFashion is a prototype-guided fashion video generation framework leveraging multiple reference images and human keypoint motion flow to achieve improved view consistency and temporal coherence.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/cinstructor.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Controllable Navigation Instruction Generation with Chain of Thought Prompting](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/04155.pdf)

**Xianghao Kong**<sup>*</sup>, Jinyu Chen<sup>*</sup>, Wenguan Wang<sup>†</sup>, Hang Su, Xiaolin Hu, Yi Yang, Si Liu<sup>†</sup>

[**Code**](https://github.com/refkxh/C-Instructor)
<!-- <strong><span class='show_paper_citations' data='yQ0CXqUAAAAJ:AzYLM7Y9cAGgC'></span></strong> -->

- We propose C-Instructor, which utilizes the chain-of-thought-style prompt for style-controllable and content-controllable instruction generation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/dusa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DUSA: Decoupled Unsupervised Sim2Real Adaptation for Vehicle-to-Everything Collaborative Perception](https://arxiv.org/abs/2310.08117)

**Xianghao Kong**, Wentao Jiang, Jinrang Jia, Yifeng Shi<sup>†</sup>, Runsheng Xu, Si Liu

[**Code**](https://github.com/refkxh/DUSA)
<!-- <strong><span class='show_paper_citations' data='yQ0CXqUAAAAJ:Ad1gkVwhDpl0C'></span></strong> -->

- DUSA decouples the V2X collaborative sim2real domain adaptation problem into two sub-problems: sim2real adaptation and inter-agent adaptation.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022 (Oral)</div><img src='images/3dsps.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[3D-SPS: Single-Stage 3D Visual Grounding via Referred Point Progressive Selection](https://openaccess.thecvf.com/content/CVPR2022/html/Luo_3D-SPS_Single-Stage_3D_Visual_Grounding_via_Referred_Point_Progressive_Selection_CVPR_2022_paper.html)

Junyu Luo<sup>*</sup>, Jiahui Fu<sup>*</sup>, **Xianghao Kong**, Chen Gao<sup>†</sup>, Haibing Ren, Hao Shen, Huaxia Xia, Si Liu

[**Code**](https://github.com/fjhzhixi/3D-SPS)
<!-- <strong><span class='show_paper_citations' data='yQ0CXqUAAAAJ:Au5HHmVD_uO8C'></span></strong> -->

- 3D-SPS bridges the gap between detection and matching in the 3D visual grounding task and localizes the target in a single stage.

</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 👨‍🎓 Educations

- *Sept. 2025 - Present*, **Ph.D. Student in Individualized Interdisciplinary Program, The Hong Kong University of Science and Technology (HKUST)**
  - Current Research Directions: Visual Content Generation and Editing, Visual Creativity
  - Supervisors: [Prof. Anyi Rao](https://anyirao.com/), [Prof. Huamin Qu](http://www.huamin.org/index.htm)
- *Sept. 2022 - Jan. 2025*, **M.Eng. in Computer Science and Technology, Beihang University (BUAA)**
  - Main Research Directions: Visual Content Generation, Vision & Language, Collaborative Perception
  - Supervisor: [Prof. Si Liu](https://iai.buaa.edu.cn/info/1013/1096.htm)
  - Standardized Tests: TOEFL 114 / 120, GRE 332 / 340
- *Sept. 2018 - June 2022*, **B.Eng. in Computer Science and Technology, Beihang University (BUAA)**
  - Comprehensive Performance Ranking: 1st / 193

# 💻 Internships

- *June 2024 - Nov. 2024*, Taobao & Tmall Group, Alibaba Group
- *Nov. 2022 - July 2023*, Baidu Inc.
- *July 2022 - Nov. 2022*, Alibaba Group
- *July 2021 - July 2022*, Meituan

# 🎖 Achievements

- Hong Kong PhD Fellowship (HKPFS)
- National Scholarship of China (both undergraduate and postgraduate levels)
- Samsung Scholarship, and many university-level and school-level scholarships
- Outstanding Graduate of Beijing
- Merit Student of Beihang University, Outstanding Student of Beihang University

<span class='anchor' id='academic-services'></span>

# 🕴️ Academic Services

- Organizer of the 7th [CVEU Workshop](https://cveu.github.io/) at SIGGRAPH 2025
- Conference Reviewer for CVPR, SIGGRAPH Asia, AAAI, and ACM MM

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
