---
permalink: /
title: ""
excerpt: "About me"
author_profile: true

redirect_from:
  - /about/
  - /about.html
---
I am an economist working at the intersection of agriculture and environmental economics. My current research focuses on the estimation and projection of land use responses to environmental change, methods for empirically measuring adaptation, and health externalities associated with pesticide use.

**I am on the job market in the 2026-2027 academic year.**

<section class="section-light">
<div class="section-inner">


<h2>Research in Progress </h2>

{% assign papers = site.worksinprogress | where_exp: "p", "p.title" | sort: "date" | reverse %}

{% for paper in papers %}

<div style="margin-bottom: 2rem;">

  <p style="margin: 0;">
    <strong>{{ paper.title }}</strong>
    {% if paper.paperurl %}
      — <a href="{{ paper.paperurl }}" target="_blank">[link]</a>
    {% endif %}
  </p>

  {% if paper.authors %}
    <p style="margin: 0; font-size: 0.95em;">
      {{ paper.authors }}
    </p>
  {% endif %}

  {% if paper.content %}
    <p style="margin: 0.5em 0 0 0;">
      {{ paper.content }}
    </p>
  {% endif %}

</div>

{% endfor %}

</div>
</section>



<section class="section-white">
<div class="section-inner">

<h2>Publications</h2>

<ul style="list-style: none; margin: 0; padding: 0;">
{% for pub in site.publications %}
  <li style="margin-bottom: 0.75rem;">
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
<li>PhD, University of California, Davis (Expected 2027) </li>
<li>MSc, University of Guelph, 2021 </li>
<li>BSc, University of Waterloo, 2019 </li>
</ul>

</div>
</section>


    
