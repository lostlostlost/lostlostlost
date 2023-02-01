---
layout: page
---

# Earth Water Motor

<strong><b><a href="https://vimeo.com/793661491" rel="noopener noreferrer" target="_blank">Earth Water Motor</a></b></strong>, 2022, 16mm, b/w, silent, 4min <br>

Topology of a Tyrolean mountain landscape in a 16mm triple projection. The audio-visual as well as the auto-mobile machine traverse and transcend the valley from Boden to Bschlabs. The film was made during a residency at the Tyrolean Bschlabertal and reflects the topology of an abandoned place as well as the conditions of its own creation. A darkroom was built in the old elementary school, film strips were hung to dry in the classrooms and then projected in a self-built cinema in an old shed. The images were filmed on print material with a Bolex camera, they are thus raw and multilayered like the valley, created by manual labor as it is still the basis of everyday existence in the Bschlabertal.

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
    {% if image.path contains 'assets/img/earthI' %}
<img src="{{ image.path }}"/>
    {% endif %}
{% endfor %}
</ul>