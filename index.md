---
layout: page
---

I am an experimental filmmaker, projectionist and lecturer in media theory, spatial theory and artistic research. I am interested in analogue filmmaking as artistic practice and emancipatory aesthetic politics. The aspect of sharing and open source technology in the analogue world also brought me to computers, code and free software.

If you wanna get in touch, write me a <a href="mailto:lostlostlost@posteo.net">mail</a>

<img src="/assets/img/CosmaGrosser_Projektionist.JPG" alt="Cosma Grosser" title="Projektionist" width="1000" />
Photo: Cosma Grosser

# Blog

{% for post in site.posts %}

<a href="{{ post.url }}">{{post.title}}</a><br>

{% endfor %}