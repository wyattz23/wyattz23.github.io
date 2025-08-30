---
title: Publications
cms_exclude: true

# View.
view: 1

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---

<div class="publications">

## 2024

<div class="publication-entry">
  <div class="conference-box">NeurIPS</div>
  <div class="publication-content">
    <div class="title">A character-level length-control algorithm for non-autoregressive sentence summarization</div>
    <div class="authors">Puyuan Liu, <strong>Your Name</strong>, Lili Mou</div>
    <div class="venue">Advances in Neural Information Processing Systems (NeurIPS), 2024</div>
    <div class="links">
      <a href="https://proceedings.neurips.cc/paper_files/paper/2022/file/bb0f9af6a4881ccb6e14c11b8b4be710-Paper-Conference.pdf">PDF</a> | 
      <a href="https://github.com/MANGA-UOFA/NACC">Code</a> | 
      <a href="https://neurips.cc/media/neurips-2022/Slides/53964.pdf">Slides</a>
    </div>
  </div>
</div>

<div class="publication-entry">
  <div class="conference-box">Journal</div>
  <div class="publication-content">
    <div class="title">Sample journal publication title</div>
    <div class="authors"><strong>Your Name</strong>, Co-author Name</div>
    <div class="venue">Journal of Example Research, 2024</div>
    <div class="links">
      <a href="#">PDF</a> | <a href="#">Code</a>
    </div>
  </div>
</div>

## 2023

<div class="publication-entry">
  <div class="conference-box">ICEX</div>
  <div class="publication-content">
    <div class="title">Another conference paper title</div>
    <div class="authors"><strong>Your Name</strong>, Another Author</div>
    <div class="venue">International Conference on Example (ICEX), 2023</div>
    <div class="links">
      <a href="#">PDF</a> | <a href="#">Code</a>
    </div>
  </div>
</div>

<div class="publication-entry">
  <div class="conference-box">Journal</div>
  <div class="publication-content">
    <div class="title">Sample journal publication from 2023</div>
    <div class="authors"><strong>Your Name</strong>, Co-author Name</div>
    <div class="venue">Example Journal, 2023</div>
    <div class="links">
      <a href="#">PDF</a> | <a href="#">Code</a>
    </div>
  </div>
</div>

## 2022

<div class="publication-entry">
  <div class="conference-box">CES</div>
  <div class="publication-content">
    <div class="title">Conference paper from 2022</div>
    <div class="authors"><strong>Your Name</strong>, Co-author Name</div>
    <div class="venue">Conference on Example Systems (CES), 2022</div>
    <div class="links">
      <a href="#">PDF</a> | <a href="#">Code</a>
    </div>
  </div>
</div>

## 2021

<div class="publication-entry">
  <div class="conference-box">Journal</div>
  <div class="publication-content">
    <div class="title">Journal publication from 2021</div>
    <div class="authors"><strong>Your Name</strong>, Co-author Name</div>
    <div class="venue">Example Research Journal, 2021</div>
    <div class="links">
      <a href="#">PDF</a> | <a href="#">Code</a>
    </div>
  </div>
</div>

</div>

<style>
.publications {
  max-width: 1000px;
  margin: 0 auto;
  padding: 20px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}

.publications h2 {
  color: #333;
  border-bottom: 2px solid #007acc;
  padding-bottom: 10px;
  margin-top: 40px;
  margin-bottom: 25px;
  font-size: 1.8em;
  font-weight: 600;
}

.publication-entry {
  display: flex;
  margin-bottom: 30px;
  padding: 20px;
  background-color: #f8f9fa;
  border-radius: 8px;
  border-left: 4px solid #007acc;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.conference-box {
  background-color: #007acc;
  color: white;
  padding: 8px 16px;
  border-radius: 6px;
  font-weight: 600;
  font-size: 0.9em;
  text-align: center;
  min-width: 80px;
  height: fit-content;
  margin-right: 20px;
  flex-shrink: 0;
}

.publication-content {
  flex: 1;
}

.publication-content .title {
  font-size: 1.1em;
  font-weight: 600;
  color: #333;
  margin-bottom: 8px;
  line-height: 1.4;
}

.publication-content .authors {
  color: #555;
  margin-bottom: 6px;
  font-size: 0.95em;
}

.publication-content .venue {
  color: #666;
  font-style: italic;
  margin-bottom: 10px;
  font-size: 0.9em;
}

.publication-content .links {
  margin-top: 8px;
}

.publication-content .links a {
  color: #007acc;
  text-decoration: none;
  margin-right: 15px;
  font-weight: 500;
  font-size: 0.9em;
}

.publication-content .links a:hover {
  text-decoration: underline;
}

.publications strong {
  color: #333;
  font-weight: 600;
}

@media (max-width: 768px) {
  .publication-entry {
    flex-direction: column;
  }
  
  .conference-box {
    margin-bottom: 15px;
    margin-right: 0;
    align-self: flex-start;
  }
}
</style>
