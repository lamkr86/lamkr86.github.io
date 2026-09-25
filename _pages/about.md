<!-- Style dành cho các nút tròn -->
<style>
  .social-buttons {
    display: flex;
    gap: 10px;
    margin-top: 15px;
  }
  .btn-circle {
    width: 36px;
    height: 36px;
    border-radius: 50%;
    border: 1px solid #d0d7de;
    display: flex;
    align-items: center;
    justify-content: center;
    color: #57606a;
    text-decoration: none;
    font-size: 14px;
    font-weight: 500;
    transition: all 0.2s ease;
    background-color: #ffffff;
  }
  .btn-circle:hover {
    border-color: #0969da;
    color: #0969da;
    background-color: #f6f8fa;
  }
</style>

<!-- Danh sách các nút icons -->
<div class="social-buttons">
  <!-- 1. Email -->
  <a href="mailto:26611301@hansung.ac.kr" class="btn-circle" title="Email">
    <i class="far fa-envelope"></i>
  </a>

  <!-- 2. Google Scholar (Dành cho sinh viên/nghiên cứu) -->
  <a href="https://scholar.google.com" target="_blank" class="btn-circle" title="Google Scholar">
    <i class="fas fa-graduation-cap"></i>
  </a>

  <!-- 3. GitHub -->
  <a href="https://github.com/lamkr86" target="_blank" class="btn-circle" title="GitHub">
    <i class="fab fa-github"></i>
  </a>

  <!-- 4. ResearchGate (Chữ RG tròn) -->
  <a href="https://www.researchgate.net" target="_blank" class="btn-circle" title="ResearchGate" style="font-size: 11px; font-weight: bold;">
    RG
  </a>

  <!-- 5. LinkedIn -->
  <a href="https://linkedin.com" target="_blank" class="btn-circle" title="LinkedIn">
    <i class="fab fa-linkedin-in"></i>
  </a>
</div>
