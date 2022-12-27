---
layout: archive
title: ""
author_profile: true
permalink: /posts/
redirect_from: 
  - /posts/
  - /posts.html
---
{% include base_path %}

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
    {% if post.tags contains "blog" %}
         {% include archive-single.html %}           
    {% endif %}
  
{% endfor %}

