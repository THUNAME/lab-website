---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


清华大学网络体系结构与测量研究组(THUNAME)目前由刘莹研究员、何林助理研究员负责，组内共有博士生6名、硕士生5名。我们致力于研究网络体系结构与测量技术，并以此为基础，开展网络空间测绘、互联网体系结构、网络管理、计算机系统等方面的研究。


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi1'" %}
{% include list.html data="members" component="portrait" filter="role == 'pi2'" %}
{% include list.html data="members" component="portrait" filter="role == 'PhD2022' or role == 'masters2022' "%}
{% include list.html data="members" component="portrait" filter="role == 'PhD2023' or role == 'masters2023' "%}
{% include list.html data="members" component="portrait" filter="role == 'PhD2024' or role =='masters2024' "%}
{% include list.html data="members" component="portrait" filter="role == 'PhD2025' or role =='masters2025' "%}
{% include list.html data="members" component="portrait" filter="role == 'PhD2026' or role =='masters2026' "%}
{% include list.html data="members" component="portrait" filter="role == 'PhD2027' or role =='masters2027' "%}



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
