---
---

{% include section.html %}

## Highlights

{% capture text %}

Here you'll find content related to Design, Pedagogy, Culturally Responsive Teaching, Emerging Technologies, and Synchronous Instruction.

{%
  include button.html
  link="projects"
  text="Browse all content"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/workshop.png"
  link="projects"
  title="My Content and Projects"
  flip=true
  style="bare"
  text=text
%}


{% comment %}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% endcomment %}

{% capture text %}

Learn more about me and my background.

{%
  include button.html
  link="team"
  text="Learn More"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/mesmaller.jpg"
  link="team"
  title="About Me"
  text=text
%}
