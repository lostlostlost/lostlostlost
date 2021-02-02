---
layout: page
---

# Installations

2019<br>
<strong> Light Spills, </strong> <a href="https://www.filmkoopwien.at/de/fotowien/" rel="noopener noreferrer" target="_blank">Analog Layers Exhibition</a>, Foto Wien

{% for file in site.static_files %}
  {% if file.image %}
  <img src="{{file.path}}" alt="{{file.name}}">
  {% endif %}
{% endfor %}

![](/assets/img/AnalogLayers_HQ-4.jpg "Analog Layers")
![](/assets/img/AnalogLayers_HQ-11.jpg "Analog Layers")
![](/assets/img/AnalogLayers_HQ-10.jpg "Analog Layers")