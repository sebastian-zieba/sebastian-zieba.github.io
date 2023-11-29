---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


Here you can find a list of all my publications: [ADS link](
https://ui.adsabs.harvard.edu/user/libraries/1ryuxALvQN2rWE-86p4lCQ)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

