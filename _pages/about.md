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

Welcome to my homepage!

I'm a senior student majored in information security at the School of Electronic Information and Electrical Engineering of Shanghai Jiao Tong University(SJTU) and an undergraduate member of Thinklab.

My research interest includes natural language processing and time-series analysis.


# 🔥 News
- *2024.05*: &nbsp;🎉🎉 Our work, UP2ME: Univariate Pre-training to Multivariate Fine-tuning as a General-purpose Framework for Multivariate Time Series Analysis, was been accepted by ICML 2024. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/UP2ME.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UP2ME: Univariate Pre-training to Multivariate Fine-tuning as a General-purpose Framework for Multivariate Time Series Analysis](https://icml.cc/virtual/2024/poster/33686)

Yunhao Zhang, Minghao Liu, Shengyang Zhou, Junchi Yan

- UP2ME is a general-purpose framework for Multivariate Time Series Analysis. It conducts taskagnostic pre-training when downstream tasks are unspecified. Once the task and setting (e.g. forecasting length) are determined, it gives sensible solutions with frozen pre-trained parameters. Further accuracy is achieved through multivariate fine-tuning.
</div>
</div>

# 🎖 Honors and Awards
- *2022.05* Finalist Prize in 2022 MCM

# 📖 Educations
- *2021.09 - 2025.06 (now)*, BEng in Information Security, Shanghai Jiao Tong University 

# 💻 Internships
- *2023.09 - 2025.06 (now)*, intern in [ThinkLab](https://thinklab.sjtu.edu.cn/), China as an undergraduate student
- *2024.06 - 2024.08*, intern in [Meituan](https://www.meituan.com/)
- *2022.06 - 2023.09*, intern in [NSEC Lab](https://nsec.sjtu.edu.cn/), China as an undergraduate student
