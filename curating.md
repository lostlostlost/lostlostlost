---
layout: page
---
# Curating

<strong><a href="" target="_blank">Blätter im Herbst</a></strong>, Blickle Kino, 2022<br>

<strong><a href="" target="_blank">Self-made, analog cinema!</a></strong>, Waldarena Krumpendorf, 2022

<strong><a href="https://www.rotlicht-festival.at/" rel="noopener noreferrer" target="_blank">Analog Film is Alive!</a></strong>, Rotlicht - Festival für analoge Fotografie, 2021 

<strong><a href="https://www.filmmuseum.at/kinoprogramm/schiene?schienen_id=1571968231436" rel="noopener noreferrer" target="_blank">10 years filmkoop wien</a></strong>, Austrian Filmmuseum, 2019<br>

<strong><a href="https://www.filmkoopwien.at/de/10-jahre-dotdotdot-open-air-kurzfilmfestival-10-jahre-filmkoop-wien/" rel="noopener noreferrer" target="_blank">10 years dotdotdot Open Air Kurzfilmfestival</a></strong>, Cinema Walk, 2019<br>

<strong><a href="https://www.filmkoopwien.at/de/filmkoop-wien-spaetsommerfest/" rel="noopener noreferrer" target="_blank">filmkoop wien</a></strong>, Sommerfest, 2018<br>

<strong><a href="https://www.freiburger-filmforum.de/archiv/programm-2017/" rel="noopener noreferrer" target="_blank">Freiburger Film Forum</a></strong>, Student's Platform, 2017<br>

<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/curating' %}
<img src="{{ image.path }}"/>
    {% endif %}
{% endfor %}
</ul>