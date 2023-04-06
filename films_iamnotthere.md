---
layout: page
---

# I am not there

<strong><b><a href="https://vimeo.com/608228364" rel="noopener noreferrer" target="_blank">I am not there</a></b></strong>, 2017, 16mm, colour, sound, 3min <br>

In I am not there personal memories and family recordings of the past are haunting the present. Video8 fragments of a day as a child are superimposed with images thirty years later, the look through the viewfinder onto the empty spaces of the present collide with the look of the father through the viewfinder back then. Just as the mind assembles images of the past, connects it to perceptions of the present and imaginations of the future, analogue film materializes what Freud called the primary process: it collapses stable representations of linear time and space into a prismatic collage of images that physically relate to the actual event and create a new one, as material object and projected light here and now. The film as a physical object bears the imprint not only of images but of its development by hand.

Distribution: Canyon Cinema, Light Cone

# Screenings

Analog Mania, Rumania<br>
Artifact Small Format Film Festival, Canada<br>
Cinemistica, Spain<br>
Experiments in Cinema, USA<br>
International Short Film Festival Oberhausen, Germany<br>
Moscow International Experimental Film Festival (MIEFF), Russia<br>
Udine Film Forum, Online<br>
WestLicht/Diagonale, Vienna<br>


<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/iamnotthere' %}
<a class="img" href="{{ image.path }}"><img title="" src="{{ image.path }}"/></a>
    {% endif %}
{% endfor %}
</ul>