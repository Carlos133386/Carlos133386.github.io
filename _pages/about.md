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
- *2024.10*  &nbsp;🎉🎉 I have ended my memorable attachment at [Centre for Frontier AI Research](https://www.a-star.edu.sg/cfar), [Agency for Science, Technology and Research (A*STAR)](https://www.a-star.edu.sg/) at Singapore, serving as an intern researcher.
- *2024.09*  &nbsp;🎉🎉 My invention patent *A Single-UAV Atmospheric Pollutant Source Tracing Method Based on Gradient Ascent and Physical Kinematics* is published.
- *2024.05*  &nbsp;🎉🎉 My invention patent *A Method, System, Terminal Device, and Storage Medium for Air Quality Spatial Inference* is officially granted! 
- *2024.09*: &nbsp;🎉🎉 Our paper [*Machine Learning-Driven Spatiotemporal Analysis of Ozone Exposure and Health Risks in China*](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2024JD041593) is accepted by *Journal of Geophysical Research - Atmospheres*.
- *2023.12*: &nbsp;🎉🎉 I co-founded one enterprise named "Metasequoia Intelligence" with [Dr. Jun Song](https://scholars.hkbu.edu.hk/en/persons/JUNSONG) from HKBU, serving as technical collaborator.


# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Quality Diversity Imitation Learning (Research Intern)](https://arxiv.org/abs/2410.06151)

**Supervisor:** [Xingrui Yu](https://www.a-star.edu.sg/cfar/about-cfar/our-team/yu-xingrui), [David Bossens](https://www.a-star.edu.sg/cfar/about-cfar/our-team/david-bossens)  
**Host:** [Centre for Frontier AI Research](https://www.a-star.edu.sg/cfar), A*STAR, Singapore  
**Duration:** Jun. 2024 - Oct. 2024  

- Proposed measure-level curiosity mechanism with measure-aware adversarial imitation to promote diverse behavior patterns, achieving near-expert performance in Walker2d and 2x expert performance in Humanoid (Mujoco).
- Pioneered "learning from diverse behaviors" paradigm, enabling imitation learning algorithms to acquire a broad set of diverse skills from limited expert demonstrations. Submitted a paper to ICLR 2025 as the first author.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[POI Recommendation via Multi-Objective Imitation Learning](https://arxiv.org/abs/2410.06152)

**Supervisor:** [Xingrui Yu](https://www.a-star.edu.sg/cfar/about-cfar/our-team/yu-xingrui)  
**Host:** [Centre for Frontier AI Research](https://www.a-star.edu.sg/cfar), A*STAR, Singapore  
**Duration:** Feb. 2024 - Aug. 2024  

- Proposed a multi-objective imitation learning architecture with variational inference to address data sparsity and noise in POI data, utilizing adaptive graphs to capture spatial-temporal dependencies of POI sequences and user patterns.
- Demonstrated that the proposed architecture outperformed the current state-of-the-art by 8%, and by 31% in extremely sparse data scenarios. Submitted a paper to AAAI 2025 as the first author.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal Submission</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reinforcement Learning on Airport Delay Network](https://arxiv.org/abs/2410.06153)

**Supervisor:** [Jianfeng Mao](https://sds.cuhk.edu.cn/en/teacher/268)  
**Host:** School of Data Science, CUHK (Shenzhen)  
**Duration:** Jun. 2023 - Aug. 2024  

- Developed a data-driven method combining graph representation learning with value-based reinforcement learning to identify key airports in delay networks, addressing low inference efficiency and cost-unaware management.
- Independently implemented the model, achieving a 32% performance increase on the US airport delay dataset. Submitted a paper to *Transportation Research Part E: Logistics and Transportation Review*.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Consulting Project</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DEEP VIEW: Mobile Inspection and Environmental Digital AI Supervision Service Project](https://arxiv.org/abs/2410.06154)

**Project Consultant:** [Yike Guo](https://cse.hkust.edu.hk/admin/people/faculty/profile/yikeguo), Provost of HKUST  
**Supervisor:** [Jun Song](https://scholars.hkbu.edu.hk/en/persons/JUNSONG), HKBU  
**Duration:** Nov. 2023 - May. 2024  

- Developed an automated environmental monitoring system using LLM agents and drones for comprehensive air quality monitoring.
- Integrated multi-source data fusion, drone scheduling, and deep learning-based analysis into a unified system for real-time environmental oversight.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal Submission</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLM-Based Air Quality Analysis and Decision-Making Agent](https://arxiv.org/abs/2410.06155)

**Supervisor:** [Jun Song](https://scholars.hkbu.edu.hk/en/persons/JUNSONG), HKBU  
**Duration:** Nov. 2023 - Jan. 2024  

- Integrated air quality assessment into tools for an LLM-based agent using LangChain, enabling real-time interaction for efficient data analysis.
- Completed a paper and submitted it to *Science Advances*.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Patent Pending</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unmanned Aerial Vehicle Pollutant Tracking using Optimization Methods](https://arxiv.org/abs/2410.06156)

**Institution:** Metasequoia Intelligence  
**Duration:** Nov. 2023 - Feb. 2024  

- Developed optimization algorithms for UAV-based pollutant tracking, demonstrating notable improvements in accuracy and efficiency.
- Conducted simulations validating the algorithms' effectiveness in real-world tracking, resulting in two patent applications.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal Submission</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Temporal-Spatial Data-Mining on Environmental Data](https://arxiv.org/abs/2410.06157)

**Institution:** Metasequoia Intelligence  
**Duration:** Feb. 2023 - May. 2023  

- Used seq2seq models and gradient-boosting decision trees to improve prediction and imputation of environmental patterns, achieving state-of-the-art performance.
- Engaged in implementing machine learning methodologies and conducted experiments, resulting in a publication in the *Journal of Geophysical Research - Atmospheres*.

</div>
</div>


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
