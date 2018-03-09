---
layout: photolist
title: Publications
menu: yes
mathjax: yes
---

[Papers](#papers) $$\mid$$ [Theses](#theses)

<br>

# Papers


{% assign years = site.data.papers | group_by: "year" %}
{% assign yearsSorted = years | sort: "name" | reverse %}
{% for y in yearsSorted %}

<br>
**{{ y.name }}**

{% assign books = y.items | group_by: "booktitle" %}
{% assign booksSorted = books | sort: "name" %}
{% for book in booksSorted %}

{% assign papers = book.items | sort: "authors" %}
{% for paper in papers %}
{% include paper.html paper=paper %}
{% endfor %}
{% endfor %}
{% endfor %}

<br>


Check [here](https://staff.fnwi.uva.nl/k.simaan/Sel_Publications.html) for older publications.

<br>

# Theses

