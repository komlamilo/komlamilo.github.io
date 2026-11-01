---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

<div class="gallery-grid">
  <img src="/images/gallery/Airman.jpg" alt="Airman">
  <img src="/images/gallery/Airman%202.jpg" alt="Airman 2">
  <img src="/images/gallery/Conference%201.jpg" alt="Conference 1">
  <img src="/images/gallery/Conference%202.jpg" alt="Conference 2">
  <img src="/images/gallery/Music.jpg" alt="Music">
  <img src="/images/gallery/OU%20Grad.jpg" alt="OU Graduation">
  <img src="/images/gallery/UG%20Grad.JPG" alt="UG Graduation">
  <img src="/images/gallery/SIU%20Grad.jpg" alt="SIU Graduation">
  <img src="/images/gallery/NYU%20Grad.JPG" alt="NYU Graduation">
  <img src="/images/gallery/Wright.jpg" alt="Wright">
  <img src="/images/gallery/Space.jpg" alt="Space">

</div>

<style>
.gallery-grid {
  columns: 3;
  column-gap: 16px;
}

.gallery-grid img {
  display: block;
  width: 100%;
  height: auto;
  margin-bottom: 16px;
  border-radius: 6px;
  break-inside: avoid;
}

@media (max-width: 768px) {
  .gallery-grid {
    columns: 2;
  }
}

@media (max-width: 480px) {
  .gallery-grid {
    columns: 1;
  }
}
</style>
