---
layout: single
author_profile: false
permalink: /
---

<style>
  .academic-container {
    max-width: 760px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  }

  .header-flex {
    display: flex;
    align-items: center;
    gap: 28px;
    margin-bottom: 25px;
    flex-wrap: wrap;
  }

  /* -------------------------------------------------------------
     1. MẶC ĐỊNH CHO LIGHT MODE
     ------------------------------------------------------------- */
  .academic-container .txt-main,
  .academic-container h1,
  .academic-container strong {
    color: #000000 !important;
    opacity: 1 !important;
  }

  .academic-container .txt-sub,
  .academic-container p,
  .academic-container li,
  .academic-container td {
    color: #1a1a1a !important;
    opacity: 1 !important;
  }

  .academic-container .txt-muted {
    color: #4a4a4a !important;
    opacity: 1 !important;
  }

  .academic-container .avatar-img {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    object-fit: cover;
    border: 1px solid #000000 !important;
  }

  .academic-container .section-heading {
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 1.2px;
    text-transform: uppercase;
    color: #000000 !important;
    border-bottom: 1px solid #000000 !important;
    padding-bottom: 8px;
    margin-top: 35px;
    margin-bottom: 18px;
    opacity: 1 !important;
  }

  /* BẢNG ABOUT: BO CÔNG 10PX THANH THOÁT, BỎ ĐƯỜNG KẺ CỘT */
  .academic-container .styled-card-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    border: 1px solid #000000 !important;
    border-radius: 10px;
    overflow: hidden;
    margin-top: 12px;
    background-color: transparent !important;
  }

  .academic-container .styled-card-table td {
    padding: 16px 20px;
    vertical-align: top;
  }

  .academic-container .styled-card-table td:first-child {
    width: 26%;
    font-size: 14px;
    font-weight: 600;
    /* Đã loại bỏ border-right giúp bảng thanh thoát hơn */
  }

  /* BUTTON: BO NHẸ GÓC 8PX DẠNG HÌNH CHỮ NHẬT HIỆN ĐẠI */
  .academic-container .social-icon-btn {
    height: 36px;
    padding: 0 12px;
    border-radius: 8px; /* Bo cong tinh tế */
    border: 1px solid #000000 !important;
    background-color: #ffffff !important;
    color: #000000 !important;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-decoration: none !important;
    font-size: 14px;
    transition: all 0.2s ease;
  }

  .academic-container .social-icon-btn i,
  .academic-container .social-icon-btn span {
    color: #000000 !important;
    opacity: 1 !important;
  }

  .academic-container .social-icon-btn:hover {
    background-color: #000000 !important;
    color: #ffffff !important;
    transform: translateY(-1px);
  }
  
  .academic-container .social-icon-btn:hover i,
  .academic-container .social-icon-btn:hover span {
    color: #ffffff !important;
  }


  /* -------------------------------------------------------------
     2. GIAO DIỆN TỐI (DARK MODE)
     ------------------------------------------------------------- */
  html[data-theme="dark"] .academic-container .txt-main,
  html.dark .academic-container .txt-main,
  body.dark .academic-container .txt-main,
  [data-theme="dark"] .academic-container .txt-main,
  html[data-theme="dark"] .academic-container h1,
  html[data-theme="dark"] .academic-container strong {
    color: #ffffff !important;
  }

  html[data-theme="dark"] .academic-container .txt-sub,
  html.dark .academic-container .txt-sub,
  body.dark .academic-container .txt-sub,
  [data-theme="dark"] .academic-container .txt-sub,
  html[data-theme="dark"] .academic-container p,
  html[data-theme="dark"] .academic-container li,
  html[data-theme="dark"] .academic-container td {
    color: #f3f4f6 !important;
  }

  html[data-theme="dark"] .academic-container .txt-muted {
    color: #d1d5db !important;
  }

  html[data-theme="dark"] .academic-container .avatar-img,
  html[data-theme="dark"] .academic-container .section-heading,
  html[data-theme="dark"] .academic-container .styled-card-table {
    border-color: #ffffff !important;
    color: #ffffff !important;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn {
    border-color: #ffffff !important;
    background-color: transparent !important;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn i,
  html[data-theme="dark"] .academic-container .social-icon-btn span {
    color: #ffffff !important;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn:hover {
    background-color: #ffffff !important;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn:hover i,
  html[data-theme="dark"] .academic-container .social-icon-btn:hover span {
    color: #000000 !important;
  }
</style>

<div class="academic-container">

  <!-- HEADER -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 class="txt-main" style="margin: 0; font-size: 28px; font-weight: 700;">
        Pham Quang Lam <span class="txt-muted" style="font-size: 16px; font-weight: normal;">(범광람)</span>
      </h1>
      <p class="txt-sub" style="margin: 6px 0 14px 0; font-size: 15px; line-height: 1.5;">
        Undergraduate Student · Division of Computer Engineering<br>
        <strong class="txt-main">Hansung University</strong>, Seoul, South Korea
      </p>

      <!-- HÀNG NÚT ICON BO NHẸ TINH TẾ -->
      <div style="display: flex; gap: 8px; align-items: center; flex-wrap: wrap;">
        <a href="mailto:26611301@hansung.ac.kr" class="social-icon-btn" title="Email"><i class="far fa-envelope"></i></a>
        <a href="https://scholar.google.com" target="_blank" class="social-icon-btn" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="https://github.com/lamkr86" target="_blank" class="social-icon-btn" title="GitHub"><i class="fab fa-github"></i></a>
        <a href="https://www.researchgate.net" target="_blank" class="social-icon-btn" style="font-size: 12px; font-weight: 700;" title="ResearchGate"><span>RG</span></a>
        <a href="https://linkedin.com" target="_blank" class="social-icon-btn" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </div>

  <!-- GIỚI THIỆU -->
  <p class="txt-sub" style="font-size: 15px; line-height: 1.7; margin-bottom: 25px;">
    I am an undergraduate student in the Division of Computer Engineering at <strong class="txt-main">Hansung University</strong>. My current study focuses on software engineering, web technologies, and artificial intelligence.
  </p>

  <!-- MỤC ABOUT -->
  <div class="section-heading">ABOUT</div>
  <table class="styled-card-table">
    <tr>
      <td class="txt-sub">2024 – Present</td>
      <td>
        <strong class="txt-main" style="font-size: 15px;">Hansung University</strong><br>
        <span class="txt-sub" style="font-size: 14px;">Undergraduate Student, Division of Computer Engineering</span>
      </td>
    </tr>
  </table>

  <!-- MỤC PROJECTS -->
  <div class="section-heading">PROJECTS & ACTIVITIES</div>
  <ul style="padding-left: 18px; margin: 0; line-height: 1.7;">
    <li style="margin-bottom: 12px;">
      <strong class="txt-main">Academic Personal Website</strong> <span class="txt-muted" style="font-size: 13px;">(2026)</span><br>
      <span class="txt-sub" style="font-size: 14px;">Designed and deployed a minimal academic profile hosted on GitHub Pages.</span>
    </li>
    <li>
      <strong class="txt-main">Computer Engineering Coursework</strong><br>
      <span class="txt-sub" style="font-size: 14px;">Developing software projects and core algorithms at Hansung University.</span>
    </li>
  </ul>

</div>
