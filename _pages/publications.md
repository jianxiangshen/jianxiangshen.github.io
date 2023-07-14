---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* A updated list of my publications could be found at my [Google Scholar](https://scholar.google.com/citations?user=nJu03eIAAAAJ&hl=en) page.

* The personal copies of my papers could be found in my [ResearchGate](https://www.researchgate.net/profile/Jianxiang-Shen) page.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
