---
layout: page
title: Projects
---

# Projects

Below are some of the software projects I’ve built.

<ul>
  {% for project in site.projects %}
    <li>
      <strong>
        <a href="{{ project.url }}">{{ project.title }}</a>
      </strong>
      <br>
      {{ project.description }}
    </li>
  {% endfor %}
</ul>
