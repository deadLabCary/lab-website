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
        image="images/field/PXL_20231005_224621230.jpg"
        caption="The field station at Barro Colorado Island"
        width="400px"
    %}
    {%
        include figure.html
        image="images/field/PXL_20230502_162513735.jpg"
        caption="One of the field change meters to detect lightning"
        width="400px"
    %}
    {%
        include figure.html
        image="images/field/PXL_20231005_184049637.jpg"
        caption="Excited to be setting up the Gigante protocol at BCI!"
        width="400px"
    %}
    {%
        include figure.html
        image="images/field/PXL_20231003_133531494.jpg"
        caption="Taking the boat to find lightning strikes on southern BCI"
        width="400px"
    %}
    {%
        include figure.html
        image="images/field/PXL_20231007_165940778-EFFECTS.jpg"
        caption="A view of Panama City from Punta Culebra"
        width="400px"
    %}
    {%
        include figure.html
        image="images/field/IMG_9629.png"
        caption="Gigante team in the forest"
        width="400px"
    %}
    {%
        include figure.html
        image="images/field/PXL_20231008_153758007.jpg"
        caption="Tall tree next to a gap"
        width="400px"
    %}
    {%
        include figure.html
        image="images/field/IMG_2628.jpg"
        caption="Watching the drone come in to land, BCI"
        width="400px"
    %}
    {%
        include figure.html
        image="images/field/PXL_20231008_151419145.jpg"
        caption="One of the tall trees on BCI"
        width="400px"
    %}
{% endcapture %}

{%
  include grid.html
  content=content
%}