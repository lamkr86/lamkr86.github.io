---
layout: single
author_profile: false
permalink: /
---

<style>
  /* 1. KHỞI TẠO BỘ MÀU TƯƠNG PHẢN ĐỘNG (DYNAMIC CONTRAST) */
  :root {
    --color-main: #000000;         /* Chữ chính, tiêu đề, đường kẻ, viền */
    --color-sub: #374151;          /* Chữ phụ xám đậm cực kỳ rõ trên nền sáng */
    --color-muted: #6b7280;        /* Ngày tháng / chữ phụ mờ */
    --border-color: #000000;       /* Đường viền khung & viền nút */
    --btn-bg: #ffffff;             /* Nền nút bấm */
    --btn-hover-bg: #000000;       /* Nền nút khi di chuột */
    --btn-hover-text: #ffffff;     /* Chữ nút khi di chuột */
  }

  /* 2. TỰ ĐỘNG CHUYỂN SANG TRẮNG KHI Ở GIAO DIỆN TỐI (DARK MODE) */
  @media (prefers-color-scheme: dark) {
    :root {
      --color-main: #ffffff;
      --color-sub: #e5e7eb;        /* Chữ phụ xám sáng rõ nét trên nền tối */
      --color-muted: #9ca3af;
      --border-color: #ffffff;
      --btn-bg: transparent;
      --btn-hover-bg: #ffffff;
      --btn-hover-text: #000000;
    }
  }

  /* Tương thích tuyệt đối với nút bấm đổi Theme của Jekyll */
  [data-theme="dark"], body.dark, .dark, html.dark {
    --color-main: #ffffff !important;
    --color-sub: #e5e7eb !important;
    --color-muted: #9ca3af !important;
    --border-color: #ffffff !important;
    --btn-bg: transparent !important;
    --btn-hover-bg: #ffffff !important;
    --btn-hover-text: #000000 !important;
  }

  [data-theme="light"], body.light, .light, html.light {
    --color-main: #000000 !important;
    --color-sub: #374151 !important;
    --color-muted: #6b7280 !important;
    --border-color: #000000 !important;
    --btn-bg: #ffffff !important;
    --btn-hover-bg: #000000 !important;
    --btn-hover-text: #ffffff !important;
  }

  /* 3. LAYOUT & ĐỊNH DẠNG KHUNG/NÚT */
  .academic-container {
    max-width: 760px;
    margin: 0 auto;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  }

  .text-main { color: var(--color-main) !important; }
  .text-sub { color: var(--color-sub) !important; }
  .text-muted { color: var(--color-muted) !important; }

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
    border: 2px solid var(--border-color) !important;
  }

  /* BUTTON BO TRÒN - ĐẢO MÀU TINH TẾ KHI HOVER */
  .social-icon-btn {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    border: 1.5px solid var(--border-color) !important;
    background-color: var(--btn-bg) !important;
    color: var(--color-main) !important;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-decoration: none !important;
    font-size: 14px;
    transition: all 0.25s ease;
  }

  .social-icon-btn i, .social-icon-btn span {
    color: inherit !important;
  }

  .social-icon-btn:hover {
    background-color: var(--btn-hover-bg) !important;
    color: var(--btn-hover-text) !important;
    border-color: var(--border-color) !important;
  }

  /* TIÊU ĐỀ MỤC & ĐƯỜNG KẺ PHÂN CÁCH */
  .section-heading {
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 1.2px;
    text-transform: uppercase;
    color: var(--color-main) !important;
    border-bottom: 2px solid var(--border-color) !important;
    padding-bottom: 6px;
    margin-top: 35px;
    margin-bottom: 16px;
  }

  /* KHUNG BẢNG BO CONG VỚI KHOẢNG ĐỆM RỘNG */
  .styled-card-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    border: 1.5px solid var(--border-color) !important;
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
    border-right: 1.5px solid var(--border-color) !important;
    font-size: 14px;
    font-weight: 600;
  }
</style>

<div class="academic-container">

  <!-- HEADER -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 class="text-main" style="margin: 0; font-size: 28px; font-weight: 700;">
        Pham Quang Lam <span class="text-muted" style="font-size: 16px; font-weight: normal;">(범광람)</span>
      </h1>
      <p class="text-sub" style="margin: 6px 0 14px 0; font-size: 15px; line-height: 1.5;">
        Undergraduate Student · Division of Computer Engineering<br>
        <strong class="text-main">Hansung University</strong>, Seoul, South Korea
      </p>

      <!-- DÀN NÚT ICON -->
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
  <p class="text-sub" style="font-size: 15px; line-height: 1.7; margin-bottom: 25px;">
    I am an undergraduate student in the Division of Computer Engineering at <strong class="text-main">Hansung University</strong>. My current study focuses on software engineering, web technologies, and artificial intelligence.
  </p>

  <!-- MỤC ABOUT KHUNG VIỀN BO CONG -->
  <div class="section-heading">ABOUT</div>
  <table class="styled-card-table">
    <tr>
      <td class="text-sub">2024 – Present</td>
      <td>
        <strong class="text-main" style="font-size: 15px;">Hansung University</strong><br>
        <span class="text-sub" style="font-size: 14px;">Undergraduate Student, Division of Computer Engineering</span>
      </td>
    </tr>
  </table>

  <!-- MỤC PROJECTS & ACTIVITIES -->
  <div class="section-heading">PROJECTS & ACTIVITIES</div>
  <ul style="padding-left: 18px; margin: 0; line-height: 1.7;">
    <li style="margin-bottom: 12px;">
      <strong class="text-main">Academic Personal Website</strong> <span class="text-muted" style="font-size: 13px;">(2026)</span><br>
      <span class="text-sub" style="font-size: 14px;">Designed and deployed a minimal academic profile hosted on GitHub Pages.</span>
    </li>
    <li>
      <strong class="text-main">Computer Engineering Coursework</strong><br>
      <span class="text-sub" style="font-size: 14px;">Developing software projects and core algorithms at Hansung University.</span>
    </li>
  </ul>

</div>
