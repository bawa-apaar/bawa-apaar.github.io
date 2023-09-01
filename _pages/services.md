---
title: "My Photography Collection"
permalink: /services/
author_profile: true
---

Not a professional photographer but I try to be one. Enjoy some of my clicks 📷

<div class="image-grid">
  <div class="image-item">
    <img class="landscape" src="/images/photography/pic1.jpeg" alt="Landscape 1">
    <span class="tooltip">Location 1</span>
  </div>
  <div class="image-item">
    <img class="landscape" src="/images/photography/pic2.jpeg" alt="Landscape 2">
    <span class="tooltip">Location 3</span>
  </div>
  <div class="image-item">
    <img class="portrait" src="/images/photography/pic3.jpeg" alt="Portrait 1">
    <span class="tooltip">Location 2</span>
  </div>
  <div class="image-item">
    <img class="portrait" src="/images/photography/pic4.jpeg" alt="Portrait 2">
    <span class="tooltip">Location 4</span>
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
    text-align: center;
    border: none;
    overflow: hidden; /* Prevent images from overflowing grid items */
    max-height: 250px; /* Set a fixed height for all grid items */
  }

  .landscape,
  .portrait {
    max-width: 100%;
    max-height: 100%;
    width: auto;
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
