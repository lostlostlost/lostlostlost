---
layout: page
---

# As you are coming closer

<strong><b>As you are coming closer</b></strong>, 2017, 16mm, colour, silent, 3min <br> 

As you are coming closer is interested in the relation between reality and image and the fact that our view onto reality is always framed. The world is posited as an image, a phantasmatic reality that is becoming more and more unstable the closer you get, until it dissolves.

# Screenings

Analogica, Online<br>
Cinemistica, Spain<br>
Festival de Sevilla, Spain<br>
Metro Kinokulturhaus, Austria<br>
Moscow International Experimental Film Festival (MIEFF), Russia<br>
Syros International Film Festival, Greece<br>
WestLicht/Diagonale, Austria<br>

<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/asyouarecomingcloser' %}
<img src="{{ image.path }}"/>
    {% endif %}
{% endfor %}
</ul>