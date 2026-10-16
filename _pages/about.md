
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

I am **Haoxi Li (李昊翕)**, a Ph.D. student in the Department of Computer Science and Engineering at **The Hong Kong University of Science and Technology (HKUST)**.

My research focuses on **reasoning and decision-making in foundation models**, particularly large reasoning models, reinforcement learning, and vision-language agents. I am interested in developing intelligent systems that can reason efficiently, evaluate their own decisions, and continually improve through interaction with their environments.

You can find my publications on [Google Scholar](https://scholar.google.com/citations?user=zVSdKpoAAAAJ).

<span class='anchor' id='research'></span>

# 🔬 Research Interests

- **Large Reasoning Models:** Efficient reasoning, metacognition, and reliable model behavior.
- **Agentic Reinforcement Learning:** Self-exploration, test-time adaptation, and adaptive decision-making.
- **Vision-Language Agents:** World modeling, multimodal reasoning, and curiosity-driven exploration.

<span class='anchor' id='news'></span>

# 🔥 News

- **2026.07:** Our paper on visual-linguistic curiosity (**GLANCE**) was published at **ICML 2026**.
- **2026.07:** Our papers **Think How to Think** and **TTVS** were published at **ACL 2026** and **Findings of ACL 2026**, respectively.
- **2025.04:** Our paper **CausM** was accepted at **ICLR 2025**.

<span class='anchor' id='publications'></span>

# 📝 Selected Publications

### 2026

**[What You Think is What You See: Driving Exploration in VLM Agents via Visual-Linguistic Curiosity](https://proceedings.mlr.press/v306/li26bj.html)**

**Haoxi Li**, Qinglin Hou, Jianfei Ma, Jinxiang Lai, Tao Han, Sikai Bai, Jingcai Guo, Jie Zhang, Song Guo

*International Conference on Machine Learning (ICML), 2026*

[Paper](https://proceedings.mlr.press/v306/li26bj.html)

A curiosity-driven exploration framework that connects linguistic world modeling with visual feedback in VLM agents.

---

**[Think How to Think: Mitigating Overthinking with Autonomous Difficulty Cognition in Large Reasoning Models](https://aclanthology.org/2026.acl-long.1766/)**

Yongjiang Liu, **Haoxi Li**, Xiaosong Ma, Jie Zhang, Song Guo

*Annual Meeting of the Association for Computational Linguistics (ACL), 2026*

[Paper](https://aclanthology.org/2026.acl-long.1766/)

Improving reasoning efficiency by enabling language models to recognize task difficulty and reduce redundant reasoning.

---

**[TTVS: Boosting Self-Exploring Reinforcement Learning via Test-time Variational Synthesis](https://aclanthology.org/2026.findings-acl.1634/)**

Sikai Bai, **Haoxi Li**, Jie Zhang, Yongjiang Liu, Song Guo

*Findings of the Association for Computational Linguistics (ACL), 2026*

[Paper](https://aclanthology.org/2026.findings-acl.1634/)

A test-time self-exploration framework that improves reasoning models through variational synthesis and unlabeled queries.

---

### 2025

**[CausM: Causally Motivated Sycophancy Mitigation for Large Language Models](https://openreview.net/pdf/a24fb8781480a42b0b7877a0529b415440c7a3a7.pdf)**

**Haoxi Li**, Xueyang Tang, Jie Zhang, Song Guo, Sikai Bai, Peiran Dong, Yue Yu

*International Conference on Learning Representations (ICLR), 2025*

[Paper](https://openreview.net/pdf/a24fb8781480a42b0b7877a0529b415440c7a3a7.pdf)

A causally motivated framework for mitigating sycophantic behavior and improving the reliability of large language models.

---

**[CoRE: Enhancing Metacognition with Label-free Self-evaluation in LRMs](https://arxiv.org/abs/2507.06087)**

**Haoxi Li**, Sikai Bai, Jie Zhang, Song Guo

*arXiv Preprint, 2025*

[Paper](https://arxiv.org/abs/2507.06087)

A latent-representation-based approach to self-evaluating reasoning trajectories without external labels.

<span class='anchor' id='education'></span>

# 📖 Education

- **Ph.D. Student**, Department of Computer Science and Engineering, The Hong Kong University of Science and Technology (HKUST).
