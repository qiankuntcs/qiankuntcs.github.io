---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
/* 只保留内容排版相关的自定义样式，不影响全局布局 */

.cv-section-title {
  color: #2c3e50;
  font-size: 1.4em;
  border-bottom: 2px solid #3498db;
  padding-bottom: 0.2em;
  margin-bottom: 0.6em;
  letter-spacing: 0.5px;
}

.cv-entry {
  margin-bottom: 0.6em;
  padding-left: 0.8em;
  position: relative;
}

.cv-entry:before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.5em;
  width: 4px;
  height: 4px;
  background: #3498db;
  border-radius: 50%;
}

.cv-entry-title {
  color: #34495e;
  font-weight: 600;
  font-size: 1em;
  margin-bottom: 0.2em;
  letter-spacing: 0.3px;
}

.cv-entry-subtitle {
  color: #7f8c8d;
  font-size: 0.9em;
  margin-bottom: 0.1em;
}

.cv-entry-detail {
  color: #666;
  font-size: 0.85em;
  margin-left: 0.8em;
  line-height: 1.3;
}

.grants-section {
  background: #f8f9fa;
  padding: 0.8em;
  border-radius: 4px;
  margin-top: 0.6em;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
}

.grant-entry {
  margin-bottom: 0.6em;
  padding-left: 0.8em;
  border-left: 2px solid #3498db;
}

.grant-title {
  font-weight: 600;
  color: #2c3e50;
  font-size: 0.95em;
}

.cv-entry:hover:before {
  background: #2980b9;
  transform: scale(1.2);
  transition: all 0.2s ease;
}

.grant-entry:hover {
  border-left-color: #2980b9;
  transition: all 0.2s ease;
}
</style>

<div class="cv-container">
  <div class="cv-section">
    <h1 class="cv-section-title">Education</h1>
    <div class="cv-entry">
      <div class="cv-entry-title">Ph.D in Computer Science</div>
      <div class="cv-entry-subtitle">The University of Hong Kong, 2017-2021</div>
      <div class="cv-entry-detail">
        <div>Thesis: Online Primal Dual Algorithms for Generalized Online Bipartite Matching Problems</div>
        <div>Advisor: Zhiyi Huang</div>
      </div>
    </div>
    
    <div class="cv-entry">
      <div class="cv-entry-title">Bachelor of Engineering in Computer Science and Engineering</div>
      <div class="cv-entry-subtitle">Chu Kochen Honors College, Zhejiang University, 2013-2017</div>
      <div class="cv-entry-detail">Advisor: Guochuan Zhang</div>
    </div>
  </div>

  <div class="cv-section">
    <h1 class="cv-section-title">Work Experience</h1>
    <div class="cv-entry">
      <div class="cv-entry-title">Research Associate Professor</div>
      <div class="cv-entry-subtitle">2021 - present</div>
      <div class="cv-entry-detail">School of Cyber Science and Engineering, Huazhong University of Science and Technology</div>
    </div>

    <div class="cv-entry">
      <div class="cv-entry-title">Research Intern</div>
      <div class="cv-entry-subtitle">2016 - 2017</div>
      <div class="cv-entry-detail">Vision Lab, SenseTime</div>
    </div>

    <div class="cv-entry">
      <div class="cv-entry-title">Visiting Scholar</div>
      <div class="cv-entry-subtitle">2016</div>
      <div class="cv-entry-detail">
        <div>Department of Electrical and Computer Engineering, University of Waterloo</div>
        <div>Mentor: Sebastian Fischmeister</div>
      </div>
    </div>
  </div>

  <div class="cv-section">
    <h1 class="cv-section-title">Selected Honors</h1>
    <div class="cv-entry">
      <div class="cv-entry-title">Wuhan Young Talent</div>
      <div class="cv-entry-subtitle">Wuhan, 2022</div>
    </div>

    <div class="cv-entry">
      <div class="cv-entry-title">East Lake Young Talent</div>
      <div class="cv-entry-subtitle">Huawei & Huazhong University of Science and Technology, 2022</div>
    </div>

    <div class="cv-entry">
      <div class="cv-entry-title">Lee Shau Kee Postgraduate Fellowships</div>
      <div class="cv-entry-subtitle">The University of Hong Kong, 2017</div>
    </div>

    <div class="cv-entry">
      <div class="cv-entry-title">Y S and Christabel Lung Postgraduate Scholarship</div>
      <div class="cv-entry-subtitle">Faculty of Engineering, The University of Hong Kong, 2017</div>
    </div>

    <div class="cv-entry">
      <div class="cv-entry-title">Dean's Scholarship</div>
      <div class="cv-entry-subtitle">Chu Kochen Honors College, Zhejiang University, 2016</div>
    </div>
  </div>

  <div class="cv-section">
    <h1 class="cv-section-title">Grants</h1>
    <h3 style="color: #34495e; margin-bottom: 1em;">As PI</h3>
    <div class="grants-section">
      <div class="grant-entry">
        <div class="grant-title">Competitive analysis of online matching problems</div>
        <div class="cv-entry-subtitle">2024-2026</div>
        <div class="cv-entry-detail">Young Scientists Fund, National Natural Science Foundation of China</div>
      </div>

      <div class="grant-entry">
        <div class="grant-title">Online matching with stochastic rewards</div>
        <div class="cv-entry-subtitle">2023-2024</div>
        <div class="cv-entry-detail">CCF-Huawei Huyanglin Fund for Theoretical Computer Science</div>
      </div>

      <div class="grant-entry">
        <div class="grant-title">Generalized online matching problems</div>
        <div class="cv-entry-subtitle">2023-2025</div>
        <div class="cv-entry-detail">Young Scientists Fund, Natural Science Foundation of Hubei Province</div>
      </div>
    </div>
  </div>
</div>


