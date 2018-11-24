---
title: "Welcome"
layout: splash
date: 2018-11-23T12:00:00-00:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/img/splash_1.jpg
  actions:
    - label: "Learn more"
      url: "http://bit.ly/wbc-prodteam"
  caption: "Photo credit: **Wycliffe Production Team**"
excerpt: "We use creative and technical arts to help the community at Wycliffe Baptist Church respond to God in worship."
---
# Latest Updates
{% for post in site.posts limit:5 %}
  {% include archive-single.html %}
{% endfor %}