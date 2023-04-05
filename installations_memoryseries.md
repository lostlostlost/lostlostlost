---
layout: page
---

# Memory Series

<strong><b>Memory Series</b></strong>, Three-Channel Video Installation

The installation shows the three-part film "Memory Series" on three CRT monitors. The video signal is coming from Raspberry Pi Zeros that are programmed as video loopers. An analog output has been soldered onto the boards, the cables go directly into the analog input of the monitors, displaying where "memory" is being processesd and how the signal travels from the machine to the display. The Memory Series compresses 10 human years, captured on Video8 tapes, into three different states of binary information: 10 megabytes, 1 megabyte and 1000 bits. The algorithm is working, memory is fading, images are becoming more and more abstract. The series thinks about the analog, the human, the subjective in relation to the digital, the objective and the algorithmic. What is the meaning of "memory" in the digital age?

# Exhibitions

Galerie Kras, 2023<br>

<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/videomemory' %}
    {% if image.extname == '.jpg' or image.extname == '.jpeg' or image.extname == '.JPG' or image.extname == '.JPEG' %}
<img src="{{ image.path }}"/>
    {% endif %}
    {% endif %}
{% endfor %}
</ul>