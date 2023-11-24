---
#layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Dimond, D., Heo, S., Ip, A., Rohr, C.S., Tansey, R., Graff, K., Dhollander, T., Smith, R.E., Lebel, C., Dewey, D., Connelly, A., & Bray, S. (2020). Maturation and interhemispheric asymmetry in neurite density and orientation dispersion in early childhood. NeuroImage, 221(117168). https://doi.org/10.1016/j.neuroimage.2020.117168

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
