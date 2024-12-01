---
layout: home
title: "Willkommen auf Gochxx Blog"
permalink: /
description: "Dein Ort für Data Science und maschinelles Lernen"
---

# Willkommen auf Gochxx Blog!

Hier findest du spannende Inhalte zu:

- **Data Science**: Von den Grundlagen bis zu fortgeschrittenen Modellen.
- **Maschinelles Lernen**: Algorithmen, Python-Tutorials und praktische Anwendungen.
- **Python-Tools**: Pandas, NumPy, Scikit-Learn und mehr.

## Highlights

- 📚 [Über mich](/about/): Erfahre mehr über den Autor.
- 📝 [Erster Beitrag](/2024-12-01-erster-post/): Einblicke in die Welt von Data Science.
- 🚀 [Kontakt](/contact/): Lass uns in Verbindung bleiben.

## Kategorien

{% for category in site.categories %}
- [{{ category[0] }}]({{ site.url }}/categories/{{ category[0] | slugify }}/)
{% endfor %}

---

Bleib dran für weitere Updates und spannende Inhalte! 🎉
