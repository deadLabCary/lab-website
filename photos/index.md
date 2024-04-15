---
title: Photos
nav:
  order: 5
  tooltip: Lab photos
---

# {% include icon.html icon="fa-solid fa-camera" %}Lab photos

{% capture content %}
    {%
        include figure.html
        image="images/group-photo.jpg"
        caption="The team at our annual Christmas party, 2025"
        link="team"
        width="400px"
    %}
  {% include figure.html ... %}
  {% include figure.html ... %}
  {% include figure.html ... %}
  {% include figure.html ... %}
{% endcapture %}

{%
  include grid.html
  content=content
%}