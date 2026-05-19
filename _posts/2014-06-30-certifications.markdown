---
layout: post
title:  "Certifications"
categories:
tags: 
image:
---

<style>
  .cert-container {
    display: flex;
    flex-direction: column;
    gap: 16px;          /* 卡片與卡片之間的上下間距 */
    margin: 30px 0;
    font-family: inherit;
  }
  
  .cert-card {
    display: flex;
    align-items: center;
    background: #fcfcfc;
    border: 1px solid #e5e5e5;
    border-radius: 8px;
    padding: 20px 24px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.02);
    transition: transform 0.2s, box-shadow 0.2s;
  }
  
  .cert-card:hover {
    transform: translateX(4px); /* 💡 改為向右微動，打破上下浮動的單調感 */
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    border-color: #cccccc;
  }
  
  /* 📊 核心亮點：替代圖片的極簡幾何縮寫圖章 */
  .cert-badge-placeholder {
    width: 50px;
    height: 50px;
    background-color: #333333; /* 深灰底色 */
    color: #ffffff;            /* 純白文字 */
    border-radius: 50%;        /* 完美正圓 */
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.9rem;
    font-weight: bold;
    letter-spacing: 0.5px;
    margin-right: 20px;
    flex-shrink: 0;            /* 防止圓圈被文字擠壓變形 */
  }
  
  .cert-info {
    flex-grow: 1;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 10px;
  }
  
  .cert-main {
    display: flex;
    flex-direction: column;
  }
  
  .cert-name {
    font-size: 1.25rem;
    font-weight: bold;
    color: #222222;
    margin: 0 0 4px 0;
  }
  
  .cert-issuer {
    font-size: 1.05rem;
    color: #555555;
    font-weight: 500;
  }
  
  .cert-date {
    font-size: 1rem;
    color: #999999;
    font-weight: normal;
    white-space: nowrap; /* 確保時間在同一行 */
  }
</style>

<div class="cert-container">

  <div class="cert-card">
    <div class="cert-badge-placeholder">ISO</div>
    <div class="cert-info">
      <div class="cert-main">
        <h3 class="cert-name">ISO/IEC 27001 Information Security Management Lead Auditor</h3>
        <span class="cert-issuer">BSI (British Standards Institution)</span>
      </div>
      <div class="cert-date">Issued Dec 2025</div>
    </div>
  </div>

  <div class="cert-card">
    <div class="cert-badge-placeholder">AWS</div>
    <div class="cert-info">
      <div class="cert-main">
        <h3 class="cert-name">AWS Certified Solutions Architect – Associate</h3>
        <span class="cert-issuer">Amazon Web Services</span>
      </div>
      <div class="cert-date">Issued Oct 2025</div>
    </div>
  </div>

  <div class="cert-card">
    <div class="cert-badge-placeholder">GCE</div>
    <div class="cert-info">
      <div class="cert-main">
        <h3 class="cert-name">Google Cloud Certified Associate Cloud Engineer</h3>
        <span class="cert-issuer">Google Cloud</span>
      </div>
      <div class="cert-date">Issued Aug 2025</div>
    </div>
  </div>

</div>
