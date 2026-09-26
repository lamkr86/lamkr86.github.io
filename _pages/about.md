---
layout: single
author_profile: false
permalink: /
---

<!-- NHẬP PHÔNG CHỮ INTER VÀ PLUS JAKARTA SANS -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Plus+Jakarta+Sans:wght@600;700;800&display=swap" rel="stylesheet">

<style>
  /* Cuộn mượt */
  html {
    scroll-behavior: smooth;
  }

  /* 1. ĐỊNH DẠNG MASTHEAD (ẨN MENU, NÚT THEME SÁT PHẢI, XÓA DÒNG KẺ) */
  .masthead {
    display: block !important;
    border-bottom: none !important;
    box-shadow: none !important;
    background: transparent !important;
    position: absolute !important;
    top: 10px !important;
    right: 20px !important;
    left: auto !important;
    width: auto !important;
    z-index: 1000 !important;
  }

  .masthead__inner-wrap {
    border-bottom: none !important;
    padding: 0 !important;
    max-width: 100% !important;
  }

  .site-title {
    display: none !important;
  }

  .masthead__menu-item {
    display: none !important;
  }

  .masthead__menu-item:last-child,
  .masthead__menu-item:has(i),
  .masthead__menu-item:has(.fa-cog),
  .masthead__menu-item:has(.fa-gear) {
    display: inline-block !important;
    float: right !important;
  }

  .masthead__menu {
    float: right !important;
    width: auto !important;
  }

  /* 2. ĐỊNH DẠNG FOOTER (CHỈ CĂN NÚT FOLLOW SÁT HẲN LỀ TRÁI MÀN HÌNH) */
  .page__footer,
  footer {
    background-color: transparent !important;
    background: none !important;
    border: none !important;
    box-shadow: none !important;
    padding: 15px 0 !important;
    margin-top: 30px !important;
    width: 100% !important;
  }

  .page__footer-follow {
    max-width: 100% !important;
    margin-left: 0 !important;
    margin-right: auto !important;
    padding-left: 2rem !important;
  }

  .page__footer-follow ul {
    margin: 0 !important;
    padding: 0 !important;
    display: flex !important;
    justify-content: flex-start !important;
    align-items: center !important;
    gap: 6px !important;
  }

  .page__footer-follow li,
  .page__footer-follow a {
    color: #64748b !important;
    font-size: 12px !important;
    font-weight: 600 !important;
    text-transform: uppercase !important;
    text-decoration: none !important;
  }

  .page__footer-follow a:hover {
    color: #0f172a !important;
  }

  .page__footer-copyright {
    display: none !important;
  }

  /* 3. TỐI ƯU DARK MODE CHUYÊN SÂU */
  html[data-theme="dark"] p,
  html[data-theme="dark"] li,
  html[data-theme="dark"] span,
  body.dark p,
  body.dark li,
  body.dark span {
    color: #c9d1d9 !important;
  }

  html[data-theme="dark"] strong,
  html[data-theme="dark"] b,
  body.dark strong,
  body.dark b {
    color: #ffffff !important;
  }

  html[data-theme="dark"] .academic-container td,
  body.dark td {
    border-color: rgba(255, 255, 255, 0.1) !important;
    color: #e1e4e8 !important;
  }

  html[data-theme="dark"] .page__footer-follow li,
  html[data-theme="dark"] .page__footer-follow a {
    color: #94a3b8 !important;
  }

  html[data-theme="dark"] .page__footer-follow a:hover {
    color: #ffffff !important;
  }

  /* 4. CẤU TRÚC CONTAINER & NỘI DUNG CHÍNH */
  .academic-container {
    max-width: 760px;
    margin: 0 auto;
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    -webkit-font-smoothing: antialiased;
  }

  .academic-container h1, 
  .academic-container .section-heading {
    font-family: 'Plus Jakarta Sans', 'Inter', sans-serif;
  }

  /* HEADER INFO */
  .header-flex {
    display: flex;
    align-items: center;
    gap: 28px;
    margin-bottom: 25px;
    flex-wrap: wrap;
  }

  /* THANH MENU NỘI BỘ (NẰM PHÍA DƯỚI ẢNH CÁ NHÂN) */
  .sub-nav {
    display: flex;
    gap: 24px;
    border-bottom: 1px solid rgba(0, 0, 0, 0.08);
    padding-bottom: 12px;
    margin-top: 10px;
    margin-bottom: 20px;
    flex-wrap: wrap;
  }

  .sub-nav a {
    text-decoration: none !important;
    font-size: 14.5px;
    font-weight: 500;
    color: #64748b !important;
    transition: color 0.2s ease;
  }

  .sub-nav a:hover {
    color: #0f172a !important;
  }

  /* CHUNG LIGHT MODE */
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

  .academic-container .avatar-img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 0 0 1px rgba(0, 0, 0, 0.08), 0 4px 12px rgba(0, 0, 0, 0.05);
  }

  /* SECTION HEADING & KHOẢNG BÙ TẠO DỐC CUỘN DỪNG LẠI TRƯỚC TIÊU ĐỀ */
  .academic-container .section-heading {
    font-size: 11px;
    font-weight: 700;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    color: #0f172a !important;
    border-bottom: 1px solid rgba(0, 0, 0, 0.08) !important;
    padding-bottom: 8px;
    margin-top: 40px;
    margin-bottom: 18px;
    scroll-margin-top: 30px; /* Chừa khoảng trống phía trên tiêu đề khi cuộn đến */
  }

  /* Bảng Thẻ */
  .academic-container .styled-card-table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0;
    border: 1px solid rgba(0, 0, 0, 0.08) !important;
    border-radius: 12px;
    overflow: hidden;
    margin-top: 12px;
    margin-bottom: 16px;
    background-color: rgba(255, 255, 255, 0.5) !important;
    box-shadow: 0 1px 2px rgba(0, 0, 0, 0.02), 0 4px 12px rgba(0, 0, 0, 0.03);
  }

  .academic-container .styled-card-table td {
    padding: 16px 20px;
    vertical-align: top;
  }

  .academic-container .styled-card-table td:first-child {
    width: 26%;
    font-size: 13.5px;
    font-weight: 600;
  }

  /* Button Mạng Xã Hội */
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

  /* CHỈNH THÊM CHO DARK MODE CHO CÁC THẺ CARD & SUB-NAV */
  html[data-theme="dark"] .sub-nav {
    border-bottom-color: rgba(255, 255, 255, 0.1);
  }

  html[data-theme="dark"] .sub-nav a {
    color: #94a3b8 !important;
  }

  html[data-theme="dark"] .sub-nav a:hover {
    color: #ffffff !important;
  }

  html[data-theme="dark"] .academic-container .txt-main,
  html.dark .academic-container .txt-main,
  body.dark .academic-container .txt-main,
  [data-theme="dark"] .academic-container .txt-main {
    color: #f8fafc !important;
  }

  html[data-theme="dark"] .academic-container .txt-sub,
  html.dark .academic-container .txt-sub,
  body.dark .academic-container .txt-sub,
  [data-theme="dark"] .academic-container .txt-sub {
    color: #cbd5e1 !important;
  }

  html[data-theme="dark"] .academic-container .section-heading {
    border-bottom-color: rgba(255, 255, 255, 0.1) !important;
    color: #f8fafc !important;
  }

  html[data-theme="dark"] .academic-container .styled-card-table {
    border-color: rgba(255, 255, 255, 0.1) !important;
    background-color: rgba(255, 255, 255, 0.03) !important;
  }

  html[data-theme="dark"] .academic-container .social-icon-btn {
    border-color: rgba(255, 255, 255, 0.15) !important;
    background-color: rgba(255, 255, 255, 0.05) !important;
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

  <!-- HEADER NỘI DUNG PHÍA TRÊN -->
  <div class="header-flex">
    <img src="/profile.jpg" alt="Pham Quang Lam" class="avatar-img">
    
    <div>
      <h1 class="txt-main" style="margin: 0; font-size: 28px; font-weight: 700; letter-spacing: -0.5px;">
        Pham Quang Lam <span class="txt-muted" style="font-size: 15px; font-weight: 400;">(팜광람)</span>
      </h1>
      <p class="txt-sub" style="margin: 6px 0 16px 0; font-size: 14px; line-height: 1.5; letter-spacing: -0.1px;">
        Master's Student · Division of Computer Engineering<br>
        <strong class="txt-main">Hansung University</strong>, Seoul, South Korea
      </p>

      <div style="display: flex; gap: 8px; align-items: center; flex-wrap: wrap;">
        <a href="mailto:lamkr86@gmail.com" class="social-icon-btn" title="Email"><i class="far fa-envelope"></i></a>
        <a href="https://scholar.google.com/citations?user=IJwe5lUAAAAJ&hl=vi&authuser=3" target="_blank" class="social-icon-btn" title="Google Scholar"><i class="fas fa-graduation-cap"></i></a>
        <a href="https://github.com/lamkr86" target="_blank" class="social-icon-btn" title="GitHub"><i class="fab fa-github"></i></a>
        <a href="https://www.researchgate.net/profile/Pham-Lam-16?ev=prf_overview" target="_blank" class="social-icon-btn" style="font-size: 11px; font-weight: 700;" title="ResearchGate"><span>RG</span></a>
        <a href="https://www.linkedin.com/in/quang-lam-pham-19654743a/" target="_blank" class="social-icon-btn" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
      </div>
    </div>
  </div>

  <!-- THANH ĐIỀU HƯỚNG NẰM PHÍA DƯỚI ẢNH -->
  <div class="sub-nav">
    <a href="#about">About</a>
    <a href="#experience">Experience & Projects</a>
    <a href="#skills">Skills & Certifications</a>
    <a href="#activities">Activities</a>
  </div>

  <!-- PHẦN GIỚI THIỆU NGẮN (XUẤT HIỆN NGAY DƯỚI THANH MENU) -->
  <p class="txt-sub" style="font-size: 13.5px; line-height: 1.6; margin-bottom: 25px; letter-spacing: -0.1px;">
    I am a Master's student in Computer Engineering at <strong class="txt-main">Hansung University</strong>. My background encompasses database management, data visualization, web development, and medical data optimization. I am passionate about applying data-driven approaches and modern web technologies to solve real-world engineering problems.
  </p>

  <!-- 1. MỤC ABOUT (Bao gồm bảng Bằng cấp/Học vấn) -->
  <div id="about" class="section-heading">ABOUT</div>
  <table class="styled-card-table">
    <tr>
      <td class="txt-sub">2026 – Present</td>
      <td>
        <strong class="txt-main" style="font-size: 13.5px;">Hansung University Graduate School</strong><br>
        <span class="txt-sub" style="font-size: 13px;">Master's Degree in Computer Engineering</span>
      </td>
    </tr>
    <tr>
      <td class="txt-sub">2023 – 2025</td>
      <td>
        <strong class="txt-main" style="font-size: 13.5px;">Kwangwoon University</strong><br>
        <span class="txt-sub" style="font-size: 13px;">B.S. in Computer Information Engineering</span>
      </td>
    </tr>
    <tr>
      <td class="txt-sub">2019 – 2021</td>
      <td>
        <strong class="txt-main" style="font-size: 13.5px;">Sahmyook Health University</strong><br>
        <span class="txt-sub" style="font-size: 13px;">Medical Information Department</span>
      </td>
    </tr>
  </table>

  <!-- 2. MỤC EXPERIENCE & PROJECTS -->
  <div id="experience" class="section-heading">EXPERIENCE & PROJECTS</div>
  
  <p class="txt-main" style="font-weight: 600; font-size: 13.5px; margin-bottom: 8px;">Research & Project Experience</p>
  <ul style="padding-left: 18px; margin-bottom: 18px; line-height: 1.6; font-size: 13.5px;" class="txt-sub">
    <li style="margin-bottom: 8px;">
      <strong class="txt-main">Database & Data Visualization Project:</strong>
      Large-scale data analysis & visualization system development; research on database optimization and search speed enhancement.
    </li>
    <li>
      <strong class="txt-main">Web System Development Project:</strong>
      E-commerce website development for shoe sales, data processing optimization, and UX improvement driven by data analytics.
    </li>
  </ul>

  <p class="txt-main" style="font-weight: 600; font-size: 13.5px; margin-bottom: 8px;">Practical Experience</p>
  <ul style="padding-left: 18px; margin-bottom: 20px; line-height: 1.6; font-size: 13.5px;" class="txt-sub">
    <li style="margin-bottom: 6px;">
      <strong class="txt-main">Language Center Office, Sahmyook Health University:</strong> Vietnamese student info management & data systemization.
    </li>
    <li style="margin-bottom: 6px;">
      <strong class="txt-main">Sahmyook Medical Center:</strong> Hands-on experience in customer info management, medical data security, and optimization processes.
    </li>
    <li>
      <strong class="txt-main">Silver Senior Nursing Home:</strong> Patient data entry and information system maintenance.
    </li>
  </ul>

  <!-- 3. MỤC SKILLS & CERTIFICATIONS -->
  <div id="skills" class="section-heading">SKILLS & CERTIFICATIONS</div>
  <table class="styled-card-table">
    <tr>
      <td class="txt-sub">Programming</td>
      <td><span class="txt-main" style="font-size: 13.5px;">C, C++, JavaScript, PHP</span></td>
    </tr>
    <tr>
      <td class="txt-sub">Database & Network</td>
      <td><span class="txt-main" style="font-size: 13.5px;">SQL, Database Optimization, Network Traffic Analysis</span></td>
    </tr>
    <tr>
      <td class="txt-sub">Certifications</td>
      <td>
        <span class="txt-main" style="font-size: 13.5px;">• ITQ Information Technology Qualification (Grade A)</span><br>
        <span class="txt-main" style="font-size: 13.5px;">• TOPIK Level 5</span><br>
        <span class="txt-main" style="font-size: 13.5px;">• Social Integration Program Level 5</span>
      </td>
    </tr>
  </table>

  <!-- 4. MỤC ACTIVITIES -->
  <div id="activities" class="section-heading">ACTIVITIES</div>
  <p class="txt-main" style="font-weight: 600; font-size: 13.5px; margin-bottom: 8px;">Volunteer Experience</p>
  <ul style="padding-left: 18px; margin: 0; line-height: 1.6; font-size: 13.5px;" class="txt-sub">
    <li style="margin-bottom: 8px;">
      <strong class="txt-main">Sahmyook Medical Center Daycare Center Volunteer:</strong> Medical system data management and social contribution.
    </li>
    <li>
      <strong class="txt-main">Bapfor Sharing Movement Volunteer:</strong> Data-driven operation management and community service participation.
    </li>
  </ul>

</div>

<!-- SCRIPT XỬ LÝ CUỘN MƯỢT VÀ DỪNG NGAY TRƯỚC TIÊU ĐỀ -->
<script>
  document.querySelectorAll('.sub-nav a').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      const targetId = this.getAttribute('href').substring(1);
      const targetElement = document.getElementById(targetId);
      
      if (targetElement) {
        // Khoảng chừa phía trên tiêu đề (tăng/giảm số này để chỉnh vị trí dừng)
        const offset = 25; 
        const elementPosition = targetElement.getBoundingClientRect().top;
        const offsetPosition = elementPosition + window.pageYOffset - offset;

        window.scrollTo({
          top: offsetPosition,
          behavior: 'smooth'
        });
      }
    });
  });
</script>
