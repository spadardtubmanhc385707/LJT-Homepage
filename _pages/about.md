---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a first-year PhD candidate at HKUST NLP Group, supervised by Professor Junxian He. My research focuses on natural language processing and machine learning.

## Academic Background

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024-Present
- **B.Eng.**, Shanghai Jiao Tong University, 2020-2024; graduated in June 2024
- **Research group:** HKUST NLP Group, supervised by Professor Junxian He
- **Earlier advising:** Professor Junxian He advised me during my undergraduate studies at Shanghai Jiao Tong University

## Research Experience

- **Research Intern**, MINIMAX, February 2025-Present
- **Research Intern**, Tencent WXG, June 2024-September 2024
  - Advisor: Zifei Shan
- **Research Intern**, Shanghai AI Lab, June 2023-December 2023
  - Advisor: Prof. Yu Cheng

## Research Skills

- Natural language processing
- Machine learning
- LLM reasoning and reinforcement learning
- Hallucination in Vision-Language Models
- LLM truthfulness and interpretability

## Honors

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Publications

{% include base_path %}
{% for category in site.publication_category %}
  {% assign title_shown = false %}
  {% for post in site.publications reversed %}
    {% if post.category != category[0] %}
      {% continue %}
    {% endif %}
    {% unless title_shown %}
      <h2>{{ category[1].title }}</h2>
      <hr />
      {% assign title_shown = true %}
    {% endunless %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X:** [@junteng88716710](https://twitter.com/junteng88716710)
