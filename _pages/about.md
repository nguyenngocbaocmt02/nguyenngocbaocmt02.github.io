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

# About Me

Hello, I'm Bao,  a Ph.D. student in [The Department of Systems Engineering and Engineering Management](https://www.se.cuhk.edu.hk/) at [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/english/index.html) under the supervision of [Prof. Viet Anh Nguyen](https://vietanhnguyen.net). Previously, I worked as a research assistant under the supervision of [Prof. Viet Anh Nguyen](https://vietanhnguyen.net) and [Prof. Khoa D Doan](https://khoadoan.me/) at [VinUniversity](https://vinuni.edu.vn/). I received a bachelor's degree in computer science from Hanoi University of Science and Technology (HUST) in 2023. At HUST, I was fortunate to be advised by [Prof. Huynh Thi Thanh Binh](https://users.soict.hust.edu.vn/binhht/).

My research interests center on the intersection of optimization, generative models, and machine learning. Additionally, I have experience in reinforcement learning, model interpretability, and robustness in machine learning. Recently, I've been focusing on language models and reasoning.


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<span class='anchor' id='news'></span>
# 🔥 News

- *Jan 2025*: Two papers about intervention for LMs [Probe-Free Low-Rank Activation Intervention](https://arxiv.org/abs/2502.04043), [Task-driven Layerwise Additive Activation Intervention](https://arxiv.org/abs/2502.06115) are accepted to NAACL 2024!
- *May 2024*: Our paper [Generative Conditional Distributions by Neural (Entropic) Optimal Transport](https://arxiv.org/pdf/2406.02317) is accepted to ICML 2024!
- *March 2024*: I am fortunate to be granted ICLR 2024 Travel Grant (~$2,200)!
- *January 2024*: Our paper [Bellman Optimal Step-size Straightening of Flow-Matching Models](https://arxiv.org/abs/2312.16414) is accepted to ICLR 2024!
- *June 2023*: Our paper [Efficient Failure Pattern Identification of Predictive Algorithms](https://arxiv.org/abs/2306.00760) is accepted to UAI 2023!

# 📝 Selected Publications

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
</div>
</div> -->



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2022</div><img src='images/GSAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Interpretable and Generalizable Graph Learning via Stochastic Attention Mechanism](https://arxiv.org/abs/2201.12987) \\
**Siqi Miao**, Miaoyuan Liu, Pan Li, **ICML 2022**

<a href="https://github.com/Graph-COM/GSAT"><img src="https://img.shields.io/github/stars/Graph-COM/GSAT?style=social&label=Code+Stars" alt=""></a>
</div>
</div> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/gentle.png' alt="sym" style="width: 300px; max-height: 300px;"></div></div>
<div class='paper-box-text' markdown="1">

[Generative Conditional Distributions by Neural (Entropic) Optimal Transport](https://arxiv.org/pdf/2406.02317) \\
**Bao Nguyen**, Binh Nguyen, Hieu Nguyen, Viet Anh Nguyen. \\
The International Conference on Machine Learning (ICML), 2024.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/boss.png' alt="sym" style="width: 300px; max-height: 300px;"></div></div>
<div class='paper-box-text' markdown="1">

[Bellman Optimal Step-size Straightening of Flow-Matching Models](https://arxiv.org/abs/2312.16414) \\
**Bao Nguyen**, Binh Nguyen, Viet Anh Nguyen. \\
The International Conference on Learning Representations (ICLR), 2024. \\
<a href="https://openreview.net/forum?id=Iyve2ycvGZ"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICLR 2024&color=blue"></a>
<a href="https://arxiv.org/abs/2312.16414"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/nguyenngocbaocmt02/BOSS"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
<!-- <a href="https://colab.research.google.com/drive/1t0_4BxEJ0XncyYvn_VyEQhxwNMvtSUNx?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab"></a> -->
<!-- <a href="https://proceedings.mlr.press/v162/miao22a.html"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=ICML%2722&color=blue"> </a> -->

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UAI 2023</div><img src='images/fpd.png' alt="sym" style="width: 300px; max-height: 300px;"></div></div>
<div class='paper-box-text' markdown="1">

[Efficient Failure Pattern Identification of Predictive Algorithms](https://arxiv.org/abs/2306.00760) \\
**Bao Nguyen**, Viet Anh Nguyen. \\
The Conference on Uncertainty in Artificial Intelligence (UAI), 2023. \\
<a href="https://openreview.net/forum?id=DBs6SA_fKb"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=UAI 2023&color=blue"></a>
<a href="https://arxiv.org/abs/2306.00760"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/nguyenngocbaocmt02/FPD"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
<!-- <a href="https://colab.research.google.com/drive/1t0_4BxEJ0XncyYvn_VyEQhxwNMvtSUNx?usp=sharing"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Colab"></a> -->
<a href="https://proceedings.mlr.press/v216/nguyen23c"> <img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=UAI%2723&color=blue"> </a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal</div><img src='images/disq.png' alt="sym" style="width: 300px; max-height: 300px;"></div></div>
<div class='paper-box-text' markdown="1">

[Q-learning-based distributed multi-charging algorithm for large-scale WRSNs](https://www.researchgate.net/publication/366775648_Q-learning-based_distributed_multi-charging_algorithm_for_large-scale_WRSNs) \\
Nguyen Thanh Long, Tran Thi Huong, **Nguyen Ngoc Bao**, Huynh Thi Thanh Binh, Phi Le Nguyen, and Kien Nguyen \\
Nonlinear Theory and Its Applications Journal, IEICE, 2023. \\
<a href="https://doi.org/10.1587/nolta.14.18"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=NOLTA&color=blue"></a>
<a href="https://www.researchgate.net/publication/366775648_Q-learning-based_distributed_multi-charging_algorithm_for_large-scale_WRSNs"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Journal"></a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GECCO</div><img src='images/de.png' alt="sym" style="width: 300px; max-height: 300px;"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic perturbation for population diversity management in differential evolution](https://www.researchgate.net/publication/362114322_Dynamic_perturbation_for_population_diversity_management_in_differential_evolution) \\
Le Van Cuong, **Nguyen Ngoc Bao**, Phuong Khanh Nguyen, Huynh Thi Thanh Binh\\
Genetic and Evolutionary Computation Conference (GECCO), 2022. \\
<a href="https://doi.org/10.1145/3520304.3529075"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=GECCO&color=blue"></a>
<a href="https://www.researchgate.net/publication/362114322_Dynamic_perturbation_for_population_diversity_management_in_differential_evolution"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/nguyenngocbaocmt02/S-LSHADE-DP-GECCO2022-"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">GECCO</div><img src='images/de-report.png' alt="sym" style="width: 300px; max-height: 300px;"></div></div>
<div class='paper-box-text' markdown="1">

[Technical report: A Multi-start Local Search Algorithm with L-SHADE for Single Objective Bound Constrained Optimization](https://www.researchgate.net/publication/372752118_Technical_report_A_Multi-start_Local_Search_Algorithm_with_L-SHADE_for_Single_Objective_Bound_Constrained_Optimization) \\
Le Van Cuong, **Nguyen Ngoc Bao**, Huynh Thi Thanh Binh\\
The Optimization Competition at Genetic and Evolutionary Computation Conference (GECCO), 2021. \\
<a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=0X9TWMEAAAAJ&citation_for_view=0X9TWMEAAAAJ:qjMakFHDy7sC"><img alt="License" src="https://img.shields.io/static/v1?label=Pub&message=GECCO&color=blue"></a>
<a href="https://www.researchgate.net/publication/372752118_Technical_report_A_Multi-start_Local_Search_Algorithm_with_L-SHADE_for_Single_Objective_Bound_Constrained_Optimization"><img src="https://img.shields.io/badge/-Paper-grey?logo=gitbook&logoColor=white" alt="Paper"></a>
<a href="https://github.com/nguyenngocbaocmt02/MS-LSHADE-GECCO2021-"><img src="https://img.shields.io/badge/-Github-grey?logo=github" alt="Github"></a>
</div>
</div>
  
<span class='anchor' id='pub'></span>
# 📰 Publications

## Journal Publications

- Nguyen Thanh Long, Tran Thi Huong, **Nguyen Ngoc Bao**, Huynh Thi Thanh Binh, Phi Le Nguyen, and Kien Nguyen. [Q-learning-based distributed multi-charging algorithm for large-scale WRSNs](https://doi.org/10.1587/nolta.14.18), *Nonlinear Theory and Its Applications Journal, IEICE, 2023*. [[Paper]](https://www.researchgate.net/publication/366775648_Q-learning-based_distributed_multi-charging_algorithm_for_large-scale_WRSNs)

## Conference Publications
- Chonghe Jiang, **Bao Nguyen**, Anthony Man-Cho So, Viet Anh Nguyen. [Probe-Free Low-Rank Activation Intervention](https://arxiv.org/abs/2502.04043), *NAACL, 2025*.

- Hieu Nguyen, **Bao Nguyen**, Binh Nguyen, , Viet Anh Nguyen. , [Task-driven Layerwise Additive Activation Intervention](https://arxiv.org/abs/2502.06115), *NAACL, 2025*.
    
- **Bao Nguyen**, Binh Nguyen, Hieu Nguyen, Viet Anh Nguyen. [Generative Conditional Distributions by Neural (Entropic) Optimal Transport](https://arxiv.org/pdf/2406.02317), *ICML, 2024*.
  
- **Bao Nguyen**, Binh Nguyen, Viet Anh Nguyen. [Bellman Optimal Step-size Straightening of Flow-Matching Models](https://arxiv.org/abs/2312.16414), *ICLR, 2024*. [[GitHub]](https://github.com/nguyenngocbaocmt02/BOSS)

- **Bao Nguyen**, Viet Anh Nguyen. [Efficient Failure Pattern Identification of Predictive Algorithms](https://arxiv.org/abs/2306.00760), *UAI, 2023*. [[GitHub]](https://github.com/nguyenngocbaocmt02/FPD)

- Le Van Cuong, **Nguyen Ngoc Bao**, Phuong Khanh Nguyen, Huynh Thi Thanh Binh. [Dynamic perturbation for population diversity management in differential evolution](https://doi.org/10.1145/3520304.3529075), *GECCO, 2022*. [[Paper]](https://www.researchgate.net/publication/362114322_Dynamic_perturbation_for_population_diversity_management_in_differential_evolution) [[GitHub]](https://github.com/nguyenngocbaocmt02/S-LSHADE-DP-GECCO2022-)

- Le Van Cuong, **Nguyen Ngoc Bao**, Huynh Thi Thanh Binh. [Technical report: A Multi-start Local Search Algorithm with L-SHADE for Single Objective Bound Constrained Optimization](https://www.researchgate.net/publication/372752118_Technical_report_A_Multi-start_Local_Search_Algorithm_with_L-SHADE_for_Single_Objective_Bound_Constrained_Optimization), *GECCO, 2021*. [[GitHub]](https://github.com/nguyenngocbaocmt02/MS-LSHADE-GECCO2021-)

- Tran Thi Huong, **Nguyen Ngoc Bao**, Ngo Minh Hai, Huynh Thi Thanh Binh. [Effective partial charging scheme for minimizing the energy depletion and charging cost in wireless rechargeable sensor networks](https://ieeexplore.ieee.org/document/9504948/), *IEEE Congress on Evolutionary Computation (CEC), 2021*. [[Paper]](https://www.researchgate.net/publication/353782930_Effective_Partial_Charging_Scheme_For_Minimizing_The_Energy_Depletion_And_Charging_Cost_In_Wireless_Rechargeable_Sensor_Networks)

- Hue Thi Tran, **Bao Nguyen**, Nguyen Tran Nhat Quoc, Pham Phu Manh, Nguyen Khanh Phuong, Huynh Thi Thanh Binh, Dang Quang Thang. The Vehicle Routing Problem with Drones and Flexibility Demands. IEEE World Congress on Computational Intelligence (WCCI), 2024.

<span style="color:red">If you encounter any technical or implementation errors in our papers or codes, please report them by sending me an email. Thank you!</span>

# 📄 Thesis
- Bachelor's research thesis. Multi-agent reinforcement learning strategy to maximize the lifetime of Wireless Rechargeable Sensor Networks. [[Link]](https://www.researchgate.net/publication/378292170_Multi-agent_reinforcement_learning_strategy_to_maximize_the_lifetime_of_Wireless_Rechargeable_Sensor_Networks) [[GitHub]](https://github.com/nguyenngocbaocmt02/multi_agent_rl_wrsn)

<span class='anchor' id='scholarships'></span>

# 📄 Preprints

- Duy Nguyen, **Bao Nguyen** and Viet Anh Nguyen. Cost Adaptive Recourse Recommendation by Adaptive Preference Elicitation. *Under Review*.

- **Bao Nguyen**, Tran Thi Huong, Huynh Thi Thanh Binh, Le Trong Vinh. Asynchronous multi-agent reinforcement learning-based general charging scheme for connected target coverage maximization. *Under Review*.

- Tran Thi Huong, **Bao Nguyen**, Vo Khac Hiep, Le Trong Vinh, Huynh Thi Thanh Binh. Adaptive periodic charging scheme using hybrid fuzzy state-based reinforcement learning in WRSNs. *Under Review*.

<span class='anchor' id='scholarships'></span>

# 🏆 Scholarships and Grants
- *Mar 2024*: ICLR 2024 Travel Grant (~$2,200)
- *Jul 2021, Jan 2022, Jun 2022, Jan 2023*: Study encouragement scholarship, awarded by Hanoi University of Science and Technology, Hanoi, Vietnam [Cert20212](https://drive.google.com/file/d/1HP79nrwFTZjdoKkQSFP5Ql1jrSd4-Rze/view?usp=drive_link) [Cert20221](https://drive.google.com/file/d/1OFXqLnmfC3_CdG1KGQzp27ISL2mvpHyO/view?usp=drive_link) [Cert20222](https://drive.google.com/file/d/1qr-d8lrlPecRrHj2x5hnBxkJozv2krsz/view?usp=drive_link) [Cert20231](https://drive.google.com/file/d/1Or6yroomRBb7CPeW16tI33Rx4PUWwE6i/view?usp=drive_link)
- *Jun 2022*: Scholarship from Lotte Corporation, awarded by Lotte Corporation, Hanoi, Vietnam
- *Jun 2021*: Scholarship from Vietnam Gas Corporation, awarded by Vietnam Gas Corporation, Hanoi, Vietnam [Cert](https://drive.google.com/file/d/1nI81Y82wiAXDUx8z4YoA57gzB7Yrxz0R/view?usp=drive_link)

# 🏅 Competitions
- *Sep 2023*: Top 13 out of 216 in the Vietnam Winter Alphathon 2023, issued by WorldQuant Brain, Hanoi, Vietnam [Link](https://platform.worldquantbrain.com/competition/winteralphathonVN2023) [Cert](https://drive.google.com/file/d/1AwGfpAw7rW6Ylf1NTyV9sDqs34zupxsz/view?usp=drive_link)
- *Sep 2023*: The third place in the Face Analysis Challenge, organized by PIXTA Vietnam, Cohost AI, and Viblo, Hanoi, Vietnam [Link](https://hackathon.pixta.vn) [Cert](https://drive.google.com/file/d/1hGysKn_jls8gCvAbIUZlwQRuYsDvjEr8/view?usp=drive_link)
- *Jul 2023*: Runners-up in NESTQUANT Tournament, organized by NestQuant Incorporation, Hanoi, Vietnam [Link](https://tournament-docs.nestquant.com/nestquant-tournament/overview) [Cert](https://drive.google.com/file/d/1ZzbkBZS3NcLDeBOBOxwIIqe80jahe4z5/view?usp=drive_link)
- *Jun 2023*: UAI conference scholarship, awarded by the Association for Uncertainty in Artificial Intelligence, held at Carnegie Mellon University, Pittsburgh, PA, USA [Link](https://www.auai.org/uai2023/scholarships) [Cert](https://drive.google.com/file/d/1GYW8DPq_NcIwUVfCoBFVHJsvFgJqESF6/view?usp=drive_link)
- *Apr 2023*: International Quant Championship 2023, organized by WorldQuant Brain, Hanoi, Vietnam [Link](https://platform.worldquantbrain.com/competition/IQC2023S2F) [Cert](https://drive.google.com/file/d/1b_TbVCPOPwPKbUO61sNSeMKLRfNm-FR5/view?usp=drive_link)
- *Aug 2021, Jun 2022*: The $4^{th}$ prize of Competition Single Objective Bound Constrained Optimization, organized by Association for Computing Machinery Special Interest Group (SIGEVO), New York, US [Link](https://gecco-2022.sigevo.org/Competitions#id_Competition%20on%20Real%20Parameter%20Single%20Objective%20Bound%20Constrained%20Optimization) [Cert2021](https://drive.google.com/file/d/11-RjIVgjrG4w_ODmAAB5GazdYQvI_9kc/view?usp=drive_link) [Cert 2022](https://drive.google.com/file/d/1tjPd-WNuBWVO-PHOF-lFai4TN4uP6cNh/view?usp=drive_link)
- *Sep 2019*: Top 5 students with the highest scores in the National University Entrance Exam, awarded by Vietnam Ministry of Education, Hanoi, Vietnam
- *Jan 2016*: The Silver Medal of Mathematics National Exam, awarded by Vietnam Ministry of Education, Vietnam [Cert](https://drive.google.com/file/d/13Wtmon2d7VyCnZ1OA5bvOJZOEY2seXpG/view?usp=drive_link)
- *Jan 2016*: The consolidation prize in the Science and Technology National Contest, awarded by the Vietnam Ministry of Education, Vietnam [Cert](https://drive.google.com/file/d/1xC5QIsoqwS5IFjpE8t30tTFqN_dTh8im/view?usp=drive_link)

<span class='anchor' id='experience'></span>
# 🎓 Education
- *Sep 2019 - Sep 2023*: Bachelor in Computer Science (Talented Programme)
  - Hanoi University of Science and Technology, Hanoi, Vietnam
  - GPA: 3.85/4.00

# 💼 Work Experience
- *April 2022 - Present*: Research Assistant
  - VinUniversity, Hanoi, Vietnam

- *Jul 2022 - Apr 2023*: Research Assistant
  - Hanoi University of Science and Technology, Hanoi, Vietnam

# 🚀 Projects
- Generative AI Technologies for Gynecological Healthcare in Vietnam. [Link](https://gcgh.grandchallenges.org/grant/generative-ai-technologies-gynecological-healthcare-vietnam)

- Bot game MarioBros based on imitation learning and reinforcement learning. [Github](https://github.com/nguyenngocbaocmt02/Bot-game-MarioBros-based-on-inmitation-learning-and-reinforcement-learning)

- Stock Price Prediction for the Vietnamese stock market. [Github](https://github.com/nguyenngocbaocmt02/VietnameseStockMarketAnalysis)
  
# 💻 Skills
- **Programming:** Python, C, C++, Java, MATLAB, SQL
- **Technologies:** Pytorch, TensorFlow, Git, Docker, SSH, Spark, Hadoop
- **Languages:** Vietnamese (Native), English (IELTS Academic 7.0 - All skills are above 6.0, TOEIC 900) 

# 🛠 Professional Services
- Reviewer for conferences: *NeurIPS 2023, 2024*, *ICLR 2024*, *ICML 2024*, *AAAI 2025*.

<span class='anchor' id='cv'></span>
# Latest CV
- CV updated to 18/2/2024: [Link](https://drive.google.com/file/d/18s9g88U9RBr4nUvHiOVC9QZuV0AVEgnQ/view?usp=sharing)
  
# References
- [Prof. Huynh Thi Thanh Binh](https://users.soict.hust.edu.vn/binhht/)
- [Prof. Viet Anh Nguyen](https://vietanhnguyen.net)
