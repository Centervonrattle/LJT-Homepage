---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Science** — Hong Kong University of Science and Technology, 2024 to present
  * Supervisor: Professor Junxian He (HKUST NLP Group)
* **B.Eng.** — Shanghai Jiao Tong University, 2020 to 2024 (graduated June 2024)
  * Advised by Professor Junxian He during my undergraduate studies

Work experience
======
* **Research Intern**, MINIMAX — February 2025 to present
* **Research Intern**, Tencent WXG — June 2024 to September 2024
  * Internship advisor: Zifei Shan
* **Research Intern**, Shanghai AI Lab — June 2023 to December 2023
  * Internship advisor: Prof. Yu Cheng

Awards
======
* **Zhiyuan Honor Scholarship** — Shanghai Jiao Tong University

Skills
======
* Natural Language Processing, Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability
* Synthesis of verifiable reasoning data at scale (SynLogic)
* Inner-representation analysis for hallucination mitigation
* Composition of parameter-efficient modules
* Multi-discipline evaluation suite construction (C-Eval)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
