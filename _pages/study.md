<!-- ---
layout: archive
title: "Course and Projects"
permalink: /study/
author_profile: true
---
这里有很多的课程项目：

{% include base_path %}

{% for post in site.study reversed %}
  {% include archive-single.html %}
{% endfor %} -->
---
layout: archive
title: "Teaching"
permalink: /study/
author_profile: true
---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
