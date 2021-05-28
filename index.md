---
title: Instructions hébergées en ligne
permalink: index.html
layout: home
---

# Répertoire de contenu

Les liens hypertexte vers chaque exercice et démonstration d’atelier sont répertoriés ci-dessous.

## Labos

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
| Module | Labo |
| --- | --- | 
{% for activity in labs  %}| {{ activity.lab.module }} | [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}

## Démos

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| Module | Démo |
| --- | --- | 
{% for activity in demos  %}| {{ activity.demo.module }} | [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
