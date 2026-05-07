---
layout: page
title: Cool Stuff
permalink: /cool-stuff/
description: A little library of cool stuff I didn't make.

categories:
- resource
- friend
- game
- other
---

{{ page.description }}

## Resources

## Games

## Friends
Some friends of mine who also have their own websites!

{% assign links = site.data.cool-stuff | where: "tag", "friend" %}

{%- for link in links %}
- [{{ link.name }}]({{ link.url }})
{%- endfor %}

## Blogs and other cool stuff