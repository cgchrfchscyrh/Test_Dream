---
title: People
nav:
  order: 3
  tooltip: About our team
---

{% capture text %}
{:.center}
# Professor
---
{%
  include button.html
  link="members/JinhoLee.html"
  text="Shuai Li"
  flip=true
  style="bare"
%}
{:.center}
Email: shuai.li@essie.ufl.edu

{% endcapture %}

{%
  include feature.html
  image="images_profile/ShuaiLi.jpg"
  link="members/JinhoLee.html"
  flip=true
  style="bare"
  text=text
%}


{% include section.html %}

# Graduate Students

{% include listmember.html data="members" component="portrait" filters="role: ^(?!pi$), role: ^(?!alumni$)" %}

{% include section.html %}

# Alumni

{% include listmember.html data="members" component="portrait" filters="role: alumni" %}

