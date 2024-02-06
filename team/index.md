---
title: Team
nav:
  order: 3
  tooltip: Meet the lab!
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Members at the Cary Institute

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: msc, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: intern, group: " %}
{% include list.html data="members" component="portrait" filters="role: technician, group: " %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: " %}

## Affiliate researchers

Members at other institutions

{% include list.html data="members" component="portrait" filters="role: pi, group: affiliate" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: affiliate" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: affiliate" %}
{% include list.html data="members" component="portrait" filters="role: technician, group: affiliate" %}
{% include list.html data="members" component="portrait" filters="role: msc, group: affiliate" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: affiliate" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: affiliate" %}

## Lab alumni

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: msc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: intern, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: technician, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}

{% include section.html %}

## Funding and affiliations

{% capture content %}

{% 
  include figure.html 
  image="/images/funding/stri.png" 
  link="https://stri.si.edu/"
%}

{% 
  include figure.html 
  image="/images/funding/nsf.png" 
  link="https://www.nsf.gov/"
%}

{% 
  include figure.html 
  image="/images/funding/cary-institute.jpg" 
  link="https://www.caryinstitute.org/"
%}

{%
  include figure.html 
  image="/images/funding/nasa.png" 
  link="https://www.nasa.gov/"
%}

{% 
  include figure.html 
  image="/images/funding/forest-geo.jpeg" 
  link="https://forestgeo.si.edu/"
%}

{%
  include figure.html 
  image="/images/funding/ukri-nerc-square-logo.png" 
  link="https://www.ukri.org/councils/nerc/"
%}

{%
  include figure.html 
  image="/images/funding/royal-society.png" 
  link="https://royalsociety.org/"
%}

{%
  include figure.html 
  image="/images/funding/yncc.jpeg" 
  link="https://naturalcarboncapture.yale.edu/"
%}

{% endcapture %}

{% include grid.html content=content %}
