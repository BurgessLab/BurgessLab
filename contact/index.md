---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Applications from prospective postdocs and grad students are welcome. Please send your CV and briefly outline the type of research project you'd be interested in pursuing here.

{%
  include button.html
  type="email"
  text="burgessha@mail.nih.gov"
  link="jburgessha@mail.nih.gov"
%}
{%
  include button.html
  type="phone"
  text="(301) 402-6018"
  link="+1-301-402-6018"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/MHfodYsgi8xPGp666"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/dc-blossoms.jpg"
  caption="Cherry blossoms in Washington DC in spring"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/nih-bethesda.jpg"
  caption="The lab is part of the NIH intramural research program"
%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/fish-facility.jpg"
  caption="Part of the zebrafish facility at the NIH"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

{% include section.html dark=true %}

{% capture col1 %}
This is not an official NIH site and does not represent official NIH or government views.
{:.center}
{% endcapture %}

{% include cols.html col1=col1 %}
