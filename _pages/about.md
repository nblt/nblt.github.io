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

I am a fourth-year Ph.D. candidate  in the Department of Automation at SEIEE, SJTU, advised by [Prof. Xiaolin Huang](http://www.pami.sjtu.edu.cn/xiaolin). I also spend several wonderful months in the Department of Computer Science and Engineering, HKUST, as a visiting student, under the guidance of [Prof. James Kwok](https://www.cse.ust.hk/~jamesk/).
My research primarily revolves around machine learning and optimization. Specifically, I am deeply interested in efficiency, robustness, and generalization aspects associated with learning algorithms and large-scale models. 
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.03*: &nbsp;🎉🎉 Our paper "[Revisiting Random Weight Perturbation for Efficiently Improving Generalization](https://openreview.net/pdf?id=WbbgOHpoPX)" is accepted to TMLR. A short version is on NeurIPS Workshops on Optimization for Machine Learning (2023).
- *2024.02*: &nbsp;🎉🎉 Our paper "[Friendly Sharpness-Aware Minimization](https://arxiv.org/abs/2403.12350)" is accepted to CVPR 2024. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR 2024</div><img src='images/RWP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Revisiting Random Weight Perturbation for Efficiently Improving Generalization](https://openreview.net/pdf?id=WbbgOHpoPX) \\
**Tao Li**, Qinghua Tao, Weihao Yan, Yingwen Wu, Zehao Lei, Kun Fang, Mingzhen He, Xiaolin Huang

[**Code**](https://github.com/nblt/mARWP) 
 - This work enhances the generalization performance of random weight perturbation from the perspective of convergence and perturbation generation, and shows that it can achieve more efficient generalization improvement than SAM with comparable or even better performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/fsam.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Friendly Sharpness-Aware Minimization](https://arxiv.org/pdf/2403.12350.pdf) \\
**Tao Li**, Pan Zhou, Zhengbao He, Xinwen Cheng, Xiaolin Huang

[**Code**](https://github.com/nblt/F-SAM) 
 - This work uncovers that the full gradient component in SAM's adversarial perturbation does not contribute to generalization and, in fact, has undesirable effects. We propose an efficient variant to mitigate these effects and enhance the generalization performance.
</div>
</div>


<!-- **Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- </div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2020.09 -  now*, Ph.D., Control Science and Engineering, Shanghai Jiao Tong University 
- *2016.09 - 2020.06*, Undergraduate, Automation, Shanghai Jiao Tong University

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2021.09 - 2022.02*, Tecent, China.