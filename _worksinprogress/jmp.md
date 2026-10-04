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
  gap: 24px;
  align-items: flex-start;
  margin-bottom: 2rem;
}

/* Abstract Column (~60%) */
.abstract-col {
  flex: 0 0 58%;
  width: 58%;
  line-height: 1.6;
}

.abstract-col p {
  margin-top: 0;
}

/* Vertically Stacked Figures Column (~40%) */
.figures-col {
  flex: 0 0 38%;
  width: 38%;
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
      Projections of the potential impacts of climate change on agricultural systems are crucial for developing climate policy. In a dynamic setting where outcomes are persistent, adjustments in response to climate change may be gradual rather than immediate. Using a dynamic panel model that accounts for feedback from lagged allocations, I identify considerable persistence in crop acreage allocations. This persistence has a first-order effect on how climate-change projections should be constructed. Future acreage allocations must account for the cumulative effect of climate along the entire transition path. Existing research often conducts projections using comparative-statics based on models that omit information on past acreage decisions. By disregarding the adjustment path, acreage projections under CMIP6 scenarios with static models overestimate acreage responses by 2050 by an average of 19% and 22% under moderate and high emissions scenarios.
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
