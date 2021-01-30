---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[OpenRTiST: End-to-End Benchmarking for Edge Computing](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9229154)<br/>
George, S., Eiszler, T., Iyengar, R., Turki, H., Feng, Z., Wang, J., Pillai, P., Satyanarayanan, M.<br/>
IEEE Pervasive Computing, Volume 19, Issue 4, October-December 2020

[Towards Scalable Edge-Native Applications](http://elijah.cs.cmu.edu/DOCS/wang-sec2019.pdf)<br/>
Wang, J, Feng, Z., George, S., Iyengar, R., Pillai, P., Satyanarayanan, M.<br/>
Proceedings of the Fourth IEEE/ACM Symposium on Edge Computing (SEC 2019), Washington, DC, November 2019

[Towards Drone-sourced Live Video Analytics for the Construction Industry](http://elijah.cs.cmu.edu/DOCS/george-hotmobile2019.pdf)<br/>
George, S., Wang, J., Bala, M., Eiszler, T., Pillai, P., Satyanarayanan, M.<br/>
Proceedings of the 20th International Workshop on Mobile Computing Systems and Applications (HotMobile ’19)

[Bandwidth-efficient Live Video Analytics for Drones via Edge Computing](http://elijah.cs.cmu.edu/DOCS/wang-sec2018.pdf)<br/>
Wang, J., Feng, Z.,  Chen, Z., George, S., Bala, M., Pillai, P., Yang, S., Satyanarayanan, M.<br/>
Proceedings of the Third IEEE/ACM Symposium on Edge Computing (SEC 2018), Bellevue, WA, October 2018

[Edge-based Discovery of Training Data for Machine Learning](http://elijah.cs.cmu.edu/DOCS/feng-sec2018.pdf)<br/>
Feng, Z.,  George, S., Harkes, J.,  Pillai, P. , Klatzky, R., Satyanarayanan, M.<br/>
Proceedings of the Third IEEE/ACM Symposium on Edge Computing (SEC 2018), Bellevue, WA, October 2018

[An algorithm for automated, noninvasive detection of cortical spreading depolarizations based on EEG simulations](https://ieeexplore.ieee.org/abstract/document/8445667)<br/>
Chamanzar, A., George, S., Venkatesh, P., Chamanzar, M.,Shutter, L., Elmer, J., Grover, P.<br/>
IEEE Transactions on Biomedical Engineering 66.4 (2018): 1115-1126.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
