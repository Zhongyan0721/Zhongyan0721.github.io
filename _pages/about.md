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

I am a Master's student in Machine Learning at **Carnegie Mellon University (CMU)**. I received my B.S. in Data Science from the **University of California, San Diego (UCSD)** and the **University of California, Santa Barbara (UCSB)** (GPA: 3.96/4.0, Provost Honor, Top 2%).

My research interests include **LLM systems**, **AI agents**, **explainable AI**, and **machine learning**. I have experience building large-scale AI systems, developing research agents, and optimizing language model training and inference pipelines. I am currently a Research Assistant at **UCSD MixLab x Meta AI**, working on AI research agents and personalization.


# 🔥 News
- *2025.04*: &nbsp;🎉🎉 Started research collaboration with UCSD MixLab x Meta AI on AI Research Agents.
- *2025.02*: &nbsp;🎉🎉 Language Model System Optimization project completed — achieved 5x speedup via Speculative Decoding on TPU.
- *2024.09*: &nbsp;🎉🎉 Paper "DeepPersona" accepted as **Spotlight** at NeurIPS 2025 LAW Workshop.

# 📝 Publications 

- [FIRE-Bench: Evaluating Research Agents on the Rediscovery of Scientific Insights](https://github.com) *(ICML 2026 Under Review)*
  Zhen Wang\*, Fan Bai\*, **Zhongyan Luo**\*, Jinyan Su, Kaiser Sun, Weiqi Liu, Albert Chen, Jieyuan Liu, Kun Zhou, Claire Cardie, Mark Dredze, Eric P. Xing, Zhiting Hu

- [DeepPersona: A Generative Engine for Scaling Deep Synthetic Personas](https://github.com) *(NeurIPS 2025 LAW Spotlight)*
  Zhen Wang\*, Yufan Zhou\*, **Zhongyan Luo**, Lyumanshan Ye, Adam Wood, Man Yao, Saab Mansour, Luoshang Pan

- [Exploration and practice of human-machine trustworthy mechanism in XAI](https://github.com) *(Published on Big Data Research)*
  **Zhongyan Luo**, Zhengxun Xia, Jianfei Tang, Yifan Yang, Hongshan Yang, Haohua Li, Yan Zhang

- *(Patent)* SQL generation method, device, equipment and medium based on background knowledge enhancement
- *(Patent)* Question answering method and apparatus based on large language model, electronic device, and storage medium
- *(Patent)* Information classification method, device, equipment and storage medium
- *(Patent)* Method and device for query processing of label data, computer equipment and medium

# 🎖 Honors and Awards
- *2022 - 2024* Provost Honor, University of California, Santa Barbara (Top 2%)
- *2022 - 2024* GPA: 3.96/4.0

# 📖 Educations
- *2026.09 - 2028.06*, M.S. in Machine Learning, Carnegie Mellon University (CMU), Pittsburgh, PA
- *2024.09 - 2026.06*, B.S. in Data Science, University of California, San Diego (UCSD), San Diego, CA
- *2022.09 - 2024.06*, B.S. in Data Science, University of California, Santa Barbara (UCSB), Santa Barbara, CA

# 💻 Experience
- *2025.04 - Present*, Research Assistant, [UCSD MixLab x Meta AI](https://github.com)
  - Developed AI Research Agent using LangGraph, integrating brainstorming, multi-agent discussion and runtime tools.
  - Benchmarked scientific discovery ability of AI Research Agents by building a containerized environment using Docker.
  - Built large scale human-attribute taxonomy and synthesized MB-level profiles, promoting better personalization in AI.
  - Constructed a meta-learning framework for self-evolving agent skills, achieving 40% accuracy increase on SkillsBench.

- *2024.06 - 2024.09*, AI Research Intern, [Transwarp](https://github.com)
  - Implemented LoRA-based fine-tuning pipeline in PyTorch improving downstream tasks accuracy by around 15%.
  - Established automated evaluation pipeline for 20+ Text2SQL benchmarks via vLLM, LLM APIs and Python SQLite.
  - Built finance-oriented RAG system that integrates 200+ multimodal documents, achieving 30% accuracy increase.
  - Built an XAI (Explainable AI) module through a single interface, making model behavior easier to audit and debug.

- *2023.06 - 2023.09*, Software Engineer Intern, [Transwarp](https://github.com)
  - Contributed to Kubernetes-based LLM training platform; used TorchX and Volcano to optimize resource allocation.
  - Integrated Prometheus and Grafana dashboards for training & inference workload, reducing debugging time by 50%.
  - Built a security gateway for AI applications and deployed via CI/CD pipelines, reducing information leakage by 98%.
  - Automated microservice releases using Docker and Kubernetes deployment workflow for repeatable rollouts & scaling.

# 🛠 Projects
- *2025.02*, **Language Model System Optimization** \| Python, NLP, Web Scraping
  - Improved training throughput and memory utilization by enabling mixed precision, ZeRO-3, and FlashAttention.
  - Transfer inference accelerating algorithms including Speculative Decoding from GPU to TPU, achieving 5x speedup.

- *2024.04*, **Path Tracing Render** \| C++, Computer Graphics, Offline Rendering
  - Engineered path tracing renderer in C++ implementing Multiple Importance Sampling and Microfacet BRDF.
  - Integrated in-depth acceleration structures including BVH trees handling complex scenes with 100K+ polygons.
