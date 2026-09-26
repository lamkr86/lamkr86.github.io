---
layout: single
author_profile: false
permalink: /
---

<!-- NHẬP PHÔNG CHỮ INTER VÀ PLUS JAKARTA SANS -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet">

<style>
  /* Kích hoạt tự động cuộn mượt khi bấm vào nút điều hướng */
  html {
    scroll-behavior: smooth;
  }

  .academic-container {
    max-width: 760px;
    margin: 0 auto;
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    -webkit-font-smoothing: antialiased;
  }

  .academic-container h1, 
  .academic-container .section-heading {
    font-family: 'Plus Jakarta Sans', 'Inter', sans-serif;
  }

  /* HEADER INFO */
  .header-flex {
    display: flex;
    align-items: center;
    gap: 28px;
    margin-bottom: 25px;
    flex-wrap: wrap;
  }

  /* -------------------------------------------------------------
     THANH MENU NỘI BỘ (ĐẶT PHÍA DƯỚI HEADER)
     ------------------------------------------------------------- */
  .sub-nav {
    display: flex;
    gap: 28px;
    border-bottom: 1px solid rgba(0, 0, 0, 0.08);
    padding-bottom: 12px;
    margin-top: 10px;
    margin-bottom: 25px;
  }

  .sub-nav a {
    text-decoration: none !important;
    font-size: 14.5px;
    font-weight: 500;
    color: #64748b !important;
    transition: color 0.2s ease;
  }

  .sub-nav a:hover {
    color: #0f172a !important;
  }

  /* -------------------------------------------------------------
     CÁC THÀNH PHẦN KHÁC
     ------------------------------------------------------------- */
  .academic-container .txt-main,
  .academic-container h1,
  .academic-container strong {
    color: #0f172a !important;
    opacity: 1 !important;
  }

  .academic-container .txt-sub,
  .academic-container p,
  .academic-container li,
  .academic-container td {
    color: #334155 !important;
    opacity: 1 !important;
  }

  .academic-container .txt-muted {
    color: #64748b !important;
    opacity: 1 !important;
  }

  .academic-container .avatar-img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.08), 0 4px 12px rgba(0, 0, 0, 0.05);
  }

  /* Section Header thanh thoát + Khoảng bù khi cuộn đến */
  .academic-container .section-heading {
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    color: #0f172a !important;
    border-bottom: 1px solid rgba(0, 0, 0, 0.08) !important;
    padding-bottom: 8px;
    margin-top: 40px;
    margin-bottom: 18px;
    scroll-margin-top: 20px;
  }

  /* Bảng About */
  .academic-container .styled-card-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    border: 1px solid rgba(0, 0, 0, 0.08) !important;
    border-radius: 12px;
    overflow: hidden;
    margin-top: 12px;
    background-color: rgba(255, 255, 255, 0.5) !important;
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.02), 0 4px 12px rgba(0, 0, 0, 0.03);
  }

  .academic-container .styled-card-table td {
    padding: 16px 20px;
    vertical-align: top;
  }

  .academic-container .styled-card-table td:first-child {
    width: 26%;
    font-size: 14px;
    font-weight: 600;
  }

  /* Nút mạng xã hội Pill Button */
  .academic-container .social-icon-btn {
    height: 34px;
    padding: 0 14px;
    border-radius: 9999px;
    border: 1px solid rgba(0, 0, 0, 0.12) !important;
    background-color: #ffffff !important;
    color: #0f172a !important;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-decoration: none !important;
    font-size: 13px;
    font-weight: 500;
    transition: all 0.2s cubic-bezier(0.16, 1, 0.3, 1);
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.04);
  }

  .academic-container .social-icon-btn i,
  .academic-container .social-icon-btn span {
    color: #0f172a !important;
  }

  .academic-container .social-icon-btn:hover {
    background-color: #0f172a !important;
    border-color: #0f172a !important;
    color: #ffffff !important;
    transform: translateY(-1px);
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.12);
  }
  
  .academic-container .social-icon-btn:hover i,
  .academic-container .social-icon-btn:hover span {
    color: #ffffff !important;
  }

  /* DARK MODE */
  html[data-theme="dark"] .sub-nav {
    border-bottom-color: rgba(255, 255, 255, 0.1);
  }

  html[data-theme="dark"] .sub-nav a {
    color: #94a3b8 !important;
  }

  html[data-theme="dark"] .sub-nav a:hover {
    color: #ffffff !important;
  }

  html[data-theme="dark"] .academic-container .txt-main,
  html.dark .academic-container .txt-main,
  body.dark .academic-container .txt-main,
  [data-theme="dark"] .academic-container .txt-main {
    color: #f8fafc !important;
  }

  html[data-theme="dark"] .academic-container .txt-sub,
  html.dark .academic-container .txt-sub,
  body.dark .academic-container .txt-sub,
  [data-theme="dark"] .academic-container .txt-sub {
    color: #cbd5e1 !important;
  }

  html[data-theme="dark"] .academic-container .section-heading {
    border-bottom-color: rgba(255, 255, 255, 0.1) !important;
    color: #f8fafc !important;
  }

  html[data-theme="dark"] .academic-container .styled-card-table {
    border-color: rgba(255, 255, 255, 0.1) !important;
    background-color: rgba(255, 255, 255, 0.03) !important;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn {
    border-color: rgba(255, 255, 255, 0.15) !important;
    background-color: rgba(255, 255, 255, 0.05) !important;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn i,
  html[data-theme="dark"] .academic-container .social-icon-btn span {
    color: #f8fafc !important;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn:hover {
    background-color: #ffffff !important;
    border-color: #ffffff !important;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn:hover i,
  html[data-theme="dark"] .academic-container .social-icon-btn:hover span {
    color: #0f172a !important;
  }
</style>

<div class="academic-container">

  <!-- HEADER NỘI DUNG PHÍA TRÊN -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 class="txt-main" style="margin: 0; font-size: 28px; font-weight: 700; letter-spacing: -0.5px;">
        Pham Quang Lam <span class="txt-muted" style="font-size: 15px; font-weight: 400;">(팜광람)</span>
      </h1>
      <p class="txt-sub" style="margin: 6px 0 16px 0; font-size: 14.5px; line-height: 1.5; letter-spacing: -0.1px;">
        Master's Student · Division of Computer Engineering<br>
        <strong class="txt-main">Hansung University</strong>, Seoul, South Korea
      </p>

      <div style="display: flex; gap: 8px; align-items: center; flex-wrap: wrap;">
        <a href="mailto:26611301@hansung.ac.kr" class="social-icon-btn" title="Email"><i class="far fa-envelope"></i></a>
        <a href="https://scholar.google.com" target="_blank" class="social-icon-btn" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="https://github.com/lamkr86" target="_blank" class="social-icon-btn" title="GitHub"><i class="fab fa-github"></i></a>
        <a href="https://www.researchgate.net" target="_blank" class="social-icon-btn" style="font-size: 11px; font-weight: 700;" title="ResearchGate"><span>RG</span></a>
        <a href="https://linkedin.com" target="_blank" class="social-icon-btn" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </div>

  <!-- THANH ĐIỀU HƯỚNG NẰM PHÍA DƯỚI ẢNH & THÔNG TIN CÁ NHÂN -->
  <div class="sub-nav">
    <a href="#about">About</a>
    <a href="#publications">Publications</a>
    <a href="#teaching">Teaching</a>
    <a href="#honors">Honors</a>
    <a href="#prism-lab">PRISM Lab</a>
  </div>

  <!-- GIỚI THIỆU CHUNG -->
  <p class="txt-sub" style="font-size: 14.5px; line-height: 1.7; margin-bottom: 25px; letter-spacing: -0.1px;">
    I am a Master's student in the Division of Computer Engineering at <strong class="txt-main">Hansung University</strong>. My current research focuses on software engineering, web technologies, and artificial intelligence.
  </p>

  <!-- 1. MỤC ABOUT -->
  <div id="about" class="section-heading">ABOUT</div>
  <table class="styled-card-table">
    <tr>
      <td class="txt-sub" style="letter-spacing: -0.1px;">2024 – Present</td>
      <td>
        <strong class="txt-main" style="font-size: 14.5px; letter-spacing: -0.2px;">Hansung University</strong><br>
        <span class="txt-sub" style="font-size: 13.5px; letter-spacing: -0.1px;">Master's Student, Division of Computer Engineering</span>
      </td>
    </tr>
  </table>

  <!-- 2. MỤC PUBLICATIONS -->
  <div id="publications" class="section-heading">PUBLICATIONS</div>
  <p class="txt-sub" style="font-size: 13.5px;">Publications list will be updated soon.</p>

  <!-- 3. MỤC TEACHING -->
  <div id="teaching" class="section-heading">TEACHING</div>
  <p class="txt-sub" style="font-size: 13.5px;">Teaching activities will be updated soon.</p>

  <!-- 4. MỤC HONORS -->
  <div id="honors" class="section-heading">HONORS</div>
  <p class="txt-sub" style="font-size: 13.5px;">Honors and awards will be updated soon.</p>

  <!-- 5. MỤC PRISM LAB -->
  <div id="prism-lab" class="section-heading">PRISM LAB</div>
  <p class="txt-sub" style="font-size: 13.5px;">PRISM Lab research details will be updated soon.</p>

</div>
