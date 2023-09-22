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

I am now an assistant professor at the School of Software Technology at Zhejiang University. Before that, I was a postdoctoral scholar at the Penn State University working under Prof. [Ting Wang](https://alps-lab.github.io/). 

I obtained my Ph.D. degree in the College of Computer Science and Technology at the Zhejiang University in 2022, supervised by Prof. [Shouling Ji](https://nesa.zju.edu.cn/webpage/crew/jsl.html). During Ph.D., I have spent wonderful times in collaborating with academics at the university (e.g., Prof. [Bo Li](https://aisecure.github.io/) at UIUC, and Prof. [Ting Wang](https://alps-lab.github.io/) at PSU), and researchers in the industrial community (e.g., Dr. [Tao Wei](https://scholar.google.com/citations?user=Ao3wEckAAAAJ&hl=zh-CN) at Baidu USA (now Ant Financial), Dr. [Jie Shi](https://scholar.google.com/citations?user=GQJDlW8AAAAJ&hl=zh-CN) at Huawei Singapore Research Center). Before that, I obtained my B.E. degree in the Communication Engineering at the College of Information Science and Techonology, Xiamen University.

My current research interests includes adversarial machine learning, robustness of deep learning systems, and the security of large language models. I have published 20+ papers at the top international conferences and journals such as USENIX Security, CCS, NDSS, ICCV, ICSE, TDSC, etc. 

*<span style="color:red">Openings:</span> I am looking for motivated master students and interns to join my research group. Please drop me an email if you are interested in working with me!*


# 🔥 News
- *2023.09*: &nbsp; 🎉 Three papers were accepted by [NeurIPS 2023](https://nips.cc/).
- *2023.07*: &nbsp; 🎉 One paper was accepted by [ICCV 2023](https://iccv2023.thecvf.com/).
- *2023.06*: &nbsp; I will join the School of Software Technology at Zhejiang University as an Assistant Professor in Aug 2023!
- *2023.06*: &nbsp; I was invited to serve as a reviewer for EMNLP 2023.
- *2023.05*: &nbsp; 🎉 One paper was accepted by [USENIX Security 2023](https://www.usenix.org/conference/usenixsecurity23). 
- *2023.04*: &nbsp; I was invited to serve as a reviewer for [Cybersecurity](https://cybersecurity.springeropen.com/about).
- *2023.01*: &nbsp; I was invited to serve as a PC member for ACL 2023.
- *2022.08*: &nbsp; Join College of Information Sciences and Technology, Penn State University as a postdoctoral scholar.
<!-- - *2022.05*: &nbsp; Successfully defense my Ph.D. thesis. -->

# 📝 Conference Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2021</div><img src='images/cert-rnn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cert-RNN: Towards Certifying the Robustness of Recurrent Neural Networks](https://dl.acm.org/doi/10.1145/3460120.3484538)

**Tianyu Du**, Shouling Ji, Lujia Shen, Yao Zhang, Jinfeng Li, Jie Shi, Chengfang Fang, Jianwei Yin, Raheem Beyah, Ting Wang

<strong><span class='show_paper_citations' data='kBqTzrwAAAAJ:5nxA0vEk-isC'></span></strong>
- This work proposes Cert-RNN, a general framework for certifying the robustness of RNNs. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">USENIX Security 2021</div><img src='images/textshield.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[TextShield: Robust Text Classification Based on Multimodal Embedding and Neural Machine Translation](https://www.usenix.org/system/files/sec20-li-jinfeng.pdf)

Jinfeng Li\*, **Tianyu Du\***, Shouling Ji, Rong Zhang, Quan Lu, Min Yang, and Ting Wang (\*Co-first authors)

<strong><span class='show_paper_citations' data='kBqTzrwAAAAJ:LkGwnXOMwfcC'></span></strong>
- This work proposes TextShield, a new adversarial defense framework specifically designed for Chinese deep learning-based text classification models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2019</div><img src='images/textbugger.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[TextBugger: Generating Adversarial Text Against Real-world Applications](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_03A-5_Li_paper.pdf)
Jinfeng Li, Shouling Ji, **Tianyu Du**, Bo Li, and Ting Wang

<strong><span class='show_paper_citations' data='kBqTzrwAAAAJ:ufrVoPGSRksC'></span></strong>
- This work proposes TextBugger, a general attack framework for generating adversarial texts.
</div>
</div>

- ``NeurIPS 2023`` Defending Pre-trained Language Models as Few-shot Learners against Backdoor Attacks, Tianyu Du, Zhaohan Xi, Changjiang Li, Ren Pang, Shouling Ji, Jinghui Chen, Fenglong Ma, Ting Wang, **NeurIPS 2023**. [CCF-A]
- ``NeurIPS 2023`` UniT: A Unified Look at Certified Robust Training against Text Adversarial Perturbation, Muchao Ye, Ziyi Yin, Tianrong Zhang, Tianyu Du, Jinghui Chen, Ting Wang, Fenglong Ma, **NeurIPS 2023**. [CCF-A]
- - ``NeurIPS 2023`` VLATTACK: Multimodal Adversarial Attacks on Vision-Language Tasks via Pre-trained Models, Ziyi Yin, Muchao Ye, Tianrong Zhang, Tianyu Du, Jinguo Zhu, Han Liu, Jinghui Chen, Ting Wang, Fenglong Ma, **NeurIPS 2023**. [CCF-A]
- ``ICCV 2023`` [An Embarrassingly Simple Self-supervised Trojan Attack](https://arxiv.org/abs/2210.07346), Changjiang Li, Ren Pang, Zhaohan Xi, **Tianyu Du**, Shouling Ji, Ting Wang, Yuan Yao, **ICCV 2023**. [CCF-A]
- ``USENIX Security 2023`` [On the Security Risks of Knowledge Graph Reasoning](https://arxiv.org/pdf/2305.02383.pdf), Zhaohan Xi, **Tianyu Du**, Changjiang Li, Ren Pang, Shouling Ji, Xiapu Luo, Xusheng Xiao, Fenglong Ma, Ting Wang, **USENIX Security 2023**. [CCF-A]
- ``ICSE 2022`` [NeuronFair: Interpretable White-Box Fairness Testing through Biased Neuron Identification](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9793943), Haibin Zheng, Zhiqing Chen, **Tianyu Du**, Xuhong Zhang, Yao Cheng, Shouling Ji, Jingyi Wang, Yue Yu, Jinyin Chen, **ICSE 2022**. [CCF-A]
- ``CCS 2021`` [Cert-RNN: Towards Certifying the Robustness of Recurrent Neural Networks](https://dl.acm.org/doi/10.1145/3460120.3484538), **Tianyu Du**, Shouling Ji, Lujia Shen, Yao Zhang, Jinfeng Li, Jie Shi, Chengfang Fang, Jianwei Yin, Raheem Beyah, Ting Wang, **CCS 2021**. [CCF-A]
- ``ICASSP 2021`` [Enhancing Model Robustness by Incorporating Adversarial Knowledge into Semantic Representation](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9414793), Jinfeng Li, **Tianyu Du**, Xiangyu Liu, Rong Zhang, Hui Xue, Shouling Ji, **ICASSP 2021**. [CCF-B]
- ``AsiaCCS 2020`` [SirenAttack: Generating Adversarial Audio for End-to-End Acoustic Systems](https://par.nsf.gov/servlets/purl/10174631), **Tianyu Du**, Shouling Ji, Jinfeng Li, Qinchen Gu, Ting Wang and Raheem Beyah, **AsiaCCS 2020**. [CCF-C, Tier 2 in security domain]
- ``USENIX Security 2020`` [TextShield: Robust Text Classification Based on Multimodal Embedding and Neural Machine Translation](https://www.usenix.org/system/files/sec20-li-jinfeng.pdf), Jinfeng Li\*, **Tianyu Du\***, Shouling Ji, Rong Zhang, Quan Lu, Min Yang, and Ting Wang, **USENIX Security 2020**, (\*Co-first authors). [CCF-A]
- ``NDSS 2019`` [TextBugger: Generating Adversarial Text Against Real-world Applications](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_03A-5_Li_paper.pdf), Jinfeng Li, Shouling Ji, **Tianyu Du**, Bo Li, and Ting Wang, **NDSS 2019**. [CCF-A]
- ``Inscrypt 2019`` [Invisible Poisoning: Highly Stealthy Targeted Poisoning Attack](https://www.researchgate.net/profile/Chen-Jinyin/publication/340423472_Invisible_Poisoning_Highly_Stealthy_Targeted_Poisoning_Attack/links/5f841dc9a6fdccfd7b5aa812/Invisible-Poisoning-Highly-Stealthy-Targeted-Poisoning-Attack.pdf), Jinyin Chen, Haibin Zheng, Mengmeng Su, **Tianyu Du**, Changting Lin, and Shouling Ji, **Inscrypt 2019**. <span style="color:red">(Best Paper Award)</span>
- ``Inscrypt 2019`` [Symmetric Frame Cracking: a Powerful Dynamic Textual CAPTCHA Cracking Policy](https://link.springer.com/chapter/10.1007/978-3-030-42921-8_9), Yueyao Chen, Qianjun Liu, **Tianyu Du**, Yuan Chen, and Shouling Ji, **Inscrypt 2019**.
- ``ICPCSEE 2019`` [Neural Network Model for Classifying the Economic Recession and Construction of Financial Stress Index](https://link.springer.com/chapter/10.1007/978-981-15-0121-0_44), Lujia Shen, **Tianyu Du**, and Shouling Ji, **ICPCSEE 2019**.
- ``INFOCOM 2018`` [Quantifying Graph Anonymity, Utility, and De-anonymity](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8486356), Shouling Ji, **Tianyu Du**, Zhen Hong, Ting Wang, and Raheem Beyah, **INFOCOM 2018**. [CCF-A]
- ``ICDE 2018`` [Online E-Commerce Fraud: A Large-scale Detection and Analysis](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8509383), Haiqin Weng, Zhao Li, Shouling Ji, Chen Chu, Haifeng Lu, **Tianyu Du**, and Qinming He, **ICDE 2018**. [CCF-A]
- ``SICBS 2018`` [You Are What You Search: Attribute Inference Attacks Through Web Search Queries](https://link.springer.com/chapter/10.1007/978-3-030-16946-6_27), **Tianyu Du**, Tao Tao, Bijing Liu, Xueqi Jin, Jinfeng Li, and Shouling Ji, **SICBS 2018**.
- ``CSS 2017`` [Static taint analysis method for intent injection vulnerability in android applications](https://nesa.zju.edu.cn/download/Static%20Taint%20Analysis%20Method%20for%20Intent%20Injection%20Vulnerability%20in%20Android%20Applications.pdf), Bin Xiong, Guangli Xiang, **Tianyu Du**, Jing Selena He, and Shouling Ji, **CSS 2017**.
- ``COCOON 2017`` [Influence Spread in Social Networks with both Positive and Negative Influences](https://nesa.zju.edu.cn/download/Influence%20Spread%20in%20Social%20Networks%20with%20Both%20Positive%20and%20Negative%20Influences.pdf), Jing Selena He, Ying Xie, **Tianyu Du**, Shouling Ji, and Zhao Li, **COCOON 2017**.

# 📝 Journal Publications 

- [DetectSec: Evaluating the Robustness of Object Detection Models to Adversarial Attacks](https://onlinelibrary.wiley.com/doi/pdf/10.1002/int.22851), **Tianyu Du**, Shouling Ji, Bo Wang, Sirui He, Jinfeng Li, Bo Li, Tao Wei, Yunhan Jia, Raheem Beyah, and Ting Wang, **International Journal of Intelligent Systems, 2022**. [IF=8.993]
- ``TDSC 2022`` [Your labels are selling you out: Relation leaks in vertical federated learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9899694), Pengyu Qiu, Xuhong Zhang, Shouling Ji, **Tianyu Du**, Yuwen Pu, Jun Zhou, Ting Wang, **IEEE Transactions on Dependable and Secure Computing, 2022**. [CCF A]
- [FineFool: A Novel DNN Object Contour Attack on Image Recognition Based on the Attention Perturbation Adversarial Technique](https://www.sciencedirect.com/science/article/pii/S0167404821000444), Jinyin Chen, Haibin Zheng, Hui Xiong, Ruoxi Chen, **Tianyu Du**, Zhen Hong, Shouling Ji, **Computers & Security**, 2021(9):102220. [CCF-B]
- [Robustness Certification Research on Deep Learning Models: A Survey](http://159.226.43.17/online/bfpub/jsl-2021128163639.pdf), Shouling Ji, **Tianyu Du**, Shuiguang Deng, Jie Shi, Min Yang, Bo Li, Chinese Journal of Computers, 2022, 45(1): 190-206.
- [Security and Privacy of Machine Learning Models: A Survey](https://www.jos.org.cn/jos/article/pdf/6131), Shouling Ji, **Tianyu Du**, Jinfeng Li, Chao Shen, and Bo Li, Journal of Software, 2021, 32(1): 41-67. 
- [Survey on Techniques, Applications and Security of Machine Learning Interpretability](https://crad.ict.ac.cn/cn/article/doi/10.7544/issn1000-1239.2019.20190540), Shouling Ji, Jinfeng Li, **Tianyu Du**, and Bo Li, Journal of Computer Research and Development, 2019, 56(10): 2071.
- [Spreading Social Influence with Both Positive and Negative Opinions in Online Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8665728), Jing Selena He, Meng Han, Shouling Ji, **Tianyu Du**, and Zhao Li, Big Data Mining and Analytics, 2019, 2(2): 100-117.

# 🧾 Poster 
- [SirenAttack: Generating Adversarial Audio for End-to-End Acoustic Systems](https://nesa.zju.edu.cn/download/SirenAttack%20Generating%20Adversarial%20Audio%20for%20End-to-End%20Acoustic%20Systems.pdf), **Tianyu Du**, Shouling Ji, Jinfeng Li, Qinchen Gu, Ting Wang and Raheem Beyah, **NDSS 2019 Poster Session**. 

# 📖 arXiv Publications 

- [RNN-Guard: Certified Robustness Against Multi-frame Attacks for Recurrent Neural Networks](https://arxiv.org/pdf/2304.07980.pdf), Yunruo Zhang, **Tianyu Du**, Shouling Ji, Peng Tang, Shanqing Guo.
- [Reasoning over Multi-view Knowledge Graphs](https://arxiv.org/abs/2209.13702), Zhaohan Xi, Ren Pang, Changjiang Li, **Tianyu Du**, Shouling Ji, Fenglong Ma, Ting Wang.

# 📓 Patents 
- CN, "A method and system for generating adversarial audio under white-box settings"

# 💻 Experience
- *2022.08 - 2023.08*, Postdoctoral Scholar, Penn State University.
- *2017.03 - 2018.03*, Research Scientist Intern, Alibaba, Hangzhou.

# 🎓 Education
- *2017.09 - 2022.06*, Ph.D., Cyber Security, Zhejiang University, Hangzhou. 
- *2013.09 - 2017.06*, B.E., Communication Engineering, Xiamen University, Xiamen. 

# 👩‍🏫 Service
- **Conference Program Committee or Reviewer**: [EMNLP 2023](https://2023.emnlp.org/), [ACL 2023](https://2023.aclweb.org/).
- **Journal Reviewer**: [Cybersecurity](https://cybersecurity.springeropen.com/about).

# 💬 Invited Talks
- *2021.07*, Adversarial attack and defense in the natural language procesing domain, G.O.S.S.I.P Summer School, Shanghai.

# 🎖 Honors and Awards
- *2019.12* Inscrypt 2019 Best Paper Award
- *2018.10* Guanglianda Second Prize Scholarship
- *2014.10* National Scholarship (Undergraduate) (Top 1%)
