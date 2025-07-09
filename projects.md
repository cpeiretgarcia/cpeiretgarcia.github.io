---
layout: page
title: Projects
permalink: /projects/
---

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 40px;
  margin-top: 2rem;
}
.project-item {
  display: flex;
  flex-direction: column;
  gap: 0.75rem;
}
.project-item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 8px;
}
.project-title {
  font-size: 1.1rem;
  font-weight: bold;
  margin: 0;
}
.project-title a {
  color: #222;
  text-decoration: none;
}
.project-title a:hover {
  text-decoration: underline;
}
.project-description {
  font-size: 0.95rem;
  color: #444;
  margin: 0;
}
.project-author {
  font-size: 0.85rem;
  color: #666;
}
</style>

<div class="project-grid">

<div class="project-item">
  <img src="/assets/img/projects/sae_workshop.jpg" alt="SAE Workshop">
  <p class="project-title"><a href="/projects/sae_workshop/">SAE Workshop</a></p>
  <p class="project-description">
    A hands-on workshop introducing Small Area Estimation methods to a general audience with examples in R.
  </p>
  <p class="project-author">
    By Clara Peiret-García. Materials available on <a href="https://github.com/cpeiretgarcia/sae_workshop" target="_blank">GitHub</a>.
  </p>
</div>

<!-- Add more project blocks here -->

</div>
