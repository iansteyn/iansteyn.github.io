---
layout: page
title: Cool Stuff
permalink: /cool-stuff/
description: A little library of cool stuff I didn't make.
---

{{ page.description }}

## Resources

## Games

## Friends
Some friends of mine who also have their own websites!

{% for item in site.data.cool-stuff | where: 'tag', "friend" %}
- [{{ item.name }}]({{ item.url }})
{% endfor %}

## Blogs and other cool stuff