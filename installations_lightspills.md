---
layout: page
---

# Light Spills

<strong><b>Light Spills</b></strong>, 16mm/DiaProjector Installation

Light Spills investigates analog film and photography as captured and projected light. At the beginning and end of each film roll light floods the emulsion, pulsates uncontrollably, retracts and marks the beginning and end of each roll. Film is a medium based on light and movement; movement however is an illusion created by the serial projection of still images. Light Spills reflects the relationship between film and photography, between movement and stillness and between projection and imprint. The installation shows one frame from the end of a roll of 16mm film, a look that is frozen in time, now becoming visible as an ephemeral light projection through a slide projector. The frame is projected onto an unexposed photo paper, it remains to be seen whether an imprint created by the projection will remain, as the sliver halogens slowly transform into silver particles. Next to the projection there is a text written with a typewriter, analog, fragile and only readable within the light projection. In order to be able to read the text one has to go through the projection and become aware that the image is not stable but a beam of light.

# Exhibitions

<a href="https://www.filmkoopwien.at/de/fotowien/" rel="noopener noreferrer" target="_blank">Analog Layers Exhibition</a>, Foto Wien, 2019<br>
<a href="https://www.analogmania.ro/Analog" rel="noopener noreferrer" target="_blank"> Analog Mania</a>, Rumania, 2021


<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/lightspills' %}
<img src="{{ image.path }}"/>
    {% endif %}
{% endfor %}
</ul>