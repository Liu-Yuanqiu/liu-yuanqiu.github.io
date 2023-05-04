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

I'm a first-year doctoral student from [School of Software](http://ssdut.dlut.edu.cn/), [DALIAN UNIVERSITY OF TECHNOLOGY](https://www.dlut.edu.cn/).   

My research interest includes computer vision and machine learning.


# 🔥 News
- *2023.02*: &nbsp;🎉 One paper is accepted by ICASSP 2023. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2023</div><img src='images/eenaic-icassp2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[End-to-End Non-Autoregressive Image Captioning](https://liu-yuanqiu.github.io/)

Hong Yu, **Yuanqiu Liu**, Baokun Qi, Zhaolong Hu, Han Liu

[**Code**](https://github.com/Liu-Yuanqiu/EENAIC)  
  
Most of the existing image captioning models use the autoregressive approach to generate captions, which leads to high latency in the inference process. Non-autoregressive decoding generates words in parallel, which greatly improves the model inference speed. However, non-autoregressive decoding usually leads to performance loss due to the loss of word input. In this paper, we propose a semantic retrieval module that uses image features to retrieve semantic information as input of the non-autoregressive decoder, narrowing the performance gap between the non-autoregressive and the autoregressive model. Furthermore, we adopt Swin-Transformer instead of Faster R-CNN to extract image features, thus building an end-to-end image caption model. Experiments conducted on the MSCOCO dataset show that our model achieves new state-of-the-art performances of 122.6% CIDEr score on the 'Karpathy' offline test split with 37× inference speedup.
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
