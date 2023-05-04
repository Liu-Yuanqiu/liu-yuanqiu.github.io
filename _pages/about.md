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

I am a first-year Ph.D. student from [School of Software](http://ssdut.dlut.edu.cn/), [DALIAN UNIVERSITY OF TECHNOLOGY](https://www.dlut.edu.cn/), Dalian, China.   

My research interest includes **Computer Vision** and **Multimodal Learning**.


# 🔥 News
- *2023.02*: &nbsp;🎉 One paper is accepted by ICASSP 2023. 

# 📝 Publications  

## Inage Captioning  

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2023</div><img src='images/eenaic-icassp2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[End-to-End Non-Autoregressive Image Captioning](https://liu-yuanqiu.github.io/)

Hong Yu, **Yuanqiu Liu**, Baokun Qi, Zhaolong Hu, Han Liu

[**PDF**](https://liu-yuanqiu.github.io) \| [**Code**](https://github.com/Liu-Yuanqiu/EENAIC)  
  
Most of the existing image captioning models use the autoregressive approach to generate captions, which leads to high latency in the inference process. Non-autoregressive decoding generates words in parallel, which greatly improves the model inference speed. However, non-autoregressive decoding usually leads to performance loss due to the loss of word input. In this paper, we propose a semantic retrieval module that uses image features to retrieve semantic information as input of the non-autoregressive decoder, narrowing the performance gap between the non-autoregressive and the autoregressive model. Furthermore, we adopt Swin-Transformer instead of Faster R-CNN to extract image features, thus building an end-to-end image caption model. Experiments conducted on the MSCOCO dataset show that our model achieves new state-of-the-art performances of 122.6% CIDEr score on the 'Karpathy' offline test split with 37× inference speedup.
</div></div>

- **CVPR 2020** [End-to-End Non-Autoregressive Image Captioning](https://liu-yuanqiu.github.io), Hong Yu, **Yuanqiu Liu**, Baokun Qi, Zhaolong Hu, Han Liu*.

# 🎖 Honors and Awards
- *2022.11* 昇腾AI创新大赛全国总决赛-铜奖 
- *2022.09* 昇腾AI创新大赛大连赛区-金奖 

# 📖 Educations
- *2020.09 - present*, Ph.D., School of Software, Dalian University of Technology. 
- *2016.09 - 2020.06*, Undergraduate, School of Software, Dalian University of Technology. 

# 💬 Invited Talks
- *2023.06*, xxxxxxxxx.  \| [\[video\]](https://liu-yuanqiu.github.io/)

# 💻 Internships
- *2016.09 - 2023.06*, [Dalian University of Technology](https://www.dlut.edu.cn/), China.
