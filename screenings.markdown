---
title: SCREENINGS
date: 2026-09-10 14:32:00 -04:00
---

new page for screening

---
layout: page
title: SCREENING ROOM
permalink: /screening-room/
---

<p style="text-align: center; font-style: italic; margin-bottom: 50px; color: #555; font-size: 1.1em;">
  Industry Professionals: For private screeners, development slates, or pitch materials, please <a href="/contact" style="color: #222; text-decoration: underline;">contact our development team</a>.
</p>

<!-- The Gumroad Overlay Script: This makes the videos play directly on your site -->
<script src="https://gumroad.com/js/gumroad.js"></script>

<style>
  .screening-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 30px;
    margin-bottom: 40px;
  }
  
  .screening-item {
    display: flex;
    flex-direction: column;
    text-align: center;
    background: #fbfbfb;
    border: 1px solid #eaeaea;
    border-radius: 4px;
    overflow: hidden;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    padding-bottom: 20px;
  }
  
  .screening-item img {
    width: 100%;
    aspect-ratio: 16 / 9;
    object-fit: cover;
    margin-bottom: 15px;
  }
  
  .screening-title {
    font-weight: 600;
    font-size: 1.05em;
    margin-bottom: 15px;
    padding: 0 10px;
    color: #222;
  }
  
  /* Styling the Gumroad links to look like studio buttons */
  .gumroad-button {
    display: inline-block;
    background-color: #111; 
    color: #fff !important;
    text-decoration: none;
    padding: 10px 24px;
    border-radius: 3px;
    font-size: 0.9em;
    font-weight: bold;
    letter-spacing: 1px;
    margin: auto auto 0 auto; 
    transition: background-color 0.3s ease;
  }
  
  .gumroad-button:hover {
    background-color: #555;
  }

  /* Responsive Stacking for Mobile */
  @media (max-width: 768px) {
    .screening-grid {
      grid-template-columns: repeat(2, 1fr);
    }
  }
  @media (max-width: 480px) {
    .screening-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="screening-grid">
  <!-- 1. True Drama -->
  <div class="screening-item">
    <img src="/uploads/6_True_Drama_FeatureFilm.jpg" alt="True Drama">
    <div class="screening-title">True Drama (Feature Film)</div>
    <a class="gumroad-button" href="https://macmillanfilms.gumroad.com/l/ihdhf">VIEW ON DEMAND</a>
  </div>

  <!-- 2. Cato -->
  <div class="screening-item">
    <img src="/uploads/7_CATObyAddisonMarionetteJUBAandMARCIA.jpg" alt="Cato by Joseph Addison">
    <div class="screening-title">Cato by Joseph Addison</div>
    <a class="gumroad-button" href="https://macmillanfilms.gumroad.com/l/ocdnb">VIEW ON DEMAND</a>
  </div>

  <!-- 3. Lysistrata Feature Film -->
  <div class="screening-item">
    <img src="/uploads/3_LYSISTRATA_MOVIE_OnStageLiveTheater2026.jpg" alt="Lysistrata Feature Film">
    <div class="screening-title">Lysistrata (Feature Film)</div>
    <a class="gumroad-button" href="https://macmillanfilms.gumroad.com/l/kHZXp">VIEW ON DEMAND</a>
  </div>
  
  <!-- 4. Prometheus Bound -->
  <div class="screening-item">
    <img src="/uploads/5_PROMETHIUS_BOUND_OnStageLiveTheater2026.jpg" alt="Prometheus Bound">
    <div class="screening-title">Prometheus Bound</div>
    <a class="gumroad-button" href="https://macmillanfilms.gumroad.com/l/prometheus-bound-staging">VIEW ON DEMAND</a>
  </div>
  
  <!-- 5. The Bacchae -->
  <div class="screening-item">
    <img src="/uploads/2_BacchaeStagingMiaasDionysos%20%E2%80%AFPM.jpg" alt="The Bacchae">
    <div class="screening-title">The Bacchae</div>
    <a class="gumroad-button" href="https://macmillanfilms.gumroad.com/l/bacchae-staging">VIEW ON DEMAND</a>
  </div>

  <!-- 6. Oedipus Rex -->
  <div class="screening-item">
    <img src="/uploads/4_OEDIPUS_REX_OnStageLiveTheater20262.jpg" alt="Oedipus Rex">
    <div class="screening-title">Oedipus Rex</div>
    <a class="gumroad-button" href="https://macmillanfilms.gumroad.com/l/fwwaz">VIEW ON DEMAND</a>
  </div>
</div>