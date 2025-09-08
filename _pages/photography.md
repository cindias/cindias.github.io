---
layout: page
permalink: /photography/
title: photography
description: A collection of my photographs with demograhpic perspectives behind each shot.
nav: true
nav_order: 5
---

<div class="row mt-3">
  <div class="col-sm-6 mb-4">
    {% assign img_path = 'assets/img/bean.jpg' %}
    <img src="{{ img_path | relative_url }}" class="img-fluid rounded" alt="Cloud Gate at the Millennium Park">
    <h5 class="mt-3">Cloud Gate at the Millennium Park</h5>
    <p>Cloud Gate reflects Chicago's transformation from a small trading post to America's third-largest city through successive waves of migration: European immigrants in the late 1800s, African Americans during the Great Migration (1916-1970), and more recent Latino and Asian populations (Grossman, 1989; Pacyga, 2009). The towering skyscrapers mirrored in the sculpture demonstrate urban density as a response to demographic growth, while Chicago's transportation infrastructure historically made it a magnet for both internal and international migrants (Abu-Lughod, 1999). Unlike other Rust Belt cities that lost population during deindustrialization, Chicago maintained demographic stability by diversifying its economy and investing in cultural amenities like Millennium Park (Beauregard, 2006). The juxtaposition of the reflective sculpture with corporate towers symbolizes the city's transition from a blue-collar industrial workforce to today's service-based economy. This scene captures Chicago's ongoing role as the demographic hub of the Midwest, where population flows continue to converge and reshape the urban landscape.</p>
    <small class="text-muted"><i class="fas fa-map-marker-alt"></i> Chicago, IL • Sep 2025</small>
  </div>
  
  <div class="col-sm-6 mb-4">
    {% assign img_path2 = 'assets/img/rocky.jpg' %}
    <img src="{{ img_path2 | relative_url }}" class="img-fluid rounded" alt="Alpine Lake in the Rocky Mountains">
    <h5 class="mt-3">Alpine Lake</h5>
    <p>This alpine lake represents an early model of permanent high-elevation settlement where Paleo-Indian populations maintained year-round residence, demonstrating how small hunter-gatherer groups could sustain themselves in extreme environments. Later demographic patterns shifted dramatically - the So-so-goi (Northwestern Shoshone) developed seasonal population flows that brought concentrated groups to alpine lakes like this during autumn fishing periods before dispersing to winter hunting grounds. What I find fascinating is how the physical geography of this lake - its rocky shorelines and clear waters - supported temporary demographic spikes when indigenous groups arrived with "spears, gill nets, and basket traps" during peak resource seasons. Ute population dynamics followed similar patterns, with family units aggregating at "seasonally-specific camps" around such lakes, creating temporary demographic densities that the harsh alpine environment couldn't support year-round. This landscape demonstrates the evolution from static demographic models (permanent Paleo-Indian settlement) to dynamic seasonal population systems where the same geographic space supported radically different population densities and settlement patterns depending on the time of year and the cultural group occupying it.</p>
    <small class="text-muted"><i class="fas fa-map-marker-alt"></i> Rocky Mountains, CO • Aug 2025</small>
  </div>
</div>

<div class="row">
  <div class="col-sm-6 mb-4">
    {% assign img_path3 = 'assets/img/tokyo.jpg' %}
    <img src="{{ img_path3 | relative_url }}" class="img-fluid rounded" alt="Shibuya Crossing in Tokyo">
    <h5 class="mt-3">Metropolitan Population Flow</h5>
    <p>Shinjuku station handles 3.34 million people daily, making it the world's busiest train station, and this crosswalk captures a fraction of that massive flow. As part of the Greater Tokyo Area's 37 million residents, these individuals demonstrate how extreme population concentration creates new patterns of human movement. This intersection shows infrastructure engineered to accommodate population densities that challenge conventional city planning models.</p>
    <small class="text-muted"><i class="fas fa-map-marker-alt"></i> Tokyo, Japan • Jul 2025</small>
    <small class="text-muted d-block"><i class="fas fa-camera"></i> iPhone 13</small>
  </div>
</div>

<style>
/* Additional styling for photography page */
.photography-item {
  margin-bottom: 2rem;
}

.photography-item img {
  transition: transform 0.3s ease;
}

.photography-item:hover img {
  transform: scale(1.02);
}

.photo-description {
  text-align: justify;
  line-height: 1.6;
}

.photo-meta {
  color: var(--global-text-color-light);
}

@media (max-width: 768px) {
  .photography-item {
    margin-bottom: 1.5rem;
  }
}
</style>
