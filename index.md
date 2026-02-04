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
    <h2>Welcome to my website!</h2>
    <ul>
      <li>Current graduate from Cal Poly Pomona with a B.S. in General Physics (with an Astrophysics Emphasis) and in Applied Mathematics and Statistics</li>
      <li><a href="https://www.linkedin.com/in/william-salazar-50b673264" target="_blank">LinkedIn</a>.</li>
      <li><a href="https://github.com/willsalazar5221" target="_blank">GitHub</a>.</li>
    </ul>
  </div>

  <!-- Image + info block -->
  <div style="flex: 1; min-width: 250px; display: flex; flex-direction: column; align-items: center;">
    <!-- Image -->
    <img 
      src="/assets/img/profile_pic.png" 
      alt="Portrait" 
      class="glow-on-hover"
      style="width: 200px; height: 200px; object-fit: cover; border-radius: 50%; border: 3px solid #9b59b6;"
    >
    <!-- Caption (still a caption) -->
    <div style="margin-top: 0.5rem; color: #555; font-size: 0.9rem; text-align: center;">
      Fig 1. Speech given at the 2024 CSU-LSAMP PROUD Scholars Award ceremony
    </div>
    <!-- Info block under photo (NOT a caption) -->
    <div style="margin-top: 0.75rem; text-align: center;">
      <div style="font-weight: bold; font-size: 1.15rem;">
        William Salazar
      </div>
      <div style="font-size: 0.9rem; color: #666;">
        he/him
      </div>
      <div style="font-size: 0.95rem; margin-bottom: 0.6rem;">
        Undergraduate Researcher
      </div>
      <ul style="padding-left: 1.2rem; text-align: left;">
        <li>Computational astrophysics</li>
        <li>Scientific computing & modeling</li>
        <li>Data analysis & visualization</li>
      </ul>
    </div>
  </div>

  
</div>
