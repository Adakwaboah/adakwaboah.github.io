---
layout: archive
title: "In The News"
permalink: /inTheNews/
author_profile: true
---


* [March 2023] First Organoid Intelligence Workshop I participate in captured in media: \\
  - [Move over, artificial intelligence. Scientists announce a new ‘organoid intelligence’ field](https://www.cnn.com/2023/03/02/world/brain-computer-organoids-scn/index.html)

{% comment %}
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% endcomment %}
