---
layout: post
title:  "Language Proficiency"
categories:
tags: 
image:
---

<style>
  .lang-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin: 30px 0;
    font-family: inherit;
  }
  
  .lang-card {
    flex: 1;
    min-width: 250px;
    background: #fcfcfc;
    border: 1px solid #e5e5e5;
    border-radius: 8px;
    padding: 24px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.02);
    transition: transform 0.2s, box-shadow 0.2s;
  }
  
  /* 滑鼠懸停的優雅微動效 */
  .lang-card:hover {
    transform: translateY(-2px);
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
  
  /* 📊 核心亮點：高質感黑灰膠囊標籤 */
  .lang-badge {
    font-size: 0.85rem;
    font-weight: 600;
    background-color: #333333; /* 核心深灰 */
    color: #ffffff; /* 純白字 */
    padding: 4px 12px;
    border-radius: 20px;
    letter-spacing: 0.5px;
  }
  
  /* 🛠️ 極簡微型進度條 */
  .progress-bg {
    background: #eee;
    height: 4px;
    border-radius: 2px;
    margin-bottom: 15px;
    overflow: hidden;
  }
  .progress-fill {
    background: #555; /* 進度條顏色 */
    height: 100%;
    border-radius: 2px;
  }
  
  .lang-detail-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  .lang-detail-list li {
    font-size: 0.95rem;
    color: #666666;
    margin-bottom: 6px;
    position: relative;
    padding-left: 15px;
  }
  
  /* 用小短橫線取代傳統圓點 */
  .lang-detail-list li::before {
    content: "—";
    position: absolute;
    left: 0;
    color: #999999;
  }
</style>

<div class="lang-grid">

  <div class="lang-card">
    <div class="lang-header">
      <h3 class="lang-name">English</h3>
      <span class="lang-badge">Fluent / Native</span>
    </div>
    <div class="progress-bg">
      <div class="progress-fill" style="width: 90%;"></div>
    </div>
    <ul class="lang-detail-list">
      <li>Professional working proficiency</li>
      <li>Academic research & report writing</li>
      <li>Cross-cultural communication support</li>
    </ul>
  </div>

  <div class="lang-card">
    <div class="lang-header">
      <h3 class="lang-name">Mandarin</h3>
      <span class="lang-badge">Native</span>
    </div>
    <div class="progress-bg">
      <div class="progress-fill" style="width: 100%;"></div>
    </div>
    <ul class="lang-detail-list">
      <li>Mother tongue</li>
      <li>Excellent presentation & narration skills</li>
      <li>Traditional & Simplified Chinese localization</li>
    </ul>
  </div>

</div>
