---
layout: page
title: Notícias
description: Página voltada para divulgação de notícias e avisos relacionados ao curso.
nav_order: 1
---

# Notícias

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
