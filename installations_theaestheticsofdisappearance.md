---
layout: page
---

# The Aesthetics of Disappearance

<strong><b>The Aesthetics of Disappearance</b></strong>, Video Installation

The Aesthetics of Disappearance thinks about the illusionary character of the image and its limits. Cinema has always been associated with illusion, but also with truth. If film is, according to Goddard, "truth 24 times per second“, then video is half truths 50 lines per second. And if film is the illusion of movement then video is the illusion of an image. What are the limits of this illusion? At what point is the illusion turning into its own raw material? I took a shot of my face with a Video8 camera and digitized the sequence into a file. The command-line program ffmpeg keeps compressing the file via a script for as long as it is running. Because the algorithm has to work over each new compression, the structural basis of the images becomes more and more visible.

# Exhibitions

Analog Mania, 2023<br>

<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/theaestheticsofdisappearance' %}
    {% if image.extname == '.jpg' or image.extname == '.jpeg' or image.extname == '.JPG' or image.extname == '.JPEG' %}
<a class="img" href="{{ image.path }}"><img title="" src="{{ image.path }}"/></a>
    {% endif %}
    {% endif %}
{% endfor %}
</ul>