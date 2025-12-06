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


I am a Ph.D. student in the [College of Computer Science and Technology](https://www.en.cs.zju.edu.cn/) at [Zhejiang University](https://www.zju.edu.cn/english/), under the supervision of Prof. [Mingli Song](https://person.zju.edu.cn/en/msong) and Prof. [Yang Yang](http://yangy.org/). Beyond these two distinguished advisors, I am fortunate to collaborate with several excellent researchers, such as [Jiarong Xu](https://galina0217.github.io/), [Shunyu Liu](https://liushunyu.github.io/), and [Tongya Zheng](https://doujiang-zheng.github.io/). Prior to beginning my doctoral studies, I received a Bachelor’s degree in Artificial Intelligence from [University of Science and Technology Beijing](https://en.ustb.edu.cn/) and a [dual Bachelor’s degree](https://nsd.pku.edu.cn/jxxm/bks/zsxx/sxwxwzs/265105.htm) in Economics from [Peking University](https://english.pku.edu.cn/).

In the early stage of my research, I mainly focused on data mining, including time‑series data and graph data. For example, in collaboration with [Finvolution](https://en.finvgroup.com/), we explored several privacy issues in graph data and graph neural networks, which can provide insights into data security and model security in the financial domain.

More recently, my work centers on developing training techniques for LLMs/MLMs and leveraging them in practical recommender and advertising system applications. For example, in collaboration with [Alibaba](https://www.alibabagroup.com/), we proposed a unified multimodal large model, Fox, which excels in complex compositional text-to-image generation and can be used for AIGC product poster creation in advertising scenarios. As a side project, I am also working on agentic capabilities for coding. 

I am genuinely excited about future opportunities, especially those that offer meaningful research potential. I expect to graduate in **June 2026**, and I welcome any discussions about potential roles. **If you are interested in my work or know of any suitable job openings or post‑doctoral positions, please do not hesitate to contact me.**

<!--
I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🔥 News
- *2025.11*: &nbsp;🎉🎉 One paper was accepted as an oral presentation at AAAI 2026.
- *2025.11*: &nbsp;🎉🎉 One paper is now available online on arXiv: [Link](https://arxiv.org/abs/2511.17923)
- *2025.10*: &nbsp;🎉🎉 One paper was accepted as a poster at NeurIPS 2025.

# 📝 Publications 

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>
-->


- [Towards Efficient LLM-aware Heterogeneous Graph Learning](https://arxiv.org/abs/2511.17923), Wenda Li, Tongya Zheng, Shunyu Liu, Yu Wang, Kaixuan Chen, **Hanyang Yuan**, Bingde Hu, Zujie Ren, Mingli Song, and Gang Chen, **arXiv preprint**
- [Neural Graph Navigation for Intelligent Subgraph Matching](https://arxiv.org/abs/2511.17939), Yuchen Ying, Yiyang Dai, Wenda Li, Wenjie Huang, Rui Wang, Tongya Zheng, Yu Wang, **Hanyang Yuan**, and Mingli Song, **AAAI 2026 Oral**
- [Tree of Preferences for Diversified Recommendation](https://neurips.cc/virtual/2025/loc/san-diego/poster/118613), **Hanyang Yuan**<sup>\*</sup>, Ning Tang<sup>\*</sup>, Tongya Zheng, Jiarong Xu, Xintong Hu, Renhong Huang, Shunyu Liu, Jiacong Hu, Jiawei Chen, and Mingli Song, **NeurIPS 2025** (<sup>\*</sup>: equal controbution)
- Towards Enhanced Image Generation Via Multi-modal Chain of Thought in Unified Generative Models, Yi Wang<sup>\*</sup>, Mushui Liu<sup>\*</sup>, Wanggui He<sup>\*</sup>, **Hanyang Yuan**<sup>\*</sup>, Longxiang Zhang, Ziwei Huang, Guanghao Zhang, Wenkai Fang, Haoze Jiang, Shengxuming Zhang, Dong She, Jinlong Liu, Weilong Dai, Mingli Song, Hao Jiang, and Jie Song, **ICLR 2026 submission** (<sup>\*</sup>: equal controbution)
- [Can Graph Neural Networks Expose Training Data Properties? An Efficient Risk Assessment Approach](https://proceedings.neurips.cc/paper_files/paper/2024/hash/806288e682d8a38c0bf21e37ab38af0a-Abstract-Conference.html), **Hanyang Yuan**, Jiarong Xu, Renhong Huang, Mingli Song, Chunping Wang, and Yang Yang, **NeurIPS 2024**
- [Extracting Training Data from Molecular Pre-trained Models](https://proceedings.neurips.cc/paper_files/paper/2024/hash/b17e1642998a8214be240b3056f5faa5-Abstract-Conference.html), Renhong Huang, Jiarong Xu, Zhiming Yang, Xiang Si, Xin Jiang, **Hanyang Yuan**, Chunping Wang, and Yang Yang, **NeurIPS 2024**
- [Unveiling Privacy Vulnerabilities: Investigating the Role of Structure in Graph Data](https://dl.acm.org/doi/abs/10.1145/3637528.3672013), **Hanyang Yuan**, Jiarong Xu, Cong Wang, Ziqi Yang, Chunping Wang, Keting Yin, and Yang Yang, **KDD 2024 Oral**
- [Unsupervised Distance Metric Learning for Anomaly Detection Over Multivariate Time Series](https://arxiv.org/abs/2403.01895), **Hanyang Yuan**, Qinglin Cai, and Keting Yin, **arXiv preprint**

# 🎖 Selected Honors and Awards
- *2021.06*, Outstanding Graduates of University of Science and Technology Beijing.
- *2019.04*, Second Prize, [Standard Platform League](http://en.wikipedia.org/wiki/RoboCup_Standard_Platform_League), RoboCup China Open.
- *2018.10*, Second Prize, National Mathematics Competition for College Students.

# 📖 Educations
- *2021.09 - 2026.06 (expected)*, Ph.D. in Computer Science and Technology, Zhejiang University, Hangzhou.
- *2018.09 - 2021.06*, Dual Bachelor’s Degree in Economics, Peking University, Beijing.
- *2017.09 - 2021.06*, Bachelor’s Degree in Artificial Intelligence, University of Science and Technology Beijing, Beijing.

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
