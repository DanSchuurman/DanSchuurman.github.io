---
title: "Yesterday Matters: Accounting for Feedback in Acreage Responses to Climate Change"
collection: workingpapers
permalink: /workingpapers/jmp
excerpt: 'Job market paper'
date: 2026-09-01
authors: 'Job market paper'
venue: 
paperurl: 
---

<style>
/* Layout Containers */
.top-section {
  display: flex;
  gap: 40px;
  align-items: flex-start;
  margin-bottom: 2rem;
}

/* Abstract Column (~60%) */
.abstract-col {
  flex: 0 0 55%;
  width: 55%;
  line-height: 1.6;
}

.abstract-col p {
  margin-top: 0;
}

/* Vertically Stacked Figures Column (~40%) */
.figures-col {
  flex: 0 0 30%;
  width: 30%;
  display: flex;
  flex-direction: column;
  gap: 16px;
}

.figures-col img {
  width: 100%;
  height: auto;
  border-radius: 6px;
  border: 1px solid #e2e8f0;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.08);
}

/* Bottom Grid for GIFs (33% each) */
.gif-grid {
  display: flex;
  gap: 16px;
  width: 100%;
  margin-top: 1.5rem;
}

.gif-card {
  flex: 1;
  width: 33.333%;
}

.gif-card img {
  width: 100%;
  height: auto;
  border-radius: 6px;
  border: 1px solid #e2e8f0;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.08);
  display: block;
}

/* Responsive breakdown for mobile viewports */
@media (max-width: 768px) {
  .top-section {
    flex-direction: column;
  }
  .abstract-col,
  .figures-col {
    width: 100%;
    flex: 0 0 100%;
  }
  .gif-grid {
    flex-direction: column;
  }
  .gif-card {
    width: 100%;
  }
}
</style>

<!-- Top Section: Abstract (60%) + 2 Vertically Stacked Figures (40%) -->
<div class="top-section">
  <div class="abstract-col">
    <p> 
      Projections of the potential impacts of climate change on agricultural systems are crucial for developing climate policy. Yet projections of crop reallocation often rely on static models that assume immediate adjustment. When outcomes are persistent, adjustments in response to climate change may be gradual rather than immediate. Using a dynamic panel model of county-level corn and soybean acreage in the United States, I find considerable persistence in crop acreage allocations. This persistence implies partial adjustment, where acreage responds to climate change incrementally. In contrast to static projections, dynamic projections of future acreage allocations require accounting for the cumulative effect of acreage adjustments along the full climate transition path. I show that compared to dynamic projections, static models overestimate the magnitude of 2050 acreage reductions by 21.6--28.0\% across CMIP6 scenarios relative to a no-climate-change baseline.
    </p>
  </div>

  <div class="figures-col">
    <img src="/images/treatment.png" alt="GFDL-ESM4 Treatment">
    <img src="/images/pathway.png" alt="GFDL-ESM4 Full Static">
  </div>
</div>

<!-- Bottom Section: 3 GIFs side-by-side (33% each) -->
<div class="gif-grid">
  <div class="gif-card">
    <img src="/images/ssp585_static_map_2023_2050.gif" alt="SSP5-8.5 Static projections">
  </div>
  <div class="gif-card">
    <img src="/images/ssp585_dynamic_map_2023_2050.gif" alt="SSP5-8.5 Dynamic projections">
  </div>
  <div class="gif-card">
    <img src="/images/ssp585_diff_map_2023_2050.gif" alt="Difference of Static and Dynamic projections">
  </div>
</div>
