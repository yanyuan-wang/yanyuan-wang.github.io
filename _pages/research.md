---
layout: archive
# title: "Research"
permalink: /research/
author_profile: true
# redirect_from: 
#   - /resume
---

{% include base_path %}

Research Interests: 
======
* AI/LLMs for Simulation and Optimization
* Stochastic Optimization
* Reinforcement Learning
* Service Operations

<br>

Direction I: LLMs &times; Simulation + Optimization
======

* **Yanyuan Wang** and Xiaowei Zhang (2026). Optimizing Service Operations via LLM-powered Multi-agent Simulation. <a href="https://arxiv.org/abs/2604.04383" target="_blank">*Under Review*</a>.

This work addresses service system design task, using LLMs to incorporate realistic human behavioral patterns into decision-making process.


<img src="/images/bridge.png">

My thoughts on future directions in **LLM-MAS&O** (**LLM**-powered **M**ulti-**A**gent **S**imulation & **O**ptimization)
- **Reliability:** ensuring behaviorally aligned system *(work in progress)*  
- **Efficiency:** achieving speedups for large-scale system *(work in progress)*  
- **Robustness:** addressing uncertainty in system configurations *(work in progress)*  
- **Applicability:** enabling domain-specific applications  
  - strategic queues  
  - online marketplaces (e.g., gig-economy platforms)
  - blockchain auctions
  - cloud computing
  - *(... other mechanism design in dynamic markets)*

**Happy to discuss further with interested collaborators!**

<br>

Direction II: ML/GenAI &times; Optimization
======


* **Yanyuan Wang** and Xiaowei Zhang (2026). "Over-optimizing" for Normality: Budget-constrained Uncertainty Quantification for Contextual Decision-making. <a href="https://arxiv.org/abs/2503.12747" target="_blank">*Major Revision at Manufacturing & Service Operations Management*</a>.

<img src="/images/overopt.png">


This work studies statistical validity and computational efficiency in quantifying uncertainty for context-aware decision-making. 
It uncovers a counterintuitive phenomenon that answers the question *"When does more data stop helping?"*
---exploring whether more samples invariably lead to better outcomes.



<br>

Direction III: ML &times; Simulation
======

<img src="/images/nskrr.png">

* Wenjia Wang, **Yanyuan Wang** and Xiaowei Zhang (2024). Smooth Nested Simulation: Bridging Cubic and Square Root Convergence Rates in High Dimensions. <a href="https://pubsonline.informs.org/doi/10.1287/mnsc.2022.00204" target="_blank">*Management Science*</a>.

This work focuses on achieving sample efficiency in high-dimensional uncertainty quantification, 
specifically on understanding how input uncertainty propagates through the behavior of stochastic systems.
- Portfolio risk management: estimate risk measures for complex portfolio
- Queueing, service systems: estimate performance metrics (e.g., waiting times, service levels) under uncertain inputs (e.g., arrival rates, service distributions)
- Stochastic control: evaluate optimal policies based on estimated expectations (e.g., newsvendor with multinomial logit model)
- Engineering design: assess system reliability with unknwon parameters (e.g., material properties)