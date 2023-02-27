---
title: Studying
nav:
  order: 3
  tooltip: Relevant material for students
---

# <i class="fas fa-solid fa-book-open"></i>Studying

{% include section.html %}


<!-- 1st paragraph -->
{% capture text %}
{%
  include link.html
  link="studying/courses"
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
  image="images/website/fa-courses.png"
  link="studying/courses"
  title=""
  text=text
%}


<!-- 2nd paragraph -->

{% capture text %}
{%
  include link.html
  link="studying/resources"
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
  image="images/website/fa-book.png"
  link="studying/resources"
  title=""
  text=text
%}



<!-- 3rd paragraph -->
{% capture text %}
{%
  include link.html
  link="studying/thesis_topics"
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
  image="images/website/fa-theses.png"
  link="studying/thesis_topics"
  title=""
  text=text
%}