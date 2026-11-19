<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CÔNG TY CỔ PHẦN NCOPA | Thiết Kế - Thi Công Xây Dựng &amp; Giám Sát Đà Nẵng - ncopa.com</title>
  <meta name="description" content="CÔNG TY CỔ PHẦN NCOPA (ncopa.com) - Chuyên Thiết kế kiến trúc, Thi công phần thô, Thi công hoàn thiện, Nội thất và Tư vấn giám sát công trình tại Đà Nẵng. Hotline: 0908.470.011.">
  <meta name="keywords" content="NCOPA, Công ty cổ phần NCOPA, ncopa.com, xây dựng Đà Nẵng, thiết kế thi công Đà Nẵng, thi công phần thô, thi công hoàn thiện, tư vấn giám sát">

  <!-- Thumbnail logo khi chia sẻ liên kết trang web (Open Graph & Twitter Card) -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="CÔNG TY CỔ PHẦN NCOPA">
  <meta property="og:title" content="CÔNG TY CỔ PHẦN NCOPA - Thiết Kế &amp; Thi Công Xây Dựng Đà Nẵng">
  <meta property="og:description" content="Chuyên Thiết kế kiến trúc, Thi công xây dựng trọn gói, Công trình cao tầng, Tầng hầm &amp; Tư vấn giám sát tại Đà Nẵng. Hotline: 0908.470.011">
  <meta property="og:url" content="https://ncopa.com">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF&sz=w1200">
  <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF&sz=w1200">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="CÔNG TY CỔ PHẦN NCOPA - ncopa.com">
  <meta name="twitter:description" content="Thiết kế - Thi công xây dựng &amp; Giám sát công trình tại Đà Nẵng. Địa chỉ: 24 An Hải 8, Phường An Hải, TP Đà Nẵng.">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF&sz=w1200">
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF&sz=w256">
  <link rel="apple-touch-icon" href="https://drive.google.com/thumbnail?id=1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF&sz=w256">

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              primary: '#0D3B66',
              dark: '#082744',
              light: '#16558F',
              accent: '#D96B16',
              accentHover: '#BF5A0D',
              soft: '#F4F7FA',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* ==========================================================================
       FLATSOME-STYLE CORE LAYOUT & ANTI-OVERFLOW RULES
       Chiều ngang máy tính 95%, tuyệt đối không tràn viền hay lệch phải
       ========================================================================== */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
      -webkit-font-smoothing: antialiased;
    }

    /* Container 95% trên máy tính, 100% có padding cân đối trên di động */
    .ncopa-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 14px;
      padding-right: 14px;
    }

    @media (min-width: 768px) {
      .ncopa-container {
        width: 95%;
        max-width: 95%;
        padding-left: 12px;
        padding-right: 12px;
      }
    }

    @media (min-width: 1024px) {
      .ncopa-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu điều hướng & Danh mục viết liền không xuống dòng trong tên danh mục */
    .nav-item-nowrap {
      white-space: nowrap;
    }

    /* Dropdown Flatsome mượt mà trên Desktop */
    .has-dropdown {
      position: relative;
    }
    .has-dropdown .dropdown-menu {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }
    .has-dropdown:hover .dropdown-menu {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* ==========================================================================
       BANNER SLIDER CHUYÊN NGHIỆP - 2 SLIDE KÍCH THƯỚC BẰNG NHAU
       Chữ & hình nằm trọn trong vùng an toàn, cách xa viền, không mất chữ
       ========================================================================== */
    .hero-slider-viewport {
      position: relative;
      width: 100%;
      overflow: hidden;
      background-color: #082744;
    }

    .hero-slides-track {
      display: flex;
      width: 100%;
      transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
    }

    .hero-slide-item {
      min-width: 100%;
      width: 100%;
      flex-shrink: 0;
      position: relative;
      display: flex;
      align-items: center;
      /* Chiều cao đồng nhất cho cả 2 slide trên từng thiết bị */
      height: 410px;
    }

    @media (min-width: 640px) {
      .hero-slide-item {
        height: 440px;
      }
    }

    @media (min-width: 1024px) {
      .hero-slide-item {
        height: 500px;
      }
    }

    @media (min-width: 1280px) {
      .hero-slide-item {
        height: 540px;
      }
    }

    /* Nút lọc danh mục tinh gọn, không ngắt dòng trong tên danh mục */
    .cat-tab-btn {
      white-space: nowrap;
      transition: all 0.2s ease;
    }
    .cat-tab-btn.active {
      background-color: #0D3B66;
      color: #FFFFFF;
      border-color: #0D3B66;
    }

    /* Đường gạch chân tiêu đề phong cách Flatsome */
    .section-title-bar {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .section-title-bar::after {
      content: '';
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background-color: #D96B16;
      border-radius: 999px;
    }

    /* Hiệu ứng card nhẹ nhàng, dễ dựng lại trên UX Builder */
    .flatsome-card {
      transition: transform 0.25s ease, box-shadow 0.25s ease;
    }
    .flatsome-card:hover {
      transform: translateY(-4px);
      box-shadow: 0 12px 26px -8px rgba(13, 59, 102, 0.16);
    }
    .flatsome-card img {
      transition: transform 0.4s ease;
    }
    .flatsome-card:hover img {
      transform: scale(1.04);
    }

    /* Hiệu ứng nổi bật nút liên hệ nổi */
    @keyframes softPulse {
      0% { box-shadow: 0 0 0 0 rgba(217, 107, 22, 0.55); }
      70% { box-shadow: 0 0 0 12px rgba(217, 107, 22, 0); }
      100% { box-shadow: 0 0 0 0 rgba(217, 107, 22, 0); }
    }
    .pulse-hotline {
      animation: softPulse 2s infinite;
    }
  </style>
</head>
<body class="bg-white text-slate-800">

  <!-- =========================================================================
       FLATSOME SECTION 1: TOP BAR (Thông tin liên hệ gọn gàng)
       ========================================================================= -->
  <div class="bg-brand-primary text-white text-xs py-2 border-b border-white/10">
    <div class="ncopa-container flex flex-wrap items-center justify-between gap-y-1 gap-x-4">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-brand-accent"></i>
          <span>24 An Hải 8, Phường An Hải, TP Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-envelope text-brand-accent"></i>
          <span>ncopajsc@gmail.com</span>
        </span>
      </div>
      <div class="flex items-center gap-4">
        <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
          <i class="fa-solid fa-globe text-brand-accent"></i>
          <span>ncopa.com</span>
        </span>
        <span class="inline-flex items-center gap-1.5 font-semibold">
          <i class="fa-solid fa-phone text-brand-accent"></i>
          <span>0908.470.011</span>
        </span>
      </div>
    </div>
  </div>

  <!-- =========================================================================
       FLATSOME SECTION 2: MAIN HEADER
       Logo chỉnh gọn nhỏ lại, không đặt nút Gọi ngay trên Header, Menu 1 hàng
       ========================================================================= -->
  <header class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
    <div class="ncopa-container">
      <div class="flex items-center justify-between h-16 lg:h-[72px] gap-4">

        <!-- Logo NCOPA chỉnh gọn nhỏ -->
        <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 focus:outline-none">
          <img
            src="https://drive.google.com/thumbnail?id=1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF&sz=w400"
            data-gdrive-id="1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF"
            data-size="w400"
            alt="Logo CÔNG TY CỔ PHẦN NCOPA"
            class="gdrive-img h-10 sm:h-11 lg:h-12 w-auto max-w-[140px] object-contain rounded"
          >
          <div class="leading-tight hidden sm:block">
            <span class="block text-sm lg:text-[15px] font-extrabold tracking-tight text-brand-primary">NCOPA JSC</span>
            <span class="block text-[10px] font-medium uppercase tracking-wider text-slate-500">Design &amp; Build</span>
          </div>
        </a>

        <!-- Desktop Navigation: 1 hàng liền mạch, chữ gọn, không xuống dòng tên danh mục -->
        <nav class="hidden lg:flex items-center justify-end flex-wrap gap-x-4 xl:gap-x-6 gap-y-1 text-[12.5px] xl:text-[13.5px] font-semibold text-slate-700" aria-label="Menu chính">
          <a href="#trang-chu" class="nav-item-nowrap py-2 text-brand-primary hover:text-brand-accent transition">Trang chủ</a>
          <a href="#gioi-thieu" class="nav-item-nowrap py-2 hover:text-brand-accent transition">Giới thiệu</a>

          <!-- Dropdown Công trình thực tế (theo mẫu tintruongthinh.com) -->
          <div class="has-dropdown">
            <a href="#cong-trinh-thuc-te" class="nav-item-nowrap py-2 inline-flex items-center gap-1 hover:text-brand-accent transition">
              <span>Công trình thực tế</span>
              <i class="fa-solid fa-chevron-down text-[10px]"></i>
            </a>
            <div class="dropdown-menu absolute left-0 top-full pt-1 w-60 z-50">
              <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-2">
                <a href="#cong-trinh-thuc-te" onclick="selectWorkCategory('khach-san-can-ho')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Khách sạn – Căn hộ – Phòng trọ</a>
                <a href="#cong-trinh-thuc-te" onclick="selectWorkCategory('biet-thu')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Biệt thự</a>
                <a href="#cong-trinh-thuc-te" onclick="selectWorkCategory('nha-pho')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Nhà phố</a>
                <a href="#cong-trinh-thuc-te" onclick="selectWorkCategory('van-phong-nha-xuong')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Văn phòng – Nhà xưởng</a>
                <a href="#cong-trinh-thuc-te" onclick="selectWorkCategory('ket-cau-tang-ham')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Kết cấu &amp; Tầng hầm</a>
              </div>
            </div>
          </div>

          <!-- Dropdown Lĩnh vực hoạt động (theo mẫu tintruongthinh.com) -->
          <div class="has-dropdown">
            <a href="#linh-vuc-hoat-dong" class="nav-item-nowrap py-2 inline-flex items-center gap-1 hover:text-brand-accent transition">
              <span>Lĩnh vực hoạt động</span>
              <i class="fa-solid fa-chevron-down text-[10px]"></i>
            </a>
            <div class="dropdown-menu absolute left-0 top-full pt-1 w-60 z-50">
              <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-2">
                <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Thiết kế Kiến trúc – Nội thất</a>
                <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Thi công phần thô</a>
                <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Thi công hoàn thiện</a>
                <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Thi công nội thất &amp; Giám sát</a>
              </div>
            </div>
          </div>

          <a href="#du-an-da-nang" class="nav-item-nowrap py-2 hover:text-brand-accent transition">Dự án Đà Nẵng</a>

          <!-- Dropdown Báo giá (theo mẫu tintruongthinh.com) -->
          <div class="has-dropdown">
            <a href="#bao-gia" class="nav-item-nowrap py-2 inline-flex items-center gap-1 hover:text-brand-accent transition">
              <span>Báo giá</span>
              <i class="fa-solid fa-chevron-down text-[10px]"></i>
            </a>
            <div class="dropdown-menu absolute right-0 top-full pt-1 w-60 z-50">
              <div class="bg-white rounded-lg shadow-lg border border-slate-100 py-2">
                <a href="#bao-gia" onclick="prefillQuote('Thiết kế Kiến trúc – Nội thất')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Báo giá thiết kế kiến trúc</a>
                <a href="#bao-gia" onclick="prefillQuote('Thi công phần thô')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Báo giá thi công phần thô</a>
                <a href="#bao-gia" onclick="prefillQuote('Thi công hoàn thiện')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Báo giá thi công hoàn thiện</a>
                <a href="#bao-gia" onclick="prefillQuote('Thi công trọn gói')" class="block px-4 py-2 text-[13px] font-medium text-slate-700 hover:bg-brand-soft hover:text-brand-primary">Báo giá thi công trọn gói</a>
              </div>
            </div>
          </div>

          <a href="#doi-tac" class="nav-item-nowrap py-2 hover:text-brand-accent transition">Đối tác</a>
          <a href="#tin-tuc" class="nav-item-nowrap py-2 hover:text-brand-accent transition">Tin tức</a>
          <a href="#lien-he" class="nav-item-nowrap py-2 hover:text-brand-accent transition">Liên hệ</a>
        </nav>

        <!-- Nút mở Menu Mobile (Không đặt nút Gọi ngay trên header) -->
        <button id="mobileMenuBtn" type="button" aria-label="Mở menu điều hướng" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-primary hover:bg-brand-soft transition">
          <i class="fa-solid fa-bars text-lg"></i>
        </button>
      </div>
    </div>

    <!-- Mobile Navigation Drawer -->
    <div id="mobileMenuPanel" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="ncopa-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-700">
        <a href="#trang-chu" class="mobile-nav-link py-2.5 hover:text-brand-accent">Trang chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link py-2.5 hover:text-brand-accent">Giới thiệu</a>
        <a href="#linh-vuc-hoat-dong" class="mobile-nav-link py-2.5 hover:text-brand-accent">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh-thuc-te" class="mobile-nav-link py-2.5 hover:text-brand-accent">Công trình thực tế</a>
        <a href="#du-an-da-nang" class="mobile-nav-link py-2.5 hover:text-brand-accent">Dự án tại Đà Nẵng</a>
        <a href="#doi-tac" class="mobile-nav-link py-2.5 hover:text-brand-accent">Đối tác</a>
        <a href="#bao-gia" class="mobile-nav-link py-2.5 hover:text-brand-accent">Báo giá &amp; Tư vấn</a>
        <a href="#tin-tuc" class="mobile-nav-link py-2.5 hover:text-brand-accent">Tin tức &amp; Bài viết</a>
        <a href="#lien-he" class="mobile-nav-link py-2.5 hover:text-brand-accent">Liên hệ &amp; Bản đồ</a>
      </div>
    </div>
  </header>

  <!-- =========================================================================
       FLATSOME SECTION 3: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
       Hình ảnh & chữ nằm trọn trong banner, cách xa viền, không mất chữ trên Mobile & PC
       ========================================================================= -->
  <section id="trang-chu" class="w-full bg-brand-dark">
    <div class="hero-slider-viewport" id="heroSlider">
      <div class="hero-slides-track" id="heroTrack">

        <!-- SLIDE 1 -->
        <div class="hero-slide-item">
          <!-- Ảnh nền công trình thực tế -->
          <img
            src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
            data-gdrive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
            data-size="w1600"
            alt="Thi công xây dựng chuyên nghiệp CÔNG TY CỔ PHẦN NCOPA"
            class="gdrive-img absolute inset-0 w-full h-full object-cover object-center"
          >
          <!-- Lớp phủ gradient tối tạo tương phản rõ nét -->
          <div class="absolute inset-0 bg-gradient-to-r from-[#061E36]/92 via-[#0D3B66]/80 to-[#061E36]/60"></div>

          <!-- Vùng an toàn cách xa 4 viền banner (đảm bảo không bao giờ mất chữ trên mobile và PC) -->
          <div class="relative z-10 w-full px-10 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-10">
            <div class="max-w-5xl mx-auto grid grid-cols-1 lg:grid-cols-12 items-center gap-6">
              <div class="lg:col-span-8 text-white">
                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.16em] text-amber-300 mb-2">
                  CÔNG TY CỔ PHẦN NCOPA • DESIGN &amp; BUILD
                </p>
                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug mb-3">
                  THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
                </h1>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed mb-5 max-w-2xl">
                  Chuyên thi công công trình cao tầng, nhà phố, biệt thự, khách sạn, văn phòng, kết cấu sàn chuyển và tầng hầm với chuẩn kỹ thuật, an toàn và đúng tiến độ.
                </p>
                <div class="flex flex-wrap items-center gap-3">
                  <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold shadow transition">
                    Nhận báo giá miễn phí
                  </a>
                  <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                    Xem dự án Đà Nẵng
                  </a>
                </div>
              </div>
              <!-- Ảnh phụ đóng khung gọn trong banner trên máy tính -->
              <div class="hidden lg:block lg:col-span-4">
                <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-white/10 p-1.5">
                  <img
                    src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800"
                    data-gdrive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                    data-size="w800"
                    alt="Biện pháp thi công kết cấu tầng hầm NCOPA"
                    class="gdrive-img w-full h-56 object-cover rounded-lg"
                  >
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 2 (Kích thước hoàn toàn bằng Slide 1) -->
        <div class="hero-slide-item">
          <img
            src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
            data-gdrive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
            data-size="w1600"
            alt="Dự án kiến trúc và xây dựng tiêu biểu tại Đà Nẵng - NCOPA"
            class="gdrive-img absolute inset-0 w-full h-full object-cover object-center"
          >
          <div class="absolute inset-0 bg-gradient-to-r from-[#061E36]/92 via-[#0D3B66]/80 to-[#061E36]/60"></div>

          <!-- Vùng an toàn cách xa 4 viền banner -->
          <div class="relative z-10 w-full px-10 sm:px-16 md:px-20 lg:px-24 py-8 sm:py-10">
            <div class="max-w-5xl mx-auto grid grid-cols-1 lg:grid-cols-12 items-center gap-6">
              <div class="lg:col-span-8 text-white">
                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-[0.16em] text-amber-300 mb-2">
                  NCOPA JSC • TƯ VẤN GIÁM SÁT &amp; THI CÔNG
                </p>
                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug mb-3">
                  AN TOÀN – CHẤT LƯỢNG – BỀN VỮNG CHO MỌI CÔNG TRÌNH
                </h2>
                <p class="text-xs sm:text-sm lg:text-base text-slate-200 leading-relaxed mb-5 max-w-2xl">
                  Đội ngũ kỹ sư xây dựng dân dụng &amp; công nghiệp giàu kinh nghiệm thực chiến. Đồng hành cùng chủ đầu tư từ khâu thiết kế, thi công phần thô đến hoàn thiện nội thất.
                </p>
                <div class="flex flex-wrap items-center gap-3">
                  <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold shadow transition">
                    Xem công trình thực tế
                  </a>
                  <a href="#lien-he" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white text-xs sm:text-sm font-semibold transition">
                    Liên hệ tư vấn 24/7
                  </a>
                </div>
              </div>
              <div class="hidden lg:block lg:col-span-4">
                <div class="rounded-xl overflow-hidden border-2 border-white/25 shadow-2xl bg-white/10 p-1.5">
                  <img
                    src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800"
                    data-gdrive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                    data-size="w800"
                    alt="Công trình tiêu biểu tại Đà Nẵng của NCOPA"
                    class="gdrive-img w-full h-56 object-cover rounded-lg"
                  >
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>

      <!-- Nút điều hướng Banner gọn sát biên, không đè chữ -->
      <button id="prevSlideBtn" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition">
        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
      </button>
      <button id="nextSlideBtn" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-accent text-white flex items-center justify-center transition">
        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
      </button>

      <!-- Chấm chuyển slide -->
      <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
        <button type="button" class="hero-dot w-7 h-2 rounded-full bg-brand-accent transition-all" data-slide="0" aria-label="Slide 1"></button>
        <button type="button" class="hero-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all" data-slide="1" aria-label="Slide 2"></button>
      </div>
    </div>
  </section>

  <!-- =========================================================================
       FLATSOME SECTION 4: DỊCH VỤ TIÊU BIỂU (Bố cục 4 khối giống web mẫu)
       ========================================================================= -->
  <section id="linh-vuc-hoat-dong" class="py-10 lg:py-14 bg-white">
    <div class="ncopa-container">
      <div class="text-center mb-8">
        <h2 class="section-title-bar text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-primary tracking-tight">
          Dịch vụ tiêu biểu
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-500 max-w-2xl mx-auto">
          Giải pháp tổng thể từ Thiết kế, Thi công phần thô, Hoàn thiện nội thất đến Tư vấn giám sát chuyên nghiệp
        </p>
      </div>

      <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <div class="flatsome-card bg-brand-soft border border-slate-200/80 rounded-xl p-4 sm:p-6 text-center flex flex-col items-center">
          <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-primary text-white flex items-center justify-center mb-3.5 shadow-sm">
            <i class="fa-solid fa-compass-drafting text-lg sm:text-xl"></i>
          </div>
          <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1.5 break-words">THIẾT KẾ KIẾN TRÚC</h3>
          <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
            Thiết kế nhà phố, biệt thự, khách sạn, căn hộ và văn phòng tối ưu công năng &amp; thẩm mỹ.
          </p>
        </div>

        <div class="flatsome-card bg-brand-soft border border-slate-200/80 rounded-xl p-4 sm:p-6 text-center flex flex-col items-center">
          <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-accent text-white flex items-center justify-center mb-3.5 shadow-sm">
            <i class="fa-solid fa-helmet-safety text-lg sm:text-xl"></i>
          </div>
          <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1.5 break-words">THI CÔNG PHẦN THÔ</h3>
          <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
            Chuyên kết cấu móng, công trình 2 tầng hầm, sàn chuyển và xây dựng nhà cao tầng chuẩn kỹ thuật.
          </p>
        </div>

        <div class="flatsome-card bg-brand-soft border border-slate-200/80 rounded-xl p-4 sm:p-6 text-center flex flex-col items-center">
          <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-primary text-white flex items-center justify-center mb-3.5 shadow-sm">
            <i class="fa-solid fa-paint-roller text-lg sm:text-xl"></i>
          </div>
          <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1.5 break-words">THI CÔNG HOÀN THIỆN</h3>
          <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
            Hoàn thiện trọn gói, nhôm kính, sơn nước, chống thấm, trần thạch cao và hệ thống M&amp;E.
          </p>
        </div>

        <div class="flatsome-card bg-brand-soft border border-slate-200/80 rounded-xl p-4 sm:p-6 text-center flex flex-col items-center">
          <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl bg-brand-accent text-white flex items-center justify-center mb-3.5 shadow-sm">
            <i class="fa-solid fa-couch text-lg sm:text-xl"></i>
          </div>
          <h3 class="text-sm sm:text-base font-bold text-brand-primary mb-1.5 break-words">NỘI THẤT &amp; GIÁM SÁT</h3>
          <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">
            Thi công nội thất tinh tế kết hợp tư vấn giám sát chất lượng, an toàn và tiến độ công trình.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================
       FLATSOME SECTION 5: GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA CHÚNG TÔI
       ========================================================================= -->
  <section id="gioi-thieu" class="py-10 lg:py-14 bg-brand-soft border-y border-slate-200/70">
    <div class="ncopa-container">
      <!-- Giới thiệu 2 cột -->
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center mb-12">
        <div class="lg:col-span-6">
          <p class="text-xs font-bold uppercase tracking-widest text-brand-accent mb-2">VỀ CHÚNG TÔI</p>
          <h2 class="text-xl sm:text-2xl lg:text-[28px] font-extrabold text-brand-primary leading-snug mb-4">
            CÔNG TY CỔ PHẦN NCOPA
          </h2>
          <p class="text-sm text-slate-700 leading-relaxed mb-3">
            <strong>CÔNG TY CỔ PHẦN NCOPA (NCOPA JSC / N.House Design &amp; Build)</strong> chuyên Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất và Tư vấn giám sát các công trình Dân dụng &amp; Công nghiệp như Khách sạn, Căn hộ cao cấp, Biệt thự, Nhà phố, Văn phòng, Nhà xưởng tại khu vực <strong>Đà Nẵng và các tỉnh miền Trung – toàn quốc</strong>.
          </p>
          <p class="text-sm text-slate-700 leading-relaxed mb-5">
            Đặt chữ <strong>“TÂM – TÍN – CHẤT LƯỢNG”</strong> làm nền tảng, đội ngũ kỹ sư xây dựng, kỹ sư M&amp;E và kiến trúc sư dày dặn kinh nghiệm công trình cao tầng của NCOPA luôn đảm bảo mỗi công trình bàn giao đạt tiêu chuẩn <strong>An toàn – Vững chắc – Đúng tiến độ – Tối ưu chi phí</strong>.
          </p>
          <div class="grid grid-cols-3 gap-3 text-center">
            <div class="bg-white rounded-lg p-3 border border-slate-200">
              <div class="text-lg sm:text-2xl font-extrabold text-brand-primary">10+</div>
              <div class="text-[11px] sm:text-xs text-slate-600 font-medium">Năm kinh nghiệm</div>
            </div>
            <div class="bg-white rounded-lg p-3 border border-slate-200">
              <div class="text-lg sm:text-2xl font-extrabold text-brand-accent">100+</div>
              <div class="text-[11px] sm:text-xs text-slate-600 font-medium">Công trình hoàn thành</div>
            </div>
            <div class="bg-white rounded-lg p-3 border border-slate-200">
              <div class="text-lg sm:text-2xl font-extrabold text-brand-primary">24/7</div>
              <div class="text-[11px] sm:text-xs text-slate-600 font-medium">Hỗ trợ &amp; Bảo hành</div>
            </div>
          </div>
        </div>

        <div class="lg:col-span-6">
          <div class="grid grid-cols-2 gap-3">
            <div class="rounded-xl overflow-hidden shadow-md bg-white p-1.5 border border-slate-200">
              <img
                src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800"
                data-gdrive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                data-size="w800"
                alt="Thi công công trình thực tế NCOPA Đà Nẵng"
                class="gdrive-img w-full h-44 sm:h-56 object-cover rounded-lg"
              >
            </div>
            <div class="rounded-xl overflow-hidden shadow-md bg-white p-1.5 border border-slate-200">
              <img
                src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800"
                data-gdrive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                data-size="w800"
                alt="Đội ngũ kỹ sư thi công giám sát NCOPA"
                class="gdrive-img w-full h-44 sm:h-56 object-cover rounded-lg"
              >
            </div>
          </div>
        </div>
      </div>

      <!-- 6 Thế mạnh của chúng tôi (theo bố cục tintruongthinh.com) -->
      <div class="text-center mb-7">
        <h3 class="section-title-bar text-lg sm:text-xl lg:text-2xl font-extrabold uppercase text-brand-primary">
          Thế mạnh của chúng tôi
        </h3>
      </div>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
            <i class="fa-solid fa-users-gear text-base"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Đội ngũ kỹ sư, kiến trúc sư giỏi</h4>
            <p class="text-xs text-slate-600 leading-relaxed">Kỹ sư xây dựng DD&amp;CN, M&amp;E kinh nghiệm công trình cao tầng, tận tâm và chuyên nghiệp.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-accent/10 text-brand-accent flex items-center justify-center shrink-0">
            <i class="fa-solid fa-layer-group text-base"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Biện pháp thi công hiện đại</h4>
            <p class="text-xs text-slate-600 leading-relaxed">Làm chủ kỹ thuật thi công tầng hầm, sàn chuyển, kết cấu thép và vật liệu xây dựng tiên tiến.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
            <i class="fa-solid fa-clipboard-check text-base"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Giám sát tiến độ chuẩn xác</h4>
            <p class="text-xs text-slate-600 leading-relaxed">Báo cáo tiến độ thường xuyên, kiểm soát chặt chẽ an toàn lao động và chất lượng từng hạng mục.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-accent/10 text-brand-accent flex items-center justify-center shrink-0">
            <i class="fa-solid fa-shield-halved text-base"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Bảo hành công trình lâu dài</h4>
            <p class="text-xs text-slate-600 leading-relaxed">Chế độ hậu mãi rõ ràng, hỗ trợ kịp thời sau bàn giao để chủ đầu tư hoàn toàn an tâm.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-primary/10 text-brand-primary flex items-center justify-center shrink-0">
            <i class="fa-solid fa-hand-holding-dollar text-base"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Chi phí minh bạch, hợp lý</h4>
            <p class="text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục, cam kết không phát sinh vô lý và tối ưu giá trị đầu tư.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-slate-200/80 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brand-accent/10 text-brand-accent flex items-center justify-center shrink-0">
            <i class="fa-solid fa-headset text-base"></i>
          </div>
          <div>
            <h4 class="text-sm font-bold text-brand-primary mb-1">Tư vấn miễn phí 24/7</h4>
            <p class="text-xs text-slate-600 leading-relaxed">Khảo sát mặt bằng, tư vấn phương án thiết kế và lập khái toán hoàn toàn miễn phí.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================
       FLATSOME SECTION 6: CÔNG TRÌNH THI CÔNG THỰC TẾ (9 ẢNH THỰC TẾ)
       - Không để nhãn dán trên ảnh
       - Danh mục nhỏ gọn, viết liền không xuống dòng trong tên danh mục
       - 2 cột trên điện thoại, tên sản phẩm/công trình hiển thị đủ chữ, không tràn
       ========================================================================= -->
  <section id="cong-trinh-thuc-te" class="py-10 lg:py-14 bg-white">
    <div class="ncopa-container">
      <div class="text-center mb-6">
        <h2 class="section-title-bar text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-primary">
          Công trình thi công thực tế
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-500">
          Hình ảnh thi công thực tế các hạng mục xây dựng do CÔNG TY CỔ PHẦN NCOPA trực tiếp triển khai
        </p>
      </div>

      <!-- Thanh danh mục sản phẩm nhỏ gọn (theo danh mục web mẫu), không ngắt dòng trong tên danh mục -->
      <div id="workCategoryTabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
        <button type="button" data-cat="all" class="cat-tab-btn active px-3 py-1.5 rounded-md border border-slate-200 text-[12px] sm:text-[13px] font-semibold">
          Tất cả
        </button>
        <button type="button" data-cat="khach-san-can-ho" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary text-[12px] sm:text-[13px] font-semibold">
          Khách sạn – Căn hộ
        </button>
        <button type="button" data-cat="biet-thu" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary text-[12px] sm:text-[13px] font-semibold">
          Biệt thự
        </button>
        <button type="button" data-cat="nha-pho" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary text-[12px] sm:text-[13px] font-semibold">
          Nhà phố
        </button>
        <button type="button" data-cat="van-phong-nha-xuong" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary text-[12px] sm:text-[13px] font-semibold">
          Văn phòng – Nhà xưởng
        </button>
        <button type="button" data-cat="ket-cau-tang-ham" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary text-[12px] sm:text-[13px] font-semibold">
          Kết cấu &amp; Tầng hầm
        </button>
      </div>

      <!-- Lưới sản phẩm / công trình thực tế: 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="workGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Dữ liệu 9 ảnh thi công thực tế được render bằng JS sạch sẽ, không nhãn dán -->
      </div>
    </div>
  </section>

  <!-- =========================================================================
       FLATSOME SECTION 7: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (10 ẢNH DỰ ÁN)
       ========================================================================= -->
  <section id="du-an-da-nang" class="py-10 lg:py-14 bg-brand-soft border-y border-slate-200/70">
    <div class="ncopa-container">
      <div class="text-center mb-6">
        <h2 class="section-title-bar text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-primary">
          Các dự án tại Đà Nẵng
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-500">
          Tuyển tập các công trình và dự án tiêu biểu NCOPA đã và đang thực hiện trên địa bàn Thành phố Đà Nẵng
        </p>
      </div>

      <!-- Bộ lọc khu vực tại Đà Nẵng gọn gàng -->
      <div id="danangTabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
        <button type="button" data-area="all" class="cat-tab-btn active px-3 py-1.5 rounded-md border border-slate-200 text-[12px] sm:text-[13px] font-semibold">
          Tất cả dự án
        </button>
        <button type="button" data-area="son-tra" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary text-[12px] sm:text-[13px] font-semibold">
          Sơn Trà – An Hải
        </button>
        <button type="button" data-area="hai-chau" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary text-[12px] sm:text-[13px] font-semibold">
          Hải Châu
        </button>
        <button type="button" data-area="ngu-hanh-son" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary text-[12px] sm:text-[13px] font-semibold">
          Ngũ Hành Sơn
        </button>
        <button type="button" data-area="hoa-xuan" class="cat-tab-btn px-3 py-1.5 rounded-md border border-slate-200 bg-white text-slate-700 hover:border-brand-primary hover:text-brand-primary text-[12px] sm:text-[13px] font-semibold">
          Cẩm Lệ – Hòa Xuân
        </button>
      </div>

      <!-- 2 cột trên điện thoại, 5 cột (2 hàng x 5) trên màn hình rộng -->
      <div id="danangGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
        <!-- Render 10 dự án Đà Nẵng -->
      </div>
    </div>
  </section>

  <!-- =========================================================================
       FLATSOME SECTION 8: DANH MỤC CÁC ĐỐI TÁC
       ========================================================================= -->
  <section id="doi-tac" class="py-10 lg:py-12 bg-white">
    <div class="ncopa-container">
      <div class="text-center mb-7">
        <h2 class="section-title-bar text-xl sm:text-2xl lg:text-[24px] font-extrabold uppercase text-brand-primary">
          Đối tác &amp; Nhà cung cấp
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-500">
          Hợp tác cùng các thương hiệu vật tư, kết cấu và thiết bị xây dựng uy tín hàng đầu
        </p>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-3 sm:gap-4">
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-primary">HÒA PHÁT</span>
          <span class="text-[10px] text-slate-500">Thép xây dựng</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-primary">VICEM HẢI VÂN</span>
          <span class="text-[10px] text-slate-500">Xi măng cao cấp</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-accent">DULUX</span>
          <span class="text-[10px] text-slate-500">Sơn hoàn thiện</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-primary">SIKA</span>
          <span class="text-[10px] text-slate-500">Hóa chất &amp; Chống thấm</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-primary">XINGFA</span>
          <span class="text-[10px] text-slate-500">Hệ nhôm kính</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-accent">AN CƯỜNG</span>
          <span class="text-[10px] text-slate-500">Vật liệu nội thất</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-primary">CADIVI</span>
          <span class="text-[10px] text-slate-500">Dây cáp điện M&amp;E</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-primary">PANASONIC</span>
          <span class="text-[10px] text-slate-500">Thiết bị điện</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-accent">JOTUN</span>
          <span class="text-[10px] text-slate-500">Sơn nội ngoại thất</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-primary">VĨNH TƯỜNG</span>
          <span class="text-[10px] text-slate-500">Trần vách thạch cao</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-primary">BÌNH MINH</span>
          <span class="text-[10px] text-slate-500">Hệ thống cấp thoát nước</span>
        </div>
        <div class="h-20 rounded-xl border border-slate-200 bg-brand-soft/60 hover:bg-white hover:border-brand-primary/40 hover:shadow-sm flex flex-col items-center justify-center px-3 text-center transition">
          <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-accent">TOTO</span>
          <span class="text-[10px] text-slate-500">Thiết bị vệ sinh</span>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================
       FLATSOME SECTION 9: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ (theo mẫu tintruongthinh.com)
       ========================================================================= -->
  <section id="bao-gia" class="py-10 lg:py-14 bg-brand-primary text-white">
    <div class="ncopa-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
        <!-- Thông tin cam kết bên trái -->
        <div class="lg:col-span-5">
          <p class="text-xs font-bold uppercase tracking-widest text-amber-300 mb-2">MIỄN PHÍ TƯ VẤN &amp; KHÁI TOÁN</p>
          <h2 class="text-2xl sm:text-3xl font-extrabold leading-snug mb-4">
            YÊU CẦU TƯ VẤN &amp; BÁO GIÁ XÂY DỰNG
          </h2>
          <p class="text-sm text-slate-200 leading-relaxed mb-6">
            Quý khách vui lòng để lại thông tin loại công trình và nhu cầu dự kiến. Kỹ sư trưởng của <strong>CÔNG TY CỔ PHẦN NCOPA</strong> sẽ liên hệ tư vấn phương án tối ưu và gửi bảng dự toán chi tiết nhanh nhất.
          </p>
          <div class="space-y-3 text-sm">
            <div class="flex items-center gap-3">
              <span class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center text-amber-300 shrink-0">
                <i class="fa-solid fa-phone-volume"></i>
              </span>
              <div>
                <div class="text-xs text-slate-300">Hotline / Zalo hỗ trợ trực tiếp</div>
                <a href="tel:0908470011" class="font-bold text-white hover:text-amber-300">0908.470.011</a>
              </div>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center text-amber-300 shrink-0">
                <i class="fa-solid fa-location-dot"></i>
              </span>
              <div>
                <div class="text-xs text-slate-300">Văn phòng giao dịch</div>
                <div class="font-semibold text-white">24 An Hải 8, Phường An Hải, TP Đà Nẵng</div>
              </div>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-9 h-9 rounded-lg bg-white/10 flex items-center justify-center text-amber-300 shrink-0">
                <i class="fa-solid fa-envelope"></i>
              </span>
              <div>
                <div class="text-xs text-slate-300">Email nhận hồ sơ &amp; bản vẽ</div>
                <div class="font-semibold text-white">ncopajsc@gmail.com</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Form báo giá bên phải -->
        <div class="lg:col-span-7">
          <form id="quoteForm" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qName" class="block text-xs font-bold text-slate-700 mb-1.5">Họ và tên *</label>
                <input id="qName" type="text" required placeholder="Nhập họ tên của quý khách" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
              </div>
              <div>
                <label for="qPhone" class="block text-xs font-bold text-slate-700 mb-1.5">Số điện thoại *</label>
                <input id="qPhone" type="tel" required placeholder="VD: 0908 470 011" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
              </div>
              <div>
                <label for="qEmail" class="block text-xs font-bold text-slate-700 mb-1.5">Email</label>
                <input id="qEmail" type="email" placeholder="example@gmail.com" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
              </div>
              <div>
                <label for="qType" class="block text-xs font-bold text-slate-700 mb-1.5">Loại công trình</label>
                <select id="qType" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                  <option value="Nhà phố">Nhà phố</option>
                  <option value="Biệt thự">Biệt thự</option>
                  <option value="Khách sạn – Căn hộ cho thuê">Khách sạn – Căn hộ cho thuê</option>
                  <option value="Văn phòng – Nhà xưởng">Văn phòng – Nhà xưởng</option>
                  <option value="Thi công phần thô">Thi công phần thô</option>
                  <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                  <option value="Thi công trọn gói">Thi công trọn gói</option>
                  <option value="Thiết kế Kiến trúc – Nội thất">Thiết kế Kiến trúc – Nội thất</option>
                  <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                </select>
              </div>
              <div>
                <label for="qBudget" class="block text-xs font-bold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                <select id="qBudget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
                  <option value="Chưa xác định">Chưa xác định</option>
                  <option value="Dưới 1 tỷ">Dưới 1 tỷ</option>
                  <option value="1 - 2 tỷ">1 - 2 tỷ</option>
                  <option value="2 - 3 tỷ">2 - 3 tỷ</option>
                  <option value="3 - 5 tỷ">3 - 5 tỷ</option>
                  <option value="Trên 5 tỷ">Trên 5 tỷ</option>
                </select>
              </div>
              <div>
                <label for="qArea" class="block text-xs font-bold text-slate-700 mb-1.5">Địa điểm &amp; Diện tích (m²)</label>
                <input id="qArea" type="text" placeholder="VD: Sơn Trà, Đà Nẵng - 100m² x 4 tầng" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15">
              </div>
              <div class="sm:col-span-2">
                <label for="qNote" class="block text-xs font-bold text-slate-700 mb-1.5">Nội dung yêu cầu báo giá</label>
                <textarea id="qNote" rows="3" placeholder="Mô tả sơ bộ nhu cầu thiết kế, thi công phần thô, hoàn thiện hoặc giám sát..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"></textarea>
              </div>
            </div>

            <div class="mt-5 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
              <button type="submit" class="inline-flex items-center justify-center gap-2 px-6 py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-sm font-bold shadow transition">
                <i class="fa-solid fa-paper-plane"></i>
                <span>Gửi yêu cầu báo giá ngay</span>
              </button>
              <span class="text-xs text-slate-500">Phản hồi nhanh qua điện thoại &amp; Zalo</span>
            </div>

            <!-- Thông báo gửi thành công trực tiếp (không dùng alert) -->
            <div id="quoteFeedback" class="hidden mt-4 p-3.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs sm:text-sm font-medium"></div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================
       FLATSOME SECTION 10: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức xây dựng)
       ========================================================================= -->
  <section id="tin-tuc" class="py-10 lg:py-14 bg-white">
    <div class="ncopa-container">
      <div class="text-center mb-7">
        <h2 class="section-title-bar text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-primary">
          Tin tức &amp; Bài viết
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-500">
          Chia sẻ kinh nghiệm kỹ thuật thi công, xu hướng kiến trúc và thông tin xây dựng hữu ích
        </p>
      </div>

      <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Render danh sách bài viết bằng JS -->
      </div>
    </div>
  </section>

  <!-- =========================================================================
       FLATSOME SECTION 11: GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
       ========================================================================= -->
  <section id="lien-he" class="py-10 lg:py-14 bg-brand-soft border-t border-slate-200/80">
    <div class="ncopa-container">
      <div class="text-center mb-8">
        <h2 class="section-title-bar text-xl sm:text-2xl lg:text-[26px] font-extrabold uppercase text-brand-primary">
          Bản đồ &amp; Kết nối Fanpage
        </h2>
        <p class="mt-3 text-xs sm:text-sm text-slate-500">
          Trụ sở: 24 An Hải 8, Phường An Hải, TP Đà Nẵng • Hotline: 0908.470.011
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
        <!-- Google Map trực quan ngoài trang chủ -->
        <div class="lg:col-span-7 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-5 py-3.5 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2">
              <i class="fa-solid fa-map-location-dot text-brand-accent"></i>
              <h3 class="text-sm font-bold text-brand-primary">Vị trí CÔNG TY CỔ PHẦN NCOPA trên Google Maps</h3>
            </div>
            <a href="https://www.google.com/maps/search/?api=1&query=24+An+H%E1%BA%A3i+8,+Ph%C6%B0%E1%BB%9Dng+An+H%E1%BA%A3i,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-accent hover:underline">
              Chỉ đường <i class="fa-solid fa-arrow-up-right-from-square ml-0.5 text-[10px]"></i>
            </a>
          </div>
          <div class="w-full h-[320px] sm:h-[360px] flex-1 bg-slate-100">
            <iframe
              title="Bản đồ Google Maps CÔNG TY CỔ PHẦN NCOPA - 24 An Hải 8, Phường An Hải, TP Đà Nẵng"
              src="https://maps.google.com/maps?q=24%20An%20H%E1%BA%A3i%208,%20An%20H%E1%BA%A3i,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              width="100%"
              height="100%"
              style="border:0;"
              allowfullscreen=""
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>

        <!-- Fanpage Facebook trực tiếp ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-5 py-3.5 border-b border-slate-100 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2">
              <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
              <h3 class="text-sm font-bold text-brand-primary">Fanpage NCOPA JSC</h3>
            </div>
            <a href="https://www.facebook.com/N.HouseJSC/" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-[#1877F2] hover:underline">
              Mở Fanpage <i class="fa-solid fa-arrow-up-right-from-square ml-0.5 text-[10px]"></i>
            </a>
          </div>

          <div class="p-4 flex-1 flex flex-col justify-between gap-3">
            <!-- Thẻ giới thiệu nhanh Fanpage luôn hiển thị rõ ràng -->
            <div class="flex items-center gap-3 p-3 rounded-xl bg-brand-soft border border-slate-200/80">
              <img
                src="https://drive.google.com/thumbnail?id=1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF&sz=w200"
                data-gdrive-id="1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF"
                data-size="w200"
                alt="NCOPA JSC Fanpage"
                class="gdrive-img w-12 h-12 rounded-lg object-contain bg-white p-1 border border-slate-200 shrink-0"
              >
              <div class="min-w-0 flex-1">
                <div class="text-sm font-bold text-brand-primary truncate">NCOPA JSC • N.House Design &amp; Build</div>
                <div class="text-xs text-slate-600">Cập nhật tiến độ thi công thực tế hàng ngày</div>
              </div>
              <a href="https://www.facebook.com/N.HouseJSC/" target="_blank" rel="noopener noreferrer" class="shrink-0 px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold transition">
                Theo dõi
              </a>
            </div>

            <!-- Facebook Page Plugin Iframe -->
            <div class="w-full h-[255px] rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
              <iframe
                title="Facebook Fanpage NCOPA JSC"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FN.HouseJSC%2F&tabs=timeline&width=500&height=255&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                width="100%"
                height="255"
                style="border:none;overflow:hidden;"
                scrolling="no"
                frameborder="0"
                allowfullscreen="true"
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
              ></iframe>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =========================================================================
       FLATSOME SECTION 12: FOOTER (3 Cột rõ ràng, dễ dựng lại UX Builder)
       ========================================================================= -->
  <footer class="bg-brand-dark text-slate-300 pt-12 pb-6">
    <div class="ncopa-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-10 border-b border-white/10">

        <!-- Cột 1: Thông tin doanh nghiệp -->
        <div class="lg:col-span-5">
          <div class="flex items-center gap-3 mb-4">
            <div class="bg-white rounded-lg p-1.5 inline-flex items-center justify-center">
              <img
                src="https://drive.google.com/thumbnail?id=1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF&sz=w300"
                data-gdrive-id="1PoWUdwXsCwMGeY1cylIHGFksv7lKJihF"
                data-size="w300"
                alt="Logo NCOPA"
                class="gdrive-img h-9 w-auto object-contain"
              >
            </div>
            <div>
              <h4 class="text-base font-extrabold text-white">CÔNG TY CỔ PHẦN NCOPA</h4>
              <p class="text-xs text-amber-300">Website: ncopa.com</p>
            </div>
          </div>
          <ul class="space-y-2.5 text-xs sm:text-sm text-slate-300">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-location-dot text-brand-accent mt-1"></i>
              <span><strong>Trụ sở:</strong> 24 An Hải 8, Phường An Hải, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone text-brand-accent"></i>
              <span><strong>Hotline / Zalo:</strong> <a href="tel:0908470011" class="text-white font-semibold hover:text-amber-300">0908.470.011</a></span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-envelope text-brand-accent"></i>
              <span><strong>Email:</strong> ncopajsc@gmail.com</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-file-invoice text-brand-accent"></i>
              <span><strong>Mã số thuế:</strong> 0402234128</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-brands fa-facebook text-brand-accent"></i>
              <a href="https://www.facebook.com/N.HouseJSC/" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">facebook.com/N.HouseJSC</a>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-4">
          <h4 class="text-sm font-bold uppercase tracking-wider text-white mb-4 pb-2 border-b border-white/15 inline-block">
            Lĩnh vực hoạt động
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-300 transition">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-amber-300 transition">Thi công phần thô &amp; Tầng hầm</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-amber-300 transition">Thi công hoàn thiện trọn gói</a></li>
            <li><a href="#cong-trinh-thuc-te" class="hover:text-amber-300 transition">Thi công nội thất văn phòng, nhà ở</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-amber-300 transition">Tư vấn giám sát công trình cao tầng</a></li>
          </ul>
        </div>

        <!-- Cột 3: Liên kết nhanh -->
        <div class="lg:col-span-3">
          <h4 class="text-sm font-bold uppercase tracking-wider text-white mb-4 pb-2 border-b border-white/15 inline-block">
            Danh mục chính
          </h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#trang-chu" class="hover:text-amber-300 transition">Trang chủ</a></li>
            <li><a href="#gioi-thieu" class="hover:text-amber-300 transition">Giới thiệu công ty</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-amber-300 transition">Dự án tại Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-amber-300 transition">Yêu cầu báo giá</a></li>
            <li><a href="#tin-tuc" class="hover:text-amber-300 transition">Tin tức &amp; Bài viết</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <div>Copyright 2026 © <strong class="text-white">CÔNG TY CỔ PHẦN NCOPA</strong> (ncopa.com). All rights reserved.</div>
        <div>Thiết kế tối ưu chuẩn Flatsome UX Builder</div>
      </div>
    </div>
  </footer>

  <!-- =========================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (Tương thích PC & Mobile)
       ========================================================================= -->
  <div class="fixed right-3 bottom-4 sm:right-5 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút lên đầu trang -->
    <button id="backToTopBtn" type="button" aria-label="Lên đầu trang" class="hidden w-10 h-10 rounded-full bg-brand-primary/90 hover:bg-brand-primary text-white shadow-lg flex items-center justify-center transition">
      <i class="fa-solid fa-arrow-up text-sm"></i>
    </button>

    <!-- Nút Facebook Fanpage -->
    <a href="https://www.facebook.com/N.HouseJSC/" target="_blank" rel="noopener noreferrer" aria-label="Facebook NCOPA" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition">
      <i class="fa-brands fa-facebook-f text-base sm:text-lg w-5 text-center"></i>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a href="https://zalo.me/0908470011" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0908470011" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition">
      <span class="w-5 h-5 flex items-center justify-center font-extrabold text-[11px] border border-white/80 rounded-full leading-none">Z</span>
      <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a href="tel:0908470011" aria-label="Gọi Hotline 0908.470.011" class="pulse-hotline flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white rounded-full shadow-xl px-3.5 py-2.5 sm:px-4 sm:py-2.5 transition">
      <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
      <span class="text-xs sm:text-[13px] font-extrabold tracking-wide whitespace-nowrap">0908.470.011</span>
    </a>
  </div>

  <!-- =========================================================================
       MODAL XEM CHI TIẾT CÔNG TRÌNH / DỰ ÁN / BÀI VIẾT
       ========================================================================= -->
  <div id="detailModal" class="hidden fixed inset-0 z-50 bg-black/70 backdrop-blur-sm flex items-center justify-center p-3 sm:p-6">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
      <button id="closeModalBtn" type="button" aria-label="Đóng cửa sổ" class="sticky top-3 float-right mr-3 mt-3 z-10 w-9 h-9 rounded-full bg-slate-900/75 hover:bg-brand-accent text-white flex items-center justify-center transition">
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div id="modalBody" class="p-4 sm:p-6 pt-2"></div>
    </div>
  </div>

  <!-- =========================================================================
       JAVASCRIPT: DỮ LIỆU CÔNG TRÌNH, DỰ ÁN ĐÀ NẴNG, BÀI VIẾT, SLIDER & TƯƠNG TÁC
       ========================================================================= -->
  <script>
    /**
     * Hàm tạo URL ảnh Google Drive tối ưu cùng cơ chế dự phòng đa tầng
     * giúp ảnh hiển thị ổn định trên cả máy tính và điện thoại.
     */
    function getDriveUrl(id, size = 'w1000') {
      return `https://drive.google.com/thumbnail?id=${id}&sz=${size}`;
    }

    function attachDriveFallback(img) {
      if (!img || img.dataset.fallbackBound === '1') return;
      img.dataset.fallbackBound = '1';
      img.dataset.attempt = '0';

      img.addEventListener('error', function () {
        const id = img.dataset.gdriveId;
        const size = img.dataset.size || 'w1000';
        const attempt = parseInt(img.dataset.attempt || '0', 10);

        if (!id) return;

        if (attempt === 0) {
          img.dataset.attempt = '1';
          img.src = `https://lh3.googleusercontent.com/d/${id}=${size}`;
        } else if (attempt === 1) {
          img.dataset.attempt = '2';
          img.src = `https://drive.google.com/uc?export=view&id=${id}`;
        } else {
          img.dataset.attempt = '3';
          img.src = `https://placehold.co/800x600/0D3B66/FFFFFF?text=NCOPA+JSC`;
        }
      });
    }

    // -------------------------------------------------------------------------
    // 1. DỮ LIỆU 9 ẢNH CÔNG TRÌNH THI CÔNG XÂY DỰNG THỰC TẾ (Từ Google Drive)
    // -------------------------------------------------------------------------
    const constructionWorks = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi công phần thô & Kết cấu sàn chuyển công trình cao tầng',
        category: 'ket-cau-tang-ham',
        categoryLabel: 'Kết cấu & Tầng hầm',
        location: 'Đà Nẵng',
        desc: 'Triển khai thi công hệ dầm sàn chuyển chịu lực lớn, kiểm soát nghiêm ngặt cốt thép, cốp pha và công tác đổ bê tông đạt cường độ thiết kế.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Biện pháp thi công phần ngầm & Công trình 2 tầng hầm',
        category: 'ket-cau-tang-ham',
        categoryLabel: 'Kết cấu & Tầng hầm',
        location: 'Đà Nẵng',
        desc: 'Thi công hệ tường vây, hệ shoring chống văng và kết cấu móng bè cho công trình 2 tầng hầm bảo đảm an toàn tuyệt đối cho công trình lân cận.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thi công xây dựng trọn gói Nhà phố hiện đại 4 tầng',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        location: 'Quận Sơn Trà, Đà Nẵng',
        desc: 'Thi công trọn gói từ phần móng, khung bê tông cốt thép đến hoàn thiện mặt tiền, hệ cửa nhôm kính và nội thất đồng bộ.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi công phần thô & Hoàn thiện Biệt thự 2 mặt tiền',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        location: 'Quận Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Tổ chức thi công bài bản hạng mục kết cấu, chống thấm sàn mái, sơn nước cao cấp và hoàn thiện kiến trúc ngoại thất sang trọng.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi công Khách sạn & Tòa nhà Căn hộ dịch vụ cao cấp',
        category: 'khach-san-can-ho',
        categoryLabel: 'Khách sạn – Căn hộ',
        location: 'Khu vực Biển Mỹ Khê, Đà Nẵng',
        desc: 'Thi công đồng bộ kết cấu cao tầng, hệ thống cơ điện M&E, PCCC và hoàn thiện không gian lưu trú tiêu chuẩn khách sạn.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thiết kế & Thi công Xưởng sản xuất – Nhà công nghiệp',
        category: 'van-phong-nha-xuong',
        categoryLabel: 'Văn phòng – Nhà xưởng',
        location: 'Khu Công Nghiệp',
        desc: 'Giải pháp Design & Build nhà xưởng kết cấu thép tiền chế kết hợp nền bê tông chịu tải, đáp ứng tiến độ bàn giao nhanh.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thi công Hoàn thiện & Nội thất Văn phòng doanh nghiệp',
        category: 'van-phong-nha-xuong',
        categoryLabel: 'Văn phòng – Nhà xưởng',
        location: 'Quận Hải Châu, Đà Nẵng',
        desc: 'Hoàn thiện vách ngăn nhôm kính, trần thạch cao, hệ thống chiếu sáng và đồ gỗ nội thất văn phòng hiện đại.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Giám sát & Thi công phần thô Nhà phố 3 tầng mái bằng',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        location: 'Khu đô thị Hòa Xuân, Đà Nẵng',
        desc: 'Kiểm tra kỹ lưỡng từng công đoạn buộc thép, lắp dựng cốp pha, xây tô và nghiệm thu từng sàn trước khi chuyển bước.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thiết kế & Thi công Biệt thự nghỉ dưỡng sân vườn',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        location: 'Đà Nẵng – Quảng Nam',
        desc: 'Thi công hoàn thiện không gian biệt thự sân vườn thoáng đãng, sử dụng vật liệu bền vững thích nghi khí hậu ven biển miền Trung.'
      }
    ];

    // -------------------------------------------------------------------------
    // 2. DỮ LIỆU 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Từ Google Drive)
    // -------------------------------------------------------------------------
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Dự án Sàn chuyển Solis – Đà Nẵng',
        area: 'son-tra',
        location: 'Quận Sơn Trà, TP Đà Nẵng',
        desc: 'Hạng mục thi công kết cấu sàn chuyển kỹ thuật cao, kiểm soát chặt chẽ độ võng và tiến độ theo yêu cầu chủ đầu tư.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Công trình Tòa nhà 2 Tầng hầm – An Hải',
        area: 'son-tra',
        location: 'Phường An Hải, TP Đà Nẵng',
        desc: 'Hoàn thành bàn giao biện pháp và triển khai thi công kết cấu phần ngầm 2 tầng hầm an toàn, đạt chuẩn kỹ thuật.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Tòa nhà Căn hộ Dịch vụ – Mỹ Khê',
        area: 'ngu-hanh-son',
        location: 'Ngũ Hành Sơn, TP Đà Nẵng',
        desc: 'Thiết kế và thi công trọn gói căn hộ lưu trú ven biển với tối ưu công năng khai thác và hệ thống M&E đồng bộ.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Khách sạn Boutique – Đường Võ Nguyên Giáp',
        area: 'son-tra',
        location: 'Quận Sơn Trà, TP Đà Nẵng',
        desc: 'Thi công phần thô và hoàn thiện mặt đứng kiến trúc khách sạn cao tầng khu vực ven biển Đà Nẵng.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Nhà phố Thương mại – Trung tâm Hải Châu',
        area: 'hai-chau',
        location: 'Quận Hải Châu, TP Đà Nẵng',
        desc: 'Xây dựng trọn gói nhà phố kết hợp kinh doanh văn phòng với mặt tiền sang trọng và không gian lấy sáng tự nhiên.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Biệt thự Hiện đại – Khu Nam Việt Á',
        area: 'ngu-hanh-son',
        location: 'Ngũ Hành Sơn, TP Đà Nẵng',
        desc: 'Thi công hoàn thiện biệt thự gia đình hiện đại, chú trọng xử lý chống thấm, cách nhiệt và thẩm mỹ nội ngoại thất.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Nhà phố 4 tầng – Khu đô thị Hòa Xuân',
        area: 'hoa-xuan',
        location: 'Quận Cẩm Lệ, TP Đà Nẵng',
        desc: 'Thiết kế và thi công trọn gói nhà phố 4 tầng phong cách tối giản, tối ưu công năng sinh hoạt cho gia đình trẻ.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Tòa nhà Văn phòng – Đường 2 Tháng 9',
        area: 'hai-chau',
        location: 'Quận Hải Châu, TP Đà Nẵng',
        desc: 'Thi công kết cấu, hoàn thiện mặt dựng kính và nội thất văn phòng hiện đại ngay trục đường trung tâm Đà Nẵng.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Biệt thự Vườn Ven Sông – Hòa Xuân',
        area: 'hoa-xuan',
        location: 'Hòa Xuân, TP Đà Nẵng',
        desc: 'Thi công kiến trúc biệt thự xanh hòa hợp cảnh quan sông nước, đảm bảo độ bền kết cấu và tiện nghi cao cấp.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Tổ hợp Căn hộ & Thương mại – Sơn Trà',
        area: 'son-tra',
        location: 'Quận Sơn Trà, TP Đà Nẵng',
        desc: 'Tư vấn giám sát và thi công xây dựng công trình hỗn hợp căn hộ – thương mại đạt chuẩn an toàn và tiến độ.'
      }
    ];

    // -------------------------------------------------------------------------
    // 3. DỮ LIỆU DANH MỤC CÁC BÀI VIẾT TRANG CHỦ
    // -------------------------------------------------------------------------
    const articles = [
      {
        imageId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        date: '15/11/2026',
        title: 'Biện pháp thi công công trình 2 tầng hầm an toàn tại khu đô thị Đà Nẵng',
        excerpt: 'Phân tích chi tiết quy trình thi công tường vây, hệ giằng chống và kiểm soát mực nước ngầm cho nhà phố và tòa nhà cao tầng.',
        content: 'Thi công công trình có 2 tầng hầm đòi hỏi sự tính toán kỹ lưỡng về địa chất, giải pháp tường vây, hệ shoring chống văng và quy trình quan trắc lún nghiêng công trình lân cận. Đội ngũ kỹ sư CÔNG TY CỔ PHẦN NCOPA luôn lập thuyết minh biện pháp chi tiết, giám sát 24/7 tại hiện trường nhằm bảo đảm an toàn tuyệt đối và đúng tiến độ cam kết.'
      },
      {
        imageId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        date: '08/11/2026',
        title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn chuyển đúng tiêu chuẩn kỹ thuật',
        excerpt: 'Bảo dưỡng bê tông đúng cách trong 7 ngày đầu quyết định độ bền nén, khả năng chống nứt và tuổi thọ kết cấu ngôi nhà.',
        content: 'Trong kết cấu xây dựng, đặc biệt với bê tông khối lớn như móng bè và sàn chuyển, công tác giữ ẩm, che phủ và kiểm soát nhiệt độ thủy hóa là vô cùng quan trọng. Thực hiện đúng quy trình tưới nước bảo dưỡng giúp bê tông đạt cường độ thiết kế tối đa, hạn chế nứt co ngót và bảo vệ cốt thép lâu dài.'
      },
      {
        imageId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        date: '29/10/2026',
        title: 'Kinh nghiệm lựa chọn nhà thầu Thiết kế & Thi công trọn gói (Design & Build)',
        excerpt: 'Những tiêu chí quan trọng giúp chủ đầu tư kiểm soát tốt ngân sách, chất lượng vật tư và hạn chế tối đa chi phí phát sinh.',
        content: 'Mô hình Design & Build giúp đồng bộ từ bản vẽ kiến trúc, kết cấu, M&E đến thi công thực tế tại công trường. Khi chọn nhà thầu, chủ đầu tư nên đánh giá hồ sơ năng lực thực tế, bảng dự toán vật tư minh bạch, quy trình nghiệm thu từng giai đoạn và cam kết bảo hành sau bàn giao.'
      },
      {
        imageId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        date: '18/10/2026',
        title: '03 lưu ý quan trọng trước khi xây nhà phố và căn hộ cho thuê tại Đà Nẵng',
        excerpt: 'Từ thủ tục xin phép xây dựng, thiết kế tối ưu thông gió tự nhiên đến lựa chọn vật liệu chống ăn mòn khí hậu ven biển.',
        content: 'Khí hậu ven biển Đà Nẵng có độ ẩm cao và gió mạnh theo mùa. Do đó, ngay từ giai đoạn thiết kế, cần đặc biệt chú trọng giải pháp chống thấm toàn diện, lựa chọn hệ nhôm kính chịu gió bão, sơn ngoại thất kháng kiềm và bố trí công năng hợp lý để công trình luôn bền đẹp theo thời gian.'
      }
    ];

    // -------------------------------------------------------------------------
    // RENDER CÔNG TRÌNH THỰC TẾ (Không nhãn dán, tên hiển thị đủ chữ)
    // -------------------------------------------------------------------------
    function renderWorks(category = 'all') {
      const grid = document.getElementById('workGrid');
      const filtered = category === 'all'
        ? constructionWorks
        : constructionWorks.filter(item => item.category === category);

      grid.innerHTML = filtered.map((item, idx) => `
        <article class="flatsome-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col cursor-pointer" onclick="openWorkModal('${item.id}', 'work')">
          <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="${getDriveUrl(item.id, 'w800')}"
              data-gdrive-id="${item.id}"
              data-size="w800"
              alt="${item.title}"
              loading="lazy"
              class="gdrive-img w-full h-full object-cover"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-primary leading-snug break-words">
              ${item.title}
            </h3>
            <p class="mt-1.5 text-[11px] sm:text-xs text-slate-500">
              <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>${item.location}
            </p>
          </div>
        </article>
      `).join('');

      grid.querySelectorAll('.gdrive-img').forEach(attachDriveFallback);
    }

    // -------------------------------------------------------------------------
    // RENDER 10 DỰ ÁN TẠI ĐÀ NẴNG (Không nhãn dán, 2 cột mobile, tên đủ chữ)
    // -------------------------------------------------------------------------
    function renderDanangProjects(area = 'all') {
      const grid = document.getElementById('danangGrid');
      const filtered = area === 'all'
        ? danangProjects
        : danangProjects.filter(item => item.area === area);

      grid.innerHTML = filtered.map(item => `
        <article class="flatsome-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col cursor-pointer" onclick="openWorkModal('${item.id}', 'danang')">
          <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
            <img
              src="${getDriveUrl(item.id, 'w800')}"
              data-gdrive-id="${item.id}"
              data-size="w800"
              alt="${item.title}"
              loading="lazy"
              class="gdrive-img w-full h-full object-cover"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <h3 class="text-[12px] sm:text-[13px] font-bold text-brand-primary leading-snug break-words">
              ${item.title}
            </h3>
            <p class="mt-1.5 text-[11px] text-slate-500">
              <i class="fa-solid fa-map-pin text-brand-accent mr-1"></i>${item.location}
            </p>
          </div>
        </article>
      `).join('');

      grid.querySelectorAll('.gdrive-img').forEach(attachDriveFallback);
    }

    // -------------------------------------------------------------------------
    // RENDER BÀI VIẾT TRANG CHỦ
    // -------------------------------------------------------------------------
    function renderArticles() {
      const grid = document.getElementById('articlesGrid');
      grid.innerHTML = articles.map((art, index) => `
        <article class="flatsome-card bg-white rounded-xl border border-slate-200 overflow-hidden flex flex-col cursor-pointer" onclick="openArticleModal(${index})">
          <div class="w-full aspect-[16/10] overflow-hidden bg-slate-100">
            <img
              src="${getDriveUrl(art.imageId, 'w800')}"
              data-gdrive-id="${art.imageId}"
              data-size="w800"
              alt="${art.title}"
              loading="lazy"
              class="gdrive-img w-full h-full object-cover"
            >
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col">
            <div class="text-[11px] text-slate-400 font-medium mb-1">
              <i class="fa-regular fa-calendar mr-1"></i>${art.date}
            </div>
            <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-primary leading-snug break-words mb-2">
              ${art.title}
            </h3>
            <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed flex-1">
              ${art.excerpt}
            </p>
            <div class="mt-3 text-xs font-semibold text-brand-accent">
              Đọc chi tiết <i class="fa-solid fa-arrow-right ml-1 text-[10px]"></i>
            </div>
          </div>
        </article>
      `).join('');

      grid.querySelectorAll('.gdrive-img').forEach(attachDriveFallback);
    }

    // -------------------------------------------------------------------------
    // BỘ LỌC DANH MỤC CÔNG TRÌNH & DỰ ÁN ĐÀ NẴNG
    // -------------------------------------------------------------------------
    function selectWorkCategory(cat) {
      const tabs = document.querySelectorAll('#workCategoryTabs .cat-tab-btn');
      tabs.forEach(btn => {
        btn.classList.toggle('active', btn.dataset.cat === cat);
        if (btn.dataset.cat !== cat) {
          btn.classList.add('bg-white', 'text-slate-700');
        } else {
          btn.classList.remove('bg-white', 'text-slate-700');
        }
      });
      renderWorks(cat);
    }

    document.querySelectorAll('#workCategoryTabs .cat-tab-btn').forEach(btn => {
      btn.addEventListener('click', () => selectWorkCategory(btn.dataset.cat));
    });

    document.querySelectorAll('#danangTabs .cat-tab-btn').forEach(btn => {
      btn.addEventListener('click', () => {
        const area = btn.dataset.area;
        document.querySelectorAll('#danangTabs .cat-tab-btn').forEach(b => {
          b.classList.toggle('active', b.dataset.area === area);
          if (b.dataset.area !== area) {
            b.classList.add('bg-white', 'text-slate-700');
          } else {
            b.classList.remove('bg-white', 'text-slate-700');
          }
        });
        renderDanangProjects(area);
      });
    });

    // -------------------------------------------------------------------------
    // MODAL XEM CHI TIẾT CÔNG TRÌNH / BÀI VIẾT
    // -------------------------------------------------------------------------
    const detailModal = document.getElementById('detailModal');
    const modalBody = document.getElementById('modalBody');
    const closeModalBtn = document.getElementById('closeModalBtn');

    function openWorkModal(id, type) {
      const list = type === 'danang' ? danangProjects : constructionWorks;
      const item = list.find(x => x.id === id);
      if (!item) return;

      modalBody.innerHTML = `
        <div class="rounded-xl overflow-hidden bg-slate-100 mb-4">
          <img
            src="${getDriveUrl(item.id, 'w1200')}"
            data-gdrive-id="${item.id}"
            data-size="w1200"
            alt="${item.title}"
            class="gdrive-img w-full max-h-[420px] object-cover"
          >
        </div>
        <h3 class="text-lg sm:text-xl font-extrabold text-brand-primary mb-2">${item.title}</h3>
        <p class="text-xs sm:text-sm font-semibold text-brand-accent mb-3">
          <i class="fa-solid fa-location-dot mr-1"></i>${item.location} • CÔNG TY CỔ PHẦN NCOPA
        </p>
        <p class="text-sm text-slate-700 leading-relaxed mb-5">${item.desc}</p>
        <div class="flex flex-wrap items-center gap-3 pt-3 border-t border-slate-100">
          <a href="#bao-gia" onclick="closeModal(); prefillQuote('${item.title.replace(/'/g, '')}')" class="px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs sm:text-sm font-bold transition">
            Nhận tư vấn &amp; báo giá tương tự
          </a>
          <a href="tel:0908470011" class="px-5 py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-bold transition">
            Hotline: 0908.470.011
          </a>
        </div>
      `;
      modalBody.querySelectorAll('.gdrive-img').forEach(attachDriveFallback);
      detailModal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function openArticleModal(index) {
      const art = articles[index];
      if (!art) return;
      modalBody.innerHTML = `
        <div class="rounded-xl overflow-hidden bg-slate-100 mb-4">
          <img
            src="${getDriveUrl(art.imageId, 'w1200')}"
            data-gdrive-id="${art.imageId}"
            data-size="w1200"
            alt="${art.title}"
            class="gdrive-img w-full max-h-[360px] object-cover"
          >
        </div>
        <div class="text-xs text-slate-400 font-medium mb-1">
          <i class="fa-regular fa-calendar mr-1"></i>${art.date} • NCOPA JSC
        </div>
        <h3 class="text-lg sm:text-xl font-extrabold text-brand-primary mb-3">${art.title}</h3>
        <p class="text-sm text-slate-700 leading-relaxed mb-3">${art.excerpt}</p>
        <p class="text-sm text-slate-700 leading-relaxed mb-5">${art.content}</p>
        <div class="pt-3 border-t border-slate-100">
          <a href="#bao-gia" onclick="closeModal()" class="inline-flex items-center px-5 py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-bold transition">
            Liên hệ kỹ sư tư vấn miễn phí
          </a>
        </div>
      `;
      modalBody.querySelectorAll('.gdrive-img').forEach(attachDriveFallback);
      detailModal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeModal() {
      detailModal.classList.add('hidden');
      document.body.style.overflow = '';
    }

    closeModalBtn.addEventListener('click', closeModal);
    detailModal.addEventListener('click', (e) => {
      if (e.target === detailModal) closeModal();
    });

    // -------------------------------------------------------------------------
    // SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG TRÊN ĐIỆN THOẠI
    // -------------------------------------------------------------------------
    (function initHeroSlider() {
      const track = document.getElementById('heroTrack');
      const dots = document.querySelectorAll('.hero-dot');
      const prevBtn = document.getElementById('prevSlideBtn');
      const nextBtn = document.getElementById('nextSlideBtn');
      const sliderEl = document.getElementById('heroSlider');
      const totalSlides = 2;
      let currentSlide = 0;
      let timer = null;
      let touchStartX = 0;

      function updateSlider(index) {
        currentSlide = (index + totalSlides) % totalSlides;
        track.style.transform = `translateX(-${currentSlide * 100}%)`;
        dots.forEach((dot, i) => {
          if (i === currentSlide) {
            dot.classList.add('bg-brand-accent', 'w-7');
            dot.classList.remove('bg-white/60', 'w-2.5');
          } else {
            dot.classList.remove('bg-brand-accent', 'w-7');
            dot.classList.add('bg-white/60', 'w-2.5');
          }
        });
      }

      function startAuto() {
        stopAuto();
        timer = setInterval(() => updateSlider(currentSlide + 1), 5000);
      }

      function stopAuto() {
        if (timer) clearInterval(timer);
      }

      prevBtn.addEventListener('click', () => { updateSlider(currentSlide - 1); startAuto(); });
      nextBtn.addEventListener('click', () => { updateSlider(currentSlide + 1); startAuto(); });
      dots.forEach(dot => {
        dot.addEventListener('click', () => {
          updateSlider(parseInt(dot.dataset.slide, 10));
          startAuto();
        });
      });

      sliderEl.addEventListener('mouseenter', stopAuto);
      sliderEl.addEventListener('mouseleave', startAuto);

      sliderEl.addEventListener('touchstart', (e) => {
        touchStartX = e.changedTouches[0].clientX;
        stopAuto();
      }, { passive: true });

      sliderEl.addEventListener('touchend', (e) => {
        const diff = touchStartX - e.changedTouches[0].clientX;
        if (Math.abs(diff) > 40) {
          updateSlider(diff > 0 ? currentSlide + 1 : currentSlide - 1);
        }
        startAuto();
      }, { passive: true });

      updateSlider(0);
      startAuto();
    })();

    // -------------------------------------------------------------------------
    // MENU MOBILE & NÚT LÊN ĐẦU TRANG
    // -------------------------------------------------------------------------
    const mobileMenuBtn = document.getElementById('mobileMenuBtn');
    const mobileMenuPanel = document.getElementById('mobileMenuPanel');

    mobileMenuBtn.addEventListener('click', () => {
      mobileMenuPanel.classList.toggle('hidden');
    });

    document.querySelectorAll('.mobile-nav-link').forEach(link => {
      link.addEventListener('click', () => mobileMenuPanel.classList.add('hidden'));
    });

    const backToTopBtn = document.getElementById('backToTopBtn');
    window.addEventListener('scroll', () => {
      if (window.scrollY > 360) {
        backToTopBtn.classList.remove('hidden');
      } else {
        backToTopBtn.classList.add('hidden');
      }
    });
    backToTopBtn.addEventListener('click', () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });

    // -------------------------------------------------------------------------
    // XỬ LÝ FORM YÊU CẦU BÁO GIÁ (Không dùng alert)
    // -------------------------------------------------------------------------
    function prefillQuote(noteText) {
      const typeSelect = document.getElementById('qType');
      const noteInput = document.getElementById('qNote');
      let matched = false;
      for (let i = 0; i < typeSelect.options.length; i++) {
        if (typeSelect.options[i].value === noteText) {
          typeSelect.selectedIndex = i;
          matched = true;
          break;
        }
      }
      if (!matched && noteInput) {
        noteInput.value = `Tôi cần tư vấn & báo giá hạng mục: ${noteText}`;
      }
    }

    document.getElementById('quoteForm').addEventListener('submit', function (e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const type = document.getElementById('qType').value;
      const feedback = document.getElementById('quoteFeedback');

      feedback.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá <strong>${type}</strong> của quý khách (SĐT: ${phone}) đã được tiếp nhận. Kỹ sư CÔNG TY CỔ PHẦN NCOPA sẽ liên hệ lại sớm nhất qua Hotline/Zalo 0908.470.011.`;
      feedback.classList.remove('hidden');
      this.reset();
    });

    // -------------------------------------------------------------------------
    // KHỞI TẠO TOÀN BỘ ẢNH & DANH MỤC KHI TẢI TRANG
    // -------------------------------------------------------------------------
    document.querySelectorAll('.gdrive-img').forEach(attachDriveFallback);
    renderWorks('all');
    renderDanangProjects('all');
    renderArticles();
  </script>
</body>
</html>
