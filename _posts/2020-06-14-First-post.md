---
layout: post
date: 2020/06/14 12:00 AM +1000
categories:
- Jekyll
title: 'First Post '
heading: yup, first one
robots-allow: false
sitemap: false
author: Rowan
published: true

---
{% assign author = site.data.authors.authors[page.author] %}
{% if author %}
  <img src="{{ author.image }}">
  <p>{{ author.name }}</p>
{% endif %}