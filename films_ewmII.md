---
layout: page
---

# Earth Water Motor II

<strong><b><a href="https://vimeo.com/793660463" rel="noopener noreferrer" target="_blank">Earth Water Motor II</a></b></strong>, 2023, 16mm, b/w, sound, 4min <br>

Cutting through landscapes with the machine. Destroying the postcard images of places we know. Part two of the Earth Water Motor series is filmed on soundstock with a 16mm Bolex, hand developed and edited in-camera. The film music is composed with an analogue synthesizer. Beginning in Bschabertal the series finds its continuation in Krumpendorf.

<!--
# Screenings

dot dot dot Open Air Kurzfilmfestival, Austria<br>
Small File Media Festival, Canada<br>
Split Videoart Festival, Croatia<br>
Tranås at the Fringe, Sweden <br>
Under the Radar, Austria<br>
Vienna Shorts Film Festival, Austria<br>
-->
<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/motorII' %}
<img src="{{ image.path }}"/>
    {% endif %}
{% endfor %}
</ul>