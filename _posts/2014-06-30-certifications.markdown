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
    gap: 16px;          
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
    transform: translateX(4px); 
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    border-color: #cccccc;
  }
  
  .cert-badge-placeholder {
    width: 50px;
    height: 50px;
    background-color: #333333; 
    color: #ffffff;            
    border-radius: 50%;        
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.9rem;
    font-weight: bold;
    letter-spacing: 0.5px;
    margin-right: 20px;
    flex-shrink: 0;            
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
    white-space: nowrap; 
  }
</style>

<div class="cert-container">

  <div class="cert-card">
    <div class="cert-badge-placeholder">CPC</div>
    <div class="cert-info">
      <div class="cert-main">
        <h3 class="cert-name">Fu Jen Catholic University Collegiate Programming Contest 14th place</h3>
        <span class="cert-issuer" style="display: none;"></span>
      </div>
      <div class="cert-date" style="display: none;"></div>
    </div>
  </div>

  <div class="cert-card">
    <div class="cert-badge-placeholder">TOEIC</div>
    <div class="cert-info">
      <div class="cert-main">
        <h3 class="cert-name">TOEIC 895</h3>
        <span class="cert-issuer" style="display: none;"></span>
      </div>
      <div class="cert-date" style="display: none;"></div>
    </div>
  </div>

</div>
