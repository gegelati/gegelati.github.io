---
title: Tags
layout: archive
toc: true
---

{% capture tags %}
  {% for tag in site.tags %}
    {{ tag[0] }}
  {% endfor %}
{% endcapture %}
{% assign sortedtags = tags | split:' ' | sort %}

{% for tag in sortedtags %}
  <h3 id="{{ tag }}">{{ tag }}</h3>
  {% for post in site.tags[tag] %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
{% endfor %}

[//]: # based on https://stackoverflow.com/questions/1408824/an-easy-way-to-support-tags-in-a-jekyll-blog