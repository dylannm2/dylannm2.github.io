---
layout: profiles 
permalink: /people/
title: About Me
description: Me, me, and me! 
nav: true
nav_order: 7

profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: right
    image: PILLOWWEB.jpg
    content: about_einstein.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p>
---
<style>
  .collage img {
    width: 100%;
    aspect-ratio: 1 / 1;
    object-fit: cover;
  }
</style>

<div class="row collage mt-4">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/PHOTO1.jpg" class="img-fluid rounded z-depth-1" alt="Climbing" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/PHOTO2.jpg" class="img-fluid rounded z-depth-1" alt="Peru" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/PHOTO3.jpg" class="img-fluid rounded z-depth-1" alt="Concert" %}
  </div>
</div>
<div class="caption">
  Your caption here.
</div>
