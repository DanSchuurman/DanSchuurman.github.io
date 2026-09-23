---
permalink: /
title: ""
excerpt: "About me"
author_profile: true

redirect_from:
  - /about/
  - /about.html
---
I am an economist and PhD candidate at UC Davis. My research is at the intersection of agriculture and environmental economics. I am currently focusing on the estimation and projection of land use responses to environmental change, methods for empirically measuring adaptation, and health externalities associated with pesticide use.

**I am on the job market in the 2026-2027 academic year.**

<section class="section-light">
<div class="section-inner">

<h2>Research in Progress</h2>

{% assign papers = site.worksinprogress | where_exp: "p", "p.title" | sort: "date" | reverse %}

{% for paper in papers %}

<details style="margin-bottom: 1.5rem;">

  <summary style="cursor: pointer;">
    <strong>{{ paper.title }}</strong>
    {% if paper.paperurl %}
      — <a href="{{ paper.paperurl }}" target="_blank">[link]</a>
    {% endif %}
    {% if paper.authors %}
      <br><span style="font-size: 0.95em; font-weight: normal;">{{ paper.authors }}</span>
    {% endif %}
  </summary>

  <div style="margin: 0.75em 0 0 0;">

  {% if paper.content %}
    <p style="margin: 0;">
      {{ paper.content }}
    </p>
  {% endif %}

  {% if paper.gif %}
    <img src="{{ paper.gif }}" alt="{{ paper.title }} findings" style="max-width: 100%; margin-top: 1em; border-radius: 4px;">
  {% endif %}

  </div>

</details>

{% endfor %}

</div>
</section>


<section class="section-white">
<div class="section-inner">

<h2>Publications</h2>

{% assign pubs = site.publications | where_exp: "p", "p.title" | sort: "date" | reverse %}

{% for paper in pubs %}

<details style="margin-bottom: 1.5rem;">

  <summary style="cursor: pointer;">
    <strong>{{ paper.title }}</strong>
    {% if paper.paperurl %}
      — <a href="{{ paper.paperurl }}" target="_blank">[link]</a>
    {% endif %}
    {% if paper.venue %}
      <br><em style="font-size: 0.95em; font-weight: normal;">{{ paper.venue }}</em>
    {% endif %}
    {% if paper.authors %}
      <br><span style="font-size: 0.95em; font-weight: normal;">{{ paper.authors }}</span>
    {% endif %}
  </summary>

  <div style="margin: 0.75em 0 0 0;">

  {% if paper.content %}
    <p style="margin: 0;">
      {{ paper.content }}
    </p>
  {% endif %}



  </div>

</details>

{% endfor %}


<h2>Education</h2>

<ul>
<li>PhD, University of California, Davis (Expected 2027) </li>
<li>MSc, University of Guelph, 2021 </li>
<li>BSc, University of Waterloo, 2019 </li>
</ul>

</div>
</section>


    
