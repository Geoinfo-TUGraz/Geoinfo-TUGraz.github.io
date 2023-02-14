---
title: Studying
nav:
  order: 1
  tooltip: Relevant Material for Students
---

# <i class="fas fa-microscope"></i>Studying

{% include section.html %}

{% capture text %}

{%
  include link.html
  link="courses"
  text="Courses"
  icon="fas fa-arrow-right"
  flip=true
%}

University courses offered by the Research Group Geoinformation
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="courses"
  title=""
  text=text
%}
{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  title="Resources"
  text="Helpful resources for students, such as software, books, or research papers"
%}
{%
  include feature.html
  image="images/photo.jpg"
  link="thesis_topics"
  title="BSc/MSc Thesis Topics"
  text="A list of open and completed BSc and MSc thesis topics"
%}