<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG GREEN TROPICAL | Thiết Kế & Thi Công Trọn Gói Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG GREEN TROPICAL - Chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện và nội thất trọn gói tại Đà Nẵng. Hotline: 0985.121.468." />
  <meta name="keywords" content="Green Tropical, thiết kế xây dựng Đà Nẵng, thi công trọn gói Đà Nẵng, xây nhà Ngũ Hành Sơn, greentropical.com" />

  <!-- Meta Open Graph & Thumbnail Logo khi chia sẻ đường link trang web -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="GREEN TROPICAL" />
  <meta property="og:url" content="https://greentropical.com/" />
  <meta property="og:title" content="CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG GREEN TROPICAL" />
  <meta property="og:description" content="Thiết kế Kiến trúc - Thi công Xây dựng & Nội thất trọn gói chuyên nghiệp tại Đà Nẵng. Địa chỉ: 42 Hoàng Bật Đạt, Phường Ngũ Hành Sơn, TP. Đà Nẵng. Hotline: 0985.121.468." />
  <meta property="og:image" content="https://greentropical.com/wp-content/uploads/logo-green-tropical-thumbnail.png" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG GREEN TROPICAL" />
  <meta name="twitter:description" content="Thiết kế Kiến trúc - Thi công Xây dựng & Nội thất trọn gói tại Đà Nẵng." />
  <meta name="twitter:image" content="https://greentropical.com/wp-content/uploads/logo-green-tropical-thumbnail.png" />

  <!-- Favicon Logo Green Tropical -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%230B6644'/%3E%3Cpath d='M14 34L32 18l18 16v16H38V38H26v12H14V34z' fill='none' stroke='%23FFFFFF' stroke-width='3.5' stroke-linejoin='round'/%3E%3Cpath d='M32 15c7-6 16-4 17 4-6 3-13 2-17-4z' fill='%23C89B3C'/%3E%3C/svg%3E" />

  <!-- Google Font: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS CDN -->
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
              dark: '#074B32',
              primary: '#0B6644',
              medium: '#158055',
              light: '#EAF4EF',
              gold: '#C89B3C',
              goldLight: '#F7EFE0',
            }
          }
        }
      }
    };
  </script>

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" />

  <style>
    /* Cài đặt chuẩn chống tràn viền & chống lệch phải tuyệt đối */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      scroll-behavior: smooth;
      font-family: 'Inter', sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
    }

    /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình */
    .gt-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 1024px) {
      .gt-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Dropdown Menu chuẩn Flatsome */
    .nav-item {
      position: relative;
    }

    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(6px);
      transition: all 0.2s ease;
    }

    .nav-item:hover .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Tiêu đề Section chuẩn Flatsome UX Builder */
    .flatsome-heading {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }

    .flatsome-heading::after {
      content: '';
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background: linear-gradient(90deg, #0B6644, #C89B3C);
      border-radius: 999px;
    }

    /* Banner Slider 2 ảnh bằng nhau, không cắt mất chữ */
    .banner-track {
      display: flex;
      transition: transform 0.6s cubic-bezier(0.25, 0.8, 0.25, 1);
      will-change: transform;
    }

    .banner-slide {
      flex: 0 0 100%;
      width: 100%;
      min-width: 100%;
    }

    /* Hiệu ứng ảnh Flatsome zoom nhẹ */
    .img-zoom {
      transition: transform 0.45s ease;
    }

    .group:hover .img-zoom {
      transform: scale(1.05);
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes pulse-ring {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(11, 102, 68, 0.55); }
      70% { transform: scale(1); box-shadow: 0 0 0 12px rgba(11, 102, 68, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(11, 102, 68, 0); }
    }

    .pulse-hotline {
      animation: pulse-ring 2.2s infinite;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ===================================================================== -->
  <!-- FLATSOME TOP BAR (Thông tin liên hệ ngắn gọn - không gây tràn viền)   -->
  <!-- ===================================================================== -->
  <div class="bg-brand-dark text-white text-xs py-2 border-b border-white/10">
    <div class="gt-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <a href="tel:0985121468" class="inline-flex items-center gap-1.5 hover:text-brand-gold transition-colors">
          <i class="fa-solid fa-phone text-[11px] text-brand-gold"></i>
          <span class="font-medium">0985.121.468</span>
        </a>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden sm:inline-flex items-center gap-1.5 text-white/90">
          <i class="fa-solid fa-location-dot text-[11px] text-brand-gold"></i>
          <span>42 Hoàng Bật Đạt, P. Ngũ Hành Sơn, TP. Đà Nẵng</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <span class="hidden md:inline text-white/80">greentropical.com</span>
        <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" aria-label="Facebook Green Tropical" class="hover:text-brand-gold transition-colors">
          <i class="fa-brands fa-facebook-f"></i>
        </a>
        <a href="https://zalo.me/0985121468" target="_blank" rel="noopener noreferrer" aria-label="Zalo Green Tropical" class="hover:text-brand-gold transition-colors font-bold text-[11px]">
          Zalo
        </a>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- FLATSOME MAIN HEADER (Logo gọn nhỏ + Menu 1 hàng - không nút gọi ngay)-->
  <!-- ===================================================================== -->
  <header id="site-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
    <div class="gt-container flex items-center justify-between gap-2 py-2.5">

      <!-- Logo Công Ty Green Tropical thiết kế gọn nhỏ, chuyên nghiệp -->
      <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Trang chủ Green Tropical">
        <svg class="w-9 h-9 md:w-10 md:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Green Tropical">
          <rect x="2" y="2" width="60" height="60" rx="14" fill="#0B6644"/>
          <rect x="4" y="4" width="56" height="56" rx="12" stroke="#C89B3C" stroke-opacity="0.45" stroke-width="1.5"/>
          <!-- Khung mái kiến trúc hiện đại -->
          <path d="M14 35L32 19L50 35" stroke="#FFFFFF" stroke-width="3.4" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M19 32V48H45V32" stroke="#FFFFFF" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
          <!-- Cột kiến trúc & cửa sổ -->
          <path d="M28 48V37H36V48" stroke="#C89B3C" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
          <!-- Lá nhiệt đới xanh & vàng kim biểu trưng Green Tropical -->
          <path d="M32 19C35 12 44 10 48 15C44 21 37 22 32 19Z" fill="#C89B3C"/>
          <path d="M32 19C29 14 23 12 19 16C22 20 28 21 32 19Z" fill="#34D399"/>
        </svg>
        <div class="leading-tight">
          <div class="text-[13px] sm:text-[15px] font-extrabold tracking-tight text-brand-primary whitespace-nowrap">
            GREEN <span class="text-brand-gold">TROPICAL</span>
          </div>
          <div class="text-[9px] sm:text-[10px] font-semibold tracking-wider text-slate-500 uppercase whitespace-nowrap">
            Thiết Kế &amp; Xây Dựng
          </div>
        </div>
      </a>

      <!-- Menu Desktop: viết liền trên đúng 1 hàng, chữ nhỏ gọn, không xuống dòng -->
      <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-0.5 xl:gap-1.5" aria-label="Menu chính">
        <a href="#trang-chu" class="px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-brand-primary hover:text-brand-gold whitespace-nowrap transition-colors">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Giới thiệu
        </a>

        <!-- Dropdown Công trình thực tế (theo web mẫu tintruongthinh.com) -->
        <div class="nav-item">
          <a href="#cong-trinh-thuc-te" class="px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap inline-flex items-center gap-1 transition-colors">
            <span>Công trình thực tế</span>
            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
          </a>
          <div class="nav-dropdown absolute left-0 top-full w-56 bg-white rounded-lg shadow-lg border border-slate-100 py-2 z-50">
            <button type="button" onclick="filterAndScroll('nha-pho')" class="w-full text-left px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary">Nhà phố</button>
            <button type="button" onclick="filterAndScroll('biet-thu')" class="w-full text-left px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary">Biệt thự</button>
            <button type="button" onclick="filterAndScroll('khach-san')" class="w-full text-left px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary">Khách sạn – Căn hộ – Phòng trọ</button>
            <button type="button" onclick="filterAndScroll('van-phong')" class="w-full text-left px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary">Văn phòng</button>
          </div>
        </div>

        <!-- Dropdown Lĩnh vực hoạt động -->
        <div class="nav-item">
          <a href="#dich-vu" class="px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap inline-flex items-center gap-1 transition-colors">
            <span>Lĩnh vực hoạt động</span>
            <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
          </a>
          <div class="nav-dropdown absolute left-0 top-full w-56 bg-white rounded-lg shadow-lg border border-slate-100 py-2 z-50">
            <a href="#dich-vu" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary">Thiết kế Kiến trúc – Nội thất</a>
            <a href="#dich-vu" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary">Thi công phần thô</a>
            <a href="#dich-vu" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary">Thi công hoàn thiện</a>
            <a href="#dich-vu" class="block px-4 py-2 text-[12.5px] font-medium text-slate-700 hover:bg-brand-light hover:text-brand-primary">Thi công nội thất</a>
          </div>
        </div>

        <a href="#du-an-da-nang" class="px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Dự án Đà Nẵng
        </a>
        <a href="#bao-gia" class="px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Báo giá
        </a>
        <a href="#doi-tac" class="px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Đối tác
        </a>
        <a href="#tin-tuc" class="px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Tin tức
        </a>
        <a href="#lien-he" class="px-2 xl:px-2.5 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Liên hệ
        </a>
      </nav>

      <!-- Nút mở Menu Mobile -->
      <button id="mobile-menu-btn" type="button" aria-label="Mở danh mục menu" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-primary hover:bg-brand-light transition-colors">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>

    <!-- Menu Mobile xổ xuống gọn gàng -->
    <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
      <div class="gt-container py-3 flex flex-col gap-1">
        <a href="#trang-chu" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg text-sm font-semibold text-brand-primary bg-brand-light">Trang chủ</a>
        <a href="#gioi-thieu" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg text-sm font-medium text-slate-700 hover:bg-slate-50">Giới thiệu</a>
        <a href="#dich-vu" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg text-sm font-medium text-slate-700 hover:bg-slate-50">Lĩnh vực hoạt động</a>
        <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg text-sm font-medium text-slate-700 hover:bg-slate-50">Công trình thực tế</a>
        <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg text-sm font-medium text-slate-700 hover:bg-slate-50">Dự án tại Đà Nẵng</a>
        <a href="#bao-gia" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg text-sm font-medium text-slate-700 hover:bg-slate-50">Yêu cầu &amp; Báo giá</a>
        <a href="#doi-tac" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg text-sm font-medium text-slate-700 hover:bg-slate-50">Đối tác</a>
        <a href="#tin-tuc" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg text-sm font-medium text-slate-700 hover:bg-slate-50">Tin tức</a>
        <a href="#lien-he" onclick="closeMobileMenu()" class="px-3 py-2.5 rounded-lg text-sm font-medium text-slate-700 hover:bg-slate-50">Liên hệ &amp; Bản đồ</a>
      </div>
    </div>
  </header>

  <main id="trang-chu">

    <!-- =================================================================== -->
    <!-- FLATSOME SECTION 1: 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU         -->
    <!-- Thiết kế hình ảnh & chữ nằm trọn trong banner, chữ cách xa viền     -->
    <!-- =================================================================== -->
    <section class="py-3 md:py-4 bg-white">
      <div class="gt-container">
        <div id="hero-slider" class="relative w-full overflow-hidden rounded-2xl shadow-md bg-brand-dark">
          <div id="banner-track" class="banner-track">

            <!-- BANNER 1 -->
            <div class="banner-slide relative flex items-center min-h-[340px] sm:min-h-[400px] md:min-h-[460px] lg:min-h-[510px]">
              <img
                src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                data-fallback="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
                onerror="handleImgError(this, 'Thiết Kế & Xây Dựng Green Tropical')"
                alt="Thi công xây dựng trọn gói Green Tropical Đà Nẵng"
                class="absolute inset-0 w-full h-full object-cover object-center"
              />
              <!-- Lớp phủ gradient đảm bảo chữ tương phản sắc nét -->
              <div class="absolute inset-0 bg-gradient-to-r from-[#063825]/92 via-[#0B6644]/78 to-[#063825]/45"></div>

              <!-- Vùng an toàn chữ cách xa viền ảnh banner cả 4 phía trên mobile và desktop -->
              <div class="relative z-10 w-full px-11 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-12 md:py-16">
                <div class="max-w-2xl">
                  <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-brand-gold mb-2 sm:mb-3">
                    CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG GREEN TROPICAL
                  </p>
                  <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3 sm:mb-4">
                    Thiết Kế Kiến Trúc &amp; Thi Công Xây Dựng Trọn Gói Đà Nẵng
                  </h1>
                  <p class="text-xs sm:text-sm md:text-base text-white/90 leading-relaxed mb-5 sm:mb-7 max-w-xl">
                    Kiến tạo không gian sống xanh bền vững cho nhà phố, biệt thự, khách sạn và căn hộ với quy trình giám sát chuẩn kỹ thuật, minh bạch chi phí và đúng tiến độ.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-[#b5892f] text-white font-semibold text-xs sm:text-sm transition-colors shadow">
                      Nhận Báo Giá Miễn Phí
                    </a>
                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition-colors">
                      Xem Công Trình Thực Tế
                    </a>
                  </div>
                </div>
              </div>
            </div>

            <!-- BANNER 2 (Cùng kích thước min-h và khoảng lề an toàn giống hệt Banner 1) -->
            <div class="banner-slide relative flex items-center min-h-[340px] sm:min-h-[400px] md:min-h-[460px] lg:min-h-[510px]">
              <img
                src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1600"
                data-fallback="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1600"
                onerror="handleImgError(this, 'Thi Công Hoàn Thiện & Nội Thất Đà Nẵng')"
                alt="Thi công hoàn thiện biệt thự và nội thất Green Tropical"
                class="absolute inset-0 w-full h-full object-cover object-center"
              />
              <div class="absolute inset-0 bg-gradient-to-r from-[#063825]/92 via-[#0B6644]/78 to-[#063825]/45"></div>

              <div class="relative z-10 w-full px-11 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-12 md:py-16">
                <div class="max-w-2xl">
                  <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-brand-gold mb-2 sm:mb-3">
                    NHÀ Ở GIA ĐÌNH – TIÊU CHUẨN CÔNG TRÌNH
                  </p>
                  <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3 sm:mb-4">
                    Thi Công Phần Thô, Hoàn Thiện &amp; Nội Thất Cao Cấp
                  </h2>
                  <p class="text-xs sm:text-sm md:text-base text-white/90 leading-relaxed mb-5 sm:mb-7 max-w-xl">
                    Đội ngũ kiến trúc sư và kỹ sư giàu kinh nghiệm tại Đà Nẵng trực tiếp đồng hành từ bản vẽ thiết kế 3D đến bàn giao chìa khóa trao tay và bảo hành dài hạn.
                  </p>
                  <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                    <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-[#b5892f] text-white font-semibold text-xs sm:text-sm transition-colors shadow">
                      Dự Án Tại Đà Nẵng
                    </a>
                    <a href="#lien-he" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition-colors">
                      Liên Hệ Tư Vấn
                    </a>
                  </div>
                </div>
              </div>
            </div>

          </div>

          <!-- Nút chuyển trái / phải gọn sát mép, không đè chữ -->
          <button id="banner-prev" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-primary text-white flex items-center justify-center transition-colors">
            <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
          </button>
          <button id="banner-next" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-primary text-white flex items-center justify-center transition-colors">
            <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
          </button>

          <!-- Chấm chỉ báo 2 slide -->
          <div class="absolute bottom-3 sm:bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
            <button type="button" data-slide="0" aria-label="Xem banner 1" class="banner-dot w-7 h-2 rounded-full bg-brand-gold transition-all"></button>
            <button type="button" data-slide="1" aria-label="Xem banner 2" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- FLATSOME SECTION 2: DỊCH VỤ TIÊU BIỂU (Row 4 Col chuẩn web mẫu)     -->
    <!-- =================================================================== -->
    <section id="dich-vu" class="py-10 md:py-12 bg-white">
      <div class="gt-container">
        <div class="text-center mb-7">
          <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Lĩnh Vực Hoạt Động Tiêu Biểu
          </h2>
        </div>

        <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Dịch vụ 1 -->
          <a href="#bao-gia" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-all">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800" data-fallback="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w800" onerror="handleImgError(this, 'Thiết Kế Kiến Trúc')" alt="Thiết kế Kiến trúc - Nội thất" class="img-zoom w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-4 text-center">
              <h3 class="text-xs sm:text-sm md:text-[15px] font-bold text-brand-primary uppercase leading-snug break-words">
                Thiết Kế Kiến Trúc – Nội Thất
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                Phối cảnh 3D tối ưu công năng, thẩm mỹ xanh nhiệt đới và phong thủy.
              </p>
            </div>
          </a>

          <!-- Dịch vụ 2 -->
          <a href="#bao-gia" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-all">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800" data-fallback="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w800" onerror="handleImgError(this, 'Thi Công Phần Thô')" alt="Thi công phần thô" class="img-zoom w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-4 text-center">
              <h3 class="text-xs sm:text-sm md:text-[15px] font-bold text-brand-primary uppercase leading-snug break-words">
                Thi Công Phần Thô
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                Kết cấu móng, khung bê tông cốt thép vững chắc, vật tư đúng cam kết.
              </p>
            </div>
          </a>

          <!-- Dịch vụ 3 -->
          <a href="#bao-gia" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-all">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800" data-fallback="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w800" onerror="handleImgError(this, 'Thi Công Hoàn Thiện')" alt="Thi công hoàn thiện trọn gói" class="img-zoom w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-4 text-center">
              <h3 class="text-xs sm:text-sm md:text-[15px] font-bold text-brand-primary uppercase leading-snug break-words">
                Thi Công Hoàn Thiện
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                Xây nhà trọn gói chìa khóa trao tay, kiểm soát sắc nét từng hạng mục.
              </p>
            </div>
          </a>

          <!-- Dịch vụ 4 -->
          <a href="#bao-gia" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-all">
            <div class="aspect-[4/3] overflow-hidden bg-slate-100">
              <img src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800" data-fallback="https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO=w800" onerror="handleImgError(this, 'Thi Công Nội Thất')" alt="Thi công nội thất trọn gói" class="img-zoom w-full h-full object-cover" />
            </div>
            <div class="p-3 sm:p-4 text-center">
              <h3 class="text-xs sm:text-sm md:text-[15px] font-bold text-brand-primary uppercase leading-snug break-words">
                Thi Công Nội Thất
              </h3>
              <p class="mt-1.5 text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                Sản xuất và lắp đặt nội thất tinh tế, đồng bộ bản vẽ cho nhà ở &amp; văn phòng.
              </p>
            </div>
          </a>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- FLATSOME SECTION 3: GIỚI THIỆU & THẾ MẠNH CỦA CHÚNG TÔI            -->
    <!-- =================================================================== -->
    <section id="gioi-thieu" class="py-10 md:py-14 bg-brand-light/70 border-y border-emerald-100">
      <div class="gt-container">
        <!-- Giới thiệu công ty -->
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10">
          <div class="lg:col-span-5">
            <div class="rounded-2xl overflow-hidden shadow-md border border-white bg-white">
              <img
                src="https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w1000"
                data-fallback="https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT=w1000"
                onerror="handleImgError(this, 'Green Tropical Đà Nẵng')"
                alt="Giới thiệu Công ty TNHH Thiết Kế và Xây Dựng Green Tropical"
                class="w-full aspect-[4/3] object-cover"
              />
            </div>
          </div>
          <div class="lg:col-span-7">
            <p class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">Về Chúng Tôi</p>
            <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-primary leading-snug mb-4">
              CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG GREEN TROPICAL
            </h2>
            <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-3">
              <strong>GREEN TROPICAL</strong> là đơn vị chuyên Thiết kế – Xây dựng – Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng tại khu vực Đà Nẵng và miền Trung. Với phương châm <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi đặt sự tận tâm và minh bạch làm nền tảng trong mọi dự án.
            </p>
            <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-5">
              Đặt trụ sở tại <strong>42 Hoàng Bật Đạt, Phường Ngũ Hành Sơn, Thành phố Đà Nẵng</strong>, đội ngũ kiến trúc sư và kỹ sư giám sát hiện trường của Green Tropical luôn bảo đảm mỗi công trình đạt trọn vẹn 4 giá trị cốt lõi: <strong>An Toàn – Chất Lượng – Tiến Độ – Thẩm Mỹ Bền Vững</strong>.
            </p>
            <div class="grid grid-cols-3 gap-3 sm:gap-4 pt-3 border-t border-emerald-200/80">
              <div>
                <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">10+</div>
                <div class="text-xs text-slate-600 mt-0.5">Năm kinh nghiệm</div>
              </div>
              <div>
                <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">120+</div>
                <div class="text-xs text-slate-600 mt-0.5">Công trình bàn giao</div>
              </div>
              <div>
                <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">100%</div>
                <div class="text-xs text-slate-600 mt-0.5">Đúng tiến độ cam kết</div>
              </div>
            </div>
          </div>
        </div>

        <!-- 6 Thế mạnh nổi bật giống web mẫu tintruongthinh.com -->
        <div class="text-center mb-7">
          <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Thế Mạnh Của Chúng Tôi
          </h2>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
          <div class="bg-white rounded-xl p-5 border border-emerald-100 shadow-sm flex items-start gap-3.5">
            <div class="w-11 h-11 rounded-xl bg-brand-light text-brand-primary flex items-center justify-center shrink-0">
              <i class="fa-solid fa-compass-drafting text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 mb-1">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h3>
              <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư, thợ thi công lành nghề giàu kinh nghiệm thực chiến.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-emerald-100 shadow-sm flex items-start gap-3.5">
            <div class="w-11 h-11 rounded-xl bg-brand-light text-brand-primary flex items-center justify-center shrink-0">
              <i class="fa-solid fa-leaf text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 mb-1">Cập nhật xu hướng kiến trúc xanh hiện đại</h3>
              <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Ứng dụng giải pháp thông gió tự nhiên, vật liệu bền bỉ và phương pháp thi công tiên tiến.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-emerald-100 shadow-sm flex items-start gap-3.5">
            <div class="w-11 h-11 rounded-xl bg-brand-light text-brand-primary flex items-center justify-center shrink-0">
              <i class="fa-solid fa-clipboard-check text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 mb-1">Giám sát tiến độ chuẩn xác</h3>
              <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Báo cáo hình ảnh công trường định kỳ, giúp gia chủ dễ dàng theo dõi ngôi nhà từ xa.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-emerald-100 shadow-sm flex items-start gap-3.5">
            <div class="w-11 h-11 rounded-xl bg-brand-light text-brand-primary flex items-center justify-center shrink-0">
              <i class="fa-solid fa-shield-halved text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 mb-1">Bảo hành công trình lâu dài</h3>
              <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Chính sách bảo hành kết cấu và hoàn thiện rõ ràng, luôn đồng hành hỗ trợ hậu mãi tận tâm.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-emerald-100 shadow-sm flex items-start gap-3.5">
            <div class="w-11 h-11 rounded-xl bg-brand-light text-brand-primary flex items-center justify-center shrink-0">
              <i class="fa-solid fa-file-invoice-dollar text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 mb-1">Giá cả hợp lý, không phát sinh</h3>
              <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Dự toán bóc tách chi tiết từng hạng mục, tối ưu ngân sách và bảo đảm chất lượng vật tư.</p>
            </div>
          </div>

          <div class="bg-white rounded-xl p-5 border border-emerald-100 shadow-sm flex items-start gap-3.5">
            <div class="w-11 h-11 rounded-xl bg-brand-light text-brand-primary flex items-center justify-center shrink-0">
              <i class="fa-solid fa-headset text-lg"></i>
            </div>
            <div>
              <h3 class="text-sm sm:text-[15px] font-bold text-slate-800 mb-1">Hỗ trợ tư vấn miễn phí 24/7</h3>
              <p class="text-xs sm:text-[13px] text-slate-600 leading-relaxed">Sẵn sàng khảo sát thực tế, tư vấn phương án thiết kế và khái toán chi phí hoàn toàn miễn phí.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- FLATSOME SECTION 4: CÔNG TRÌNH THI CÔNG THỰC TẾ (9 ẢNH DRIVE THỰC) -->
    <!-- Không dán nhãn trên ảnh, chữ danh mục nhỏ gọn, 2 cột trên điện thoại-->
    <!-- =================================================================== -->
    <section id="cong-trinh-thuc-te" class="py-10 md:py-14 bg-white">
      <div class="gt-container">
        <div class="text-center mb-6">
          <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Công Trình Thi Công Thực Tế
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
            Hình ảnh thực tế các công trình do đội ngũ Green Tropical trực tiếp thiết kế và thi công xây dựng.
          </p>
        </div>

        <!-- Thanh lọc danh mục: chữ nhỏ gọn, tên danh mục viết liền không bị ngắt dòng -->
        <div id="project-tabs" class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
          <button type="button" data-filter="all" onclick="filterProjects('all', this)" class="cat-tab active px-3 sm:px-4 py-1.5 sm:py-2 rounded-full text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-brand-primary text-white border border-brand-primary transition-all">
            Tất cả
          </button>
          <button type="button" data-filter="nha-pho" onclick="filterProjects('nha-pho', this)" class="cat-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-full text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-all">
            Nhà phố
          </button>
          <button type="button" data-filter="biet-thu" onclick="filterProjects('biet-thu', this)" class="cat-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-full text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-all">
            Biệt thự
          </button>
          <button type="button" data-filter="khach-san" onclick="filterProjects('khach-san', this)" class="cat-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-full text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-all">
            Khách sạn - Căn hộ
          </button>
          <button type="button" data-filter="van-phong" onclick="filterProjects('van-phong', this)" class="cat-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-full text-[11.5px] sm:text-[13px] font-semibold whitespace-nowrap bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-all">
            Văn phòng
          </button>
        </div>

        <!-- Lưới sản phẩm / công trình: đúng 2 cột trên điện thoại, 3-4 cột trên máy tính -->
        <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 xl:grid-cols-3 gap-3 sm:gap-5">
          <!-- Render tự động bằng JS từ 9 file Google Drive thực tế -->
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- FLATSOME SECTION 5: DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH DRIVE)    -->
    <!-- =================================================================== -->
    <section id="du-an-da-nang" class="py-10 md:py-14 bg-brand-light/55 border-y border-emerald-100">
      <div class="gt-container">
        <div class="text-center mb-7">
          <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Các Dự Án Tiêu Biểu Tại Đà Nẵng
          </h2>
          <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
            Tổng hợp các dự án nhà phố, biệt thự, căn hộ và khách sạn tiêu biểu mà Green Tropical triển khai tại các quận Ngũ Hành Sơn, Sơn Trà, Hải Châu, Cẩm Lệ và Hòa Xuân – Đà Nẵng.
          </p>
        </div>

        <!-- 2 cột trên điện thoại, 4-5 cột trên máy tính; tên sản phẩm hiển thị đầy đủ không thiếu chữ -->
        <div id="danang-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-3 sm:gap-4">
          <!-- Render tự động bằng JS từ 10 file Google Drive dự án Đà Nẵng -->
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- FLATSOME SECTION 6: FORM YÊU CẦU & BÁO GIÁ (MIỄN PHÍ TƯ VẤN)       -->
    <!-- =================================================================== -->
    <section id="bao-gia" class="py-10 md:py-14 bg-white">
      <div class="gt-container">
        <div class="rounded-2xl overflow-hidden border border-emerald-200 shadow-md bg-gradient-to-br from-brand-dark via-brand-primary to-[#127A52] p-5 sm:p-8 lg:p-10">
          <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">

            <!-- Cột thông tin báo giá tham khảo theo web mẫu -->
            <div class="lg:col-span-5 text-white">
              <p class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">Miễn Phí Tư Vấn 24/7</p>
              <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold leading-snug mb-3">
                Yêu Cầu Tư Vấn &amp; Nhận Báo Giá Chi Tiết
              </h2>
              <p class="text-xs sm:text-sm text-white/90 leading-relaxed mb-5">
                Gửi thông tin dự án của Quý khách để kiến trúc sư Green Tropical tư vấn phương án thiết kế tối ưu và lập bảng dự toán xây dựng minh bạch nhất.
              </p>

              <div class="space-y-2.5 text-xs sm:text-sm bg-white/10 rounded-xl p-4 border border-white/15">
                <div class="flex items-center justify-between gap-2 pb-2 border-b border-white/15">
                  <span class="text-white/90">Thiết kế Kiến trúc – Nội thất</span>
                  <span class="font-bold text-brand-gold whitespace-nowrap">Từ 120.000đ/m²</span>
                </div>
                <div class="flex items-center justify-between gap-2 pb-2 border-b border-white/15">
                  <span class="text-white/90">Thi công phần thô &amp; nhân công</span>
                  <span class="font-bold text-brand-gold whitespace-nowrap">Từ 3.500.000đ/m²</span>
                </div>
                <div class="flex items-center justify-between gap-2">
                  <span class="text-white/90">Thi công trọn gói chìa khóa trao tay</span>
                  <span class="font-bold text-brand-gold whitespace-nowrap">Từ 5.800.000đ/m²</span>
                </div>
              </div>
            </div>

            <!-- Cột Form nhập liệu chuẩn mẫu tintruongthinh.com -->
            <div class="lg:col-span-7 bg-white rounded-xl p-5 sm:p-6 shadow-lg">
              <form id="quote-form" class="space-y-3.5" novalidate>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                  <div>
                    <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                    <input id="q-name" type="text" required placeholder="Nhập họ tên Quý khách" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15" />
                  </div>
                  <div>
                    <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại *</label>
                    <input id="q-phone" type="tel" required placeholder="Ví dụ: 0985.121.468" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15" />
                  </div>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                  <div>
                    <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                    <select id="q-type" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary">
                      <option value="Nhà phố">Nhà phố</option>
                      <option value="Biệt thự">Biệt thự</option>
                      <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                      <option value="Văn phòng">Văn phòng</option>
                      <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                    </select>
                  </div>
                  <div>
                    <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                    <select id="q-budget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary">
                      <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                      <option value="500 triệu - 1 tỷ">500 triệu - 1 tỷ</option>
                      <option value="1 - 2 tỷ" selected>1 - 2 tỷ</option>
                      <option value="2 - 3 tỷ">2 - 3 tỷ</option>
                      <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                    </select>
                  </div>
                </div>

                <div>
                  <label for="q-email" class="block text-xs font-semibold text-slate-700 mb-1">Email (không bắt buộc)</label>
                  <input id="q-email" type="email" placeholder="Nhập địa chỉ email nhận bảng dự toán" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15" />
                </div>

                <div>
                  <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu chi tiết / Diện tích đất</label>
                  <textarea id="q-note" rows="3" placeholder="Ví dụ: Xây nhà phố 3 tầng diện tích 5x20m tại Ngũ Hành Sơn, Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/15"></textarea>
                </div>

                <!-- Hộp thông báo trạng thái form (thay thế hoàn toàn alert) -->
                <div id="quote-feedback" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium"></div>

                <button type="submit" class="w-full py-3 px-6 rounded-lg bg-brand-primary hover:bg-brand-dark text-white font-bold text-sm uppercase tracking-wide transition-colors shadow-sm">
                  Gửi Yêu Cầu Báo Giá Ngay
                </button>
              </form>
            </div>

          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- FLATSOME SECTION 7: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ      -->
    <!-- =================================================================== -->
    <section id="tin-tuc" class="py-10 md:py-14 bg-slate-50 border-t border-slate-200/70">
      <div class="gt-container">
        <div class="text-center mb-7">
          <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Tin Tức &amp; Kinh Nghiệm Xây Dựng
          </h2>
        </div>

        <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
        <div id="news-grid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
          <!-- Render bài viết bằng JS -->
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- FLATSOME SECTION 8: DANH MỤC CÁC ĐỐI TÁC                           -->
    <!-- =================================================================== -->
    <section id="doi-tac" class="py-10 md:py-12 bg-white border-t border-slate-200/70">
      <div class="gt-container">
        <div class="text-center mb-7">
          <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Đối Tác Cung Ứng Vật Tư &amp; Thiết Bị
          </h2>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-3 sm:gap-4">
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">HÒA PHÁT</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng</span>
          </div>
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">VICEM</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Xi măng cao cấp</span>
          </div>
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">JOTUN</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
          </div>
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">DULUX</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Sơn chống thấm</span>
          </div>
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">AN CƯỜNG</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Gỗ nội thất</span>
          </div>
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">TOTO</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh</span>
          </div>
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">XINGFA</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Cửa nhôm kính</span>
          </div>
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">PANASONIC</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện</span>
          </div>
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">CADIVI</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Dây cáp điện</span>
          </div>
          <div class="rounded-xl border border-slate-200 bg-slate-50/70 hover:border-brand-primary hover:bg-white transition-all py-4 px-3 flex flex-col items-center justify-center text-center">
            <span class="text-sm sm:text-base font-extrabold tracking-tight text-brand-primary">VIGLACERA</span>
            <span class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát</span>
          </div>
        </div>
      </div>
    </section>

    <!-- =================================================================== -->
    <!-- FLATSOME SECTION 9: GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ  -->
    <!-- =================================================================== -->
    <section id="lien-he" class="py-10 md:py-14 bg-brand-light/60 border-t border-emerald-100">
      <div class="gt-container">
        <div class="text-center mb-7">
          <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand-primary tracking-tight">
            Bản Đồ Chỉ Đường &amp; Fanpage Chính Thức
          </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
          <!-- Cột Trái: Ảnh Bản Đồ Google Map thực tế ngoài trang chủ -->
          <div class="lg:col-span-7 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
            <div class="px-4 py-3 bg-brand-primary text-white flex flex-wrap items-center justify-between gap-2">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-semibold">
                <i class="fa-solid fa-map-location-dot text-brand-gold"></i>
                <span>42 Hoàng Bật Đạt, Phường Ngũ Hành Sơn, TP. Đà Nẵng</span>
              </div>
              <a href="https://www.google.com/maps/search/?api=1&query=42+Ho%C3%A0ng+B%E1%BA%ADt+%C4%90%E1%BA%A1t,+Ng%C5%A9+H%C3%A0nh+S%C6%A1n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] sm:text-xs font-semibold text-brand-gold hover:underline whitespace-nowrap">
                Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
              </a>
            </div>
            <div class="w-full flex-1 min-h-[290px] sm:min-h-[340px]">
              <iframe
                title="Bản đồ Công ty TNHH Thiết Kế và Xây Dựng Green Tropical - 42 Hoàng Bật Đạt, Ngũ Hành Sơn, Đà Nẵng"
                src="https://maps.google.com/maps?q=42%20Ho%C3%A0ng%20B%E1%BA%ADt%20%C4%90%E1%BA%A1t,%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full min-h-[290px] sm:min-h-[340px] border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <!-- Cột Phải: Khung Fanpage Facebook hiển thị ngay ngoài trang chủ -->
          <div class="lg:col-span-5 bg-white rounded-2xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
            <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
              <div class="flex items-center gap-2 text-xs sm:text-sm font-semibold">
                <i class="fa-brands fa-facebook"></i>
                <span>Fanpage Facebook Green Tropical</span>
              </div>
              <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="text-[11px] sm:text-xs font-semibold text-white/90 hover:underline">
                Theo dõi
              </a>
            </div>

            <!-- Giao diện mô phỏng chuẩn Facebook Page Plugin luôn hiển thị sắc nét -->
            <div class="p-4 flex-1 flex flex-col justify-between gap-4">
              <!-- Cover + Avatar Fanpage -->
              <div class="rounded-xl overflow-hidden border border-slate-200">
                <div class="relative h-32 sm:h-36 bg-brand-dark">
                  <img
                    src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800"
                    data-fallback="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w800"
                    onerror="handleImgError(this, 'Fanpage Green Tropical')"
                    alt="Ảnh bìa Fanpage Green Tropical"
                    class="w-full h-full object-cover"
                  />
                  <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/30 to-transparent"></div>
                  <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                    <div class="w-12 h-12 rounded-xl bg-brand-primary border-2 border-white flex items-center justify-center shrink-0 shadow">
                      <svg class="w-8 h-8" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 35L32 19L50 35" stroke="#FFFFFF" stroke-width="3.6" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M19 32V48H45V32" stroke="#FFFFFF" stroke-width="3" stroke-linecap="round" stroke-linejoin="round"/>
                        <path d="M32 19C35 12 44 10 48 15C44 21 37 22 32 19Z" fill="#C89B3C"/>
                      </svg>
                    </div>
                    <div class="min-w-0 text-white">
                      <div class="text-sm font-bold leading-tight break-words">Thiết Kế &amp; Xây Dựng Green Tropical</div>
                      <div class="text-[11px] text-white/85 mt-0.5">greentropical.com • Đà Nẵng</div>
                    </div>
                  </div>
                </div>

                <!-- Thanh nút Thích Trang & Nhắn tin -->
                <div class="p-3 bg-slate-50 flex flex-wrap items-center justify-between gap-2">
                  <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-md bg-[#1877F2] hover:bg-[#1465ce] text-white text-xs font-semibold transition-colors">
                    <i class="fa-solid fa-thumbs-up"></i>
                    <span>Thích Trang</span>
                  </a>
                  <a href="https://m.me/greentropical.danang" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-md bg-white hover:bg-slate-100 text-slate-700 border border-slate-300 text-xs font-semibold transition-colors">
                    <i class="fa-brands fa-facebook-messenger text-[#0084FF]"></i>
                    <span>Nhắn tin tư vấn</span>
                  </a>
                </div>
              </div>

              <!-- Bài đăng cập nhật mới trên Fanpage -->
              <div class="rounded-xl border border-slate-200 p-3.5 bg-white">
                <div class="flex items-center justify-between gap-2 mb-2">
                  <span class="text-xs font-bold text-brand-primary">Cập nhật công trường mới nhất</span>
                  <span class="text-[11px] text-slate-400">Đà Nẵng</span>
                </div>
                <p class="text-xs text-slate-600 leading-relaxed mb-3">
                  Bàn giao hồ sơ thiết kế &amp; khởi công công trình nhà phố hiện đại tại Ngũ Hành Sơn, Đà Nẵng. Liên hệ Hotline <strong>0985.121.468</strong> để nhận ưu đãi thiết kế khi thi công trọn gói.
                </p>
                <div class="flex items-center gap-4 text-[11px] text-slate-500 pt-2 border-t border-slate-100">
                  <span><i class="fa-regular fa-thumbs-up mr-1 text-[#1877F2]"></i>186 lượt thích</span>
                  <span><i class="fa-regular fa-comment mr-1"></i>24 bình luận</span>
                  <span><i class="fa-solid fa-share mr-1"></i>15 chia sẻ</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <!-- ===================================================================== -->
  <!-- FLATSOME FOOTER                                                       -->
  <!-- ===================================================================== -->
  <footer class="bg-brand-dark text-white pt-10 pb-6 border-t-4 border-brand-gold">
    <div class="gt-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/15">

        <!-- Cột 1: Thông tin công ty -->
        <div class="lg:col-span-5">
          <div class="flex items-center gap-2.5 mb-4">
            <svg class="w-10 h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect x="2" y="2" width="60" height="60" rx="14" fill="#0B6644" stroke="#C89B3C" stroke-width="2"/>
              <path d="M14 35L32 19L50 35" stroke="#FFFFFF" stroke-width="3.4" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M19 32V48H45V32" stroke="#FFFFFF" stroke-width="2.8" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M28 48V37H36V48" stroke="#C89B3C" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M32 19C35 12 44 10 48 15C44 21 37 22 32 19Z" fill="#C89B3C"/>
            </svg>
            <div>
              <div class="text-sm sm:text-base font-extrabold tracking-tight text-white">CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG GREEN TROPICAL</div>
              <div class="text-xs text-brand-gold font-semibold">Website: greentropical.com</div>
            </div>
          </div>

          <ul class="space-y-2 text-xs sm:text-sm text-white/85">
            <li class="flex items-start gap-2.5">
              <i class="fa-solid fa-location-dot text-brand-gold mt-1 shrink-0"></i>
              <span>Địa chỉ: 42 Hoàng Bật Đạt, Phường Ngũ Hành Sơn, Thành phố Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-phone text-brand-gold shrink-0"></i>
              <a href="tel:0985121468" class="hover:text-brand-gold transition-colors">Hotline / Zalo: 0985.121.468</a>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-globe text-brand-gold shrink-0"></i>
              <span>Website: greentropical.com</span>
            </li>
            <li class="flex items-center gap-2.5">
              <i class="fa-solid fa-building-shield text-brand-gold shrink-0"></i>
              <span>Mã số thuế: 0402214185</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3">
          <h3 class="text-sm font-bold uppercase tracking-wide text-brand-gold mb-3">Lĩnh Vực Hoạt Động</h3>
          <ul class="space-y-2 text-xs sm:text-sm text-white/85">
            <li><a href="#dich-vu" class="hover:text-brand-gold transition-colors">Thiết kế Kiến trúc – Nội thất</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-gold transition-colors">Thi công phần thô</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-gold transition-colors">Thi công hoàn thiện trọn gói</a></li>
            <li><a href="#dich-vu" class="hover:text-brand-gold transition-colors">Thi công nội thất cao cấp</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-gold transition-colors">Cải tạo &amp; sửa chữa nhà Đà Nẵng</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục công trình -->
        <div class="lg:col-span-4">
          <h3 class="text-sm font-bold uppercase tracking-wide text-brand-gold mb-3">Danh Mục Công Trình</h3>
          <ul class="space-y-2 text-xs sm:text-sm text-white/85">
            <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-gold transition-colors">Công trình thi công thực tế</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-brand-gold transition-colors">Các dự án tiêu biểu tại Đà Nẵng</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-gold transition-colors">Bảng báo giá thiết kế &amp; xây dựng</a></li>
            <li><a href="#doi-tac" class="hover:text-brand-gold transition-colors">Đối tác cung ứng vật tư</a></li>
            <li><a href="#tin-tuc" class="hover:text-brand-gold transition-colors">Tin tức &amp; kinh nghiệm xây nhà</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-5 text-center text-xs text-white/70">
        Copyright © 2026 CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG GREEN TROPICAL (greentropical.com). All rights reserved.
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (MOBILE & DESKTOP)  -->
  <!-- ===================================================================== -->
  <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
    <!-- Nút Zalo -->
    <a href="https://zalo.me/0985121468" target="_blank" rel="noopener noreferrer" aria-label="Liên hệ Zalo 0985.121.468" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0054d1] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition-all">
      <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Facebook Messenger -->
    <a href="https://m.me/greentropical.danang" target="_blank" rel="noopener noreferrer" aria-label="Nhắn tin Facebook Messenger" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#125ec2] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition-all">
      <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-messenger text-sm"></i>
      </span>
      <span class="hidden sm:inline text-xs font-bold pr-1 whitespace-nowrap">Facebook</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a href="tel:0985121468" aria-label="Gọi Hotline 0985.121.468" class="pulse-hotline flex items-center gap-2 bg-brand-primary hover:bg-brand-dark text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 border-2 border-brand-gold transition-all">
      <span class="w-7 h-7 rounded-full bg-brand-gold text-white flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone text-xs"></i>
      </span>
      <span class="hidden sm:inline text-xs font-extrabold pr-1 whitespace-nowrap">0985.121.468</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- MODAL XEM CHI TIẾT HÌNH ẢNH CÔNG TRÌNH & BÀI VIẾT                    -->
  <!-- ===================================================================== -->
  <div id="detail-modal" class="fixed inset-0 z-50 hidden bg-black/75 backdrop-blur-sm p-3 sm:p-6 flex items-center justify-center" role="dialog" aria-modal="true">
    <div class="bg-white rounded-2xl max-w-3xl w-full max-h-[90vh] overflow-y-auto shadow-2xl">
      <div class="sticky top-0 bg-white border-b border-slate-200 px-4 sm:px-6 py-3.5 flex items-center justify-between gap-3 z-10">
        <h3 id="modal-title" class="text-sm sm:text-base font-bold text-brand-primary leading-snug">Chi tiết công trình</h3>
        <button type="button" onclick="closeModal()" aria-label="Đóng hộp thoại" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 sm:p-6">
        <div class="rounded-xl overflow-hidden bg-slate-100 mb-4">
          <img id="modal-img" src="" alt="" class="w-full max-h-[420px] object-cover" />
        </div>
        <p id="modal-meta" class="text-xs font-semibold text-brand-gold uppercase tracking-wide mb-2"></p>
        <p id="modal-desc" class="text-sm text-slate-700 leading-relaxed mb-5"></p>
        <div class="flex flex-wrap items-center gap-3">
          <a href="#bao-gia" onclick="closeModal()" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg bg-brand-primary hover:bg-brand-dark text-white text-xs sm:text-sm font-semibold transition-colors">
            Nhận Báo Giá Công Trình Tương Tự
          </a>
          <a href="tel:0985121468" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-lg border border-brand-primary text-brand-primary hover:bg-brand-light text-xs sm:text-sm font-semibold transition-colors">
            <i class="fa-solid fa-phone"></i> 0985.121.468
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT: DỮ LIỆU ẢNH GOOGLE DRIVE, SLIDER, BỘ LỌC & FORM          -->
  <!-- ===================================================================== -->
  <script>
    /**
     * Tạo link ảnh trực tiếp từ Google Drive ID với cơ chế fallback nhiều lớp
     */
    function driveThumb(id) {
      return `https://drive.google.com/thumbnail?id=${id}&sz=w1000`;
    }

    function driveFallback(id) {
      return `https://lh3.googleusercontent.com/d/${id}=w1000`;
    }

    /**
     * Xử lý dự phòng nếu trình duyệt chặn ảnh Google Drive -> chuyển sang lh3 -> placeholder
     */
    function handleImgError(img, label) {
      const step = img.getAttribute('data-err-step') || '0';
      if (step === '0' && img.getAttribute('data-fallback')) {
        img.setAttribute('data-err-step', '1');
        img.src = img.getAttribute('data-fallback');
      } else {
        img.onerror = null;
        const safeText = encodeURIComponent(label || 'Green Tropical');
        img.src = `https://placehold.co/800x600/0B6644/FFFFFF?text=${safeText}`;
      }
    }

    /**
     * 1. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (từ 9 link Google Drive)
     */
    const constructionProjects = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi Công Phần Thô Nhà Phố 3 Tầng Hiện Đại',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        desc: 'Công trình nhà phố 3 tầng do Green Tropical trực tiếp thi công kết cấu phần thô chuẩn kỹ thuật, bảo đảm độ bền kết cấu và đúng tiến độ bàn giao.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thi Công Trọn Gói Biệt Thự Vườn Green Tropical',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        desc: 'Thiết kế và thi công trọn gói biệt thự phong cách nhiệt đới hiện đại, hài hòa mảng xanh thiên nhiên và ánh sáng tự nhiên.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thi Công Căn Hộ Cho Thuê & Khách Sạn Mini',
        category: 'khach-san',
        categoryLabel: 'Khách sạn - Căn hộ',
        desc: 'Hạng mục thi công xây dựng hoàn thiện tòa nhà căn hộ dịch vụ cho thuê tối ưu công năng khai thác kinh doanh lưu trú.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Hoàn Thiện Kiến Trúc Mặt Tiền Nhà Phố',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        desc: 'Thi công hoàn thiện mặt tiền nhà phố sắc nét, sử dụng vật liệu sơn ngoại thất và hệ cửa nhôm kính cao cấp bền đẹp theo thời gian.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thi Công Nội Thất Trọn Gói Biệt Thự Cao Cấp',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        desc: 'Sản xuất và lắp đặt nội thất gỗ đồng bộ theo bản vẽ 3D, tối ưu thẩm mỹ sang trọng và tiện nghi sinh hoạt gia đình.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thi Công Kết Cấu Móng & Khung Bê Tông Cốt Thép',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        desc: 'Giám sát nghiêm ngặt quy trình đan thép, ghép cốp pha và đổ bê tông thương phẩm đạt mác tiêu chuẩn xây dựng Việt Nam.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Thiết Kế & Thi Công Văn Phòng Làm Việc Hiện Đại',
        category: 'van-phong',
        categoryLabel: 'Văn phòng',
        desc: 'Không gian văn phòng chuyên nghiệp với bố cục mở, ánh sáng tiêu chuẩn và điểm nhấn cây xanh đặc trưng Green Tropical.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi Công Hoàn Thiện Nhà Phố 2 Mặt Tiền',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        desc: 'Công trình nhà phố 2 mặt tiền kết hợp ở và kinh doanh, hoàn thiện tỉ mỉ hệ thống điện nước, ốp lát và trần thạch cao.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Cải Tạo & Thi Công Trọn Gói Căn Hộ Dịch Vụ',
        category: 'khach-san',
        categoryLabel: 'Khách sạn - Căn hộ',
        desc: 'Giải pháp cải tạo và thi công hoàn thiện đồng bộ căn hộ dịch vụ giúp gia tăng giá trị công trình và tối ưu ngân sách đầu tư.'
      }
    ];

    /**
     * 2. DỮ LIỆU 10 DỰ ÁN TẠI ĐÀ NẴNG (từ 10 link Google Drive)
     */
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Nhà Phố Hiện Đại Ngũ Hành Sơn – Đà Nẵng',
        location: 'Quận Ngũ Hành Sơn, TP. Đà Nẵng',
        desc: 'Dự án thiết kế và thi công trọn gói nhà phố hiện đại tại khu vực Ngũ Hành Sơn, tối ưu thông gió tự nhiên và không gian xanh.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Biệt Thự Nghỉ Dưỡng Ven Biển Mỹ Khê – Đà Nẵng',
        location: 'Ven biển Mỹ Khê, TP. Đà Nẵng',
        desc: 'Biệt thự phong cách nhiệt đới ven biển với kết cấu chống ăn mòn gió biển và không gian sân vườn thư giãn đẳng cấp.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Căn Hộ Dịch Vụ Cao Cấp Sơn Trà – Đà Nẵng',
        location: 'Quận Sơn Trà, TP. Đà Nẵng',
        desc: 'Thi công trọn gói tòa nhà căn hộ dịch vụ gần biển Sơn Trà, đáp ứng tiêu chuẩn vận hành lưu trú du lịch cao cấp.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Nhà Phố 3 Tầng Khu Đô Thị Hòa Xuân – Đà Nẵng',
        location: 'Khu đô thị Hòa Xuân, TP. Đà Nẵng',
        desc: 'Công trình nhà phố 3 tầng hiện đại tại Hòa Xuân được Green Tropical thiết kế kiến trúc, thi công phần thô và hoàn thiện nội thất.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Khách Sạn Boutique Trung Tâm Hải Châu – Đà Nẵng',
        location: 'Quận Hải Châu, TP. Đà Nẵng',
        desc: 'Thiết kế và thi công hoàn thiện khách sạn boutique ngay trung tâm thành phố Đà Nẵng với phong cách kiến trúc tinh tế.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Biệt Thự Sân Vườn Khu Nam Việt Á – Đà Nẵng',
        location: 'Khu Nam Việt Á, TP. Đà Nẵng',
        desc: 'Biệt thự gia đình 2 mặt thoáng tại Khu Nam Việt Á, kết hợp mảng xanh nhiệt đới và nội thất gỗ tự nhiên sang trọng.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Thi Công Trọn Gói Nhà Phố Cẩm Lệ – Đà Nẵng',
        location: 'Quận Cẩm Lệ, TP. Đà Nẵng',
        desc: 'Công trình nhà ở gia đình tại Cẩm Lệ hoàn thành vượt tiến độ với chi phí tối ưu và chất lượng hoàn thiện sắc nét.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Văn Phòng & Showroom Liên Chiểu – Đà Nẵng',
        location: 'Quận Liên Chiểu, TP. Đà Nẵng',
        desc: 'Thiết kế thi công văn phòng kết hợp showroom trưng bày chuyên nghiệp, hiện đại và tối ưu công năng sử dụng.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Nhà Phố 2 Mặt Tiền Khu Phước Lý – Đà Nẵng',
        location: 'Khu đô thị Phước Lý, TP. Đà Nẵng',
        desc: 'Nhà phố góc 2 mặt tiền nổi bật tại Khu Phước Lý với kiến trúc mặt đứng hiện đại, thoáng sáng mọi không gian phòng.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Hoàn Thiện Nội Thất Căn Hộ View Sông Hàn – Đà Nẵng',
        location: 'Sông Hàn, TP. Đà Nẵng',
        desc: 'Hạng mục thiết kế và thi công nội thất trọn gói căn hộ cao cấp hướng nhìn sông Hàn với vật liệu hoàn thiện bền đẹp.'
      }
    ];

    /**
     * 3. DỮ LIỆU BÀI VIẾT TIN TỨC TRANG CHỦ
     */
    const newsArticles = [
      {
        imgId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Hướng dẫn bảo dưỡng bê tông móng đúng kỹ thuật khi xây nhà',
        date: '18/11/2026',
        excerpt: 'Bảo dưỡng bê tông móng đúng quy trình giúp tăng cường độ chịu lực, hạn chế nứt bề mặt và bảo vệ tuổi thọ công trình lâu dài.'
      },
      {
        imgId: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: '03 nỗi lo lớn nhất khi xây nhà mà chủ đầu tư thường gặp phải',
        date: '12/11/2026',
        excerpt: 'Cách kiểm soát chi phí phát sinh, chọn nhà thầu uy tín và giám sát vật tư để quá trình xây tổ ấm luôn nhẹ nhàng, minh bạch.'
      },
      {
        imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Xu hướng kiến trúc xanh nhiệt đới cho nhà phố tại Đà Nẵng',
        date: '05/11/2026',
        excerpt: 'Ứng dụng giếng trời, lam chắn nắng và cây xanh giúp nhà phố miền Trung luôn mát mẻ, tiết kiệm điện năng quanh năm.'
      },
      {
        imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Kinh nghiệm lập dự toán thi công trọn gói năm 2026 không phát sinh',
        date: '28/10/2026',
        excerpt: 'Tổng hợp các hạng mục cần thống nhất rõ ràng trong hợp đồng xây dựng trọn gói để bảo đảm quyền lợi cho gia chủ.'
      }
    ];

    /**
     * Render danh sách Công trình thực tế (không dùng nhãn dán trên ảnh)
     */
    function renderConstruction(filter = 'all') {
      const grid = document.getElementById('construction-grid');
      if (!grid) return;

      const filtered = filter === 'all'
        ? constructionProjects
        : constructionProjects.filter(item => item.category === filter);

      grid.innerHTML = filtered.map((item, idx) => `
        <article
          onclick="openProjectModal('construction', '${item.id}')"
          class="group cursor-pointer rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md hover:border-brand-primary/50 transition-all flex flex-col"
        >
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveThumb(item.id)}"
              data-fallback="${driveFallback(item.id)}"
              onerror="handleImgError(this, '${item.categoryLabel}')"
              alt="${item.title}"
              loading="lazy"
              class="img-zoom w-full h-full object-cover"
            />
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-[12.5px] sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words">
              ${item.title}
            </h3>
            <p class="mt-1.5 text-[11px] sm:text-xs font-medium text-brand-primary">
              ${item.categoryLabel}
            </p>
          </div>
        </article>
      `).join('');
    }

    /**
     * Render danh sách 10 Dự án tại Đà Nẵng
     */
    function renderDanangProjects() {
      const grid = document.getElementById('danang-grid');
      if (!grid) return;

      grid.innerHTML = danangProjects.map(item => `
        <article
          onclick="openProjectModal('danang', '${item.id}')"
          class="group cursor-pointer rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md hover:border-brand-primary/50 transition-all flex flex-col"
        >
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveThumb(item.id)}"
              data-fallback="${driveFallback(item.id)}"
              onerror="handleImgError(this, 'Dự Án Đà Nẵng')"
              alt="${item.title}"
              loading="lazy"
              class="img-zoom w-full h-full object-cover"
            />
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <h3 class="text-[12px] sm:text-[13.5px] font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words">
              ${item.title}
            </h3>
            <p class="mt-1.5 text-[11px] text-slate-500 leading-snug break-words">
              <i class="fa-solid fa-location-dot text-brand-gold mr-1"></i>${item.location}
            </p>
          </div>
        </article>
      `).join('');
    }

    /**
     * Render danh sách Tin tức trang chủ
     */
    function renderNews() {
      const grid = document.getElementById('news-grid');
      if (!grid) return;

      grid.innerHTML = newsArticles.map((post, idx) => `
        <article
          onclick="openNewsModal(${idx})"
          class="group cursor-pointer rounded-xl overflow-hidden bg-white border border-slate-200 shadow-sm hover:shadow-md transition-all flex flex-col"
        >
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="${driveThumb(post.imgId)}"
              data-fallback="${driveFallback(post.imgId)}"
              onerror="handleImgError(this, 'Tin Tức Xây Dựng')"
              alt="${post.title}"
              loading="lazy"
              class="img-zoom w-full h-full object-cover"
            />
          </div>
          <div class="p-3 sm:p-4 flex-1 flex flex-col">
            <span class="text-[11px] text-slate-400 mb-1">${post.date}</span>
            <h3 class="text-[12.5px] sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words mb-1.5">
              ${post.title}
            </h3>
            <p class="text-[11.5px] sm:text-xs text-slate-600 leading-relaxed break-words">
              ${post.excerpt}
            </p>
          </div>
        </article>
      `).join('');
    }

    /**
     * Lọc danh mục công trình thực tế
     */
    function filterProjects(category, btnEl) {
      const tabs = document.querySelectorAll('.cat-tab');
      tabs.forEach(tab => {
        tab.classList.remove('bg-brand-primary', 'text-white', 'border-brand-primary');
        tab.classList.add('bg-white', 'text-slate-700', 'border-slate-200');
      });

      const targetBtn = btnEl || document.querySelector(`.cat-tab[data-filter="${category}"]`);
      if (targetBtn) {
        targetBtn.classList.remove('bg-white', 'text-slate-700', 'border-slate-200');
        targetBtn.classList.add('bg-brand-primary', 'text-white', 'border-brand-primary');
      }

      renderConstruction(category);
    }

    function filterAndScroll(category) {
      filterProjects(category);
      const sec = document.getElementById('cong-trinh-thuc-te');
      if (sec) sec.scrollIntoView({ behavior: 'smooth' });
    }

    /**
     * Modal xem chi tiết dự án & tin tức
     */
    function openProjectModal(source, id) {
      const list = source === 'danang' ? danangProjects : constructionProjects;
      const item = list.find(x => x.id === id);
      if (!item) return;

      const modal = document.getElementById('detail-modal');
      const img = document.getElementById('modal-img');
      img.removeAttribute('data-err-step');
      img.setAttribute('data-fallback', driveFallback(item.id));
      img.onerror = function() { handleImgError(this, item.title); };
      img.src = driveThumb(item.id);
      img.alt = item.title;

      document.getElementById('modal-title').textContent = item.title;
      document.getElementById('modal-meta').textContent = item.location || `Danh mục: ${item.categoryLabel}`;
      document.getElementById('modal-desc').textContent = item.desc;

      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function openNewsModal(idx) {
      const post = newsArticles[idx];
      if (!post) return;

      const modal = document.getElementById('detail-modal');
      const img = document.getElementById('modal-img');
      img.removeAttribute('data-err-step');
      img.setAttribute('data-fallback', driveFallback(post.imgId));
      img.onerror = function() { handleImgError(this, post.title); };
      img.src = driveThumb(post.imgId);
      img.alt = post.title;

      document.getElementById('modal-title').textContent = post.title;
      document.getElementById('modal-meta').textContent = `Tin tức xây dựng • Ngày đăng: ${post.date}`;
      document.getElementById('modal-desc').textContent = post.excerpt + ' Để được kiến trúc sư Green Tropical tư vấn trực tiếp theo hiện trạng lô đất tại Đà Nẵng, Quý khách vui lòng để lại thông tin hoặc gọi Hotline 0985.121.468.';

      modal.classList.remove('hidden');
      document.body.style.overflow = 'hidden';
    }

    function closeModal() {
      const modal = document.getElementById('detail-modal');
      if (modal) modal.classList.add('hidden');
      document.body.style.overflow = '';
    }

    /**
     * Điều khiển 2 Banner tự trượt mượt mà + hỗ trợ vuốt cảm ứng mobile
     */
    let currentSlide = 0;
    const totalSlides = 2;
    let slideTimer = null;

    function updateBannerSlider(index) {
      currentSlide = (index + totalSlides) % totalSlides;
      const track = document.getElementById('banner-track');
      if (track) {
        track.style.transform = `translateX(-${currentSlide * 100}%)`;
      }

      document.querySelectorAll('.banner-dot').forEach((dot, i) => {
        if (i === currentSlide) {
          dot.classList.remove('w-2.5', 'bg-white/60');
          dot.classList.add('w-7', 'bg-brand-gold');
        } else {
          dot.classList.remove('w-7', 'bg-brand-gold');
          dot.classList.add('w-2.5', 'bg-white/60');
        }
      });
    }

    function startBannerAutoSlide() {
      stopBannerAutoSlide();
      slideTimer = setInterval(() => {
        updateBannerSlider(currentSlide + 1);
      }, 5000);
    }

    function stopBannerAutoSlide() {
      if (slideTimer) clearInterval(slideTimer);
    }

    /**
     * Điều khiển Menu Mobile
     */
    function closeMobileMenu() {
      const menu = document.getElementById('mobile-menu');
      if (menu) menu.classList.add('hidden');
    }

    /**
     * Khởi tạo toàn bộ ứng dụng khi tải trang xong
     */
    document.addEventListener('DOMContentLoaded', function() {
      try {
        renderConstruction('all');
        renderDanangProjects();
        renderNews();

        // Nút menu mobile
        const mobileBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        if (mobileBtn && mobileMenu) {
          mobileBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
          });
        }

        // Sự kiện điều khiển Slider
        const prevBtn = document.getElementById('banner-prev');
        const nextBtn = document.getElementById('banner-next');
        if (prevBtn) {
          prevBtn.addEventListener('click', () => {
            updateBannerSlider(currentSlide - 1);
            startBannerAutoSlide();
          });
        }
        if (nextBtn) {
          nextBtn.addEventListener('click', () => {
            updateBannerSlider(currentSlide + 1);
            startBannerAutoSlide();
          });
        }

        document.querySelectorAll('.banner-dot').forEach(dot => {
          dot.addEventListener('click', () => {
            const idx = parseInt(dot.getAttribute('data-slide'), 10);
            updateBannerSlider(idx);
            startBannerAutoSlide();
          });
        });

        // Hỗ trợ vuốt cảm ứng trên điện thoại cho Banner
        const sliderEl = document.getElementById('hero-slider');
        let touchStartX = 0;
        if (sliderEl) {
          sliderEl.addEventListener('touchstart', (e) => {
            touchStartX = e.changedTouches[0].screenX;
          }, { passive: true });

          sliderEl.addEventListener('touchend', (e) => {
            const diff = e.changedTouches[0].screenX - touchStartX;
            if (Math.abs(diff) > 40) {
              updateBannerSlider(diff < 0 ? currentSlide + 1 : currentSlide - 1);
              startBannerAutoSlide();
            }
          }, { passive: true });
        }

        startBannerAutoSlide();

        // Đóng modal khi bấm nền ngoài hoặc phím ESC
        const modal = document.getElementById('detail-modal');
        if (modal) {
          modal.addEventListener('click', (e) => {
            if (e.target === modal) closeModal();
          });
        }
        document.addEventListener('keydown', (e) => {
          if (e.key === 'Escape') closeModal();
        });

        // Xử lý Form Yêu cầu & Báo giá
        const quoteForm = document.getElementById('quote-form');
        const feedback = document.getElementById('quote-feedback');
        if (quoteForm && feedback) {
          quoteForm.addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const type = document.getElementById('q-type').value;
            const budget = document.getElementById('q-budget').value;

            if (!name || !phone) {
              feedback.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
              feedback.textContent = 'Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Green Tropical liên hệ báo giá.';
              feedback.classList.remove('hidden');
              return;
            }

            feedback.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-emerald-50 text-brand-primary border border-emerald-200';
            feedback.textContent = `Cảm ơn ${name}! Green Tropical đã tiếp nhận yêu cầu báo giá (${type} - ${budget}) và sẽ gọi lại số ${phone} trong thời gian sớm nhất.`;
            feedback.classList.remove('hidden');
            quoteForm.reset();
          });
        }
      } catch (err) {
        console.error('Lỗi khởi tạo giao diện Green Tropical:', err);
      }
    });
  </script>
</body>
</html>
