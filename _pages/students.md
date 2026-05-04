---
layout: archive
title: "Group"
permalink: /group/
author_profile: true
---

<style>
.student-section {
  margin-bottom: 2.5em;
  background: #f8f9fa;
  border-radius: 8px;
  padding: 1.5em;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.student-category {
  color: #2c3e50;
  margin-bottom: 1.2em;
  font-size: 1.3em;
  font-weight: 600;
  border-bottom: 3px solid #3498db;
  padding-bottom: 0.5em;
  margin-top: 0;
}

.student-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 0.9em;
  margin-left: 0;
}

.student-item {
  padding: 1em;
  background: white;
  border-radius: 6px;
  border-left: 4px solid #3498db;
  box-shadow: 0 1px 3px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
  display: grid;
  grid-template-columns: minmax(0, 1fr) auto;
  column-gap: 0.8em;
  row-gap: 0.35em;
  align-items: start;
  margin-bottom: 0;
}

.student-item:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 8px rgba(0,0,0,0.15);
}

.student-item:last-child {
  margin-bottom: 0;
}

.student-name {
  color: #2c3e50;
  font-size: 1.1em;
  font-weight: 500;
  display: block;
  margin-bottom: 0;
  min-width: 0;
}

.student-period {
  color: #7f8c8d;
  font-size: 0.9em;
  font-style: italic;
  white-space: nowrap;
  text-align: right;
}

.student-destination {
  color: #27ae60;
  font-size: 0.9em;
  font-weight: 500;
  margin-top: 0.1em;
  display: block;
  grid-column: 1 / -1;
  padding-top: 0.25em;
  border-top: 1px solid #eef2f5;
}

.student-destination::before {
  content: "→ ";
  color: #3498db;
}

.phd-students .student-item {
  border-left-color: #e74c3c;
}

.master-students .student-item {
  border-left-color: #f39c12;
}

.alumni .student-item {
  border-left-color: #9b59b6;
}

.section-header {
  margin-bottom: 2em;
  text-align: center;
}

.section-title {
  color: #2c3e50;
  font-size: 1.8em;
  font-weight: 600;
  margin-bottom: 0.5em;
}

.section-subtitle {
  color: #7f8c8d;
  font-size: 1em;
  font-style: italic;
}

@media screen and (max-width: 640px) {
  .student-list {
    grid-template-columns: 1fr;
  }
  
  .student-item {
    grid-template-columns: 1fr;
  }
  
  .student-period {
    text-align: left;
  }
}
</style>

<div class="student-section phd-students">
  <h2 class="student-category">Ph.D. Students</h2>
  <div class="student-list">
    <div class="student-item">
      <span class="student-name">Bing Liu</span>
      <span class="student-period">2023 - present</span>
    </div>
    <div class="student-item">
      <span class="student-name">Boyu Zhang</span>
      <span class="student-period">2022 - present</span>
    </div>
  </div>
</div>

<div class="student-section master-students">
  <h2 class="student-category">Master Students</h2>
  <div class="student-list">
    <div class="student-item">
      <span class="student-name">Jinyan Li</span>
      <span class="student-period">2025 - present</span>
    </div>
    <div class="student-item">
      <span class="student-name">Ruge Bai</span>
      <span class="student-period">2025 - present</span>
    </div>
    <div class="student-item">
      <span class="student-name">Jiarong Rong</span>
      <span class="student-period">2025 - present</span>
    </div>
    <div class="student-item">
      <span class="student-name">Zijun Ping</span>
      <span class="student-period">2025 - present</span>
    </div>
    <div class="student-item">
      <span class="student-name">Ruilin Han</span>
      <span class="student-period">2025 - present</span>
    </div>
    <div class="student-item">
      <span class="student-name">Qihang Fan</span>
      <span class="student-period">2024 - present</span>
    </div>
    <div class="student-item">
      <span class="student-name">Wenjun Miao</span>
      <span class="student-period">2023 - present</span>
    </div>
    <div class="student-item">
      <span class="student-name">Aocheng Shen</span>
      <span class="student-period">2023 - present</span>
    </div>
  </div>
</div>

<div class="student-section alumni">
  <h2 class="student-category">Master's Alumni</h2>
  <div class="student-list">
    <div class="student-item">
      <span class="student-name">Di Yuan</span>
      <span class="student-period">2022 - 2025</span>
      <span class="student-destination">Algorithm Engineer, Pinduoduo</span>
    </div>
    <div class="student-item">
      <span class="student-name">Jiaqi Wang</span>
      <span class="student-period">2022 - 2025</span>
      <span class="student-destination">Management Trainee, China Eastern Airlines</span>
    </div>
  </div>
</div>
