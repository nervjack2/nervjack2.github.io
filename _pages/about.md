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

I am currently a first-year PhD student at National Taiwan University, supervised by Prof. Hung-yi Lee, in the Speech Processing and Machine Learning Lab. 
My research interests include speech foundation models, spoken language models, model compression, neuron analysis, and model merging. 
I am eager to explore new research areas and am currently looking for research internships for the year 2025. 
If there are any possibilities for research collaboration, please feel free to contact me.

# 🔥 News
- *2024.09*: &nbsp;🎉🎉 Two papers accepted at SLT 2024 main conference track. See you in Macao 🇲🇴!
- *2024.06*: &nbsp;🎉🎉 Two papers accepted at Interspeech 2024. See you in Greece 🇬🇷!
- *2023.09*: &nbsp;🎉🎉 One paper accepeted at ASRU 2023.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='_pages/images/compression-taslp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Is Smaller Always Faster? Tradeoffs in Compressing Self-Supervised Speech Transformers](https://arxiv.org/abs/2211.09949)

**Tzu-Quan Lin**, Tsung-Huan Yang, Chun-Yao Charly registrationang, Kuang-Ming Chen, Tzu-hsun Feng, Hung-yi Lee, Hao Tang

[**Project**](https://github.com/nervjack2/Speech-SSL-Compression/)
- This work propose evaluating model compression methods using three different metrics: MACs, number of parameters, and real-time factor. We find that different compression methods excel in different metrics.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='_pages/images/speechft.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Speech-FT: Merging Pre-trained And Fine-Tuned Speech Representation Models For Cross-Task Generalization](https://arxiv.org/abs/2502.12672)

**Tzu-Quan Lin**, Wei-Ping Huang, Hao Tang, Hung-yi Lee

- Speech-FT is a two-stage fine-tuning framework designed for speech representation learning. It improves performance on specific tasks while maintaining cross-task generalization ability.
- Speech-FT improves HuBERT’s performance on SUPERB by reducing phone error rate from 5.17% to 3.94%, lowering word error rate from 6.38% to 5.75%, and boosting speaker ID accuracy from 81.86% to 84.11%.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='_pages/images/mamba-ssl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An Exploration of Mamba for Speech Self-Supervised Models](https://arxiv.org/abs/2506.12606)

**Tzu-Quan Lin**, Heng-Cheng Kuo, Tzu-Chieh Wei, Hsi-Chun Cheng, Chun-Wei Chen, Hsien-Fu Hsiao, Yu Tsao, Hung-yi Lee

- This work explores Mamba-based HuBERT as a speech SSL model, showing its advantages in long-context and streaming ASR, improved speech unit quality, and competitive performance on probing tasks compared to Transformer-based models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SLT 2024</div><img src='_pages/images/propertyneurons-slt-2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='_pages/images/clusterneurons.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Identifying Speaker Information in Feed-Forward Layers of Self-Supervised Speech Transformers](https://arxiv.org/abs/2506.21712)

**Tzu-Quan Lin**, Hsi-Chun Cheng, Hung-yi Lee, Hao Tang

- This work identifies speaker-relevant neurons in self-supervised speech Transformers and shows that preserving them during pruning helps maintain performance on speaker-related tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SLT 2024</div><img src='_pages/images/propertyneurons-slt-2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Property Neurons in Self-Supervised Speech Transformers](https://arxiv.org/abs/2409.05910)

**Tzu-Quan Lin**, Guan-Ting Lin, Hung-yi Lee, Hao Tang

- In this work, we identify a set of property neurons in the feedforward layers of Transformers to study how speech-related properties, such as phones, gender, and pitch, are stored.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Interspeech 2024</div><img src='_pages/images/daisy-interspeech-2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DAISY: Data Adaptive Self-Supervised Early Exit for Speech Representation Models](https://arxiv.org/abs/2406.05464)

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


- [Listen and Speak Fairly: A Study on Semantic Gender Bias in Speech Integrated Large Language Models](https://arxiv.org/abs/2407.06957), Yi-Cheng Lin, **Tzu-Quan Lin**, Chih-Kai Yang, Ke-Han Lu, Wei-Chih Chen, Chun-Yi Kuan, Hung-yi Lee. **SLT 2024**
- [On the social bias of speech self-supervised models](https://arxiv.org/abs/2406.04997), Yi-Cheng Lin, **Tzu-Quan Lin**, Hsi-Che Lin, Andy t. Liu, Hung-yi Lee. **Interspeech 2024, Best Paper Runner-up in Special Session**
- [Superb @ SLT 2022: Challenge on Generalization and Efficiency of Self-Supervised Speech Representation Learning](https://ieeexplore.ieee.org/abstract/document/10022770), Tzu-hsun Feng, Annie Dong, Ching-Feng Yeh, Shu-wen Yang, **Tzu-Quan Lin**, Jiatong Shi, et al.. **SLT 2022, Best Paper Finalists**

# 📖 Educations
- *2024.09 - now*, PhD in Electrical, Electronics, Communications Engineering (EE), Data Science and Smart Networking, National Taiwan University
- *2022.09 - 2024.06*, Master in CSIE, Networking and Multimedia, National Taiwan University
- *2018.09 - 2022.06*, Bachelor in Department of Computer Science and Information Engineering (CSIE), National Taiwan University 

# 🏆 Honors and Awards
- Interspeech 2024 Travel Grant

# 💻 Internships
- *2021.07 - 2021-09*, [aetherAI](https://www.aetherai.com/), Taipei, Taiwan.
