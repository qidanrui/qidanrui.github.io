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
# Biography

I'm Danrui Qi, a final-year Ph.D. candidate at Simon Fraser University under the supervision of [Prof. Jiannan Wang](https://www.cs.sfu.ca/~jnwang/). I also work closely with [Prof. Zhengjie Miao](https://www.miaozhengjie.com/).

Recently I am passionate about agentic AI systems, a paradigm reshaping how we tackle complex, data-intensive problems across industries. My current work focuses on building agent-powered data systems and a self-improving multi-agent scaling system, designed to enable intelligent agents to reason, plan, and collaborate in automating real-world, data-centric tasks. Through recent research, I aim to advance agentic architectures and reimagine how we design data preparation workflow and interact with data systems.

Prior to this, my research centered on automating data preparation pipelines, including automatic feature augmentation and preprocessing for tabular data. I leveraged techniques from Bayesian Optimization and AutoML to systematically address the challenges of feature engineering, demonstrating significant improvements in downstream machine learning performance across diverse datasets.

**Impact**: In my PhD, I built the DB-GPT stack (17K+ GitHub stars) and Dataprep (2K+ GitHub stars) for democratizing data science and enabling natural language interactions with databases. These systems have been deployed across data science, business intelligence, automated ML, and database applications in diverse industries. My CleanAgent framework introduced one of the first LLM-based multi-agent systems for data standardization, demonstrating how agentic architectures can automate complex data preparation tasks that traditionally required extensive domain expertise and manual effort. My research techniques such as automatic feature augmentation (ICDE 2024) and automated feature preprocessing (EDBT 2024) have contributed to advancing AutoML workflows, while my contributions to MassGen (577 GitHub stars), a multi-agent scaling system, are advancing how intelligent systems collaborate to solve complex real-world tasks at scale.

 <a href='https://scholar.google.com/citations?user=ah4B4xIAAAAJ'></a>

<span class='anchor' id='-xl'></span>

# 🎓 Education
- *2020.09 - 2025.09 (expected)*, Ph.D. Candidate, Computer Science, Simon Fraser University, Burnaby, BC, Canada, under the supervision of [Prof. Jiannan Wang](https://www.cs.sfu.ca/~jnwang/).
- *2017.09 - 2020.07*, Master of Engineering, School of Software, Tsinghua University, Beijing, China, under the supervision of [Prof. Shaoxu Song](https://sxsong.github.io/).
- *2013.09 - 2017.07*, Bachelor, School of Software, Tsinghua University, Beijing, China
 
<span class='anchor' id='-lwzl'></span>

# 📝 Publications

- Arijit Khan, Yuyu Luo, M. Tamer Ozsu, `Danrui Qi`, and Jiannan Wang. "Second International Workshop on LLM+Vector Data: Agentic RAG Edition." ICDE 2026.

- Aaron Xuxiang Tian, Ruofan Zhang, Jiayao Tang, Young Min Cho, Xueqian Li, Qiang Yi, Ji Wang, Zhunping Zhang, `Danrui Qi`, Sharath Chandra Guntuku, Lyle Ungar, Tianyu Shi and Chi Wang. "Beyond the Strongest LLM: Multi-Turn Multi-Agent Orchestration vs. Single LLMs on Benchmarks." (2025).
  
- Fan Zhou, Siqiao Xue, `Danrui Qi`, Wenhui Shi, Wang Zhao, Ganglin Wei, Hongyang Zhang et al. "DB-GPT-Hub: Towards Open Benchmarking Text-to-SQL Empowered by Large Language Models." arXiv preprint arXiv:2406.11434 (2024). [[paper]](https://arxiv.org/pdf/2312.17449)
  
- Siqiao Xue, `Danrui Qi`, Caigao Jiang, Wenhui Shi, Fangyin Cheng, Keting Chen, Hongjun Yang et al. "Demonstration of DB-GPT: Next Generation Data Interaction System Empowered by Large Language Models." VLDB 2024 (Demo Track). [[paper]](https://arxiv.org/pdf/2404.10209)
  
- `Danrui Qi`, Zhengjie Miao and Jiannan Wang. "CleanAgent: Automating Data Standardization with LLM-based Agents." DATAI@VLDB 2025. [[paper]](https://arxiv.org/pdf/2403.08291) [[code]](https://github.com/sfu-db/CleanAgent) 
  
-	`Danrui Qi`, Weiling Zheng, and Jiannan Wang. "FeatAug: Automatic Feature Augmentation From One-to-Many Relationship Tables." ICDE 2024.
[[paper]](https://www.researchgate.net/publication/378927947_FeatAug_Automatic_Feature_Augmentation_From_One-to-Many_Relationship_Tables) [[code]](https://github.com/sfu-db/FeatAug) 

-	`Danrui Qi`, Jinglin Peng, Yongjun He, and Jiannan Wang. "Auto-FP: An Experimental Study of Automated Feature Preprocessing for Tabular Data." In International Conference on Extending Database Technology (EDBT), 2024.
[[paper]](https://arxiv.org/pdf/2310.02540.pdf) [[code]](https://github.com/qidanrui/Auto-FP) [[talk]](https://drive.google.com/file/d/12W-ABZ2umrGUabeFPjH4y1PEYSMGWOnt/view?usp=sharing)

- Siqiao Xue, Caigao Jiang, Wenhui Shi, Fangyin Cheng, Keting Chen, Hongjun Yang, Zhiping Zhang, Jianshan He, Hongyang Zhang, Ganglin Wei, Wang Zhao, Fan Zhou, `Danrui Qi`, Hong Yi, Shaodong Liu, Faqiang Chen. "DB-GPT: Empowering Database Interactions with Private Large Language Models." arXiv preprint arXiv:2312.17449, 2023. [[paper]](https://arxiv.org/pdf/2312.17449.pdf) [[code]](https://github.com/eosphoros-ai/DB-GPT) [[demo]]( https://www.youtube.com/watch?v=KYs4nTDzEhk) 

-	Jinglin Peng, Weiyuan Wu, Jing Nathan Yan, `Danrui Qi`, Jeffrey M. Rzeszotarski, Jiannan Wang. "User Interfaces for Exploratory Data Analysis: A Survey of Open-Source and Commercial Tools." In IEEE Data Eng. Bull. 45(3): 116-128, 2022.
[[paper]](http://sites.computer.org/debull/A22sept/p116.pdf) 

-	`Danrui Qi`. "On concise explanations of non-answers over big data." In Proceedings of the 2017 ACM International Conference on Management of Data (SIGMOD Student Research Competition), pp. 10-12. 2017.
[[paper]](https://dl.acm.org/doi/abs/10.1145/3055167.3055180)

<span class='anchor' id='-gzsx'></span>

# 🏛️ Experiences
- *2024.05 - 2025.05*, Research Intern at Microsoft Research, worked with [Dr. Yeye He](https://www.microsoft.com/en-us/research/people/yeyehe/)
  
# 💻 Open-Source Projects
- *2020.7 - Present*, Founder Member and Maintainer of [Dataprep](https://github.com/sfu-db/dataprep), which has `2.3k stars`
- *2023.09 - Present*, Main Contributor of [DB-GPT-Hub](https://github.com/eosphoros-ai/DB-GPT-Hub), which has `1.8k stars`
- *2023.09 - Present*, Main Contributor of [DB-GPT](https://github.com/eosphoros-ai/DB-GPT), which has `17.5k stars`
- *2024.01 - Present*, Founder of [CleanAgent](https://github.com/sfu-db/CleanAgent), which has `70 stars`
- *2025.07 - Present*, Founder Member and Maintainer of [MassGen](https://github.com/Leezekun/MassGen), which has `577 stars`
  
<span class='anchor' id='-xshy'></span>

# 🏛️ Services
- Workshop Co-Chair of LLM+Vector Data@ICDE 2026
- Shadow PC of VLDB 2026
- Program Committee Member of WWW 2026, CIKM 2025, IJCAI 2025 Survey Track, CIKM 2024, ICDE 2022
- Reviewer of TKDE, ICLR 2026, KDD 2025 Research & ADS Track, WACV 2025, ICLR 2025
- External Reviewer of DASFAA 2024, ICDE 2022, ICDE 2024, CIKM 2023

<span class='anchor' id='-ryjx'></span>

# 🏅 Awards
- *2024.01*, Westak International Sales Inc. Scholarship at Simon Fraser University
- *2023.09, 2024.01*, PhD Research Scholarship at Simon Fraser University 
- *2020.09*, Graduate Dean's Entrance (GDES) at Simon Fraser University 
- *2017.06*, Outstanding Graduate Thesis Award at Tsinghua University
- *2016.10*, National Inspirational Scholarship at Tsinghua University











