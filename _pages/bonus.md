---
layout: archive
title: "Bonus"
permalink: /bonus/
author_profile: true
---

## Photo Gallery

Some photos I've deemed important enough to share online.
Guest appearances made by my wonderful cat, Mara, my family's 2 dogs, Gus and Spartacus,
a recent meal I really loved (this changes, naturally), and a little thing that's made me happy.

<style>
.photo-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 15px;
  margin: 20px 0;
}

.photo-gallery img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.photo-gallery img:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}
</style>

<div class="photo-gallery">
  <img src="/images/cat.jpg" alt="Description 1">
  <img src="/images/dog.jpg" alt="Description 2">
  <img src="/images/meal.jpg" alt="Description 3">
  <img src="/images/object.jpg" alt="Description 4">
</div>
