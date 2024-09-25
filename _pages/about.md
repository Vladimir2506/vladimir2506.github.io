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

My name is **Zhuofan Xia** (**"夏卓凡"** in Chinese). I'm currently a 4th-year Ph.D. candidate at Department of Automation, Tsinghua University, advised by Prof. [Gao Huang](https://www.gaohuang.net/) and Prof. [Shiji Song](https://www.au.tsinghua.edu.cn/info/1075/3206.htm). Before that, I did my bachelor degree in Automation at Tsinghua University in 2020. My research mainly focuses on deep learning on computer vision, and multimodal learning. Specifically, my research interests lie in the Vision Transformers (2D / 3D), dynamic neural architectures, and large multimodal models. Currently, I am focusing on the topics related to dynamic and efficient large multimodal models.

Download my [C.V.](misc\CV_XZF.pdf) (possibly outdated) here.


# 📖 Education
- *2020.08 - 2026.06 (Expected)*, 🧑‍🎓 Ph.D. in Control Science and Engineering, Tsinghua University, Beijing, China.
  - Advised by Prof. [Gao Huang](https://www.gaohuang.net/) and Prof. [Shiji Song](https://www.au.tsinghua.edu.cn/info/1075/3206.htm).
- *2016.08 - 2020.06*, 🧑‍🎓 B.Eng. in Automation, Tsinghua University, Beijing, China.
<!-- - *2010.09 - 2016.06*, high school diploma (junior & senior), Yaohua High School, Tianjin, China. -->

<!-- # 🔥 News                                                                                                                                                                                                                                                                                                                                                                                                                                                                    
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Selected Publications <a href='https://scholar.google.com/citations?user=m2M6b58AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<font size=1>*: equal contribution, †: corresponding author.</font>

For full publication list, please check my [Google Scholar](https://scholar.google.com/citations?user=m2M6b58AAAAJ) profile.


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/agent_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Agent Attention: On the Integration of Softmax and Linear Attention](https://arxiv.org/pdf/2312.08874.pdf)

*European Conference on Computer Vision (**ECCV**), 2024*

Dongchen Han\*, Tianzhu Ye\*, Yizeng Han, **Zhuofan Xia**, Shiji Song, Gao Huang†


[\[arXiv\]](https://arxiv.org/abs/2312.08874) [\[GitHub\]](https://github.com/LeapLabTHU/Agent-Attention)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/gsva_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GSVA: Generalized Segmentation via Multimodal Large Language Models](https://arxiv.org/pdf/2312.10103.pdf)

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), 2024*

**Zhuofan Xia\***, Dongchen Han\*, Yizeng Han, Xuran Pan, Shiji Song, Gao Huang†

[\[arXiv\]](https://arxiv.org/abs/2312.10103) [\[GitHub\]](https://github.com/LeapLabTHU/GSVA)

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/datpp_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DAT++: Spatially Dynamic Vision Transformer with Deformable Attention](https://arxiv.org/pdf/2309.01430.pdf)

*Preprint*

**Zhuofan Xia**, Xuran Pan, Shiji Song, Li Erran Li, Gao Huang†


[\[arXiv\]](https://arxiv.org/abs/2309.01430) [\[GitHub\]](https://github.com/LeapLabTHU/DAT)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/arc_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Adaptive Rotated Convolution for Rotated Object Detection](https://openaccess.thecvf.com/content/ICCV2023/papers/Pu_Adaptive_Rotated_Convolution_for_Rotated_Object_Detection_ICCV_2023_paper.pdf)

*IEEE/CVF International Conference on Computer Vision (**ICCV**), 2023*

Yifan Pu\*, Yiru Wang\*, **Zhuofan Xia**, Yizeng Han, Yulin Wang, Weihao Gan, Zidong Wang, Shiji Song, Gao Huang†


[\[arXiv\]](https://arxiv.org/abs/2303.07820) [\[GitHub\]](https://github.com/LeapLabTHU/ARC)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/slide_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Slide-Transformer: Hierarchical Vision Transformer with Local Self-Attention
](https://openaccess.thecvf.com/content/CVPR2023/papers/Pan_Slide-Transformer_Hierarchical_Vision_Transformer_With_Local_Self-Attention_CVPR_2023_paper.pdf)

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), 2023*

Xuran Pan\* Tianzhu Ye\*, **Zhuofan Xia**, Shiji Song, Gao Huang†


[\[arXiv\]](https://arxiv.org/abs/2304.04237) [\[GitHub\]](https://github.com/LeapLabTHU/Slide-Transformer)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2023</div><img src='images/budget_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Budgeted Training for Vision Transformer](https://openreview.net/pdf?id=sVzBN-DlJRi)

*International Conference on Learning Representations (**ICLR**), 2023*

**Zhuofan Xia\***, Xuran Pan\*, Xuan Jin\*, Yuan He, Hui Xue, Shiji Song, Gao Huang†

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/dat_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Vision Transformer with Deformable Attention](https://openaccess.thecvf.com/content/CVPR2022/papers/Xia_Vision_Transformer_With_Deformable_Attention_CVPR_2022_paper.pdf)

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), 2022*

<span style="color:red;">**Best Paper Finalists (0.4%)**</span>

**Zhuofan Xia\***, Xuran Pan\*, Shiji Song, Li Erran Li, Gao Huang†


[\[arXiv\]](https://arxiv.org/abs/2201.00520) [\[GitHub\]](https://github.com/LeapLabTHU/DAT)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021</div><img src='images/pointformer_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[3D Object Detection with Pointformer](https://openaccess.thecvf.com/content/CVPR2021/papers/Pan_3D_Object_Detection_With_Pointformer_CVPR_2021_paper.pdf)

*IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), 2021*

Xuran Pan\*, **Zhuofan Xia\***, Shiji Song, Li Erran Li, Gao Huang†


[\[arXiv\]](https://arxiv.org/abs/2201.00520) [\[GitHub\]](https://github.com/LeapLabTHU/DAT)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/mlla_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Demystify Mamba in Vision: A Linear Attention Perspective](https://arxiv.org/pdf/2405.16605)

*Preprint*

Dongchen Han, Ziyi Wang, **Zhuofan Xia**, Yizeng Han, Yifan Pu, Chunjiang Ge, Jun Song, Shiji Song, Bo Zheng, Gao Huang†

[\[arXiv\]](https://arxiv.org/abs/2405.16605) [\[GitHub\]](https://github.com/LeapLabTHU/MLLA)

</div>
</div>

<!-- ## Others -->

# 🎖 Honors and Awards

## During PhD

- *Fall 2023*, **Friend of Tsinghua – Ubiquant Scholarship of Tsinghua University**, on Comprehensive excellence.
- *Fall 2022*, **Friend of Tsinghua – Hefei Talent Scholarship of Tsinghua University**, on Comprehensive excellence.
- *Fall 2021*, **Friend of Tsinghua – Samsung Scholarship of Tsinghua University**, on Comprehensive excellence.

## During Undergraduate

- *Fall 2019*, **Friend of Tsinghua – Evergrand Scholarship of Tsinghua University** on Academic excellence.
- *Fall 2019*, **Outstanding Social Work Scholarship of Tsinghua University** on Outstanding social work.
- *Fall 2018*, **Friend of Tsinghua – Zhang Ronghua Scholarship of Tsinghua University** on Academic excellence.
- *Fall 2018*, **Outstanding Social Work Scholarship of Tsinghua University** on Outstanding social work.
- *Fall 2017*, **Academic Excellence Scholarship of Tsinghua University** on Academic excellence.

# 🎓 Academic Services

- Reviewer for ICCV(2023), CVPR(2024), ECCV(2024), NeurIPS(2024), ICLR(2025).
- Reviewer for IJCV, IEEE TCSVT.

# 💬 Invited Talks

- *2024.04, Online*, **AI Time** [\[video\]](https://www.bilibili.com/video/BV1sx421U7rk/?share_source=copy_web) talk on *GSVA: Generalized Segmentation via Multimodal Large Language Models*.

- *2022.08, Tianjin*, **VALSE 2022 Student Workshop**, talk on *Vision Transformer with Deformable Attention*. 

- *2022.07, Online*, **AI Time** [\[video\]](https://www.bilibili.com/video/BV1LB4y1e7kT/?share_source=copy_web), talk on *Vision Transformer with Deformable Attention*.

<!-- # 💻 Internships

- *2019.07 - 2019.12*, Sensetime Research, Beijing, China.
- *2021.07 - 2023.04*, Alibaba Group, Beijing, China.
- *2024.07 - 2024.08*, Tencent, Shenzhen, China.
- *2024.08 - Now*, NIO Inc., Beijing, China. -->


<div><font size=1><span style="color:lightgray;">Website Template: <a href="https://rayeren.github.io/acad-homepage.github.io/">Acad-Homepage</a>. Special thanks to the <a href="https://rayeren.github.io/">template author</a>.</span>
</font></div>