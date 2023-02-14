---
title: Studying
nav:
  order: 1
  tooltip: Relevant Material for Students
---

# <i class="fas fa-microscope"></i>Studying

{% include section.html %}


<!-- 1st paragraph -->
{% capture text %}
{%
  include link.html
  link="courses"
  text="Courses"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
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


<!-- 2nd paragraph -->

{% capture text %}
{%
  include link.html
  link="resources"
  text="Resources"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
Helpful resources for students, such as software, books, or research papers
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  title=""
  text=text
%}



<!-- 3rd paragraph -->
{% capture text %}
{%
  include link.html
  link="thesis_topics"
  text="BSc/MSc Thesis Topics"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
A list of open and completed BSc and MSc thesis topics
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="thesis_topics"
  title=""
  text=text
%}