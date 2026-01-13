---
layout: page
title: Projects
permalink: /projects/
---


#### University Software Engineering Projects
- does mixing markdown and html work?
- bullet 2

<p>
  Showcase coming soon. For now, see:
</p>

<ul class="ul--bulletless">
  {% for social in site.data.socials %}
    <li><a href="{{ social.url }}">{{ social.platform }}</a></li>
  {% endfor %}
</ul>
