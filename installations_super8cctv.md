---
layout: page
---

# Super8CCTV

<strong><b>Super8CCTV</b></strong>, Super8 Camera and Projector Installation

Super8 is watching you!

# Exhibitions

<a href="https://kulturhofvillach.at/events/2022/2022-09-02_festival/Kulturhofkeller" rel="noopener noreferrer" target="_blank"> Kulturhof Festival</a>, Kulturhof Villach, 2022<br>


<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/super8cctv' %}
<img src="{{ image.path }}"/>
    {% endif %}
{% endfor %}
</ul>