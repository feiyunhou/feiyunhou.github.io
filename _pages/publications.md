---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
meta_description: "Publications and research papers by Dr. Yunfei Hou - machine learning, data science, and transportation systems research"
meta_keywords: "research publications, machine learning papers, data science research, peer-reviewed articles"
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
