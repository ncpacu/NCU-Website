---
title: Competitions
layout: page
---

# Competitions

This page contains information about a wide range of competitions brought to you by NCU. Click on the links to view each competition in detail. If you wish to learn about any of the competitions, feel free to reach out to NCU or further research yourself.

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

# Suggesting a competition

You may also suggest a competition that you are interested but is not on this list. However, due to various constrains, NCU may not gurentee that this competition will be organized on a school level.

<form name="contact" netlify>
  <p>
    <label>Your name:</label> <br>
    <input type="email" name="name"/>
  </p>
  <p>
    <label>Your email:</label> <br>
    <input type="email" name="email"/>
  </p>
  <p>
    <label>Name of competition:</label> <br> 
    <input type="text" name="competition"/>
  </p>
  <p>
    <label>Additional information:</label> <br>
    <textarea type="text" name="additionalInfo" rows="4" cols="16">
    </textarea>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>