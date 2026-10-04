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
/* Slider Container */
.slider-container {
  display: flex;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  scroll-behavior: smooth;
  width: 100%;
  max-width: 450px; /* Reduced from 900px */
  margin: 2rem auto;
  position: relative;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  scrollbar-width: none; /* Firefox */
  -ms-overflow-style: none; /* IE/Edge */
}

.slider-container::-webkit-scrollbar {
  display: none; /* Chrome/Safari */
}

/* Slide Item */
.slide {
  flex: 0 0 100%;
  width: 100%;
  scroll-snap-align: start;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #f8f9fa;
}

/* Images */
.slide img {
  width: 100%;
  height: auto;
  max-height: 300px; /* Reduced from 600px */
  object-fit: contain;
  display: block;
}

/* Arrow Navigation */
.arrow {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background-color: rgba(0, 0, 0, 0.5);
  color: #ffffff !important;
  padding: 8px 12px; /* Scaled down arrow padding */
  text-decoration: none !important;
  font-size: 16px; /* Scaled down arrow size */
  border-radius: 50%;
  user-select: none;
  transition: background-color 0.2s ease, transform 0.2s ease;
  z-index: 10;
  line-height: 1;
}

.arrow:hover {
  background-color: rgba(0, 0, 0, 0.85);
  transform: translateY(-50%) scale(1.1);
}

.arrow.prev {
  left: 10px;
}

.arrow.next {
  right: 10px;
}
</style>

<div class="slider-container">
  <!-- Slide 1 -->
  <div class="slide" id="slide-1">
    <img src="/images/treatment.png" alt="GFDL-ESM4 Treatment">
    <a href="#slide-5" class="arrow prev">&#10094;</a>
    <a href="#slide-2" class="arrow next">&#10095;</a>
  </div>

  <!-- Slide 2 -->
  <div class="slide" id="slide-2">
    <img src="/images/pathway.png" alt="GFDL-ESM4 Full Static">
    <a href="#slide-1" class="arrow prev">&#10094;</a>
    <a href="#slide-3" class="arrow next">&#10095;</a>
  </div>

  <!-- Slide 3 -->
  <div class="slide" id="slide-3">
    <img src="/images/ssp585_static_map_2023_2050.gif" alt="SSP5-8.5 Static projections">
    <a href="#slide-2" class="arrow prev">&#10094;</a>
    <a href="#slide-4" class="arrow next">&#10095;</a>
  </div>

  <!-- Slide 4 -->
  <div class="slide" id="slide-4">
    <img src="/images/ssp585_dynamic_map_2023_2050.gif" alt="SSP5-8.5 Dynamic projections">
    <a href="#slide-3" class="arrow prev">&#10094;</a>
    <a href="#slide-5" class="arrow next">&#10095;</a>
  </div>

  <!-- Slide 5 -->
  <div class="slide" id="slide-5">
    <img src="/images/ssp585_diff_map_2023_2050.gif" alt="Difference of Static and Dynamic projections">
    <a href="#slide-4" class="arrow prev">&#10094;</a>
    <a href="#slide-1" class="arrow next">&#10095;</a>
  </div>
</div>
