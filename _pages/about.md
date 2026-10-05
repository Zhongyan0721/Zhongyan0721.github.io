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

Hi there! My name is Zhongyan Luo. Currently, I am a Master's student in Machine Learning at **Carnegie Mellon University (CMU)**. I received my B.S. in Data Science from the **University of California, San Diego (UCSD)**.

My research interests include **AI Agents**, **AI Infra**, and **Scalable Machine Learning**. Previously, I interned at Teradata as an AI Engineer and focused on Learning Agent (self-evolving in production traffic). Earlier, I interned at Transwarp and focused on AI Infra. I was a Research Assistant at **UCSD MixLab**, working on Auto Research, Inference Acceleration and AI Personalization, advised by Prof. [Zhiting Hu](https://zhiting.ucsd.edu/), Prof. [Hao Zhang](https://haozhang.ai/), and Prof. [Zhen Wang](https://zhenwang9102.github.io/).

Looking for 2027 Summer Internship Opportunity!


# 🔥 News
- *2026.03*: &nbsp;🎉🎉 Paper "FIRE-Bench" accepted to **ICML 2026**.
- *2025.11*: &nbsp;🎉🎉 Paper "DeepPersona" accepted as **Spotlight** at NeurIPS 2025 LAW Workshop.
- *2025.01*: &nbsp;🎉🎉 Paper "Exploration and practice of human-machine trustworthy mechanism in XAI" published on **Big Data Research**.

# 📝 Publications 

- [FIRE-Bench: Evaluating Research Agents on the Rediscovery of Scientific Insights](https://arxiv.org/abs/2602.02905) *(ICML 2026)*
  Zhen Wang\*, Fan Bai\*, **Zhongyan Luo**\*, Jinyan Su, Kaiser Sun, Weiqi Liu, Albert Chen, Jieyuan Liu, Kun Zhou, Claire Cardie, Mark Dredze, Eric P. Xing, Zhiting Hu

- [Paper Agent Network: Literature-Grounded Multi-Agent Program Discovery](https://openreview.net/) *(In Submission)*
  Xinle Yu, Enze Ma, **Zhongyan Luo**, Tianchun Wang, Shuaichen Chang, Zhen Wang

- [PrimeScientist: Strategic Allocation of Research Effort in Autonomous Research](https://arxiv.org/abs/2609.178465) *(In Submission)*
  Xinle Yu, Fan Bai, Kaiser Sun, Hengshuo Miao, Abhay Anand, **Zhongyan Luo**, Kun Zhou, Zhen Wang

- [DeepPersona: A Generative Engine for Scaling Deep Synthetic Personas](https://arxiv.org/abs/2511.07338) *(NeurIPS 2025 LAW Spotlight)*
  Zhen Wang\*, Yufan Zhou\*, **Zhongyan Luo**, Lyumanshan Ye, Adam Wood, Man Yao, Saab Mansour, Luoshang Pan

- [Exploration and practice of human-machine trustworthy mechanism in XAI](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=baKADWoAAAAJ&citation_for_view=baKADWoAAAAJ:u5HHmVD_uO8C) *(Published on Big Data Research)*
  **Zhongyan Luo**, Zhengxun Xia, Jianfei Tang, Yifan Yang, Hongshan Yang, Haohua Li, Yan Zhang

- *(Patent)* SQL generation method, device, equipment and medium based on background knowledge enhancement
- *(Patent)* Question answering method and apparatus based on large language model, electronic device, and storage medium
- *(Patent)* Information classification method, device, equipment and storage medium
- *(Patent)* Method and device for query processing of label data, computer equipment and medium

# 📖 Educations
- *2026.09 - 2028.06*, M.S. in Machine Learning, Carnegie Mellon University (CMU), Pittsburgh, PA
- *2024.09 - 2026.06*, B.S. in Data Science, University of California, San Diego (UCSD), San Diego, CA
- *2022.09 - 2024.06*, B.S. in Data Science, University of California, Santa Barbara (UCSB), Santa Barbara, CA

# 💻 Experience
- *2026.06 - 2026.08*, AI Engineer Intern, [Teradata](https://www.teradata.com/)
- *2025.04 - 2026.04*, Research Assistant, [UCSD MixLab](https://maitrix.org/)
- *2024.06 - 2024.09*, AI Research Intern, [Transwarp](https://www.transwarp.io/)
- *2023.06 - 2023.09*, Software Engineer Intern, [Transwarp](https://www.transwarp.io/)

# 🛠 Projects
- *2025.02*, **Language Model System Optimization** \| Python, NLP, Web Scraping
  - Ported inference acceleration algorithms including Speculative Decoding from GPU to TPU, achieving 3x avg speedup.
  - PR (#1868) merged to vLLM project TPU inference repo (400+ stars).
