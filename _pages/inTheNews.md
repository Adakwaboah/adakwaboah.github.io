---
layout: archive
title: "In The News"
permalink: /inTheNews/
author_profile: true
---

* **[June 2024]** JHU ECE announces my NSF AccelNet NeuroPAC Fellowship Award: \\
  - [ECE Graduate Student Receives NSF Fellowship Award](https://engineering.jhu.edu/ece/news/ece-graduate-student-receives-nsf-fellowship-award/)

* **[March 2023]** First Organoid Intelligence Workshop I participated in captured in media: \\
  - [Move over, artificial intelligence. Scientists announce a new ‘organoid intelligence’ field](https://www.cnn.com/2023/03/02/world/brain-computer-organoids-scn/index.html)

* **[August 2021]** Cardiomyocyte model from my master's dissertation captured in media
  - [Researchers create cardiomyocyte model using a genetic algorithm](https://www.azolifesciences.com/news/20210831/Researchers-create-cardiomyocyte-model-using-a-genetic-algorithm.aspx)

{% comment %}
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

{% endcomment %}
