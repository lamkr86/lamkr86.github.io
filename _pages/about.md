---
layout: single
author_profile: false
permalink: /
---

<style>
  /* 1. KHỞI TẠO BỘ MÀU TƯƠNG PHẢN CAO CHO CẢ LIGHT VÀ DARK MODE */
  :root {
    --text-primary: #111827;
    --text-secondary: #374151;
    --text-muted: #4b5563;
    --accent-blue: #0969da;
    --border-card: #d0d7de;
    --btn-bg: #ffffff;
    --btn-border: #d1d5db;
    --btn-hover: #f3f4f6;
  }

  /* ÉP TẤT CẢ CHỮ PHỤ SÁNG RÕ 100% KHI Ở DARK MODE */
  @media (prefers-color-scheme: dark), [data-theme="dark"], body.dark, .dark, html.dark {
    :root {
      --text-primary: #ffffff !important;      /* Chữ chính: Trắng tinh */
      --text-secondary: #e2e8f0 !important;    /* Chữ phụ: Xám trắng sáng rõ */
      --text-muted: #cbd5e1 !important;        /* Chữ mờ/ngày tháng: Sáng rõ nét */
      --accent-blue: #38bdf8 !important;      /* Màu xanh điểm nhấn nhã nhặn */
      --border-card: #475569 !important;      /* Viền khung xám rõ ràng */
      --btn-bg: #1e293b !important;
      --btn-border: #475569 !important;
      --btn-hover: #334155 !important;
    }
    
    /* Khóa độ trong suốt, không cho theme làm mờ chữ */
    * {
      opacity: 1 !important;
    }
  }

  /* 2. CẤU TRÚC LAYOUT VÀ KHUNG BO CONG */
  .academic-container {
    max-width: 760px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    color: var(--text-primary) !important;
  }

  .header-flex {
    display: flex;
    align-items: center;
    gap: 28px;
    margin-bottom: 25px;
    flex-wrap: wrap;
  }

  .avatar-img {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    object-fit: cover;
    border: 1px solid var(--border-card);
  }

  .social-icon-btn {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    border: 1px solid var(--btn-border);
    background-color: var(--btn-bg) !important;
    color: var(--accent-blue) !important;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-decoration: none !important;
    font-size: 14px;
    transition: all 0.2s ease;
  }

  .social-icon-btn:hover {
    background-color: var(--btn-hover) !important;
    border-color: var(--accent-blue) !important;
    transform: translateY(-2px);
  }

  .section-heading {
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 1.2px;
    text-transform: uppercase;
    color: var(--accent-blue) !important;
    border-bottom: 2px solid var(--border-card);
    padding-bottom: 6px;
    margin-top: 35px;
    margin-bottom: 16px;
  }

  /* BẢNG BO CONG VÀ THÔNG THOÁNG CHUẨN UX */
  .styled-card-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    border: 1px solid var(--border-card);
    border-radius: 8px;
    overflow: hidden;
    margin-top: 12px;
    background-color: transparent;
  }

  .styled-card-table td {
    padding: 14px 18px;
    vertical-align: top;
  }

  .styled-card-table td:first-child {
    width: 28%;
    border-right: 1px solid var(--border-card);
    color: var(--text-muted) !important;
    font-size: 14px;
    font-weight: 600;
  }
</style>

<div class="academic-container">

  <!-- HEADER -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 style="margin: 0; font-size: 28px; font-weight: 700; color: var(--text-primary) !important;">
        Pham Quang Lam <span style="font-size: 16px; color: var(--text-muted) !important; font-weight: normal;">(범광람)</span>
      </h1>
      <p style="margin: 6px 0 14px 0; font-size: 15px; line-height: 1.5; color: var(--text-secondary) !important;">
        Undergraduate Student · Division of Computer Engineering<br>
        <strong style="color: var(--text-primary) !important;">Hansung University</strong>, Seoul, South Korea
      </p>

      <!-- HÀNG NÚT ICON -->
      <div style="display: flex; gap: 8px; align-items: center;">
        <a href="mailto:26611301@hansung.ac.kr" class="social-icon-btn" title="Email"><i class="far fa-envelope"></i></a>
        <a href="https://scholar.google.com" target="_blank" class="social-icon-btn" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="https://github.com/lamkr86" target="_blank" class="social-icon-btn" title="GitHub"><i class="fab fa-github"></i></a>
        <a href="https://www.researchgate.net" target="_blank" class="social-icon-btn" style="font-size: 11px; font-weight: bold;" title="ResearchGate">RG</a>
        <a href="https://linkedin.com" target="_blank" class="social-icon-btn" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </div>

  <!-- GIỚI THIỆU -->
  <p style="font-size: 15px; line-height: 1.7; margin-bottom: 25px; color: var(--text-secondary) !important;">
    I am an undergraduate student in the Division of Computer Engineering at <strong style="color: var(--text-primary) !important;">Hansung University</strong>. My current study focuses on software engineering, web technologies, and artificial intelligence.
  </p>

  <!-- MỤC ABOUT BẢNG BO CONG -->
  <div class="section-heading">ABOUT</div>
  <table class="styled-card-table">
    <tr>
      <td>2024 – Present</td>
      <td>
        <strong style="font-size: 15px; color: var(--text-primary) !important;">Hansung University</strong><br>
        <span style="font-size: 14px; color: var(--text-secondary) !important;">Undergraduate Student, Division of Computer Engineering</span>
      </td>
    </tr>
  </table>

  <!-- MỤC PROJECTS & ACTIVITIES -->
  <div class="section-heading">PROJECTS & ACTIVITIES</div>
  <ul style="padding-left: 18px; margin: 0; line-height: 1.7; color: var(--text-primary) !important;">
    <li style="margin-bottom: 12px;">
      <strong style="color: var(--text-primary) !important;">Academic Personal Website</strong> <span style="color: var(--text-muted) !important; font-size: 13px;">(2026)</span><br>
      <span style="font-size: 14px; color: var(--text-secondary) !important;">Designed and deployed a minimal academic profile hosted on GitHub Pages.</span>
    </li>
    <li>
      <strong style="color: var(--text-primary) !important;">Computer Engineering Coursework</strong><br>
      <span style="font-size: 14px; color: var(--text-secondary) !important;">Developing software projects and core algorithms at Hansung University.</span>
    </li>
  </ul>

</div>
