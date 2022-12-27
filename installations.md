---
layout: page
---

# Installations

<strong> Lichtbild 4:3, </strong> 
<a href="https://kulturhofvillach.at/events/2022/2022-11-26_vernissage_maicherplessl/" rel="noopener noreferrer" target="_blank">Schauraum</a>, Kulturhof Villach, 2022<br>

<strong> Super8TV, </strong> 
<a href="https://www.viennaartweek.at/en/" rel="noopener noreferrer" target="_blank">Vienna Art Week</a>, Creative Cluster, 2022<br>

<strong> Super8CCTV, </strong>
<a href="https://kulturhofvillach.at/events/2022/2022-09-02_festival/Kulturhofkeller" rel="noopener noreferrer" target="_blank"> Kulturhof Festival</a>, Kulturhof Villach, 2022<br>

<strong> Light Spills, </strong>
<a href="https://www.filmkoopwien.at/de/fotowien/" rel="noopener noreferrer" target="_blank">Analog Layers Exhibition</a>, Foto Wien, 2019 //
<a href="https://www.analogmania.ro/Analog" rel="noopener noreferrer" target="_blank"> Analog Mania</a>, Rumania, 2021

<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/installations' %}
<img src="{{ image.path }}"/>
    {% endif %}
{% endfor %}
</ul>