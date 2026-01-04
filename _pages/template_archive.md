---
layout: page
permalink: /template-archive/
title: Template Archive
description: Archive of original clean-blog template posts
nav: false
---

<ul>
{% for post in site.templates %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
  </li>
{% endfor %}
</ul>

<h2>Template Projects</h2>
<ul>
{% for project in site.template_projects %}
  <li>
    <a href="{{ project.url | relative_url }}">{{ project.title }}</a>
  </li>
{% endfor %}
</ul>
