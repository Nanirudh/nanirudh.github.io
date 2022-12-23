---
layout: archive
title: "Projects"
author_profile: true
permalink: /projects/
redirect_from: 
  - /projects/
  - /projects.html
---
{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
    {% if post.tags contains "projects" %}
         {% include archive-single.html %}           
    {% endif %}
  
{% endfor %}


