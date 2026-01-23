---
layout: archive
title: "Bonus"
permalink: /bonus/
author_profile: true
---

Photo Gallery
------

Photos I've deemed important enough to share online. Guest appearances made by my wonderful cat, Mara, a recent meal I really loved, and a little thing that's made me happy. And yes, this does get updated periodically.

<script>
function openLightbox(src) {
  const lightbox = document.createElement('div');
  lightbox.style.cssText = 'position:fixed;top:0;left:0;width:100%;height:100%;background:rgba(0,0,0,0.9);display:flex;align-items:center;justify-content:center;z-index:9999;cursor:pointer;';
  const img = document.createElement('img');
  img.src = src;
  img.style.cssText = 'max-width:90%;max-height:90%;border-radius:8px;';
  lightbox.appendChild(img);
  lightbox.onclick = () => document.body.removeChild(lightbox);
  document.body.appendChild(lightbox);
}
</script>

<div class="photo-gallery">
  <img src="/images/cat.jpeg" alt="The lovely Maracuya" onclick="openLightbox(this.src)">
  <img src="/images/meal.jpeg" alt="Suraya pastry basket, if you know you know" onclick="openLightbox(this.src)">
  <img src="/images/thing.jpeg" alt="A sneaky picture of my family in Ecuador" onclick="openLightbox(this.src)">
</div>
