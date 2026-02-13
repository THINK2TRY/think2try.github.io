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
* PhD in Computer Science and Technology, Tsinghua University, 2021-present
* BEng in Computer Science and Technology, Tsinghua University, 2017-2021

Research interests
======
* Graph machine learning
* Self-supervised learning
* Recommender systems and robustness
* Large language models, reasoning, and agent systems

Experience
======
* GLM Team, Core Contributor
  * Led GLM post-training for improved reasoning and alignment.
  * Lead agent contributor for GLM-4.5.
  * Drove LLM training/evaluation iterations for agentic and coding capabilities.
  
Skills
======
* Python
* PyTorch
* Graph neural networks
* Representation learning

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Professional profiles
======
* OpenReview: https://openreview.net/profile?id=~Zhenyu_Hou1
* MADSys: https://www.madsys.cs.tsinghua.edu.cn/author/zhenyuhou/
* DBLP: https://dblp.org/pid/248/9148.html
