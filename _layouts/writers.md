---
layout: page
title: Authors
---
Tous les auteurs de ce projet.

{% for person in site.people %}

* <a href="{{ site.baseurl }}{{ person.url }}">{{ person.name }}</a>

{% endfor %}
