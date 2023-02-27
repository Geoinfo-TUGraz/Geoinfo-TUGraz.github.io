---
title: Team
nav:
  order: 5
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: general"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pa"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ta"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: admin"
%}
{:.center}

{% include section.html %}

