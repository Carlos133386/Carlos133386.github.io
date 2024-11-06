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

Greetings! I am Zhenglin Wan, an undergraduate student from CUHKsz majoring in Data Science. You can find my CV at [CV](https://github.com/Carlos133386/Carlos133386.github.io/raw/main/cV%20(2).pdf).

During high school, I was fortunate to receive first prize in the Chinese High School Mathematics Olympics, which helped me develop a habit of independent learning. In my undergraduate studies, I achieved nearly all A grades (4.0/4.0) in my major-related courses (statistics, mathematics, and computer science). I often preferred independent study over traditional classes, which allowed me to save time and engage in challenging and interesting research projects. My primary research interests lie in:

# Enabling agents to make intelligent decisions:

## 
Reinforcement Learning (RL) allows agents to learn from their environment through trial and error (e.g., the remarkable AlphaGo, which defeated the Go master Shishi Li in 2016, was made possible by advancements in RL). However, in my view, many real-world tasks (e.g., picking up chopsticks from a table and grasping food) are far more complex for robots than Go. The state space for these "simple" tasks is significantly larger than that of Go in RL terms, and traditional RL algorithms (like PPO) require enormous sample sizes to converge, making learning extremely slow. This is surprising, given that humans naturally view these tasks as simple, thanks to our remarkable biological evolution. Therefore, we still face substantial challenges in enabling intelligent agents to perform even basic human tasks. My long-term goal is to explore novel, genuinely sample-efficient RL algorithms.

## 
Imitation Learning (IL) appears promising because it enables agents to mimic expert (or human) behavior directly, avoiding the aimless trial and error in the environment. Learning from demonstrations also aligns closely with human learning patterns. However, IL faces limitations when an agent encounters new scenarios not covered in the demonstrations. This issue mirrors a common question in human learning: “Can you generalize the knowledge from this lesson to solve new problems?” (In Chinese, this is known as “举一反三”). My interest lies in developing such robust IL approaches.

## 
Both RL and IL represent purely data-driven approaches to agent learning and decision-making. However, I believe that human learning involves a much more complex system that includes memory, reflection, and reasoning. Currently, there is a substantial gap between RL/IL approaches and genuine intelligence. Large Language Model (LLM) agents have shown promise in bridging this gap, given their remarkable inference capabilities. However, as LLMs are largely "black boxes," their potential limitations and capacities remain unknown, which continues to fuel my curiosity and future research.

# Applications of intelligent agents:

I have observed that many real-world problems in fields such as the environment, transportation, and urban planning can be modeled as decision-making processes. I am eager to adopt this novel perspective and apply it to offer fresh insights into these complex, multidisciplinary problems.

# 🔥 News
- *2024.10*  &nbsp;🎉🎉 Our paper *Hierarchical Spatial-Temporal Graph-Enhanced Model for Map-Matching* accepted by *Australasian Database Conference 2025*.
- *2024.10*  &nbsp;🎉🎉 I have ended my memorable attachment at [Centre for Frontier AI Research](https://www.a-star.edu.sg/cfar), Agency for Science, Technology and Research [(A*STAR)](https://www.a-star.edu.sg/) at Singapore, serving as an intern researcher.
- *2024.09*  &nbsp;🎉🎉 My invention patent *A Single-UAV Atmospheric Pollutant Source Tracing Method Based on Gradient Ascent and Physical Kinematics* is published.
- *2024.05*  &nbsp;🎉🎉 My invention patent *A Method, System, Terminal Device, and Storage Medium for Air Quality Spatial Inference* is officially granted! 
- *2024.09*: &nbsp;🎉🎉 Our paper [*Machine Learning-Driven Spatiotemporal Analysis of Ozone Exposure and Health Risks in China*](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2024JD041593) is accepted by *Journal of Geophysical Research - Atmospheres*.
- *2023.12*: &nbsp;🎉🎉 I co-founded one enterprise named "Metasequoia Intelligence" with [Dr. Jun Song](https://scholars.hkbu.edu.hk/en/persons/JUNSONG) from HKBU, serving as technical collaborator.


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Conference Under Review</div><img src='personal_page_sources/QD-IL/show.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Quality Diversity Imitation Learning](https://arxiv.org/abs/2410.06151)

**Supervisor:** [Xingrui Yu](https://www.a-star.edu.sg/cfar/about-cfar/our-team/yu-xingrui), [David Bossens](https://www.a-star.edu.sg/cfar/about-cfar/our-team/david-bossens)  
**Host:** [Centre for Frontier AI Research](https://www.a-star.edu.sg/cfar), [A*STAR](https://www.a-star.edu.sg/), Singapore  
**Duration:** Jun. 2024 - Oct. 2024  

- Imitation learning (IL) approaches succeed in fast adaptation for dozens of applications. However, traditional IL assumes the demonstrations comes from one specific expert policy, thus containing only one behavior pattern. This way may result in the lack of robustness of agent to deal with various and stochastic situations.
- This work pioneers a new paradigm- learning from diverse behaviors. We proposed a novel quality-diversity imitation learning model to enable the agent to learn a broad set of skills from limited but diverse demonstrations. With multiple skills equipped, the agent can robustly deal with unseen and stochastic environment.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Conference Under Review</div><img src='personal_page_sources/POI/show.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Next-POI Recommendation via Multi-Objective Adversarial Imitation Learning

**Supervisor:** [Xingrui Yu](https://www.a-star.edu.sg/cfar/about-cfar/our-team/yu-xingrui)  
**Host:** [Centre for Frontier AI Research](https://www.a-star.edu.sg/cfar), A*STAR, Singapore  
**Duration:** Feb. 2024 - Aug. 2024  

- We proposed a multi-objective imitation learning architecture with variational inference to address the notorious data sparsity and data noise issue in POI data, and we utilize a novel adaptive graphs to capture spatial-temporal dependencies of POI sequences and user patterns.
- Demonstrated that the proposed architecture outperformed the current state-of-the-art by 8%, and by 31% in extremely sparse data scenarios.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal Under Review</div><img src='personal_page_sources/GRAND/show.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Graph-based Reinforcement learning Approach for influential Node Detection in airport delay networks

**Supervisor:** [Jianfeng Mao](https://sds.cuhk.edu.cn/en/teacher/268)  
**Host:** School of Data Science, CUHK (Shenzhen)  
**Duration:** Jun. 2023 - Aug. 2024  

- We developed a data-driven method combining graph representation learning with value-based reinforcement learning to identify key airports in delay networks, addressing the issue of low inference efficiency and cost-unaware management.
- Empirically, we achieved a 32% performance increase on the US airport delay dataset. Submitted a paper to *Transportation Research Part E: Logistics and Transportation Review*.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Project</div><img src='personal_page_sources/Deep View/show2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DEEP VIEW: Mobile Inspection and Environmental Digital AI Supervision Service Project]()

**Project Consultant:** [Yike Guo](https://cse.hkust.edu.hk/admin/people/faculty/profile/yikeguo), Provost of HKUST  
**Supervisor:** [Jun Song](https://scholars.hkbu.edu.hk/en/persons/JUNSONG), HKBU  
**Duration:** Nov. 2023 - May. 2024  

- We developed an automated environmental monitoring system using LLM agents and drones for comprehensive air quality monitoring.
- We integrated multi-source data fusion, drone scheduling, and deep learning-based analysis into a unified system for real-time environmental oversight.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal Under Review</div><img src='personal_page_sources/AlphaAir/show.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLM-Based Air Quality Analysis and Decision-Making Agent]()

**Supervisor:** [Jun Song](https://scholars.hkbu.edu.hk/en/persons/JUNSONG), HKBU  
**Duration:** Nov. 2023 - Jan. 2024  

- We integrated air quality assessment into tools for an LLM-based agent using LangChain, enabling real-time interaction for efficient data analysis.
- Submitted to *Science Advances*.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Patent Pending</div><img src='personal_page_sources/UAV/show.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unmanned Aerial Vehicle Pollutant Tracking using Optimization Methods]()

**Institution:** Metasequoia Intelligence  
**Duration:** Nov. 2023 - Feb. 2024  

- Developed optimization algorithms for UAV-based pollutant tracking, demonstrating notable improvements in accuracy and efficiency.
- Conducted simulations validating the algorithms' effectiveness in real-world tracking, resulting in two invention patents under review.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal of Geophysical Research - Atmospheres</div><img src='personal_page_sources/NetGBM/show.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Temporal-Spatial Data-Mining on Environmental Data](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2024JD041593)

**Institution:** Metasequoia Intelligence  
**Duration:** Feb. 2023 - May. 2023  




</div>
</div>


# 🎖 Honors and Awards
- **Zhejiang Guolong Inspirational & Diligentia Bowen II Scholarship** (Outstanding Academic Performance)  
  *September 2021*

- **Yearly Dean List Award** (Outstanding Academic Performance)  
  *Consecutive three years: September 2022 - September 2024*

- **Yearly Academic Scholarship: C Class** (Year GPA Top 5%)  
  *Second Academic Year: September 2023*

- **Yearly Academic Scholarship: B Class** (Year GPA Top 3%)  
  *Third Academic Year: September 2024*


# 📖 Educations
- *2021.09 - 2025.06 (now)*, The Chinese University of Hong Kong, Shenzhen 

# 💬 Press/Media
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">White Paper</div><img src='personal_page_sources/white_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


- The co-author of the first White Paper on Cross-Border Economic Large Language Model in Shenzhen, China.
[深圳卫视：深圳发布首个跨境经济大模型白皮书](https://www.sztv.com.cn/ysz/dsdb/szws/ssxw/80141762.shtml)

</div>
</div>

---

# 💻 Internships
- *2023.07 - 2024.01*, Machine Learning Algorithm Engineerer, [HUIYINTONG]([https://github.com/](http://www.hytii.cn/index.html)), China.  
- *2024.07 - 2024.10*, Intern Researcher, Agency for Science, Technology and Research [A*STAR](https://www.a-star.edu.sg/), Singapore
