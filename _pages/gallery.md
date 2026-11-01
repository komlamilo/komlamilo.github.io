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
</div>

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 15px;
}

.gallery-grid img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 6px;
}

@media (max-width: 768px) {
  .gallery-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 480px) {
  .gallery-grid {
    grid-template-columns: 1fr;
  }
}
</style>
