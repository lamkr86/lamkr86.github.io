---
layout: single
author_profile: false
permalink: /
---

<style>
  /* Ghi đè triệt để mọi cài đặt Dark mode của trình duyệt/theme */
  html, body, .initial-content, .page, .page__content, article, div {
    background-color: #ffffff !important;
    color: #111827 !important;
  }

  /* Xóa biểu tượng mặt trăng / nút chuyển giao diện tối */
  .theme-toggle, button[title*="theme"], a[href*="theme"] {
    display: none !important;
  }

  /* Layout căn giữa chuẩn UX/UI Minimalist */
  .academic-container {
    max-width: 760px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    padding: 10px 5px;
  }

  .header-flex {
    display: flex;
    align-items: center;
    gap: 25px;
    margin-bottom: 25px;
    flex-wrap: wrap;
  }

  .avatar-img {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    object-fit: cover;
    border: 1px solid #e5e7eb;
  }

  /* Nút tròn tương tác cao */
  .social-icon-btn {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    border: 1px solid #d1d5db;
    background-color: #ffffff !important;
    color: #0969da !important;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-decoration: none !important;
    font-size: 14px;
    transition: all 0.2s ease;
  }

  .social-icon-btn:hover {
    background-color: #f3f4f6 !important;
    border-color: #0969da !important;
    transform: translateY(-2px);
  }

  .section-heading {
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 1.2px;
    text-transform: uppercase;
    color: #0969da !important;
    border-bottom: 2px solid #e5e7eb;
    padding-bottom: 6px;
    margin-top: 35px;
    margin-bottom: 16px;
  }
</style>

<div class="academic-container">

  <!-- HEADER -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 style="margin: 0; font-size: 28px; font-weight: 700; color: #111827 !important;">
        Pham Quang Lam <span style="font-size: 16px; color: #4b5563 !important; font-weight: normal;">(범광람)</span>
      </h1>
      <p style="margin: 6px 0 14px 0; font-size: 15px; color: #374151 !important; line-height: 1.5;">
        Undergraduate Student · Division of Computer Engineering<br>
        <strong style="color: #111827 !important;">Hansung University</strong>, Seoul, South Korea
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
  <p style="font-size: 15px; color: #111827 !important; line-height: 1.7; margin-bottom: 25px;">
    I am an undergraduate student in the Division of Computer Engineering at <strong style="color: #111827 !important;">Hansung University</strong>. My current study focuses on software engineering, web technologies, and artificial intelligence.
  </p>

  <!-- MỤC ABOUT -->
  <div class="section-heading">ABOUT</div>
  <table style="width: 100%; border-collapse: collapse;">
    <tr>
      <td style="width: 25%; color: #4b5563 !important; font-size: 14px; font-weight: 600; vertical-align: top; padding: 6px 0;">2024 – Present</td>
      <td style="padding: 6px 0;">
        <strong style="font-size: 15px; color: #111827 !important;">Hansung University</strong><br>
        <span style="color: #374151 !important; font-size: 14px;">Undergraduate Student, Division of Computer Engineering</span>
      </td>
    </tr>
  </table>

  <!-- MỤC PROJECTS -->
  <div class="section-heading">PROJECTS & ACTIVITIES</div>
  <ul style="padding-left: 18px; margin: 0; line-height: 1.7;">
    <li style="margin-bottom: 12px;">
      <strong style="color: #111827 !important;">Academic Personal Website</strong> <span style="color: #4b5563 !important; font-size: 13px;">(2026)</span><br>
      <span style="color: #374151 !important; font-size: 14px;">Designed and deployed a minimal academic profile hosted on GitHub Pages.</span>
    </li>
    <li>
      <strong style="color: #111827 !important;">Computer Engineering Coursework</strong><br>
      <span style="color: #374151 !important; font-size: 14px;">Developing software projects and core algorithms at Hansung University.</span>
    </li>
  </ul>

</div>
