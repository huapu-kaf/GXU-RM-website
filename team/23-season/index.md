---
title: 成员
---

# {% include icon.html icon="fa-solid fa-users" %}23 赛季团队成员
{% include search-box.html %}
{% include search-info.html %}
历史成员请参考[历届成员](/team/history)。

{% include section.html %}

## {% include icon.html icon="fa-solid fa-users" %}指导老师

{% include list_portrait.html data="members" component="portrait" filters="role: 指导老师" %}

## {% include icon.html icon="fa-solid fa-users" %}团队负责人
{% include list_portrait.html data="members" component="portrait" filters="type: 23赛季团队负责人,time: 23" style="small"  %}

## {% include icon.html icon="fa-solid fa-users" %}机械组
  
{% include list_portrait.html data="members" component="portrait" filters="role: 机械组, time:23" style="small" %}

## {% include icon.html icon="fa-solid fa-users" %}电路组

{% include list_portrait.html data="members" component="portrait" filters="role: 电路组, time:23" style="small" %}
## {% include icon.html icon="fa-solid fa-users" %}嵌软组

{% include list_portrait.html data="members" component="portrait" filters="role: 嵌软组,time: 23" style="small"  %}
## {% include icon.html icon="fa-solid fa-users" %}算法组

{% include list_portrait.html data="members" component="portrait" filters="role: 算法组, time:23" style="small" %}
## {% include icon.html icon="fa-solid fa-users" %}运营组

{% include list_portrait.html data="members" component="portrait" filters="role: 运营组, time:23" style="small" %}

## {% include icon.html icon="fa-solid fa-users" %}梯队
{% include list_portrait.html data="members" component="portrait" filters="echelon: 23" style="tiny" %}




{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
