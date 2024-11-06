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

During my high school, I fortunately received the first prize in the Chinese High School Mathematics Olympics and forms the habit of independent learning.In my undergraduate, I receive nearly all A grade (4.0/4.0) in my major-related courses (statistics, mathematics and computer science). However, I seldomly take classes and prefer to learn independently, thus saving much time for me to be engaged in some challenging and interesting research projects. My primary research interests lies in:
* Enable agent to make intellectual decisions.
 * Reinforcement learning (RL) allows agent to learn from the environment by trial and error (e.g. the amazing AlphaGo beat the master of 围棋 Shishi Li in 2016 thanks to development of RL). However, from my insight, there are so many tasks in real-world (e.g. moving the chopsticks from the table and 把菜夹起来) which are far more complicated than 围棋 for robotics, because the state space of this "simple" task is much larger than 围棋 in RL sense and the traditional RL algorithm (like PPO) will need enormous amount of samples to converge, which means the agent will learn extremely slowly. That is unbelievable since we human-beings will naturally regard these task as quite-simple task, due to our amazing biological evolution. Hence, we still face challenges to enable intelligent agents to even perform the daily tasks of human-beings. Exploring novel and genuinely sample-efficient RL algorithm will be my long-term goal.
 * Imitation Learning (IL) seems a promising way since it directly mimic behavior of human (or expert) instead of aimlessly making trial and error in the environment. Learning from demonstrations also aligns with the way taht human learns. However, IL fall short when the agent encounters new scenarios that the demonstration didn't cover. This resemble the issue of human learning: we will always ask ourself, "can you generalize the knowledge from this lesson to new problem?" (In Chinese, this is called "举一反三"). Then, my interest lies in: how to make IL approaches robust against new scenarios?
 * RL and IL shows two purely data-driven ways that is possible for agent learning and making decisions. But reflect on human learnin, I believe there are an complicated mechasism (or system) that guarantees human's capability of learning and making decisions, like memory, reflection and thinking. Apparently,there is a huge gap between RL and IL approaches and genuinely intelligence. LLM agent seems to be a promising trial to close this gap these days, utilizing the inference capability of LLMs. However, LLM is a large black box and we do not really know its potential limitations and capabilities, and these are my current and future interests.

* Application of intelligent agents.
 * I observed that many problems in various field (e.g. Environment, Transportation, Urban Planning) can be modeled as decision-making process. I am keen to adopt this novel perspective to provide new insight to multiple real-world problems.

# 🔥 News
- *2024.09*: &nbsp;🎉🎉 Our paper [Machine Learning-Driven Spatiotemporal Analysis of Ozone Exposure and Health Risks in China](https://agupubs.onlinelibrary.wiley.com/doi/pdf/10.1029/2024JD041593) is accepted by *Journal of Geophysical Research - Atmospheres*. 
- *2023.12*: &nbsp;🎉🎉 I co-founded one enterprise named "Metasequoia Intelligence" with [Dr. Jun Song](https://scholars.hkbu.edu.hk/en/persons/JUNSONG) from HKBU, serving as technical collaborator.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

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
