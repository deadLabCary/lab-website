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

Some other thing here? We can also remove it.

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

## Funding

{% capture content %}
[![NASA](/images/team/nasa.svg.png)](https://www.nasa.gov/)

{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html %}

{%
  include figure.html
  image="images/team/samp.png"
  caption="This is a stock photo. Full lab picture coming soon!"
  width="100%"
%}