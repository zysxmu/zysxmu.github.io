---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D.** in Intelligence Science and Technology, Xiamen University, 2021 – 2025
  * Advisor: Prof. Rongrong Ji
  * MAC Lab, Institute of Artificial Intelligence
* **M.S.** in Software Engineering, Peking University, 2017 – 2020
* **B.S.** in Software Engineering, Beijing Institute of Technology, 2013 – 2017

Research Interests
======
* Model Quantization & Compression
* Post-Training Quantization (PTQ) & Data-Free Quantization
* Efficient Vision Transformers
* Diffusion Model Acceleration
* Image Restoration (Super-Resolution, Demoireing)
* Efficient LLM Inference

Work Experience
======
* **2023.05 – Present** — AI Teacher / Researcher
  * Xiamen University
  * Focus: Efficient deep learning, model quantization, ViT compression

* **Summer 2022 – Spring 2023** — Research Intern
  * Pengcheng Lab, Shenzhen
  * Focus: Post-training quantization for vision models

* **2020.11 – 2021.09** — Research Intern
  * MAC Lab, Xiamen University
  * Focus: Network compression and acceleration

* **2020.07 – 2020.11** — R&D Engineer
  * Baidu, Beijing
  * Computer vision and deep learning systems

* **2019.11 – 2020.02** — Research Intern
  * Kuaishou Technology, Beijing
  * Video understanding and model efficiency

* **2018.09 – 2019.09** — Research Intern
  * Megvii Technology (Face++), Beijing
  * Person re-identification and image generation

Skills
======
* **Deep Learning Frameworks:** PyTorch, TensorFlow
* **Programming:** Python, C/C++, CUDA
* **Tools:** Git, Docker, Linux, LaTeX
* **Languages:** Chinese (Native), English (Fluent)

Professional Service
======
* **Reviewer:** ICML, ICLR, NeurIPS, CVPR, ICCV, ECCV
* **Reviewer:** IEEE TNNLS, IEEE TCSVT

Publications
======
A complete list of my publications can be found on the [Publications](/publications/) page or [Google Scholar](https://scholar.google.com/citations?user=g1-HBJAAAAAJ&hl=zh-CN).

**First/co-first author papers at top venues:**
  * 2x TPAMI, 1x SCIS — top AI journals
  * ICML (Spotlight), ICLR, AAAI — top ML conferences
  * 2x ICCV, 2x ECCV, CVPR — top vision conferences
  * 15+ papers in CCF-A/B venues

Teaching
======
{% for post in site.teaching %}
  {% include archive-single.html %}
{% endfor %}
