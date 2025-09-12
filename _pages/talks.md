---
layout: default
permalink: /talks/
---

# My Talks (Test Page)

<ul>
{% for talk in site.talks %}
  <li>{{ talk.title }}</li>
{% endfor %}
</ul>
