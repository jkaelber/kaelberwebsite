---
---

# Welcome

I would like to use this website to tell you about some research questions I am interested in, some exciting findings, and the wonderful people who work in my group. I will also post reference material such as job openings, opportunities for collaboration, and publications.

I do two main things professionally: research, and service to the community through the Rutgers CryoEM & Nanoimaging Facility (RCNF). I maintain a separate page for the RCNF; you can find the RCNF webpage in the link above.

{% include section.html %}

## Highlights

{% capture text %}

Viruses are the smallest but most elegant organisms on this planet. In this group we apply our expertise in structural biology techniques, especially cryo-electron microscopy, to map the chemistry of viruses to their ecology and applications. The smallest viruses are some of our favorites: parvoviruses (such as AAV), circoviruses, and anelloviruses.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Research"
  text=text
%}

{% capture text %}

Active projects include: designing improved viral vectors for gene therapy, improving methods for cryo-electron microscopy, understanding the basic biology of virus entry into the nucleus, creating vaccines and therapeutics for humans and economically-significant species, understanding the implications of virus structure and evolution for the search for life in the universe, and developing improved hardware for structural studies.

{%
  include button.html
  link="tools"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Learn about lab members and their own interests. We come from backgrounds from condensed-matter physics to entomology to undertake cross-disciplinary investigations.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Team"
  text=text
%}
