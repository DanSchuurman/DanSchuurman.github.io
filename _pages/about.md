---
permalink: /
title: ""
excerpt: "About me"
author_profile: true

redirect_from: 
  - /about/
  - /about.html
---

I am an agricultural economist with interests in risk, environmental change, and econometrics. My current research focuses on the estimation and forecasting of land use responses to environmental change and methods for empirically measuring adaptation.


<p>Collections:</p>

{% for collection in site.collections %}
  <p>{{ collection.label }}</p>
{% endfor %}


