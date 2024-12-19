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

I am currently a joint master's student at SIGS of Tsinghua University and Huawei Technologies, supervised by <a href="https://www.sigs.tsinghua.edu.cn/lr/main.htm">Prof. Ran Liao</a> and <a href="https://gao-duan.github.io/">Dr. Duan Gao</a>.
<!-- In the first year of my master's degree, I worked on polarization optics for classification using machine learning methods. Now, -->
My research focuses on the intersection of computer vision, computer graphics, and deep learning, with a focus on 3D/2D generation.
I'm also involved in denoising for Monte Carlo rendering and model watermarking during my internship.
Before that, I received my B.E. degree in 2022 from Shanghai Polytechnic University. 


# 🔥 News
- *2024.10*: &nbsp; I'm looking for an opportunity to study for a Ph.D.
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/controlface.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ControlFace: Few-Shot 3D Face Generation via a Controllable Diffusion Model Guided by Text and Images](pdf/ControlFace.pdf)

**Jinfu Wei\***, Zheng Zhang\*, Ran Liao, Duan Gao

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- A novel framework for generating high-quality digital faces, combining the diversity inherent in pre-trained T2I diffusion models with the 3D facial priors;
- A controllable diffusion model that can generate 4K PBR facial maps supporting few-shot training and fast generation in a feed-forward manner;
- A wide range of manipulations and controls, allowing for both localized and global editing and precise adjustments to facial geometry at both detailed (wrinkles) and overall levels (topology).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/unifacegan.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UniFaceGAN: High-Quality 3D face Editing with a Unified Latent Space](pdf/UniFaceGAN.pdf)

**Jinfu Wei**, Zheng Zhang, Ran Liao, Duan Gao

- A 3D face generation framework, which bridges a unified latent space for geometry and PBR materials of faces, enabling high-quality 3D face generation and editing;
- A stylization method to synchronously manipulate PBR appearances with only a simple text description;
- A novel way to manipulate face geometries with prior of GANs, which preserves better facial consistency than previous methods.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/dreampbr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DreamPBR: Text-driven Generation of High-resolution SVBRDF with Multi-modal Guidance](https://arxiv.org/pdf/2404.14676)

Linxuan Xin, Zheng Zhang, **Jinfu Wei**, Wei Gao, Duan Gao

- We introduce a novel generative framework for high-quality material generation under text and multi-modal guidances that combine pre-trained 2D diffusion model and material domain priors efficiently;
- We present a rendering-aware decoder module that learns the mapping from a shared latent space to SVBRDFs;
- Our multi-model guidance module offers rich user-friendly controllability, enabling users to manipulate the generation process effectively;
- We propose an image-to-image editing scheme that facilitates material editing tasks such as stylization, inpainting, and seamless texture synthesis.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under review</div><img src='images/dpwd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dual-Process Watermarked Diffusion: Integrating Watermarking with Denoising in Point Clouds](pdf/DPWD.pdf)

**Jinfu Wei**\*, Heng Chang\*, Xiaohang Liu\*, Li Liu, Likun Li, Shiji Zhou, Chengyuan Li, Di Xu, Wei Gao, Ran Liao

- The first approach to add watermarks in DMs for point cloud generation;
- PI-HiDDeN tackles the challenge of extracting watermarks in the point cloud from the permutation invariant embedding space. 
- The dual-period distilling confronts the challenge of the accumulation of gradients in DMs that prevents the completion of the point cloud;
</div>
</div>

- `Under review` [Implanting Robust Watermarks in Latent Diffusion Models for Video Generation](pdf/Video_icassp-hang.pdf) Xiaohang Liu\*, Heng Chang\*, **Jinfu Wei**, Lei Zhu, Li Liu, Likun Li, Shiji Zhou, Chengyuan Li, Di Xu, Wei Gao

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📖 Educations
- *2018.09 - now*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.06 - now*, [Media Innovation Lab, Huawei](https://www.huaweicloud.com/lab/multimedia/home.html), China.

# 💡 Misc
- I am a big fan of detective fiction novels and movies.
- I tend to jog if too tired after a day's study.
- I like games with a high degree of freedom and/or excellent plots. (The Legend of Zelda, The Witcher, Elden Ring, Wukong...)
