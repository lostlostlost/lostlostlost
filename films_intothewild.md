---
layout: page
---

# Into the Wild

<strong><b><a href="https://vimeo.com/506512777" rel="noopener noreferrer" target="_blank">Into the Wild</a></b></strong>, 2020, 16mm/digital, b/w and colour, sound, 5min <br>

Images, harvested on a farm in Mount Forest, Canada, captured with a hand-cranked Bolex, on film material that is made for sound only. Processed in buckets, in shimmering red light down by the old stables. A glimpse through the cracks, somebody is walking in the meadow, trees trembling in the wind, flowers, grass. A world that only film can see, a material flow emerging from the coupling of camera, celluloid, silver salts, chemicals, light particles and the hand of the filmmaker. The film was entirely processed by hand and chemically treated: overexposed images were brought back to life with bleach, other images were solarized and reversed.

Text Diagonale (Michele Koch):
With a Bolex and analogue black-and-white material, which is actually used for sound recording, Markus Maicher captured ephemeral moments in nature on a farm in Canada and developed the film roles by hand in an improvised darkroom. Into the Wild is raw, scratched, fragile, fleeting—and full of ghostly beauty.

Distribution: Canyon Cinema, CFMDC, Light Cone

# Screenings

Bogotá Experimental Film Festival, Columbia<br>
Chicago Underground Film Festival, USA<br>
Diagonale, Austria<br>
Filmkoop Wien, Austria<br>
Harkat 16mm Film Festival, India<br>
Istanbul International Experimental Film Festival, Turkey<br>
Kinoskop – Analog Experimental Film Festival, Serbia<br>
Metrokino Kulturhaus, Austria<br>
Peripheries Experimental Film & Video Festival, USA<br>
Tranås at the Fringe, Sweden<br>
Vienna Shorts Film Festival, Austria<br>


<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/intothewild' %}
<a class="img" href="{{ image.path }}"><img title="" src="{{ image.path }}"/></a>
    {% endif %}
{% endfor %}
</ul>