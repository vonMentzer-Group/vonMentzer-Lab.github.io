---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a small but enthusiastic team and we foster an environment where team members are treated equally, and where we respect and admire our differences.  If you are interested in joining our team feel free to get in touch with a CV and cover letter/statement explaining your interest in our research, so we can discuss future opportunities. 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

We work with a wide range of outstanding groups and awesome researchers from around the world, and we’re always on the lookout for new and unique perspectives. 

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}