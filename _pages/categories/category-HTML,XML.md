---
title: "Front-end"
permalink: /categories/html-xml
layout: category
sidebar_main: true
---

about HTML / XML
{% assign posts = site.categories.['HTML/XML'] %}
{% for post in posts %} {% include archive-custom.html type=page.entries_layout %} {% endfor %}
