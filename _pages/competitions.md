---
title: Competitions
layout: page
---

A list of competitions. 

{% for competition in site.competitions %}
<article>
<ul>
    <li>
    <a href="{{ competition.url }}">
        {{ competition.title }}
    </a>
    </li>
</ul>
</article>
{% endfor %}
