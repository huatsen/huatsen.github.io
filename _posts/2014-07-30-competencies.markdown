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

  h2#language-proficiency, 
  h2#technical-skills {
    color: #333333;
    font-size: 1.5rem;
    font-weight: normal;
    margin-top: 40px;
    margin-bottom: 20px;
    letter-spacing: -0.5px;
  }
</style>

## Language Proficiency

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

## Technical Skills

<style>
  /* 框框的外層大容器 */
  .skills-grid {
    display: flex;
    flex-wrap: wrap;       /* 超過寬度自動換行，相容手機版 */
    gap: 20px;             /* 框框之間的間距 */
    margin: 25px 0 50px 0; /* 上下留出合適的呼吸空間 */
    width: 100%;
  }

  /* 單個技能小框框的基本樣式 */
  .skill-box {
    flex: 1;
    min-width: 220px;      /* 確保在小螢幕時框框不會被擠壓得太醜 */
    background: #fcfcfc;
    border: 1px solid #e5e5e5;
    border-radius: 8px;    /* 呼應語言卡片的圓角 */
    padding: 22px;
    text-align: center;    /* 文字一律精準置中 */
    box-shadow: 0 2px 5px rgba(0,0,0,0.01);
    
    /* 絲滑的滑鼠懸停動畫過渡 */
    transition: transform 0.2s cubic-bezier(0.4, 0, 0.2, 1), 
                box-shadow 0.2s ease, 
                border-color 0.2s ease;
  }

  /* 🖱️ 當滑鼠移到小框框上時的動態特效 */
  .skill-box:hover {
    transform: translateY(-4px);           /* 微微向上飄浮 4px */
    box-shadow: 0 6px 15px rgba(0,0,0,0.06); /* 稍微加深陰影，更有立體感 */
    border-color: #999999;                 /* 邊框顏色變深 */
  }

  /* 框框內文字的字體樣式 */
  .skill-title {
    font-size: 1.15rem;
    font-weight: 600;
    color: #222222;
    margin: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    letter-spacing: 0.3px;
  }
</style>

<div class="skills-grid">

  <div class="skill-box">
    <h4 class="skill-title">AI & Machine Learning</h4>
  </div>

  <div class="skill-box">
    <h4 class="skill-title">Programming</h4>
  </div>

  <div class="skill-box">
    <h4 class="skill-title">Data Analysis</h4>
  </div>

</div>
