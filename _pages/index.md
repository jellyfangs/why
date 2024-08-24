---
layout: page
title: Home
id: home
permalink: /
---

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  I’m Jerry, a new father, a product manager, web developer, mobile app developer, and AI researcher in Silicon Valley with a background in small business founder and military experience serving as a marine combat engineer.
</p>

<strong>My latest notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 10 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 64rem;
  }
</style>
