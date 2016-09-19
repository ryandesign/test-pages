---
title: Things
---

{% for thing in site.data.things.things %}
* {{ thing.name }}
{% else %}
There are no things.
{% endfor %}