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

Projections of the potential impacts of climate change on agricultural systems are crucial for developing climate policy. In a dynamic setting where outcomes are persistent, adjustments in response to climate change may be gradual rather than immediate. Using a dynamic panel model that accounts for feedback from lagged allocations, I identify considerable persistence in crop acreage allocations. This persistence has a first-order effect on how climate-change projections should be constructed. Future acreage allocations must account for the cumulative effect of climate along the entire transition path. Existing research often conducts projections using comparative-statics based on models that omit information on past acreage decisions. By disregarding the adjustment path, acreage projections under CMIP6 scenarios with static models overestimate acreage responses by 2050 by an average of 19% and 22% under moderate and high emissions scenarios.

<style>
/* Outer viewport holding visible slides */
.slider-container {
  overflow: hidden;
  width: 100%;
  max-width: 900px; /* Overall max width */
  margin: 2rem auto;
  position: relative;
  background-color: #f8f9fa;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  padding: 15px 0;
}

/* Continuous moving track */
.slider-track {
  display: flex;
  width: max-content;
  animation: marquee 25s linear infinite; /* Adjust speed here (higher = slower) */
}

/* Pause auto-scroll when user hovers over the images */
.slider-container:hover .slider-track {
  animation-play-state: paused;
}

/* Individual slide dimensions (~3 visible at once) */
.slide {
  width: 280px; /* Adjust image card width */
  margin-right: 15px; /* Spacing between slides */
  flex-shrink: 0;
}

.slide img {
  width: 100%;
  height: 200px; /* Adjust card height */
  object-fit: contain;
  display: block;
}

/* Seamless 50% keyframe loop */
@keyframes marquee {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-50%);
  }
}
</style>

<div class="slider-container">
  <div class="slider-track">
    <!-- Original 5 Slides -->
    <div class="slide"><img src="/images/treatment.png" alt="GFDL-ESM4 Treatment"></div>
    <div class="slide"><img src="/images/pathway.png" alt="GFDL-ESM4 Full Static"></div>
    <div class="slide"><img src="/images/ssp585_static_map_2023_2050.gif" alt="SSP5-8.5 Static projections"></div>
    <div class="slide"><img src="/images/ssp585_dynamic_map_2023_2050.gif" alt="SSP5-8.5 Dynamic projections"></div>
    <div class="slide"><img src="/images/ssp585_diff_map_2023_2050.gif" alt="Difference projections"></div>

    <!-- Duplicated 5 Slides (Required for seamless infinite loop) -->
    <div class="slide"><img src="/images/treatment.png" alt="GFDL-ESM4 Treatment"></div>
    <div class="slide"><img src="/images/pathway.png" alt="GFDL-ESM4 Full Static"></div>
    <div class="slide"><img src="/images/ssp585_static_map_2023_2050.gif" alt="SSP5-8.5 Static projections"></div>
    <div class="slide"><img src="/images/ssp585_dynamic_map_2023_2050.gif" alt="SSP5-8.5 Dynamic projections"></div>
    <div class="slide"><img src="/images/ssp585_diff_map_2023_2050.gif" alt="Difference projections"></div>
  </div>
</div>
