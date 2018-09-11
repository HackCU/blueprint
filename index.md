---
layout: base
title: HackCU Blueprints
description: HackCU evolving blueprints.
---

Repository for event blueprints. 

Internal guides on how to organize HackCU events, workshops and more.

## Available guides

<ul>
{% for page in site.pages %}
<li><a href="{{page.url | relative-url }}">{{page.title}}</a></li>
{% endfor %}
</ul>

## Extra 
**Open sourced here**: [{{site.original_repo}}]({{site.original_repo}})