---
permalink: /
title: "Home"
excerpt: "Welcome to my personal website"
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

<section id="about-me">
  <h1>👋 About Me</h1>

<ul>
  <li>
    I am currently a third-year Ph.D. candidate at the School of Computer Science and Engineering, Guangxi Normal University, under the supervision of <a href="http://www.se.gxnu.edu.cn/zhili/main.htm" target="_blank">Professor Zhi Li</a>. I am expected to complete my Ph.D. by June 2026.
  </li>
  <li>
    My research interests include <strong>Software Engineering (SE)</strong>, <strong>Requirements Engineering (RE)</strong>, <strong>Problem Frames (PF)</strong>, <strong>Model-Driven Development (MDD)</strong>, <strong>Model Transformation (MT)</strong>, <strong>Large Language Models (LLM)</strong>, and <strong>Artificial Intelligence (AI)</strong>.
  </li>
</ul>




</section>

<!-- # 🔥 News
- *2024.12*: &nbsp;🎉🎉 Our paper "A First Look at Package-to-Group Mechanism: An Empirical Study of the Linux Distributions" has been accepted by [SANER 2025](https://conf.researchr.org/home/saner-2025).
- *2024.10*: &nbsp;🎉🎉 We conduct an empirical study on the Package-to-Group mechanism! See more [details](https://arxiv.org/abs/2410.10131).
- *2024.08*: &nbsp;🎉🎉 We propose a CPS requirements modeling benchmark and evluate the ability of advanced LLMs on requirements modeling.
- *2024.05*: &nbsp;🎉🎉 We propose a multi-agents collaboration framework for requirements engineering! See more [details](https://arxiv.org/pdf/2405.03256).
- *2024.01*: &nbsp;🎉🎉 Our paper "ChatModeler: A Human-Machine Collaborative and Iterative Requirements Elicitation and Modeling Approach via Large Language Models" has been accepted by [Journal of Computer Research and Development](https://crad.ict.ac.cn/).
- *2023.07*: &nbsp;🎉🎉 Our paper "Automating Extraction of Problem Diagrams from Natural Language Requirements Document" has been accepted to [RE 2023](https://homepages.uc.edu/~niunn/EnviRE/EnviRE2023.html). -->

# 📝 Publications
- <span style="background-color: lightblue;">``计算机教育'26``</span> Diagnosing Organizational Bottlenecks inStudentSoftware Projects with Extended Problem Frames, Zicheng Huang、**Hongbin Xiao**、Zhi Li.
- <span style="background-color: lightblue;">``INTERNETWARE'25``</span> [XR4PD: Augmented Reality for Visualising Problem Diagrams in Requirements Analysis](https://dl.acm.org/doi/full/10.1145/3755881.3755937?locale=zh_CN), Yang Hua, **Hongbin Xiao**, Wenhao Wang, Zhi Li.
- <span style="background-color: lightblue;">``REW'25``</span> [ME4PD: A Multi-Modal and Dynamically Extensible System for Problem Frame Construction](https://ieeexplore.ieee.org/document/11190304), Yang Hua; **Hongbin Xiao**; Zhi Li.
- <span style="background-color: lightblue;">``REW'25``</span> [From Causal Graphs to Problem Diagrams: Enhancing Safety Requirement Modeling with LLM](https://ieeexplore.ieee.org/document/11190112), Liyuan Zhang; Zhi Li; **Hongbin Xiao**; Changjin Li; Bo Huang; Xu Chen.
- <span style="background-color: lightblue;">``QRS'25``</span> [Learning in Imperfect Environments: Multi-Label Classification of Non-Functional Requirements under Long-Tailed Distribution](https://ieeexplore.ieee.org/document/11216511), Wenhao Wang; Zicheng Huang; **Hongbin Xiao**; Zhi Li; Bo Huang.
- <span style="background-color: lightblue;">``QRS'25``</span> [PF4SAFE: Problem Frames extension for Safety Analysis based on FBN Evaluation](https://ieeexplore.ieee.org/document/11216502/), Liyuan Zhang; **Hongbin Xiao**; Wenhao Wang; Zhi Li; Changjin Li.
- <span style="background-color: lightblue;">``FSE'25``</span> [PF2UML: A Tool for Problem-Oriented Requirements Modeling and Transformation](https://dl.acm.org/doi/10.1145/3696630.3728596), **Hongbin Xiao**, Li, Z., Yang, Y., et al.
- <span style="background-color: lightblue;">``ICACTE'24``</span> [Combining STPA with PF Requirements Analysis: Taking the Insulin Pump Problem as an Example](https://doi.org/10.1109/ICACTE62428.2024.10871520), Zhou, X., **Hongbin Xiao**, Zheng, B., et al.
- <span style="background-color: lightblue;">``REW'24``</span> [A Microservice Decomposition Approach Driven by Sub-Requirement References in Problem Diagrams](https://doi.org/10.1109/REW61692.2024.00031), Bu, Y., **Hongbin Xiao**, Li, Z., Xie, X.
- <span style="background-color: lightblue;">``arXiv'24``</span> [An Evaluation of Requirements Modeling for Cyber-Physical Systems via LLMs](https://doi.org/10.48550/arXiv.2408.02450), Jin, D., Zhao, S., Jin, Z., Chen, X., Wang, C., Fang, Z., **Hongbin Xiao**.
- <span style="background-color: lightblue;">``REW'24``</span> [Deriving and Verifying B Specifications from Problem Frames Models via Model Transformation](https://doi.org/10.1109/REW61692.2024.00033), Yang, S., **Hongbin Xiao**, Li, Z., Xie, X.
- <span style="background-color: lightblue;">``APSEC'23``</span> [Natural Language Processing-Based Requirements Modeling: A Case Study on Problem Frames](https://doi.org/10.1109/APSEC60848.2023.00029), Wei, J., Chen, X., **Hongbin Xiao**, Tang, S., Xie, X., Li, Z.
- <span style="background-color: lightblue;">``RE'23``</span> [NFRNet-LT: Improving Accuracy in Extracting Long-tailed Non-functional Requirements](https://doi.org/10.1109/RE57278.2023.00049), Deng, J., Li, Z., Zhou, X., **Hongbin Xiao**.
- <span style="background-color: lightblue;">``Mathematics'23``</span> [One-Step Clustering with Adaptively Local Kernels and a Neighborhood Kernel](https://doi.org/10.3390/math11183950), Chen, C., Hu, Z., **Hongbin Xiao**, Ma, J., Li, Z.
- <span style="background-color: lightblue;">``RE'23``</span> [PF4MD: A Microservice Decomposition Tool Combining Problem Frames](https://doi.org/10.1109/RE57278.2023.00051), Li, Y., Li, Z., Bu, Y., **Hongbin Xiao**, Deng, Y.
- <span style="background-color: lightblue;">``QRS-C'23``</span> [Using Problem Frames Approach for Key Information Extraction from Natural Language Requirements](https://doi.org/10.1109/QRS-C60940.2023.00037), Tang, S., Chen, X., **Hongbin Xiao**, Wei, J., Li, Z.
- <span style="background-color: lightblue;">``REW'23``</span> [A Multimedia Approach to Problem Descriptions for Fine-Grained Detail Characterization](https://doi.org/10.1109/rew57809.2023.00040), Bowen Zheng, Zhi Li, **Hongbin Xiao**.
- <span style="background-color: lightblue;">``REW'23``</span> [Augmenting the Problem Frames Approach with Explicit Data Descriptions Using ChatGPT](https://doi.org/10.1109/rew57809.2023.00036), Ling Xie, **Hongbin Xiao**, Zhi Li.
- <span style="background-color: lightblue;">``RE'23``</span> [NL2PD: A Tool for Problem Diagram Generation from Requirements in Natural Language](https://doi.org/10.1109/re57278.2023.00052), Xuan Chen, **Hongbin Xiao**, Yajun Deng, Zhi Li.
- <span style="background-color: lightblue;">``arXiv'22``</span> [PF4Microservices: A decomposition scheme for microservices based on Problem Frames](https://doi.org/10.48550/arXiv.2207.04586), Bo, Y., **Hongbin Xiao**, Li, Z.
- <span style="background-color: lightblue;">``SEKE'22``</span> [Trace4PF: A tool for Automated Decomposition of Problem Diagrams with Traceability](https://doi.org/10.18293/seke2022-181), Yajun Deng, Zhi Li, **Hongbin Xiao**.
- <span style="background-color: lightblue;">``REW'21``</span> [An Extended Meta-Model of Problem Frames for Enriching Environmental Descriptions](https://doi.org/10.1109/rew53955.2021.00077), **Hongbin Xiao**, Zhi Li, Yilong Yang, Jie Deng, Shangfeng Wei.
- <span style="background-color: lightblue;">``RE'21``</span> [Zoom4PF: A Tool for Refining Static and Dynamic Domain Descriptions in Problem Frames](https://doi.org/10.1109/re51729.2021.00047), Shangfeng Wei, Zhi Li, Yilong Yang, **Hongbin Xiao**.



# 🎖 Honors and Awards
- *2022* Third Prize, 18th "Huawei Cup" China Postgraduate Mathematical Contest in Modeling
- *2021* Third Prize, 2nd Guangxi College Students Artificial Intelligence Design Competition
- *2018* First Prize, National Finals of the National College Students Intelligent Interconnection Innovation Application Design Competition

# 📖 Educations
- *2022.09 - 2026.06*, **Ph.D. in Software Engineering**, Guangxi Normal University, Guilin, China  
- *2020.09 - 2022.06*, **M.S. in Computer Science**, Guangxi Normal University, Guilin, China  
- *2016.09 - 2020.06*, **B.S. in Computer Science**, Zhengzhou University of Light Industry, Zhengzhou, China

# 💬 Invited Talks
- *2025.11*, PF-AIRM, Chinasoft 2025.
- *2025.06*, PF2UML, FSE 2025.
- *2024.11*, LLM4LCR, Chinasoft 2024.
- *2021.09*, Extended Meta-Model of Problem Frames, RE 2021.


# 📂 Projects

## As Leader
- **2024** - Requirement Modeling and Transformation of Cyber-Physical Systems for Problem-Oriented Scenarios
  - Type: University-level Research Project
  - Funding: Training Institution (XYCBZ2024024)
  - Role: **Leader**

## As Participant

- **2024** - Research on Government Procurement Audit Analysis Model Based on Big Data Technology
  - Type: Guangxi Audit Key Research Project (Open Bidding)
  - Source: Guilin Municipal Audit Bureau
  - Role: Participant
  - Achievement: **Second Prize** 🏆

- **2024** - Research and Development of Key Technologies for Human Resource Digital Intelligence Services
  - Type: Guangxi Key Research and Development Plan
  - Role: Participant

- **2023** - Research and Development of Collaborative Mechanism and Management Platform for National and Internal Auditing
  - Type: Guangxi Internal Audit Research Project
  - Role: Participant
  - Achievement: **1st Prize in Final Evaluation** 🏆

- **2022.12 - 2024.12** - Research on Multi-core Clustering Algorithms with Block Diagonal Properties
  - Type: Open Project of Guangxi Key Laboratory of Multi-source Information Mining and Security
  - Project No.: MIMS22-03
  - Role: Participant


# 🌟 Academic Service

## Journal Reviewer
- Reviewer: **Expert Systems with Applications (ESWA)**
- Reviewer: **Information and Software Technology (IST)**
- Reviewer: **SoftwareX**
- Reviewer: **Software Impacts** 

## Conference Service
- Technical Committee Member: The 18th International Conference on Advanced Computer Theory and Engineering (ICACTE 2025), Nanjing, China, September 26-28, 2025
- Reviewer: The 8th International Conference on Mechanical, Electric, and Industrial Engineering (MEIE2025)

