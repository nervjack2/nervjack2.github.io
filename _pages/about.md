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

I am currently a first-year PhD student at National Taiwan University, in the Speech Processing and Machine Learning Lab. 
My research interests include speech self-supervised models, model compression, and neuron analysis. 
I am eager to explore new research areas and am currently looking for research internships for the year 2025. 
If there are any possibilities for research collaboration, please feel free to contact me.

# 🔥 News
- *2024.06*: &nbsp;🎉🎉 Two papers accepted at Interspeech 2024. See you in Greece!
- *2023.09*: &nbsp;🎉🎉 One paper accepeted at ASRU 2023.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Interspeech 2024</div><img src='_pages/images/daisy-interspeech-2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

DAISY: Data Adaptive Self-Supervised Early Exit for Speech Representation Models

**Tzu-Quan Lin**, Hung-yi Lee, Hao Tang

- This work introduces a novel early exit method for speech self-supervised models that enhances the speed of HuBERT with minimal performance loss.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASRU 2023</div><img src='_pages/images/melhubert-asru-2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MelHuBERT: A Simplified Hubert on Mel Spectrograms](https://ieeexplore.ieee.org/abstract/document/10389700)

**Tzu-Quan Lin**, Hung-yi Lee, Hao Tang

[**Project**](https://github.com/nervjack2/MelHuBERT)
- MelHuBERT simplifies the model architecture and loss function of HuBERT, achieving comparable performance while saving 33.5% of MACs per one second of speech.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Submitted to TASLP (under review)</div><img src='_pages/images/compression-taslp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Compressing Transformer-based self-supervised models for speech processing](https://arxiv.org/abs/2211.09949)

**Tzu-Quan Lin**, Tsung-Huan Yang, Chun-Yao Chang, Kuang-Ming Chen, Tzu-hsun Feng, Hung-yi Lee, Hao Tang

[**Project**](https://github.com/nervjack2/Speech-SSL-Compression/)
- This work propose evaluating model compression methods using three different metrics: MACs, number of parameters, and real-time factor. We find that different compression methods excel in different metrics.
</div>
</div>

- On the social bias of speech self-supervised models, Yi-Cheng Lin, **Tzu-Quan Lin**, Hsi-Che Lin, Andy t. Liu, Hung-yi Lee. **Interspeech 2024**
- [Superb @ SLT 2022: Challenge on Generalization and Efficiency of Self-Supervised Speech Representation Learning](https://ieeexplore.ieee.org/abstract/document/10022770), Tzu-hsun Feng, Annie Dong, Ching-Feng Yeh, Shu-wen Yang, **Tzu-Quan Lin**, Jiatong Shi, et al.. **SLT 2022 Best Paper Finalists**

# 📖 Educations
- *(start from)2024.09*, PhD in Electrical, Electronics, Communications Engineering, National Taiwan University
- *2022.09 - 2024.06*, Master in Networking and Multimedia, National Taiwan University
- *2019.09 - 2022.06*, Bachelor in Department of Computer Science and Information Engineering, National Taiwan University 

# 💻 Internships
- *2021.07 - 2021-09*, [aetherAI](https://www.aetherai.com/), Taipei, Taiwan.
