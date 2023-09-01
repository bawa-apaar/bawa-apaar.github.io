---
title: "My Photography Collection"
permalink: /services/
author_profile: true
---

Not a professional photographer but I try to be one. Enjoy some of my clicks 📷

## Landscape Photography

<div class="image-grid">
  <div class="image-item">
    <img src="/images/photography/horseshoe_bend.jpeg" alt="Image 1">
    <span class="tooltip">Horseshoe Bend, Arizona, US</span>
  </div>
  <div class="image-item">
    <img src="/images/photography/south_beach.jpeg" alt="Image 2">
    <span class="tooltip">South Beach, Florida, US</span>
  </div>
  <div class="image-item">
    <img src="/images/photography/howrah.jpg" alt="Image 3">
    <span class="tooltip">Howrah Bridge, Kolkata, India</span>
  </div>
  <div class="image-item">
    <img src="/images/photography/living_root.jpeg" alt="Image 4">
    <span class="tooltip">Living root bridge, Meghalya, India</span>
  </div>
  <!-- Add more image items -->
</div>

<style>
  .image-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
  }

  .image-item {
    position: relative;
    padding: 10px;
    text-align: center;
  }

  .image-item img {
    max-width: 100%;
    height: auto;
  }

  .tooltip {
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    display: none;
    background-color: rgba(0, 0, 0, 0.8);
    color: #fff;
    padding: 4px 8px;
    border-radius: 4px;
    font-size: 14px;
    z-index: 1;
  }

  .image-item:hover .tooltip {
    display: block;
  }
</style>