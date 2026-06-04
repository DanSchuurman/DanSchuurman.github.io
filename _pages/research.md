---
permalink: /research/
title: "Research"
excerpt: 
author_profile: true
---

{% include base_path %}

<section class="section-white">
<div class="section-inner">

<h2>Publications</h2>

{% assign pubs = site.publications | sort: "date" | reverse %}

{% for pub in pubs %}
  <div style="margin-bottom: 2rem;">
    <h3 style="margin: 0 0 0.25rem 0;">
      <a href="{{ pub.url | relative_url }}">{{ pub.title }}</a>
    </h3>

    {% if pub.venue or pub.date %}
      <p style="margin: 0 0 0.5rem 0; font-size: 0.95em; color: #555;">
        {% if pub.venue %}{{ pub.venue }}{% endif %}
        {% if pub.venue and pub.date %}, {% endif %}
        {% if pub.date %}{{ pub.date | date: "%Y" }}{% endif %}
      </p>
    {% endif %}

    {% if pub.excerpt %}
      <p style="margin: 0 0 0.5rem 0;">{{ pub.excerpt }}</p>
    {% elsif pub.content %}
      <p style="margin: 0 0 0.5rem 0;">{{ pub.content | strip_html | truncate: 250 }}</p>
    {% endif %}

  </div>
{% endfor %}

</div>
</section>

