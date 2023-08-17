---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Feel free to reach out about XYZ.

{%
  include button.html
  type="email"
  text="gorae@caryinstitute.org"
  link="gorae@caryinstitute.org"
%}
{%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Location of Cary Institute"
  link="https://www.google.com/maps/place/Cary+Institute+of+Ecosystem+Studies/@41.7851445,-73.7364198,17z/data=!3m1!4b1!4m6!3m5!1s0x89dd6eb0ac71f6c3:0x77957d509a84f63c!8m2!3d41.7851405!4d-73.7338449!16s%2Fg%2F1vzv4nkb?entry=ttu"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Some writing here
{% endcapture %}

{% capture col2 %}
Do we want to keep this?
{% endcapture %}

{% capture col3 %}
We can remove this if we don't want it.
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
