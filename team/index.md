---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Welcome to our team members!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: msc, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: " %}

{% include section.html background="images/background.jpg" dark=true %}

Some other writing here? We can also remove it.

{% include section.html %}

## Lab alumni

Some writing here, but we can delete it also.

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: msc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}

{% include section.html %}

## Funding and affiliations

{% capture content %}

{% include figure.html image="/images/funding/stri.png" caption="Smithsonian Tropical Research Institute" %}

[![Smithsonian Tropical Research Institute](/../../images/funding/stri.png)](https://stri.si.edu/)

[![Forest Global Earth Observatory](/images/funding/forest-geo.jpeg)](https://forestgeo.si.edu/)

[![National Science Foundation](/images/funding/nsf.png)](https://www.nsf.gov/)

[![Cary Institute of Ecosystem Studies](/images/funding/cary-institute.jpg)](https://www.caryinstitute.org/)

[![National Aeronautics and Space Administration](/images/funding/nasa.png)](https://www.nasa.gov/)

[![British Royal Society](/images/funding/royal-society.png)](https://royalsociety.org/)

[![Yale Center for Natural Carbon Capture](/images/funding/yncc.jpeg)](https://naturalcarboncapture.yale.edu/)

[![UK Natural Environment Research Council](/images/funding/ukri-nerc-square-logo.png)](https://www.ukri.org/councils/nerc/)

{% endcapture %}

{% include grid.html content=content %}
