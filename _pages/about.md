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



<section class="section-light">
<div class="section-inner">

<h2>Working Papers</h2>

<ul>
{% assign papers = site.workingpapers | sort: 'date' | reverse %}
{% for paper in papers %}
  <li>
    <a href="{{ paper.url | relative_url }}">
      {{ paper.title }}
    </a>
  </li>
{% endfor %}
</ul>

</div>
</section>