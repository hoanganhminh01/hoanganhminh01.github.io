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
* Ph.D. in Electrical and Electronic Engineering, RMIT University, July 2025 – Present
* M.S. in Computer Science (Data Science), University of Washington, 2022–2024
* B.S. in Computer Science (Data Science), University of Washington, 2020–2022
* A.S. in Computer Science, Seattle Central College, 2019–2020

Work experience
======
* **Visiting Lecturer**, Asia University — Ho Chi Minh City, Vietnam *(Sept 2025 – Present)*

* **Visiting Lecturer**, FPT University — Ho Chi Minh City, Vietnam *(May 2025 – Present)*

* **Lecturer**, Swinburne University of Technology — Ho Chi Minh City, Vietnam *(Aug 2024 – Present)*

* **Machine Learning Research Intern**, Lawrence Livermore National Laboratory — Livermore, CA *(Sept 2023 – Mar 2024)*
  * Improved vehicle classification training pipeline by 50% and deployed BLIP2 & InstructBLIP for nuclear threat detection enhancements.

* **Database Research Intern**, Sandia National Laboratories — Livermore, CA *(Jun 2023 – Aug 2023)*
  * Built a database of molecular saddle points for ML tasks including reaction prediction and pathway exploration.

* **Graduate Teaching Assistant**, University of Washington — Seattle, WA *(Sept 2022 – Jun 2024)*
  * Courses: Machine Learning (CSE 446/546), Computer Vision (CSE 455), Statistical Reasoning (STAT 220).

* **Deep Learning Research Assistant**, Intel Vietnam / RMIT University — Ho Chi Minh City, Vietnam *(Jul 2022 – Nov 2022)*
  * Achieved 85.02% accuracy and 90.24% precision in photovoltaic panel fault detection using customized CNNs.

* **Research Assistant**, InfoSeeking Lab — Seattle, WA *(Feb 2022 – Dec 2022)*
  * Co-authored survey analyzing 350+ papers on counterfactual explanations & algorithmic recourse.

  
Skills
======
* **Programming:** Python, Java, JavaScript, C, C#, C++, SQL, SQLite
* **Frameworks & Tools:** PyTorch, TensorFlow, SciPy, Scikit-learn, Pandas, NumPy, PySpark, Matplotlib, Dash, OpenCV, Hadoop, Kafka, Tableau, d3.js, p5.js, KNIME

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

