---
layout: single
author_profile: false
permalink: /
---

<!-- NHẬP PHÔNG CHỮ INTER VÀ PLUS JAKARTA SANS CHUẨN THẾ GIỚI -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet">

<style>
  /* Áp dụng phông chữ Inter chuẩn thế giới cho toàn bộ container */
  .academic-container {
    max-width: 760px;
    margin: 0 auto;
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, "SF Pro Text", "Segoe UI", Roboto, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  /* Tiêu đề chính dùng Plus Jakarta Sans tạo độ hiện đại */
  .academic-container h1, 
  .academic-container .section-heading {
    font-family: 'Plus Jakarta Sans', 'Inter', sans-serif;
  }

  .header-flex {
    display: flex;
    align-items: center;
    gap: 28px;
    margin-bottom: 25px;
    flex-wrap: wrap;
  }

  /* -------------------------------------------------------------
     1. GIAO DIỆN SÁNG (LIGHT MODE)
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

  /* Avatar tinh tế */
  .academic-container .avatar-img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.08), 0 4px 12px rgba(0, 0, 0, 0.05);
  }

  /* Section Header thanh thoát chuẩn Vercel */
  .academic-container .section-heading {
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    color: #0f172a !important;
    border-bottom: 1px solid rgba(0, 0, 0, 0.08) !important;
    padding-bottom: 8px;
    margin-top: 35px;
    margin-bottom: 18px;
    opacity: 1 !important;
  }

  /* Khung Card Bo 12px + Bóng đổ Ambient cực mịn */
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

  /* Nút bấm bo hạt đậu (Pill Shape) */
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
    opacity: 1 !important;
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


  /* -------------------------------------------------------------
     2. GIAO DIỆN TỐI (DARK MODE)
     ------------------------------------------------------------- */
  html[data-theme="dark"] .academic-container .txt-main,
  html.dark .academic-container .txt-main,
  body.dark .academic-container .txt-main,
  [data-theme="dark"] .academic-container .txt-main,
  html[data-theme="dark"] .academic-container h1,
  html[data-theme="dark"] .academic-container strong {
    color: #f8fafc !important;
  }

  html[data-theme="dark"] .academic-container .txt-sub,
  html.dark .academic-container .txt-sub,
  body.dark .academic-container .txt-sub,
  [data-theme="dark"] .academic-container .txt-sub,
  html[data-theme="dark"] .academic-container p,
  html[data-theme="dark"] .academic-container li,
  html[data-theme="dark"] .academic-container td {
    color: #cbd5e1 !important;
  }

  html[data-theme="dark"] .academic-container .txt-muted {
    color: #64748b !important;
  }

  html[data-theme="dark"] .academic-container .avatar-img {
    box-shadow: 0 0 0 1px rgba(255, 255, 255, 0.15);
  }

  html[data-theme="dark"] .academic-container .section-heading {
    border-bottom-color: rgba(255, 255, 255, 0.1) !important;
    color: #f8fafc !important;
  }

  html[data-theme="dark"] .academic-container .styled-card-table {
    border-color: rgba(255, 255, 255, 0.1) !important;
    background-color: rgba(255, 255, 255, 0.03) !important;
    box-shadow: none;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn {
    border-color: rgba(255, 255, 255, 0.15) !important;
    background-color: rgba(255, 255, 255, 0.05) !important;
    box-shadow: none;
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

  <!-- HEADER -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 class="txt-main" style="margin: 0; font-size: 28px; font-weight: 700; letter-spacing: -0.5px;">
        Pham Quang Lam <span class="txt-muted" style="font-size: 15px; font-weight: 400;">(범광람)</span>
      </h1>
      <p class="txt-sub" style="margin: 6px 0 16px 0; font-size: 14.5px; line-height: 1.5; letter-spacing: -0.1px;">
        Undergraduate Student · Division of Computer Engineering<br>
        <strong class="txt-main">Hansung University</strong>, Seoul, South Korea
      </p>

      <!-- DÀN NÚT BUTTON -->
      <div style="display: flex; gap: 8px; align-items: center; flex-wrap: wrap;">
        <a href="mailto:26611301@hansung.ac.kr" class="social-icon-btn" title="Email"><i class="far fa-envelope"></i></a>
        <a href="https://scholar.google.com" target="_blank" class="social-icon-btn" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="https://github.com/lamkr86" target="_blank" class="social-icon-btn" title="GitHub"><i class="fab fa-github"></i></a>
        <a href="https://www.researchgate.net" target="_blank" class="social-icon-btn" style="font-size: 11px; font-weight: 700;" title="ResearchGate"><span>RG</span></a>
        <a href="https://linkedin.com" target="_blank" class="social-icon-btn" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </div>

  <!-- GIỚI THIỆU -->
  <p class="txt-sub" style="font-size: 14.5px; line-height: 1.7; margin-bottom: 25px; letter-spacing: -0.1px;">
    I am an undergraduate student in the Division of Computer Engineering at <strong class="txt-main">Hansung University</strong>. My current study focuses on software engineering, web technologies, and artificial intelligence.
  </p>

  <!-- MỤC ABOUT -->
  <div class="section-heading">ABOUT</div>
  <table class="styled-card-table">
    <tr>
      <td class="txt-sub" style="letter-spacing: -0.1px;">2024 – Present</td>
      <td>
        <strong class="txt-main" style="font-size: 14.5px; letter-spacing: -0.2px;">Hansung University</strong><br>
        <span class="txt-sub" style="font-size: 13.5px; letter-spacing: -0.1px;">Undergraduate Student, Division of Computer Engineering</span>
      </td>
    </tr>
  </table>

  <!-- MỤC PROJECTS -->
  <div class="section-heading">PROJECTS & ACTIVITIES</div>
  <ul style="padding-left: 18px; margin: 0; line-height: 1.7;">
    <li style="margin-bottom: 12px;">
      <strong class="txt-main" style="letter-spacing: -0.2px;">Academic Personal Website</strong> <span class="txt-muted" style="font-size: 13px;">(2026)</span><br>
      <span class="txt-sub" style="font-size: 13.5px; letter-spacing: -0.1px;">Designed and deployed a minimal academic profile hosted on GitHub Pages.</span>
    </li>
    <li>
      <strong class="txt-main" style="letter-spacing: -0.2px;">Computer Engineering Coursework</strong><br>
      <span class="txt-sub" style="font-size: 13.5px; letter-spacing: -0.1px;">Developing software projects and core algorithms at Hansung University.</span>
    </li>
  </ul>

</div>
