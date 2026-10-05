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

Hi there! I am Qidi Shu, a PhD candidate from Hong Kong PolyU. 

I am interested in **AI for a Dynamic Earth**, with a focus on **understanding**, **reconstructing**, and **reasoning** about Earth surface changes from remote sensing images across time.

My research spans remote sensing image interpretation, multimodal data fusion, vision foundation models, and lies at the intersection of **discriminative understanding** and **generative modeling**.

I am particularly interested in **bi-temporal** and **timeseries remote sensing**, with the broader goal of moving beyond static perception toward modeling and understanding a changing Earth.

（_I am currently seeking opportunities in both academia and industry. Please feel free to reach out for potential collaborations or opportunities 🤝🤝_）


# 🔥 News
- *2026.10*: &nbsp;🎉🎉 Our work [**RESTORE-DiT**](https://www.sciencedirect.com/science/article/pii/S0034425725002767) is marked as **highly cited paper** in web of science! 
- *2026.09*: &nbsp;🎉🎉 One co-author work of **30-year China Settlement Footprint** mapping is accepted by Scientific Data! The dataset is available at [Link](https://zenodo.org/records/18276819).
- *2026.02*: &nbsp;🎉🎉 I have ended my six-month visit from SNU [Ecological Sensing AI Lab](https://www.environment.snu.ac.kr). A really fruitful and happy journey! Thank you, Prof. Ryu! I will miss all of you guys.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSE 2025</div><img src='images/RESTORE_DiT_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RESTORE-DiT: Reliable satellite image time series reconstruction by multimodal sequential diffusion transformer](https://www.sciencedirect.com/science/article/pii/S0034425725002767)

**Qidi Shu**, Xiaolin Zhu, Shuai Xu, Yan Wang, Denghong Liu

[**Code**](https://github.com/SQD1/RESTORE-DiT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- RESTORE-DiT is a novel Diffusion-based framework for Satellite Image Time Series (SITS) reconstruction. Our work firstly promotes the sequence-level optical-SAR fusion through a diffusion framework. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TGRS 2024</div><img src='images/CutMixCD_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CutMix-CD: Advancing Semi-Supervised Change Detection via Mixed Sample Consistency](https://ieeexplore.ieee.org/document/10810476)

**Qidi Shu**, Xiaolin Zhu, Luoma Wan, Shuheng Zhao, Denghong Liu, Longkang Peng, Xiaobei Chen

[**Code**](https://github.com/SQD1/CutMixCD) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- To address the issue of high labeling costs in bi-temporal image change detection tasks, we propose a novel semi-supervised method CutMix-CD, which incorporates the **pair-level change-aware CutMix** augmentation into the **consistency learning** framework. Using 20% of the labeled data, the F1 score (89.4%) reached a level close to that of fully supervised learning (90.4%).
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JAG 2022</div><img src='images/MTCNet_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MTCNet: Multitask consistency network with single temporal supervision for semi-supervised building change detection](https://www.sciencedirect.com/science/article/pii/S1569843222002989)

**Qidi Shu**, Jun Pan, Zhuoer Zhang, Mi Wang

[**Code**](https://github.com/SQD1/MTCNet) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Single-temporal labels serve as a **low-cost alternative** when change labels are limited! We present a new task called "Semi-supervised change detection with single temporal supervision". We propose a multitask consistency network (MTCNet), which fully takes the advantage of easily obtained single-temporal labels for bi-temporal change detection.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JAG 2022</div><img src='images/DPCCNet_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DPCC-Net: Dual-perspective change contextual network for change detection in high-resolution remote sensing](https://www.sciencedirect.com/science/article/pii/S1569843222001376)

**Qidi Shu**, Jun Pan, Zhuoer Zhang, Mi Wang

[**Code**](https://github.com/SQD1/DPCC-Net) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- DPCCNet emphasizes the process of extraction and optimization of change features by **bi-temporal feature fusion** and **contextual modeling**. The dual-perspective fusion (DPF) takes bi-temporal features as reference respectively to increase the sensitivity to change information. The change context module (CCM) incorporates abundant contexts to facilitate the integrity of change objects.
</div>
</div>


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2025.09 - 2026.02*, Visiting PhD in SNU [Ecological Sensing AI Lab](https://www.environment.snu.ac.kr).
- *2023.09 - now*, Pursing PhD degree in PolyU (The Hong Kong Polytechnic University), [PRIDE lab](https://xzhu-lab.github.io/post/home/).
- *2020.09 - 2023.06*, Master's degree in WHU (Wuhan University), research on computer vision and remote sensing intelligent interpretation.
- *2016.09 - 2020.06*, Bachelor’s degree in UESTC (University of Electronic Science and Technology of China), major in Spatial Information and Digital Technology. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
