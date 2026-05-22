---
layout: archive
title: "Kanglin Xu's CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

PDF
======
[Download PDF CV]({{ base_path }}/files/Kanglin-Xu-CV.pdf)

Education
======
* University of Illinois Chicago, Aug 2025 - Expected May 2030
  * Ph.D. in Computer Science
  * GPA: 4.0
* Texas Tech University, Aug 2021 - Dec 2024
  * B.S. in Computer Science
  * Minor in Mathematics
  * GPA: 4.0
* Lake Superior College, Aug 2020 - May 2021
  * General Study
  * GPA: 3.75

Research Profile
======
My research lies at the intersection of machine learning and high-performance computing (HPC), with an emphasis on runtime prediction, reinforcement learning for system optimization, and AI-driven energy efficiency. I build predictive models from scheduler and system logs and develop uncertainty-aware buffering strategies to reduce underestimation and improve scheduling reliability. I am also exploring energy-aware scheduling and decision policies that improve throughput and reduce energy consumption in large-scale HPC systems.

Research Interests
======
* HPC scheduling
* Batch job runtime prediction
* Energy-aware optimization
* Reinforcement learning
* Workload characterization
* Trustworthy machine learning for systems

Skills
======
* Programming: Python, C/C++, Bash, Git
* ML / Data Science: TensorFlow, PyTorch, scikit-learn, XGBoost, Pandas, NumPy
* HPC: Linux, job schedulers such as SLURM and PBS, profiling and monitoring workflows, cluster experimentation
* Security: vulnerability assessment support, policy and risk review, audit-oriented documentation

Professional Experience
======
* Research Assistant, SPEAR Lab, University of Illinois Chicago, Aug 2025 - Present
  * Develop and implement reinforcement learning algorithms for HPC system optimization.
  * Design and run large-scale experiments on HPC clusters to evaluate RL-based approaches against traditional heuristics.
  * Collaborate on performance analysis by integrating learning-based policies with HPC workflows.
* Information Security Technician, CoNetrix Security / CoNetrix, Jan 2023 - May 2025
  * Conduct internal and external vulnerability assessment support in coordination with audit and penetration testing groups.
  * Review policies, procedures, risk assessments, and resiliency plans with information security consultants.
  * Contribute to team-based solutions for evolving security requirements.
* Research Assistant, Wu Research Group, Texas Tech University, Sep 2022 - May 2025
  * Apply machine learning methods to analyze large medical datasets and support diagnosis-related research.
  * Design and develop neural network models for clinical decision support tasks.
  * Compare algorithms through systematic evaluation and visualization of results.
* Teaching Assistant, Department of Computer Science, Texas Tech University, Sep 2024 - Dec 2024
  * Supported course delivery through grading, office hours, and student feedback.
  * Assisted with assignments, quizzes, exams, and general learning support.

Project Experience
======
* HPC Batch Job Runtime Prediction, Aug 2025 - Present
  * Build machine learning models to predict batch job wall-clock runtime from scheduler logs.
  * Engineer workload-aware and user-aware features, including runtime history and underestimation patterns.
  * Evaluate performance with RMSE, R2, underestimation rate, and scheduling implications.
* Multiagent Deep Deterministic Policy Gradient Based Card Game, Jan 2024 - May 2024
  * Designed and trained AI agents for a card game using agent-environment reinforcement learning.
  * Implemented a MADDPG-inspired framework for multiagent decision-making.
  * Visualized real-time game states and actions for trained agents and human players.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Additional Information
======
* Google Scholar: [Profile](https://scholar.google.com/citations?user=Q7FUgDYAAAAJ&hl=en-US)
* GitHub: [RuaKusa](https://github.com/RuaKusa)
* References available upon request
