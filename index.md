---
---

# deadLabCary's Website

An engaging 1-3 sentence description of your lab.

{% include section.html %}

## Highlights

{% capture text %}

Follow our news and happenings from the lab.

{%
  include button.html
  link="news"
  text="Go to news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/main/picUpdate.png"
  link="news"
  title="Lab updates"
  text=text
%}

{% capture text %}

Our lab has a number of ongoing projects, from lightning mortality to investigating deadwood and decomposition. Check them out here!

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
  image="images/main/picProjects.jpeg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are a group of ecologists, scientists, and life-long students. Together, we combine our scientific and research experience from across the globe to help us investigate and better understand the natural world around us.

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
  image="images/main/picTeam.jpeg"
  link="team"
  title="Our Team"
  text=text
%}
