---
layout: single
author_profile: false
permalink: /
---

<style>
  /* =========================================================
     1. ÉP BỘ MÀU TƯƠNG PHẢN TUYỆT ĐỐI CHO CẢ LIGHT VÀ DARK MODE
     ========================================================= */
  
  /* Cấu hình mặc định (Giao diện sáng - Light Mode) */
  :root {
    --main-text: #000000 !important;
    --sub-text: #374151 !important;
    --muted-text: #4b5563 !important;
    --border-line: #000000 !important;
    --btn-bg: #ffffff !important;
    --btn-text: #000000 !important;
  }

  /* Tự động chuyển đổi khi bật GIAO DIỆN TỐI (Dark Mode) */
  @media (prefers-color-scheme: dark), [data-theme="dark"], body.dark, .dark, html.dark {
    :root {
      --main-text: #ffffff !important;      /* Chữ chính: Trắng tinh */
      --sub-text: #e2e8f0 !important;       /* Chữ phụ: Xám trắng sáng rõ */
      --muted-text: #cbd5e1 !important;     /* Ngày tháng: Sáng nổi bật */
      --border-line: #ffffff !important;    /* Viền khung & Đường kẻ: Trắng */
      --btn-bg: transparent !important;      /* Nền nút: Trong suốt */
      --btn-text: #ffffff !important;      /* Icon nút: Trắng */
    }

    /* Ép tất cả thẻ văn bản của Theme Jekyll phải nhận màu sáng */
    .initial-content, .page, .page__content, article, p, span, li, td, h1, h2, h3 {
      color: var(--main-text);
      opacity: 1 !important; /* Xóa bỏ hiệu ứng làm mờ chữ của theme */
    }
  }

  /* =========================================================
     2. ĐỊNH DẠNG BỐ CỤC VÀ TẮT TÀNG HÌNH CHỮ
     ========================================================= */
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
    border: 2px solid var(--border-line) !important;
  }

  /* NÚT BẤM SOCIAL TƯƠNG PHẢN CHUẨN */
  .social-icon-btn {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    border: 1.5px solid var(--border-line) !important;
    background-color: var(--btn-bg) !important;
    color: var(--btn-text) !important;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    text-decoration: none !important;
    font-size: 14px;
    transition: all 0.25s ease;
  }

  .social-icon-btn i, .social-icon-btn span {
    color: var(--btn-text) !important;
  }

  .social-icon-btn:hover {
    filter: invert(1); /* Đảo ngược màu tinh tế khi di chuột */
  }

  /* TIÊU ĐỀ MỤC & ĐƯỜNG KẺ PHÂN CÁCH */
  .section-heading {
    font-size: 13px;
    font-weight: 700;
    letter-spacing: 1.2px;
    text-transform: uppercase;
    color: var(--main-text) !important;
    border-bottom: 2px solid var(--border-line) !important;
    padding-bottom: 6px;
    margin-top: 35px;
    margin-bottom: 16px;
  }

  /* KHUNG BẢNG BO CONG VỚI KHOẢNG ĐỆM RỘNG */
  .styled-card-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    border: 1.5px solid var(--border-line) !important;
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
    border-right: 1.5px solid var(--border-line) !important;
    font-size: 14px;
    font-weight: 600;
  }

  /* LỚP MÀU CHỮ ÉP ƯU TIÊN */
  .txt-main { color: var(--main-text) !important; }
  .txt-sub  { color: var(--sub-text) !important; }
  .txt-muted{ color: var(--muted-text) !important; }
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
