---
title: Team
nav:
  order: 3
  tooltip: About the team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Members of my research laboratory study topics from vaccine and therapeutic design to structure-function relationships to the basic physical properties of water.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

We only accept Ph.D. candidates when we have at least 4 years of guaranteed funding. Prospective Ph.D. candidates should reach out in October to confirm funding availability. Expressions of interest for all other positions are welcome. Currently, we are especially seeking entry-level technical staff, as well as an undergraduate for a paid entomology position.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
