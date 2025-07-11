---
layout: default
title: Welcome
stylesheet: assets/css/style.scss
---

<style>
.glow-on-hover {
  transition: box-shadow 0.3s ease;
}

.glow-on-hover:hover {
  box-shadow: 0 0 12px 3px rgba(155, 89, 182, 0.6); /* soft purple glow */
  transform: scale(1.05); /* 5% bigger */
}
</style>


<div style="display: flex; align-items: center; gap: 2rem; flex-wrap: wrap;">

  <div style="flex: 2; min-width: 250px;">
    <h2>Welcome to my site!</h2>
    <p>Hi, I’m William — welcome to my corner of the internet.</p>
    <p>This site is built with GitHub Pages using the Minima theme.</p>
  </div>

  <div style="flex: 1; min-width: 250px;">
    <figure style="display: flex; flex-direction: column; align-items: center;">
      <img 
        src="/assets/img/profile_pic.png" 
        alt="Portrait" 
        class="glow-on-hover"
        style="width: 200px; height: 200px; object-fit: cover; border-radius: 50%; border: 3px solid #9b59b6;">
      <figcaption style="margin-top: 0.5rem; color: #555; font-size: 0.9rem;">
        This is me, looking slightly over to the left.
      </figcaption>
    </figure>
  </div>
</div>
