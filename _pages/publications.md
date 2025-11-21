---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

## Preprints & arXiv

**[A.1] LV-DOT: LiDAR-visual dynamic obstacle detection and tracking for autonomous robot navigation**  
Zhefan Xu\*, Haoyu Shen\*, Xinming Han, Hanyu Jin, **Kanlong Ye**, Kenji Shimada  
*arXiv preprint arXiv:2502.20607, 2025*  
[Paper](https://arxiv.org/abs/2502.20607) | [Code](https://github.com/Zhefan-Xu/LV-DOT.git) | [Project Page](#)

---

## Conference Workshops

**[W.1] Adaptive Planning Framework for UAV-Based Surface Inspection in Partially Unknown Indoor Environments**  
Hanyu Jin, Zhefan Xu, Haoyu Shen, Xinming Han, **Kanlong Ye**, Kenji Shimada  
*ICRA 2025 Construction Robotics Workshop*  
[Paper](https://construction-robots.github.io/papers/84.pdf) | [Code](#) | [Project Page](#)

---

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
