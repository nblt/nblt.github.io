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
# I AM LOOKING FOR Academic/Industrial JOBS. FEEL FREE TO CONTACT ME!

I am currently a fourth-year Ph.D. candidate in the Department of Automation at Shanghai Jiao Tong University, supervised by [Prof. Xiaolin Huang](http://www.pami.sjtu.edu.cn/xiaolin). I also spent several wonderful months as a visiting student in the Department of Computer Science and Engineering at The Hong Kong University of Science and Technology, under the guidance of [Prof. James Kwok](https://www.cse.ust.hk/~jamesk/).
My research interests include machine learning and optimization, with a particular focus on the efficiency, robustness, and generalization of optimization algorithms in the era of large language models.

I have a keen interest in data structures and algorithms and have participated in several competitive programming contests before. I am also a *Nikon* user.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Our paper "[ Learning scalable model soup on a single GPU: An efficient subspace training strategy](https://arxiv.org/abs/2407.03641)" is accepted to ECCV 2024.
- *2024.04*: &nbsp;🎉🎉 Our paper "[ Online Continual Learning via Logit Adjusted Softmax](https://openreview.net/pdf?id=MyQKcQAte6)" is accepted to TMLR 2024.
- *2024.03*: &nbsp;🎉🎉 Our paper "[Revisiting Random Weight Perturbation for Efficiently Improving Generalization](https://openreview.net/pdf?id=WbbgOHpoPX)" is accepted to TMLR 2024. A short version is on NeurIPS Workshops on Optimization for Machine Learning (2023).
- *2024.02*: &nbsp;🎉🎉 Our paper "[Friendly Sharpness-Aware Minimization](https://arxiv.org/abs/2403.12350)" is accepted to CVPR 2024. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR 2024</div><img src='images/RWP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Revisiting Random Weight Perturbation for Efficiently Improving Generalization](https://openreview.net/pdf?id=WbbgOHpoPX) \\
**Tao Li**, Qinghua Tao, Weihao Yan, Yingwen Wu, Zehao Lei, Kun Fang, Mingzhen He, Xiaolin Huang

[**Code**](https://github.com/nblt/mARWP) 
 - This work enhances the generalization performance of random weight perturbation from the perspective of convergence and perturbation generation, and shows that it can achieve more efficient generalization improvement than adversarial weight perturbation in SAM, especially on large-scale problems.
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/TWA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Trainable Weight Averaging: Efficient Training by Optimizing Historical Solutions](https://openreview.net/pdf?id=8wbnpOJY-f) \\
**Tao Li**, Zhehao Huang, Qinghua Tao, Yingwen Wu, Xiaolin Huang

[**Code**](https://github.com/nblt/TWA) 
 - This work introduces trainable weight averaging to average the historical solutions during the DNN training process to achieve efficient training and better performance.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022 (oral) </div><img src='images/SubAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Subspace Adversarial Training](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Subspace_Adversarial_Training_CVPR_2022_paper.pdf) \\
**Tao Li**, Yingwen Wu, Sizhe Chen, Kun Fang, Xiaolin Huang

[**Code**](https://github.com/nblt/Sub-AT) 
 - This work proposes subspace training as a method to address the overfitting issues in single and multi-step adversarial training, known as catastrophic and robust overfittings. We achieve efficient and stable single-step adversarial training with comparable robustness performance of multi-step methods.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2022 </div><img src='images/DLDR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Low Dimensional Trajectory Hypothesis is True: DNNs can be Trained in Tiny Subspaces](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9782552) \\
**Tao Li**,  Lei Tan, Zhehao Huang, Qinghua Tao, Yipeng Liu, Xiaolin Huang

[**Code**](https://github.com/nblt/DLDR) 
 - This work explores the low-dimensional characteristics of DNN training trajectories and proposes a dimension reduction method for training DNNs within a lower-dimensional subspace. This approach has the potential to reduce training costs and enhance model robustness.
</div>
</div>

<!-- **Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- </div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2020.07* Shanghai Outstanding Graduates
- *2013.12* First Prize in CSP-S (full grades) 

# 📖 Educations
- *2020.09 -  now*, Ph.D., Control Science and Engineering, Shanghai Jiao Tong University, Shanghai, China 
- *2016.09 - 2020.06*, B.Eng., Automation, Shanghai Jiao Tong University, Shanghai, China

# 💬 Invited Talks
- *2023.03*, Trainable Weight Averaging, Huawei 2012 Lab internal talk. 
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2021.09 - 2021.12*, Tencent WeChat Group, China.