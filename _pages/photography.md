---
layout: page
permalink: /photography/
title: photography
description: A collection of my photographs with stories behind each shot.
nav: true
nav_order: 6
---

<div class="row mt-3">
  <div class="col-sm-6 mb-4">
    {% assign img_path = 'assets/img/bean.jpg' %}
    <img src="{{ img_path | relative_url }}" class="img-fluid rounded" alt="Cloud Gate at the Millennium Park">
    <h5 class="mt-3">Cloud Gate at the Millennium Park</h5>
    <p>I lived in the city of Chicago for about two years and Millennium Park was always a go-to spot. This picture I took captures more than just Cloud Gate - it reflects Chicago's incredible demographic journey from a small trading post to America's third-largest city through waves of migration: European immigrants in the late 1800s, African Americans during the Great Migration (1916-1970), and more recent Latino and Asian populations. Looking at the skyscrapers reflected in the sculpture, I can see how the city handled all that population growth through vertical density, built on Chicago's role as a transportation hub that drew people from everywhere. Unlike other Rust Belt cities that emptied out during deindustrialization, Chicago managed to keep its people by reinventing itself - trading factory jobs for service work and creating beautiful spaces like this park. </p>
    <small class="text-muted"><i class="fas fa-map-marker-alt"></i> Chicago, IL • Sep 2025</small>
  </div>
  
  <div class="col-sm-6 mb-4">
    {% assign img_path2 = 'assets/img/rocky.jpg' %}
    <img src="{{ img_path2 | relative_url }}" class="img-fluid rounded" alt="Alpine Lake in the Rocky Mountains">
    <h5 class="mt-3">Alpine Settlement Patterns</h5>
    <p>Looking at this alpine lake, I can see how it supported different ways of living over thousands of years. Paleo-Indians lived here year-round, while later groups like the So-so-goi (Northwestern Shoshone) and Ute developed seasonal patterns - arriving for autumn fishing then moving to winter hunting grounds. The rocky shorelines and clear waters created temporary population spikes during peak fishing seasons that these harsh mountains couldn't support year-round.  This landscape shows the shift from permanent settlement to seasonal systems where the same location supported different population patterns depending on the time of year and the group living here.</p>
    <small class="text-muted"><i class="fas fa-map-marker-alt"></i> Rocky Mountains, CO • Aug 2025</small>
  </div>
</div>

<div class="row">
  <div class="col-sm-6 mb-4">
    {% assign img_path3 = 'assets/img/tokyo.jpg' %}
    <img src="{{ img_path3 | relative_url }}" class="img-fluid rounded" alt="Shibuya Crossing in Tokyo">
    <h5 class="mt-3">Metropolitan Flow Dynamics</h5>
    <p>This photo was taken when I was traveling in Tokyo, Japan, and you feel something different when you're surrounded by a massive crowd all trying to cross the road together. Shinjuku station handles 3.34 million people daily, making it the world's busiest train station, and this crosswalk captures just a fraction of that flow. Being part of this movement with Greater Tokyo's 37 million residents shows how extreme population concentration creates entirely new patterns of human mobility. </p>
    <small class="text-muted"><i class="fas fa-map-marker-alt"></i> Tokyo, Japan • Mar 2025</small>
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
