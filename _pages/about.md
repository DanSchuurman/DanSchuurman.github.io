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
{% assign papers = site.workingpapers | where_exp: "p", "p.title" | sort: "date" | reverse %}

{% for paper in papers %}
  <li>
    <a href="{{ paper.url | relative_url }}">
      {{ paper.title }}
    </a>
    {% if paper.date %}
      <small> ({{ paper.date | date: "%Y" }})</small>
    {% endif %}
  </li>
{% endfor %}
</ul>

</div>
</section>


<section class="section-white">
<div class="section-inner">

<h2>Publications</h2>

<ul>
{% for pub in site.publications %}
  <li>
    <a href="{{ pub.url | relative_url }}">
      {{ pub.title }}
    </a>
    {% if pub.venue %}
      — {{ pub.venue }}
    {% endif %}
  </li>
{% endfor %}
</ul>

</div>
</section>


<section class="section-dark">
<div class="section-inner">

<h2>Education</h2>

<ul>
<li>PhD, University X</li>
<li>BA, University Y</li>
</ul>

</div>
</section>