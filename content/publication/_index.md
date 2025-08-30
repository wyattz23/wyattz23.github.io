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
  max-width: 1400px;
  margin: 0 auto;
  padding: 20px 40px;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}

.publications h2 {
  color: #2c3e50;
  border-bottom: 2px solid #3498db;
  padding-bottom: 8px;
  margin-top: 35px;
  margin-bottom: 20px;
  font-size: 1.5em;
  font-weight: 600;
}

.publication-entry {
  display: flex;
  margin-bottom: 20px;
  padding: 18px 22px;
  background-color: #ffffff;
  border-radius: 6px;
  border-left: 3px solid #3498db;
  box-shadow: 0 1px 3px rgba(0,0,0,0.08);
  width: 100%;
  transition: all 0.2s ease;
}

.publication-entry:hover {
  box-shadow: 0 2px 8px rgba(0,0,0,0.12);
  transform: translateY(-1px);
}

.conference-box {
  background-color: #3498db;
  color: white;
  padding: 6px 12px;
  border-radius: 4px;
  font-weight: 600;
  font-size: 0.75em;
  text-align: center;
  min-width: 70px;
  height: fit-content;
  margin-right: 18px;
  flex-shrink: 0;
  letter-spacing: 0.5px;
}

.publication-content {
  flex: 1;
  min-width: 0;
}

.publication-content .title {
  font-size: 0.95em;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 6px;
  line-height: 1.3;
}

.publication-content .authors {
  color: #7f8c8d;
  margin-bottom: 4px;
  font-size: 0.8em;
  line-height: 1.4;
}

.publication-content .venue {
  color: #95a5a6;
  font-style: italic;
  margin-bottom: 8px;
  font-size: 0.75em;
  line-height: 1.3;
}

.publication-content .links {
  margin-top: 6px;
}

.publication-content .links a {
  color: #3498db;
  text-decoration: none;
  margin-right: 12px;
  font-weight: 500;
  font-size: 0.75em;
  transition: color 0.2s ease;
}

.publication-content .links a:hover {
  color: #2980b9;
  text-decoration: underline;
}

.publications strong {
  color: #2c3e50;
  font-weight: 600;
}

@media (max-width: 1200px) {
  .publications {
    max-width: 1200px;
    padding: 20px 30px;
  }
}

@media (max-width: 768px) {
  .publications {
    max-width: 100%;
    padding: 20px;
  }
  
  .publication-entry {
    flex-direction: column;
    padding: 16px 18px;
  }
  
  .conference-box {
    margin-bottom: 12px;
    margin-right: 0;
    align-self: flex-start;
  }
}
</style>
