---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}

We are supported by several excellent core facilities, including...

{% include section.html %}

{% capture content %}

{%
  include figure.html
  image="images/sequencing.png"
  caption="NICHD Molecular Genomics Core"
  link="https://www.nichd.nih.gov/about/org/dir/other-facilities/cores/molecular-genomics"
  width="200px"
%}

{%
  include figure.html
  image="images/head-crop.png"
  caption="NIH Central Aquatics Facility"
  link="https://www.nichd.nih.gov/newsroom/releases/072512-zebrafish-slideshow"
  width="200px"
%}

{%
  include figure.html
  image="images/computing.png"
  caption="NICHD Bioinformatics Core"
  link="https://www.nichd.nih.gov/about/org/dir/other-facilities/cores/bioinformatics"
  width="200px"
%}


{% endcapture %}

{% include grid.html style="square" content=content %}
