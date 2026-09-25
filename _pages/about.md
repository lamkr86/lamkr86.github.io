---
layout: single
author_profile: false
permalink: /
---

<style>
  /* ÉP TẤT CẢ VỀ MÀU ĐEN VÀ TĂNG ĐỘ TƯƠNG PHẢN RÕ RÀNG */
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

  .avatar-img {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    object-fit: cover;
    border: 2px solid #000000 !important;
  }

  /* NÚT BẤM MÀU ĐEN */
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

  .social-icon-btn i, .social-icon-btn {
    color: #000000 !important;
  }

  .social-icon-btn:hover {
    background-color: #000000 !important;
    color: #ffffff !important;
  }
  
  .social-icon-btn:hover i {
    color: #ffffff !important;
  }

  /* TIÊU ĐỀ MỤC VÀ ĐƯỜNG KẺ MÀU ĐEN */
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

  /* BẢNG BO CONG VỚI KHUNG VIỀN ĐEN */
  .styled-card-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    border: 1.5px solid #000000 !important;
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
    border-right: 1.5px solid #000000 !important;
    color: #374151 !important; /* Chữ phụ màu xám đậm cực rõ */
    font-size: 14px;
    font-weight: 600;
  }

  /* KHÓA MÀU CHỮ PHỤ MÀU XÁM ĐẬM HIỂN THỊ CỰC KỲ RÕ NÉT */
  .text-sub-dark {
    color: #374151 !important;
  }
  
  .text-black-main {
    color: #000000 !important;
  }
</style>

<div class="academic-container">

  <!-- HEADER -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 class="text-black-main" style="margin: 0; font-size: 28px; font-weight: 700;">
        Pham Quang Lam <span class="text-sub-dark" style="font-size: 16px; font-weight: normal;">(범광람)</span>
      </h1>
      <p class="text-sub-dark" style="margin: 6px 0 14px 0; font-size: 15px; line-height: 1.5;">
        Undergraduate Student · Division of Computer Engineering<br>
        <strong class="text-black-main">Hansung University</strong>, Seoul, South Korea
      </p>

      <!-- NÚT ICON MÀU ĐEN -->
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
  <p class="text-sub-dark" style="font-size: 15px; line-height: 1.7; margin-bottom: 25px;">
    I am an undergraduate student in the Division of Computer Engineering at <strong class="text-black-main">Hansung University</strong>. My current study focuses on software engineering, web technologies, and artificial intelligence.
  </p>

  <!-- MỤC ABOUT KHUNG VIỀN ĐEN BO CONG -->
  <div class="section-heading">ABOUT</div>
  <table class="styled-card-table">
    <tr>
      <td class="text-sub-dark">2024 – Present</td>
      <td>
        <strong class="text-black-main" style="font-size: 15px;">Hansung University</strong><br>
        <span class="text-sub-dark" style="font-size: 14px;">Undergraduate Student, Division of Computer Engineering</span>
      </td>
    </tr>
  </table>

  <!-- MỤC PROJECTS & ACTIVITIES -->
  <div class="section-heading">PROJECTS & ACTIVITIES</div>
  <ul style="padding-left: 18px; margin: 0; line-height: 1.7;">
    <li style="margin-bottom: 12px;">
      <strong class="text-black-main">Academic Personal Website</strong> <span class="text-sub-dark" style="font-size: 13px;">(2026)</span><br>
      <span class="text-sub-dark" style="font-size: 14px;">Designed and deployed a minimal academic profile hosted on GitHub Pages.</span>
    </li>
    <li>
      <strong class="text-black-main">Computer Engineering Coursework</strong><br>
      <span class="text-sub-dark" style="font-size: 14px;">Developing software projects and core algorithms at Hansung University.</span>
    </li>
  </ul>

</div>
