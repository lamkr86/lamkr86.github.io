---
layout: single
author_profile: false
permalink: /
---

<style>
  /* =========================================================
     1. GIAO DIỆN SÁNG (LIGHT MODE) - MẶC ĐỊNH
     ========================================================= */
  .academic-container {
    max-width: 760px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  }

  /* Định nghĩa màu Nền Sáng - Chữ Đen */
  .txt-main { color: #000000 !important; }
  .txt-sub  { color: #374151 !important; } /* Xám đậm rõ nét */
  .txt-muted{ color: #4b5563 !important; }

  .avatar-img {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid #000000 !important;
  }

  /* Nút bấm ở nền sáng */
  .social-icon-btn {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    border: 1.5px solid #000000 !important;
    background-color: #ffffff !important;
    color: #000000 !important;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-decoration: none !important;
    font-size: 14px;
    transition: all 0.2s ease;
  }

  .social-icon-btn i, .social-icon-btn span { color: #000000 !important; }

  .social-icon-btn:hover {
    background-color: #000000 !important;
    color: #ffffff !important;
  }
  .social-icon-btn:hover i, .social-icon-btn:hover span { color: #ffffff !important; }

  /* Đường kẻ & Bảng ở nền sáng */
  .section-heading {
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 1.2px;
    text-transform: uppercase;
    color: #000000 !important;
    border-bottom: 2px solid #000000 !important;
    padding-bottom: 6px;
    margin-top: 35px;
    margin-bottom: 16px;
  }

  .styled-card-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    border: 1.5px solid #000000 !important;
    border-radius: 8px;
    overflow: hidden;
    margin-top: 12px;
    background-color: transparent !important;
  }

  .styled-card-table td {
    padding: 14px 18px;
    vertical-align: top;
  }

  .styled-card-table td:first-child {
    width: 28%;
    border-right: 1.5px solid #000000 !important;
    font-size: 14px;
    font-weight: 600;
  }

  .header-flex {
    display: flex;
    align-items: center;
    gap: 28px;
    margin-bottom: 25px;
    flex-wrap: wrap;
  }


  /* =========================================================
     2. GIAO DIỆN TỐI (DARK MODE) - ÉP ĐỔI MÀU KHI BẤM NÚT
     ========================================================= */
  html.dark .txt-main, body.dark .txt-main, [data-theme="dark"] .txt-main,
  html.dark h1, body.dark h1, [data-theme="dark"] h1,
  html.dark strong, body.dark strong, [data-theme="dark"] strong {
    color: #ffffff !important; /* Chữ chính đổi thành Trắng */
  }

  html.dark .txt-sub, body.dark .txt-sub, [data-theme="dark"] .txt-sub,
  html.dark p, body.dark p, [data-theme="dark"] p,
  html.dark span, body.dark span, [data-theme="dark"] span,
  html.dark li, body.dark li, [data-theme="dark"] li,
  html.dark td, body.dark td, [data-theme="dark"] td {
    color: #e2e8f0 !important; /* Chữ phụ đổi thành Xám Trắng sáng */
    opacity: 1 !important;
  }

  html.dark .txt-muted, body.dark .txt-muted, [data-theme="dark"] .txt-muted {
    color: #cbd5e1 !important;
  }

  /* Đổi viền khung & nút sang màu Trắng khi ở nền tối */
  html.dark .avatar-img, body.dark .avatar-img, [data-theme="dark"] .avatar-img,
  html.dark .styled-card-table, body.dark .styled-card-table, [data-theme="dark"] .styled-card-table,
  html.dark .styled-card-table td:first-child, body.dark .styled-card-table td:first-child, [data-theme="dark"] .styled-card-table td:first-child,
  html.dark .section-heading, body.dark .section-heading, [data-theme="dark"] .section-heading {
    border-color: #ffffff !important;
    color: #ffffff !important;
  }

  html.dark .social-icon-btn, body.dark .social-icon-btn, [data-theme="dark"] .social-icon-btn {
    border-color: #ffffff !important;
    background-color: transparent !important;
  }

  html.dark .social-icon-btn i, body.dark .social-icon-btn i, [data-theme="dark"] .social-icon-btn i,
  html.dark .social-icon-btn span, body.dark .social-icon-btn span, [data-theme="dark"] .social-icon-btn span {
    color: #ffffff !important;
  }

  html.dark .social-icon-btn:hover, body.dark .social-icon-btn:hover, [data-theme="dark"] .social-icon-btn:hover {
    background-color: #ffffff !important;
  }
  html.dark .social-icon-btn:hover i, body.dark .social-icon-btn:hover i, [data-theme="dark"] .social-icon-btn:hover i,
  html.dark .social-icon-btn:hover span, body.dark .social-icon-btn:hover span, [data-theme="dark"] .social-icon-btn:hover span {
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

      <!-- HÀNG NÚT ICON -->
      <div style="display: flex; gap: 8px; align-items: center;">
        <a href="mailto:26611301@hansung.ac.kr" class="social-icon-btn" title="Email"><i class="far fa-envelope"></i></a>
        <a href="https://scholar.google.com" target="_blank" class="social-icon-btn" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="https://github.com/lamkr86" target="_blank" class="social-icon-btn" title="GitHub"><i class="fab fa-github"></i></a>
        <a href="https://www.researchgate.net" target="_blank" class="social-icon-btn" style="font-size: 11px; font-weight: bold;" title="ResearchGate"><span>RG</span></a>
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

  <!-- MỤC PROJECTS & ACTIVITIES -->
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
