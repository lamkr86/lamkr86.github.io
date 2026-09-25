---
layout: single
author_profile: false
permalink: /
---

<style>
  /* 1. ĐỊNH NGHĨA BIẾN MÀU ĐỘNG (SYSTEM & THEME ADAPTIVE) */
  :root {
    --bg-card: #ffffff;
    --text-primary: #111827;
    --text-secondary: #4b5563;
    --text-muted: #6b7280;
    --accent-color: #0969da;
    --border-color: #e5e7eb;
    --btn-bg: #ffffff;
    --btn-border: #d1d5db;
    --btn-hover-bg: #f3f4f6;
  }

  /* Tự động kích hoạt bộ màu tối khi bật Dark Mode */
  [data-theme="dark"], body.dark, .dark {
    --bg-card: #1e293b;
    --text-primary: #f8fafc;
    --text-secondary: #cbd5e1;
    --text-muted: #94a3b8;
    --accent-color: #38bdf8;
    --border-color: #334155;
    --btn-bg: #0f172a;
    --btn-border: #334155;
    --btn-hover-bg: #1e293b;
  }

  /* 2. CẤU TRÚC LAYOUT VÀ TYPOGRAPHY TỐI GIẢN */
  .academic-container {
    max-width: 780px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    color: var(--text-primary);
    line-height: 1.6;
  }

  .header-flex {
    display: flex;
    align-items: center;
    gap: 28px;
    margin-bottom: 30px;
    flex-wrap: wrap;
  }

  .avatar-img {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid var(--border-color);
  }

  .profile-title {
    margin: 0;
    font-size: 28px;
    font-weight: 700;
    letter-spacing: -0.3px;
    color: var(--text-primary);
  }

  .profile-subtitle {
    margin: 6px 0 14px 0;
    font-size: 15px;
    color: var(--text-secondary);
  }

  /* Nút bấm tương tác cao */
  .social-buttons-group {
    display: flex;
    gap: 8px;
    align-items: center;
  }

  .social-icon-btn {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    border: 1px solid var(--btn-border);
    background-color: var(--btn-bg);
    color: var(--accent-color) !important;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-decoration: none !important;
    font-size: 14px;
    transition: all 0.2s ease;
  }

  .social-icon-btn:hover {
    background-color: var(--btn-hover-bg);
    transform: translateY(-2px);
    border-color: var(--accent-color);
  }

  /* Tiêu đề mục tối giản & đường phân cách */
  .section-heading {
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 1.2px;
    text-transform: uppercase;
    color: var(--accent-color);
    border-bottom: 2px solid var(--border-color);
    padding-bottom: 6px;
    margin-top: 36px;
    margin-bottom: 16px;
  }

  .timeline-table {
    width: 100%;
    border-collapse: collapse;
  }

  .timeline-table td {
    padding: 8px 0;
    vertical-align: top;
  }

  .timeline-period {
    width: 25%;
    color: var(--text-muted);
    font-size: 14px;
    font-weight: 500;
  }

  .content-list {
    padding-left: 18px;
    margin: 0;
    color: var(--text-primary);
  }

  .content-list li {
    margin-bottom: 12px;
  }

  .sub-text {
    color: var(--text-secondary);
    font-size: 14px;
  }
</style>

<div class="academic-container">

  <!-- HEADER GỒM AVATAR VÀ THÔNG TIN CHÍNH -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 class="profile-title">
        Pham Quang Lam <span style="font-size: 16px; color: var(--text-muted); font-weight: normal;">(범광람)</span>
      </h1>
      <p class="profile-subtitle">
        Undergraduate Student · Division of Computer Engineering<br>
        <strong style="color: var(--text-primary);">Hansung University</strong>, Seoul, South Korea
      </p>
      
      <!-- DÀN NÚT ICON BIẾN ĐỔI THEO CHẾ ĐỘ -->
      <div class="social-buttons-group">
        <a href="mailto:26611301@hansung.ac.kr" class="social-icon-btn" title="Email"><i class="far fa-envelope"></i></a>
        <a href="https://scholar.google.com" target="_blank" class="social-icon-btn" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="https://github.com/lamkr86" target="_blank" class="social-icon-btn" title="GitHub"><i class="fab fa-github"></i></a>
        <a href="https://www.researchgate.net" target="_blank" class="social-icon-btn" style="font-size: 11px; font-weight: bold;" title="ResearchGate">RG</a>
        <a href="https://linkedin.com" target="_blank" class="social-icon-btn" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </div>

  <!-- GIỚI THIỆU BẢN THÂN -->
  <p style="font-size: 15px; color: var(--text-secondary); margin-bottom: 25px;">
    I am an undergraduate student in the Division of Computer Engineering at <strong style="color: var(--text-primary);">Hansung University</strong>. My current study focuses on software engineering, web technologies, and artificial intelligence.
  </p>

  <!-- MỤC 1: QUÁ TRÌNH HỌC TẬP -->
  <div class="section-heading">ABOUT</div>
  <table class="timeline-table">
    <tr>
      <td class="timeline-period">2024 – Present</td>
      <td>
        <strong style="font-size: 15px; color: var(--text-primary);">Hansung University</strong><br>
        <span class="sub-text">Undergraduate Student, Division of Computer Engineering</span>
      </td>
    </tr>
  </table>

  <!-- MỤC 2: DỰ ÁN VÀ HOẠT ĐỘNG -->
  <div class="section-heading">PROJECTS & ACTIVITIES</div>
  <ul class="content-list">
    <li>
      <strong style="color: var(--text-primary);">Academic Personal Website</strong> <span style="color: var(--text-muted); font-size: 13px;">(2026)</span><br>
      <span class="sub-text">Designed and deployed a minimal academic profile hosted on GitHub Pages.</span>
    </li>
    <li>
      <strong style="color: var(--text-primary);">Computer Engineering Coursework</strong><br>
      <span class="sub-text">Developing software projects and core algorithms at Hansung University.</span>
    </li>
  </ul>

</div>
