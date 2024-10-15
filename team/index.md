---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team is still growing!

{%
  include button.html
  link="recruitment"
  text="Reach out"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/UCL.jpg" dark=true %}

Do you want to hear more?

{% include section.html %}

We are currently **recruiting**. Please [reach out](/recruitment) if interested! 

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
