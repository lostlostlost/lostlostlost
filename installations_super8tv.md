---
layout: page
---

# Super8TV

<strong><b>Super8TV</b></strong>, Super8/TV Installation

An encounter of two apparatuses that operate in a very different logic, but share a common history. Both machines used to project and emanate their „poor images“ into countless living rooms. What remains is the white beam of light of the projector and the cosmic noise of the TV set. A farewell, an embrace.

# Exhibitions

<a href="https://www.viennaartweek.at/en/" rel="noopener noreferrer" target="_blank">Vienna Art Week</a>, Creative Cluster, 2022<br>


<ul>
{% for image in site.static_files %}
    {% if image.path contains 'assets/img/super8tv' %}
<img src="{{ image.path }}"/>
    {% endif %}
{% endfor %}
</ul>