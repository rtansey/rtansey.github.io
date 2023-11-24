---
#layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
**2023**

<ins>Tansey, R.</ins>, Graff, K., Rohr, C.S., Dimond, D., Ip, A., Yin, S., Dewey, D., & Bray, S. (2023). Functional MRI responses to naturalistic stimuli are increasingly typical across early childhood. _Developmental Cognitive Neuroscience_, 62. [https://doi.org/10.1016/j.dcn.2023.101268](https://doi.org/10.1016/j.dcn.2023.101268)


**2022**

Graff, K., <ins>Tansey, R.</ins>, Rai, S., Ip, A., Rohr, C.S., Dimond, D., Dewey, D., & Bray, S. (2022). Functional connectomes become more longitudinally self-stable, but not more distinct from others, across early childhood. _NeuroImage_, 258. [https://doi.org/10.1016/j.neuroimage.2022.119367](https://doi.org/10.1016/j.neuroimage.2022.119367)

Graff, K., <ins>Tansey, R.</ins>, Ip, A., Rohr, C.S., Dimond, D., Dewey, D., & Bray, S. (2022). Benchmarking common preprocessing strategies in early childhood functional connectivity and intersubject correlation fMRI. _Developmental Cognitive Neuroscience_, 54. [https://doi.org/10.1016/j.dcn.2022.101087](https://doi.org/10.1016/j.dcn.2022.101087)

<ins>Tansey, R.</ins>, Graff, K., Rohr, C.S., Dimond, D., Ip, A., Dewey, D., & Bray, S. (2022). Inattentive and hyperactive traits differentially associate with interindividual functional synchrony during video viewing in young children without ADHD. _Cerebral Cortex Communications_, 3(1). [https://doi.org/10.1093/texcom/tgac011](https://doi.org/10.1093/texcom/tgac011)


**2021**

Samson, A.D., Rohr, C.S., Park, S., Arora, A., Ip, A., <ins>Tansey, R.</ins>, Comessotti, T., Madigan, S., Dewey, D., & Bray, S. (2021). Videogame exposure positively associates with selective attention in a cross-sectional sample of young children. _PLOS One_, 16(9). [https://doi.org/10.1016/j.neuroimage.2020.117168](https://doi.org/10.1371/journal.pone.0257877)


**2020**

Dimond, D., Heo, S., Ip, A., Rohr, C.S., <ins>Tansey, R.</ins>, Graff, K., Dhollander, T., Smith, R.E., Lebel, C., Dewey, D., Connelly, A., & Bray, S. (2020). Maturation and interhemispheric asymmetry in neurite density and orientation dispersion in early childhood. _NeuroImage_, 221. [https://doi.org/10.1016/j.neuroimage.2020.117168](https://doi.org/10.1016/j.neuroimage.2020.117168)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
