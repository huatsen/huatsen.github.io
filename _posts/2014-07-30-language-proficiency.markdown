---
layout: post
title:  "Competencies"
categories:
tags: 
image:
---

<style>
  .lang-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    margin: 30px 0;
    font-family: inherit;
  }
  
  .lang-card {
    flex: 1;
    min-width: 280px;
    background: #fcfcfc;
    border: 1px solid #e5e5e5;
    border-radius: 8px;
    padding: 26px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.02);
    transition: transform 0.2s, box-shadow 0.2s;
  }
  
  .lang-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    border-color: #cccccc;
  }
  
  .lang-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 15px;
    border-bottom: 1px solid #f0f0f0;
    padding-bottom: 10px;
  }
  
  .lang-name {
    font-size: 1.4rem;
    font-weight: bold;
    color: #222222;
    margin: 0;
  }
  
  .lang-badge {
    font-size: 0.85rem;
    font-weight: 600;
    background-color: #333333;
    color: #ffffff;
    padding: 4px 12px;
    border-radius: 20px;
    letter-spacing: 0.5px;
  }
  
  .progress-bg {
    background: #eee;
    height: 5px;
    border-radius: 2px;
    margin-bottom: 20px;
    overflow: hidden;
  }
  .progress-fill {
    background: #555;
    height: 100%;
    border-radius: 2px;
  }
  
  .lang-detail-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  .lang-detail-list li {
    font-size: 1.05rem;
    color: #444444;
    line-height: 1.7;
    margin-bottom: 8px;
    position: relative;
    padding-left: 18px;
  }
  
  .lang-detail-list li::before {
    content: "•";          
    position: absolute;
    left: 0;
    top: 4px;            
    color: #666666;        
    font-size: 1.4rem;
    line-height: 1;   
  }
</style>

<div class="lang-grid">

  <div class="lang-card">
    <div class="lang-header">
      <h3 class="lang-name">English</h3>
      <span class="lang-badge">Advanced</span>
    </div>
    <div class="progress-bg">
      <div class="progress-fill" style="width: 90%;"></div>
    </div>
    <ul class="lang-detail-list">
      <li><strong>TOEIC 895</strong> — Demonstrated advanced proficiency in global business environments.</li>
      <li><strong>Academic & Research Readiness</strong> — Skilled in delivering research presentations and writing technical papers.</li>
      <li><strong>Professional Discourse</strong> — Confident in driving cross-cultural technical collaborations and discussions.</li>
    </ul>
  </div>

  <div class="lang-card">
    <div class="lang-header">
      <h3 class="lang-name">Mandarin Chinese</h3>
      <span class="lang-badge">Native</span>
    </div>
    <div class="progress-bg">
      <div class="progress-fill" style="width: 100%;"></div>
    </div>
    <ul class="lang-detail-list">
      <li><strong>Native Proficiency</strong> — Full fluency in professional speaking, academic reading, and technical writing.</li>
      <li><strong>Bi-Scriptual Expertise</strong> — Proficient in navigating content in both Traditional and Simplified Chinese.</li>
      <li><strong>Technical Document Localization</strong> — Experienced in translating technical and research documentation.</li>
    </ul>
  </div>

</div>
