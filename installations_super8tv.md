---
layout: page
---

# Super8TV

<strong><b>Super8TV</b></strong>, Super8/TV Installation

Eine Begegnung zweier Apparate, die Bilder auf ganz unterschiedliche Weise erzeugen, aber dem gleichen Ort entspringen. Ihre „poor images" strahlten und warfen sie in unzählige Wohnzimmer. Was bleibt ist ein kosmisches Rauschen und der weiße Strahl des Projektors. Ein Abgesang. Eine Umarmung.

# Exhibitions

<a href="https://www.viennaartweek.at/en/" rel="noopener noreferrer" target="_blank">Vienna Art Week</a>, Creative Cluster, 2022<br>


<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/super8tv' %}
<img src="{{ image.path }}"/>
    {% endif %}
{% endfor %}
</ul>