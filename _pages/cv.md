---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
excerpt: "Curriculum vitae of Zhenyu Hou: education, research experience, publications, talks, and teaching."
description: "CV of Zhenyu Hou, PhD student at Tsinghua University, focusing on language models, agents, and reinforcement learning."
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in Computer Science and Technology, Tsinghua University, 2021–present
* BS in Computer Science and Technology, Tsinghua University, 2017–2021

Research interests
======
Language Model Agent and Reasoning; Reinforcement Learning; LLM Alignment; Self-Supervised Learning on Graphs

Experience
======
* GLM Team, Zhipu AI / Tsinghua University — Core Contributor
  * Led post-training (RLHF/RL) for improved reasoning and alignment across the ChatGLM and GLM model families.
  * Tech lead for the GLM-4.5 series; drove agentic, reasoning, and coding capability development.
  * Drove LLM training/evaluation iterations for GLM-5 agentic engineering.

Open-source projects
======
* [GraphMAE](https://github.com/THUDM/GraphMAE) / [GraphMAE2](https://github.com/THUDM/GraphMAE2) — Self-supervised masked graph autoencoders (KDD 2022, WWW 2023)
* [CogDL](https://github.com/THUDM/CogDL) — Comprehensive library for graph deep learning (WWW 2023)
* [AutoProNE](https://github.com/THINK2TRY/AutoProNE) — Automated unsupervised graph representation learning (TKDE 2021)

Skills
======
* Python, PyTorch
* Large language model training and RLHF
* Graph neural networks and representation learning

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Professional profiles
======
* [Google Scholar](https://scholar.google.com/citations?hl=zh-CN&oi=ao&user=44W9SfwAAAAJ)
* [GitHub](https://github.com/think2try)
* [KEG Lab](https://keg.cs.tsinghua.edu.cn/)
