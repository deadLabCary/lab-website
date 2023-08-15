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
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: " %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

## Lab alumni

{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: programmer, group: alum" style="small" %}

{% include section.html %}

## Funding

{% capture content %}
[![NASA](/images/team/nasa.png)](https://www.nasa.gov/)
{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html %}

{%
  include figure.html
  image="images/team/samp.png"
  caption="This is a stock photo. Full lab picture coming soon!"
  width="100%"
%}