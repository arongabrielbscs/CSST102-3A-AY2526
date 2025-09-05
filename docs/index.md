---
layout: default
---

# Information

<div style="display: flex; align-items: center; gap: 20px;">
  <img src="{{'/assets/images/pfp.jpg?v=' | append: site.github.build_revision | relative_url }}" alt="Alt text" width="100" height="100">
  <div>
    <strong>Aron Gabriel L. Ogayon</strong><br>
    <em>BSCS-3A</em>
  </div>
</div>

# CSST102 - Basic Machine Learning
Basic Machine Learning is a foundational course for computer science students that introduces the core principles, algorithms, and applications of machine learning. I expect that this Subject can teach me this very well.

# Projects, Assignments, and Exercises that we made.


<style>
.projects-container {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.project-card {
  background: #f8f9fa;
  border: 1px solid #e9ecef;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  text-decoration: none;
  color: inherit;
  display: block;
  cursor: pointer;
}

.project-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}

.project-title {
  font-size: 1.2em;
  font-weight: bold;
  color: #333;
  margin-bottom: 10px;
}

.project-description {
  color: #666;
  line-height: 1.5;
}
</style>

<div class="projects-container">
  <a href="https://colab.research.google.com/drive/1GasiX57FGKcNw9xnx5yfjtRvrNPkR9EB?usp=sharing" target="_blank" class="project-card">
    <div class="project-title">Fundamentals of Machine Learning - Iris Dataset</div>
    <div class="project-description">
      Some might say this is the "Hello World" of Machine Learning.
    </div>
  </a>
</div>