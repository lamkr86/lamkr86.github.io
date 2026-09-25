---
layout: single
author_profile: false
permalink: /
---

<style>
  /* Ghi đè nền sáng dứt điểm */
  html, body, .initial-content, .page, .page__content, article, div {
    background-color: #ffffff !important;
    color: #111827 !important;
  }

  .academic-container {
    max-width: 780px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
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
    border: 1px solid #e5e7eb;
  }

  .social-icon-btn {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    border: 1px solid #e5e7eb;
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
    background-color: #f8fafc !important;
    border-color: #0969da !important;
  }

  /* Tiêu đề mục nhã nhặn, khoảng cách rộng rãi */
  .section-heading {
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 1.2px;
    text-transform: uppercase;
    color: #0969da !important;
    border-bottom: 1px solid #e2e8f0;
    padding-bottom: 8px;
    margin-top: 40px;
    margin-bottom: 20px;
  }

  /* BẢNG TỐI GIẢN - BỎ KHUNG ĐỘNG, CHỈ DÙNG ĐƯỜNG KẺ MỀM MẠI */
  .minimal-table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 10px;
  }

  .minimal-table td {
    padding: 16px 12px; /* Tạo khoảng trống lề trên/dưới và hai bên */
    border-bottom: 1px solid #f1f5f9; /* Đường kẻ xám siêu nhạt, mềm mại */
    vertical-align: top;
  }

  .minimal-table tr:last-child td {
    border-bottom: none; /* Bỏ đường kẻ hàng cuối */
  }

  .timeline-year {
    width: 25%;
    color: #64748b !important;
    font-size: 14px;
    font-weight: 500;
    padding-left: 0 !important;
  }
</style>

<div class="academic-container">

  <!-- HEADER -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 style="margin: 0; font-size: 28px; font-weight: 700; color: #0f172a !important;">
        Pham Quang Lam <span style="font-size: 16px; color: #64748b !important; font-weight: normal;">(범광람)</span>
      </h1>
      <p style="margin: 6px 0 14px 0; font-size: 15px; color: #334155 !important; line-height: 1.5;">
        Undergraduate Student · Division of Computer Engineering<br>
        <strong style="color: #0f172a !important;">Hansung University</strong>, Seoul, South Korea
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

  <!-- GIỚI THIỆU BẢN THÂN -->
  <p style="font-size: 15px; color: #334155 !important; line-height: 1.7; margin-bottom: 25px;">
    I am an undergraduate student in the Division of Computer Engineering at <strong style="color: #0f172a !important;">Hansung University</strong>. My current study focuses on software engineering, web technologies, and artificial intelligence.
  </p>

  <!-- MỤC ABOUT -->
  <div class="section-heading">ABOUT</div>
  <table class="minimal-table">
    <tr>
      <td class="timeline-year">2024 – Present</td>
      <td>
        <strong style="font-size: 15px; color: #0f172a !important;">Hansung University</strong><br>
        <span style="color: #475569 !important; font-size: 14px; display: inline-block; margin-top: 4px;">Undergraduate Student, Division of Computer Engineering</span>
      </td>
    </tr>
  </table>

  <!-- MỤC PROJECTS & ACTIVITIES -->
  <div class="section-heading">PROJECTS & ACTIVITIES</div>
  <ul style="padding-left: 18px; margin: 0; line-height: 1.8;">
    <li style="margin-bottom: 14px;">
      <strong style="color: #0f172a !important;">Academic Personal Website</strong> <span style="color: #64748b !important; font-size: 13px;">(2026)</span><br>
      <span style="color: #475569 !important; font-size: 14px;">Designed and deployed a minimal academic profile hosted on GitHub Pages.</span>
    </li>
    <li>
      <strong style="color: #0f172a !important;">Computer Engineering Coursework</strong><br>
      <span style="color: #475569 !important; font-size: 14px;">Developing software projects and core algorithms at Hansung University.</span>
    </li>
  </ul>

</div>
