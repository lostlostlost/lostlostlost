---
layout: page
---

# 10 megabytes of memory

<strong><b><a href="https://vimeo.com/543725598" rel="noopener noreferrer" target="_blank">10 megabytes of memory</a></b></strong>, 2021, digital (from Video8), colour, silent, 2min <br>

Text Vienna Shorts (Neil Young):
After Mountain View (2019) and Into the Wild (2021), Vienna-based experimental miniaturist Markus Maicher lands his Vienna Shorts hat-trick with this unique study in digital autobiography. Compressing a whole decade of his family’s home movies into 10Mb of binary data, it bombards the viewer with two minutes of total sensory overload. The result is a giddy blast of turbo-speed nostalgia that manages to find a whole new angle on the well-worn found-footage format. 

<!--
Nach Mountain View (2019) und Into the Wild (2021) zaubert Markus Maicher, in Wien lebender Spezialist für experimentelle Miniaturen und mittlerweile Stammgast des Festivals, eine einzigartige digital-autobiografische Studie aus dem Hut: Er hat Privatfilme seiner Familie aus einem Jahrzehnt in 10 Megabyte an Binärdaten verwandelt und bombardiert mit der daraus entstandenen Reizüberflutung zwei Minuten lang das Publikum. Der euphorische Nostalgieflashback legt im Turbogang einen neuen Blick auf das altgediente Found-Footage-Format frei. (ny)-->

# Screenings

dot dot dot Open Air Kurzfilmfestival, Austria<br>
Small File Media Festival, Canada<br>
Split Videoart Festival, Croatia<br>
Tranås at the Fringe, Sweden <br>
Under the Radar, Austria<br>
Vienna Shorts Film Festival, Austria<br>

<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/10mbofmemory' %}
<a class="img" href="{{ image.path }}"><img title="" src="{{ image.path }}"/></a>
    {% endif %}
{% endfor %}
</ul>