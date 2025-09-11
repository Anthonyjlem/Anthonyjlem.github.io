---
permalink: /
title: "Anthony Lem"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I completed my M.Sc. in Computer Science at the [Robot Vision & Learning (RVL) Lab](https://rvl.cs.toronto.edu/) at the University of Toronto under the supervision of Professor [Florian Shkurti](https://www.cs.toronto.edu/~florian/). My research focused on generative AI for robot perception. Before that, I received my BASc. in Engineering Science at the University of Toronto, where I was fortunate to research at the [Multimedia Laboratory](https://www.dsp.utoronto.ca/) under the supervision of Professor [Konstantinos Plataniotis](https://www.comm.utoronto.ca/~kostas/). I also had an internship at Qualcomm.

# Publications {#publications}

<div class="pub-list">
  {% for post in site.publications reversed %}
    {% if post.show %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>

# Projects {#projects}

<div class="proj-list">
  {% assign portfolio = site.portfolio | sort: "date" | reverse %}
  {% for post in portfolio %}
    {% if post.show %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</div>
