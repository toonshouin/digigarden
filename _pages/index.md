---
layout: page
title: Home
id: home
permalink: /
---

# Welcome to Toonshouin's Garden! 🌱

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  All the scrap I want to share without needing create a new blog about, Enjoy!
</p>

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
