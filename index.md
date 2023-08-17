---
---

# deadLabCary's Website

An engaging 1-3 sentence description of your lab.

{% include section.html %}

## Highlights

{% capture text %}

See lab updates and follow our recent activity (this text should be changed)

{%
  include button.html
  link="news"
  text="Follow happenings in the lab"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="news"
  title="Lab updates"
  text=text
%}

{% capture text %}

Our lab focuses on a number of things, from lightning mortality to investigating deadwood and decomposition. This should probably link to topics page.

{%
  include button.html
  link="projects"
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
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are a group of ecologists, scientists, and ???. Together, we bring scientific and research experience spanning the entire globe.

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
  image="images/samp.png"
  link="team"
  title="Our Team"
  text=text
%}
