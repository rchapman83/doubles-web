---
permalink: "/doubles/"
layout: page
title: Doubles
heading: Profies
subtitle: Profiles
sitemap: true
robots-allow: true

---
<ul>
{% for profile in site.data.profiles.users %}
  <li>
      {{ profile.first_name }} {{ profile.last_name }}
  </li>
{% endfor %}
</ul>