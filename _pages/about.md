---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<!-- TODO（中文）：暂无 Google Scholar 主页，所有 Google Scholar 和 citation badge 相关内容已暂时移除。 -->

<span class='anchor' id='about-me'></span>

# About Me

Hello! I am Hao Liang(梁淏), an undergraduate student majoring in **Data Science and Big Data Technology** at **Beijing Institute of Technology(BIT)**, Class of 2023. My current GPA is 90.59/100, and I rank 1st out of 31 students in my major.

My academic interests primarily center on Large Language Models (LLMs) and Multi-Agent Systems, with a particular focus on **the rigorous reasoning capabilities of LLMs** and **the executability and robustness of multi-agent systems**. Recently, I have become deeply fascinated by AI-driven **automated scientific research** and the construction of corresponding workflows. Earlier in my career, I also engaged in research related to **computer vision**.

I am seeking **PhD positions for 2027 Fall** and warmly welcome any remote/onsite industrial or research internship. Please feel free to reach out at haoliang050307@163.com.

<!-- TODO（中文）：如果你希望主页面向保研/直博申请，可以在这里补充一句目标方向、意向导师或申请年份；目前材料中没有明确统一版本，先不写。 -->

<span class='anchor' id='-research-interests'></span>

# Research Interests

- Multi-agent systems and automated research
- Large-model reasoning and adaptive inference
- Computer vision for UAV perception and tracking
- Robust 3D trajectory estimation under visual degradation
- Diffusion-based visual logic reasoning

<span class='anchor' id='-news'></span>

# News

- *2026.05*: I started building my academic homepage.
- *2026*: One paper on automated research idea generation and novelty auditing is being prepared for submission to NeurIPS 2026, where I serve as a co-first author.
- *2026*: One paper on robust drone trajectory estimation has been submitted to IROS 2026, where I serve as the third author.
- *2025*: Our team won a Bronze Medal in ARC Prize 2025, ranking 118th among 1,456 teams globally.
- *2025*: I received the National Scholarship.

<!-- TODO（中文）：News 中年份和月份目前只保留材料中明确的信息；若你有准确月份，可继续补充。 -->

<span class='anchor' id='-research'></span>

# Research

## Multi-Agent Systems and Automated Research

**Automated Research Framework for Scientific Idea Generation and Novelty Auditing**<br>
*Prepared for submission to NeurIPS 2026 | Co-first Author*

This project studies how large language model agents can generate, evaluate, and expand research ideas in a structured and implementation-oriented manner. Instead of relying on one-shot prompting or subjective self-reflection, our framework directly works from the original research problem and builds a closed-loop process for candidate idea generation, structured review, plan expansion, and novelty auditing.

The framework asks agents to propose diverse candidate ideas with explicit hypotheses, method keywords, expected advantages, and potential risks. It then ranks candidates by problem alignment, potential improvement, feasibility, novelty, and concreteness. High-quality ideas are further expanded into executable research blueprints, including method pipelines, key modules, training or validation strategies, ablation plans, failure risks, and implementation details. The novelty audit measures semantic diversity, concept-combination rarity, historical co-occurrence, and context-aware differences.

<!-- TODO（中文）：论文正式标题、arXiv/OpenReview/项目链接、作者列表目前未在材料中完全确认，待确定后补充。 -->

## Computer Vision and UAV Trajectory Estimation

**Geometric-Temporal Fusion for Robust Estimation of Drone Trajectories**<br>
*Submitted to IROS 2026 | Third Author*

This project addresses robust 3D trajectory estimation for highly maneuverable unmanned aerial vehicles under severe visual degradation. The target object is often small, fast-moving, and visually ambiguous, which makes tracking sensitive to motion blur, low contrast, complex backgrounds, and stereo mismatch.

We proposed a lightweight binocular stereo vision framework for full-trajectory estimation. The method combines a motion tracker based on constrained stereo matching, pixel-guided visual encoding that injects sparse geometric priors into dense visual features, and a recurrent state estimation module that couples learned pseudo-measurements with strict kinematic constraints. Experiments reported in the application materials show that the method reduced 3D estimation RMSE by more than 40% on a long-distance outdoor benchmark and achieved 221 FPS while maintaining strong real-time deployment potential.

<!-- TODO（中文）：如果论文后续接收或公开，请补充论文链接、代码链接、数据集链接和完整作者列表。 -->

<span class='anchor' id='-competition'></span>

# Competition and Projects

## ARC Prize 2025

**Few-Shot Visual Logic Solver with Masked Diffusion and Adaptive Inference**<br>
*Bronze Medal | Team Leader*

I led a team in ARC Prize 2025, where we ranked 118th among 1,456 teams globally and received a Bronze Medal. The challenge focuses on abstract visual reasoning under few-shot settings, requiring models to infer two-dimensional grid transformations from only a small number of examples.

Our system combined masked diffusion, dynamic difficulty-aware curriculum learning, two-dimensional spatial priors, and an energy validator-guided search mechanism. This design allowed heuristic search to be embedded into the generation process without test-time weight updates, improving task-directed reasoning while avoiding excessive adaptation cost.

<span class='anchor' id='-education'></span>

# Education

**Beijing Institute of Technology**<br>
*B.E. in Data Science and Big Data Technology | Sep. 2023 - Jun. 2027 expected*

- GPA: 90.59/100
- Ranking: 1/31
- Core AI and CS courses: Programming Methods (100), Machine Learning (99), Data Warehouse and Data Mining (98), Web Development Basics (97), Reinforcement Learning (96), Computer Organization and Architecture (95), Interactive Computer Graphics (95), Digital Logic Basics (93), Object-Oriented Technology and Methods (90)
- Mathematical foundation: Mathematical Foundations of Data Science (99), Probability and Statistics (96), Linear Algebra (94), Engineering Mathematical Analysis (93, 93), University Physics (94, 92)
- English proficiency: CET-4 627, CET-6 570

<span class='anchor' id='-honors-and-awards'></span>

# Honors and Awards

- *2025*: Bronze Medal, ARC Prize 2025
- *2025*: National Second Prize, National College Mathematics Competition
- *2025*: National Third Prize, National Computer Competence Challenge
- *2025*: Beijing Municipal Second Prize, National College Mathematics Competition
- *2024*: Beijing Municipal Third Prize, National College Mathematics Competition
- *2025*: Provincial/Municipal Third Prize, National Computer Competence Challenge (2 awards)
- *2024*: Provincial/Municipal Third Prize, National Computer Competence Challenge (2 awards)
- *2025*: National Scholarship
- First Prize, BIT Undergraduate Scholarship for Outstanding Students
- University-level Outstanding Student, Beijing Institute of Technology

<!-- TODO（中文）：国家级数学竞赛、北京市数学竞赛等奖项在不同材料中表述略有差异；此处按科研实践材料优先整理，后续可根据证书精确改名。 -->
<!-- TODO（中文）：BIT 校内优秀学生奖和校级优秀学生的具体获奖年份未在材料中明确展示，暂时不写年份。 -->

<!--
<span class='anchor' id='-skills'></span>

# Skills

- Programming: C/C++, Python, R, LaTeX
- Deep learning: PyTorch-based model construction, training, inference, debugging, and optimization
- Scientific computing and data analysis: NumPy, Pandas, Matplotlib
- Systems and acceleration: CUDA basics, GPU parallel computing, and low-level deep learning component development
- Research workflow: literature review, theoretical analysis, codebase construction, experiment design, academic writing, and paper submission
-->

<!--
<span class='anchor' id='-contact'></span>

# Contact

- Email: [haoliang050307@163.com](mailto:haoliang050307@163.com)
- GitHub: [aeroblaze796](https://github.com/aeroblaze796)

TODO（中文）：如果你希望公开微信、备用邮箱、LinkedIn、个人照片或 CV PDF，可以后续补充；当前先不把微信号展示到公开主页。
-->
