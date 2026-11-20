---
permalink: /
title: ""
excerpt: "About me"
author_profile: false
redirect_from:
- /about/
- /about.html
---

<!-- Intro Section Wrapper (matches your Research section alignment) -->
<div style="width: 100vw; position: relative; left: calc(-1 * (50vw - 50%)); border-top: 1px solid #e8e8e8; border-bottom: 1px solid #e8e8e8; padding: 2rem 0; box-sizing: border-box;">
  <div style="max-width: 1100px; margin: 0 auto; padding: 0 2rem; display: flex; flex-wrap: wrap; align-items: flex-start; gap: 2.5rem;">
    <img src="/images/profile_2.jpeg" alt="Daniel Schuurman" style="width: 220px; height: 260px; flex-shrink: 0; object-fit: cover; object-position: center top; border-radius: 8px; box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08); margin: 0;">
    <div style="flex: 1; min-width: 280px;">
      <p style="margin-top: 0;">I am PhD candidate in the Agricultural and Resource Economics Department at UC Davis. I am an economist working in agricultural, environmental, and applied econometrics. </p>
    <p> My job market paper focuses on the estimation and projection of land use responses to climate change. My other research studies methods for empirically measuring adaptation, financial exposure to climate risk, and health externalities associated with pesticide use.</p>
      <p style="margin-bottom: 0;"><strong>I am on the 2026-27 job market.</strong> You can find my <a href="https://scholar.google.com/citations?user=lvBFBcEAAAAJ&hl=en&authuser=1&oi=ao" target="_blank" rel="noopener noreferrer">Google Scholar page here </a>.  </p>
    </div>
  </div>
</div>

<!-- Research Section wrapper (aligned with main content, no weird left shift) -->
<div style="width: 100vw; position: relative; left: calc(-1 * (50vw - 50%)); background-color: #ffffff; z-index: 10; padding: 2rem 0; box-sizing: border-box;">
  
  <!-- Inner container to keep your text/images neatly aligned -->
  <div style="max-width: 1100px; margin: 0 auto; padding: 0 2rem;">
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

    <br>
    <h2>Education</h2>

    <ul>
    <li>PhD, University of California, Davis (Expected 2027) </li>
    <li>MSc, University of Guelph, 2021 </li>
    <li>BSc, University of Waterloo, 2019 </li>
    </ul>

    </div>
    </section>

  </div> 
</div>
