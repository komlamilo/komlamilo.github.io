---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

Welcome to my photo gallery.

<div class="gallery-grid">
  <figure>
    <img src="/images/gallery/photo1.jpg"
         alt="Gallery photograph 1">
  </figure>

  <figure>
    <img src="/images/gallery/photo2.jpg"
         alt="Gallery photograph 2">
  </figure>
</div>

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.gallery-grid img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 6px;
}

.gallery-grid figure {
  margin: 0;
}
</style>
