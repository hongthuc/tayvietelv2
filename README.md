<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>TÂY VIỆT ELV - Giải Pháp Camera An Ninh, Mạng & Smarthome Đà Nẵng | tayvietelv.com</title>
  <meta name="description" content="CÔNG TY TNHH GIẢI PHÁP CÔNG NGHỆ TÂY VIỆT ELV - Chuyên thiết kế, tư vấn giải pháp, thi công lắp đặt hệ thống Camera An Ninh, Mạng LAN/Wifi, Smarthome Điện nhẹ tại Đà Nẵng. Hotline: 0329.081.555">
  <meta name="keywords" content="Tây Việt ELV, tayvietelv.com, lắp đặt camera Đà Nẵng, thi công mạng Đà Nẵng, nhà thông minh smarthome Đà Nẵng, điện nhẹ ELV Đà Nẵng">

  <!-- Open Graph / Thumbnail là Logo trang web khi gửi link chia sẻ -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://tayvietelv.com/">
  <meta property="og:site_name" content="CÔNG TY TNHH GIẢI PHÁP CÔNG NGHỆ TÂY VIỆT ELV">
  <meta property="og:title" content="CÔNG TY TNHH GIẢI PHÁP CÔNG NGHỆ TÂY VIỆT ELV - Camera An Ninh, Mạng, Smarthome">
  <meta property="og:description" content="Chuyên thiết kế - tư vấn giải pháp - thi công lắp đặt hệ thống Camera An Ninh - Mạng - Smarthome tại Đà Nẵng. Địa chỉ: 54 Đô Đốc Lộc, P. Hòa Xuân, TP Đà Nẵng. ĐT: 0329.081.555">
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3">
  <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3">
  <meta property="og:image:alt" content="Logo Công Ty TNHH Giải Pháp Công Nghệ Tây Việt ELV">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3">
  <link rel="icon" href="https://lh3.googleusercontent.com/d/1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3">

  <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter / Roboto chuẩn Flatsome) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              50: '#f0f7ff',
              100: '#e0effe',
              500: '#0284c7',
              600: '#005baa', /* Màu xanh chủ đạo theo tông logo công nghệ ELV */
              700: '#004482',
              800: '#003366',
              900: '#002244',
              accent: '#d90429', /* Màu đỏ giảm giá chuẩn Flatsome */
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Chống tràn viền tuyệt đối và đảm bảo không lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box !important;
    }
    html, body {
      width: 100% !important;
      max-width: 100% !important;
      overflow-x: hidden !important;
      margin: 0 !important;
      padding: 0 !important;
      font-family: 'Inter', sans-serif;
      background-color: #f4f6f9;
      color: #1e293b;
      scroll-behavior: smooth;
    }

    /* Tự động xóa toàn bộ padding/margin của các thẻ cha WordPress/Flatsome (.col, .row, .entry-content...) gây lệch sang phải */
    *:has(.tv-site-wrapper),
    #wrapper, #main, #content, .page-wrapper, .row, .row-main, .col, .large-12, .large-9, .col-inner, .page-inner, .entry-content {
      margin-left: 0 !important;
      margin-right: 0 !important;
      padding-left: 0 !important;
      padding-right: 0 !important;
      width: 100% !important;
      max-width: 100% !important;
      min-width: 0 !important;
      box-sizing: border-box !important;
    }

    /* Khóa wrapper chính căn giữa chuẩn xác, cân đối tuyệt đối 2 bên trái - phải */
    .tv-site-wrapper {
      width: 100% !important;
      max-width: 100% !important;
      min-width: 0 !important;
      margin: 0 auto !important;
      padding: 0 !important;
      overflow-x: hidden !important;
      position: relative;
      left: 0 !important;
      right: 0 !important;
    }

    /* Ngăn các phần tử con trong Flex/Grid tự phình ngang gây tràn màn hình điện thoại */
    .tv-site-wrapper div,
    .tv-site-wrapper section,
    .tv-site-wrapper header,
    .tv-site-wrapper footer,
    .tv-site-wrapper main,
    .tv-site-wrapper nav,
    .tv-site-wrapper article,
    .tv-site-wrapper form,
    .tv-site-wrapper input,
    .tv-site-wrapper select,
    .tv-site-wrapper textarea,
    .tv-site-wrapper button,
    .tv-site-wrapper a,
    .tv-site-wrapper span,
    .tv-site-wrapper h1,
    .tv-site-wrapper h2,
    .tv-site-wrapper h3,
    .tv-site-wrapper h4,
    .tv-site-wrapper p {
      min-width: 0;
      max-width: 100%;
    }

    /* Reset margin/padding mặc định của Flatsome trên thẻ tiêu đề, danh sách và form */
    .tv-site-wrapper h1,
    .tv-site-wrapper h2,
    .tv-site-wrapper h3,
    .tv-site-wrapper h4,
    .tv-site-wrapper p,
    .tv-site-wrapper form,
    .tv-site-wrapper input,
    .tv-site-wrapper select,
    .tv-site-wrapper textarea,
    .tv-site-wrapper button {
      margin-top: 0 !important;
      margin-bottom: 0 !important;
      border-bottom: none !important;
    }
    .tv-site-wrapper ul,
    .tv-site-wrapper ol,
    .tv-site-wrapper li {
      margin: 0 !important;
      list-style: none !important;
    }

    /* Khóa cỡ chữ tiêu đề các mục để CSS mặc định của Flatsome không phóng to gây vỡ khung trên điện thoại */
    .tv-sec-title {
      font-size: 12.5px !important;
      line-height: 1.35 !important;
      font-weight: 800 !important;
    }
    @media (min-width: 640px) {
      .tv-sec-title {
        font-size: 15px !important;
      }
    }
    @media (min-width: 1024px) {
      .tv-sec-title {
        font-size: 16px !important;
      }
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính, trên điện thoại cách đều 2 viền trái/phải 8px */
    .flatsome-container {
      width: 100% !important;
      max-width: 100% !important;
      padding-left: 8px !important;
      padding-right: 8px !important;
      margin-left: auto !important;
      margin-right: auto !important;
      box-sizing: border-box !important;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95% !important;
        max-width: 95% !important;
        padding-left: 0 !important;
        padding-right: 0 !important;
      }
    }

    /* Khung Banner cố định kích thước bằng nhau và khóa cỡ chữ không tràn viền */
    .banner-slide {
      display: none !important;
      width: 100% !important;
      height: 100% !important;
    }
    .banner-slide.slide-active {
      display: block !important;
    }
    .tv-mob-badge {
      font-size: 9px !important;
      line-height: 1.2 !important;
      padding: 2px 6px !important;
      display: inline-block !important;
    }
    .tv-mob-title {
      font-size: 11.5px !important;
      line-height: 1.28 !important;
      font-weight: 800 !important;
      color: #ffffff !important;
      margin: 3px 0 !important;
    }
    .tv-mob-desc {
      font-size: 9.5px !important;
      line-height: 1.28 !important;
      color: #e0f2fe !important;
      margin: 0 0 5px 0 !important;
    }
    .tv-pc-title {
      font-size: 18px !important;
      line-height: 1.3 !important;
      font-weight: 800 !important;
      color: #ffffff !important;
      margin: 4px 0 !important;
    }
    @media (min-width: 1280px) {
      .tv-pc-title {
        font-size: 21px !important;
      }
    }
    .tv-pc-desc {
      font-size: 12px !important;
      line-height: 1.4 !important;
      color: #e0f2fe !important;
      margin: 0 0 6px 0 !important;
    }

    /* Tên danh mục trên máy tính viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không xuống dòng giữa chừng */
    .cat-nowrap {
      white-space: nowrap !important;
    }

    /* Nút giảm giá góc trên bên trái chuẩn Flatsome WooCommerce */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #d90429;
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      line-height: 1;
      padding: 6px 7px;
      border-radius: 9999px;
      box-shadow: 0 2px 5px rgba(217, 4, 41, 0.35);
      pointer-events: none;
    }

    /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài khung */
    .product-title-full {
      word-break: break-word;
      overflow-wrap: anywhere;
      white-space: normal;
      line-height: 1.38 !important;
      font-size: 12px !important;
    }
    @media (min-width: 640px) {
      .product-title-full {
        font-size: 13.5px !important;
      }
    }

    /* Dropdown danh mục máy tính mượt mà */
    .nav-item-dropdown:hover .nav-dropdown-menu {
      display: block;
    }

    /* Hiệu ứng pulse nhẹ cho nút liên hệ nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 4, 41, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 4, 41, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 4, 41, 0); }
    }
    .pulse-hotline {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="min-h-screen flex flex-col justify-between">
<div class="tv-site-wrapper min-h-screen flex flex-col justify-between">

  <!-- ==================== TOP BAR (CHUẨN FLATSOME ĐƠN GIẢN) ==================== -->
  <div class="bg-brand-800 text-white text-[10px] sm:text-xs py-1.5 border-b border-brand-700 w-full">
    <div class="flatsome-container flex items-center justify-between gap-2">
      <div class="flex items-center gap-1.5 min-w-0 flex-1 overflow-hidden">
        <i class="fa-solid fa-shield-halved text-sky-300 shrink-0"></i>
        <span class="font-semibold tracking-wide truncate block">CÔNG TY TNHH GIẢI PHÁP CÔNG NGHỆ TÂY VIỆT ELV<span class="hidden sm:inline"> - tayvietelv.com</span></span>
      </div>
      <div class="hidden md:flex items-center gap-4 text-sky-100 shrink-0">
        <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>54 Đô Đốc Lộc, Phường Hòa Xuân, TP Đà Nẵng</span>
        <span>|</span>
        <a href="tel:0329081555" class="hover:text-white font-semibold"><i class="fa-solid fa-phone-volume text-emerald-400 mr-1"></i>0329.081.555</a>
      </div>
    </div>
  </div>

  <!-- ==================== HEADER (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
  <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200 w-full">
    <div class="flatsome-container py-2 flex items-center justify-between gap-1.5 sm:gap-3">
      
      <!-- Nút mở danh mục trên Điện thoại -->
      <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden w-8 h-8 sm:w-9 sm:h-9 rounded-lg text-brand-700 hover:bg-slate-100 border border-slate-200 flex items-center justify-center shrink-0">
        <i class="fa-solid fa-bars text-sm sm:text-base"></i>
      </button>

      <!-- Logo chỉnh gọn nhỏ lại -->
      <a href="#top" class="flex items-center gap-1.5 sm:gap-2 shrink-0 group">
        <div class="w-8 h-8 sm:w-10 sm:h-10 rounded-lg bg-white border border-slate-200 p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-xs">
          <img 
            src="https://lh3.googleusercontent.com/d/1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3" 
            onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3&sz=w400';}else{this.onerror=null;this.src='https://placehold.co/120x120/005baa/ffffff?text=TV+ELV';}"
            alt="Logo Tây Việt ELV" 
            class="max-h-full max-w-full object-contain"
          >
        </div>
        <div class="leading-tight">
          <span class="block font-extrabold text-brand-700 text-[10.5px] sm:text-sm md:text-base tracking-tight whitespace-nowrap">TÂY VIỆT ELV</span>
          <span class="block text-[9px] sm:text-[11px] text-slate-500 font-medium whitespace-nowrap">tayvietelv.com</span>
        </div>
      </a>

      <!-- Thanh tìm kiếm sản phẩm ở giữa (Thêm size="1" và min-w-0 để không bao giờ đẩy tràn màn hình điện thoại) -->
      <div class="flex-1 min-w-0 max-w-xl mx-0.5 sm:mx-2 overflow-hidden">
        <form id="searchForm" class="relative flex items-center w-full min-w-0" onsubmit="handleSearch(event)">
          <input 
            id="searchInput"
            type="text" 
            size="1"
            placeholder="Tìm camera, wifi..." 
            class="w-full min-w-0 pl-2.5 pr-7 py-1.5 sm:py-2 text-[11px] sm:text-sm bg-slate-50 border border-slate-300 rounded-lg focus:outline-none focus:border-brand-600 focus:bg-white transition"
          >
          <button type="submit" aria-label="Tìm kiếm" class="absolute right-1 top-1/2 -translate-y-1/2 px-1.5 py-1 text-brand-600 hover:text-brand-800">
            <i class="fa-solid fa-magnifying-glass text-xs sm:text-sm"></i>
          </button>
        </form>
      </div>

      <!-- Các liên kết nhanh trên máy tính & Giỏ hàng (Không có nút gọi ngay trên header để tránh tràn viền) -->
      <div class="flex items-center gap-1.5 sm:gap-2.5 shrink-0">
        <a href="#bao-gia" class="hidden xl:inline-flex items-center gap-1.5 text-xs font-semibold text-brand-700 bg-brand-50 hover:bg-brand-100 px-3 py-2 rounded-lg border border-brand-200 transition cat-nowrap">
          <i class="fa-solid fa-file-signature text-brand-600"></i> Nhận báo giá
        </a>
        <a href="#san-pham-chinh" class="inline-flex items-center gap-1 text-xs font-semibold text-slate-700 hover:text-brand-600 px-2 py-1.5 sm:p-2 rounded-lg border border-slate-200 bg-slate-50 shrink-0">
          <i class="fa-solid fa-cart-shopping text-brand-600 text-xs sm:text-sm"></i>
          <span class="hidden sm:inline cat-nowrap">Giỏ hàng</span>
          <span id="cartCountBadge" class="bg-brand-accent text-white text-[10px] font-bold px-1.5 py-0.5 rounded-full leading-none">0</span>
        </a>
      </div>

    </div>

    <!-- ==================== THANH DANH MỤC TRÊN MÁY TÍNH (CHỮ NHỎ GỌN, VIẾT LIỀN TRÊN 1 HÀNG, KHÔNG XUỐNG DÒNG TÊN DANH MỤC) ==================== -->
    <nav class="hidden lg:block bg-brand-600 text-white border-t border-brand-500">
      <div class="flatsome-container">
        <ul class="flex flex-wrap items-center justify-start gap-x-1 gap-y-0.5 py-1 text-[12px] font-semibold">
          <li>
            <a href="#danh-muc-he-thong" class="inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded bg-brand-800 text-amber-300 hover:bg-brand-900 transition cat-nowrap">
              <i class="fa-solid fa-table-cells-large text-[11px]"></i> DANH MỤC SẢN PHẨM
            </a>
          </li>
          <li class="relative nav-item-dropdown">
            <a href="#cat-camera" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-video text-[11px] text-sky-200"></i> Hệ thống Camera <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
            </a>
            <div class="nav-dropdown-menu hidden absolute left-0 top-full w-56 bg-white text-slate-700 shadow-xl rounded-b-lg border border-slate-200 py-1.5 z-50 text-xs">
              <a href="#cat-camera" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Camera Hikvision Chính Hãng</a>
              <a href="#cat-camera" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Camera Dahua / KBVision</a>
              <a href="#cat-camera" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Camera Wifi Imou / Ezviz</a>
              <a href="#cat-camera" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Camera AI Nhận Diện & Báo Cháy</a>
              <a href="#cat-camera" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Đầu Ghi Hình NVR / DVR & Ổ Cứng</a>
            </div>
          </li>
          <li class="relative nav-item-dropdown">
            <a href="#cat-mang" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-network-wired text-[11px] text-sky-200"></i> Hệ thống Mạng <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
            </a>
            <div class="nav-dropdown-menu hidden absolute left-0 top-full w-56 bg-white text-slate-700 shadow-xl rounded-b-lg border border-slate-200 py-1.5 z-50 text-xs">
              <a href="#cat-mang" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Bộ Chuyển Mạch Switch PoE</a>
              <a href="#cat-mang" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Bộ Phát Wifi – Access Point</a>
              <a href="#cat-mang" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Router Cân Bằng Tải DrayTek / Mikrotik</a>
              <a href="#cat-mang" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Gateway & Firewall Tường Lửa</a>
            </div>
          </li>
          <li class="relative nav-item-dropdown">
            <a href="#cat-smarthome" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-house-signal text-[11px] text-sky-200"></i> Nhà thông minh (Smarthome) <i class="fa-solid fa-chevron-down text-[9px] opacity-80"></i>
            </a>
            <div class="nav-dropdown-menu hidden absolute left-0 top-full w-56 bg-white text-slate-700 shadow-xl rounded-b-lg border border-slate-200 py-1.5 z-50 text-xs">
              <a href="#cat-smarthome" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Bộ Điều Khiển Trung Tâm</a>
              <a href="#cat-smarthome" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Công Tắc Thông Minh Lumi / Sonoff</a>
              <a href="#cat-smarthome" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Khóa Vân Tay Hafele / Kaadas / Yale</a>
              <a href="#cat-smarthome" class="block px-3.5 py-1.5 hover:bg-brand-50 hover:text-brand-600 cat-nowrap">Két Sắt & Chuông Cửa Thông Minh</a>
            </div>
          </li>
          <li>
            <a href="#cat-smarthome" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-fire-extinguisher text-[11px] text-sky-200"></i> Hệ thống Báo cháy
            </a>
          </li>
          <li>
            <a href="#cat-smarthome" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-volume-high text-[11px] text-sky-200"></i> Hệ thống Âm thanh
            </a>
          </li>
          <li>
            <a href="#cat-mang" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-phone-volume text-[11px] text-sky-200"></i> Tổng đài & Máy chấm công
            </a>
          </li>
          <li>
            <a href="#cat-mang" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-server text-[11px] text-sky-200"></i> Server & Lưu trữ NAS
            </a>
          </li>
          <li>
            <a href="#dich-vu-elv" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-screwdriver-wrench text-[11px] text-sky-200"></i> Thi công Điện nhẹ
            </a>
          </li>
          <li>
            <a href="#tin-tuc" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-newspaper text-[11px] text-sky-200"></i> Tin tức & Giải pháp
            </a>
          </li>
          <li>
            <a href="#lien-he-map" class="inline-flex items-center gap-1 px-2.5 py-1.5 rounded hover:bg-brand-700 transition cat-nowrap">
              <i class="fa-solid fa-map-location-dot text-[11px] text-sky-200"></i> Liên hệ
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- ==================== DRAWER MENU DANH MỤC TRÊN ĐIỆN THOẠI ==================== -->
  <div id="mobileMenuOverlay" class="fixed inset-0 bg-slate-900/60 z-50 hidden transition-opacity">
    <div class="w-[84%] max-w-xs bg-white h-full shadow-2xl flex flex-col justify-between overflow-y-auto">
      <div>
        <div class="p-3.5 bg-brand-700 text-white flex items-center justify-between">
          <div class="flex items-center gap-2">
            <img src="https://lh3.googleusercontent.com/d/1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3" alt="Logo" class="w-7 h-7 rounded bg-white p-0.5 object-contain">
            <span class="font-bold text-xs tracking-wide">DANH MỤC TÂY VIỆT ELV</span>
          </div>
          <button id="closeMobileMenuBtn" type="button" class="p-1.5 text-white hover:bg-brand-800 rounded">
            <i class="fa-solid fa-xmark text-lg"></i>
          </button>
        </div>

        <ul class="divide-y divide-slate-100 text-xs font-semibold text-slate-700">
          <li><a href="#cat-camera" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-video text-brand-600 w-5"></i> Hệ thống Camera An Ninh</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#cat-mang" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-network-wired text-brand-600 w-5"></i> Hệ thống Mạng - Wifi - Switch</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#cat-smarthome" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-house-signal text-brand-600 w-5"></i> Nhà thông minh (Smarthome)</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#cat-smarthome" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-fingerprint text-brand-600 w-5"></i> Khóa cửa vân tay chính hãng</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#cat-smarthome" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-fire-extinguisher text-brand-600 w-5"></i> Hệ thống Báo cháy tự động</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#cat-smarthome" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-volume-high text-brand-600 w-5"></i> Hệ thống Âm thanh thông báo</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#cat-mang" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-phone-volume text-brand-600 w-5"></i> Tổng đài IP & Máy chấm công</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#cat-mang" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-server text-brand-600 w-5"></i> Máy chủ Server & Lưu trữ NAS</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#dich-vu-elv" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-helmet-safety text-brand-600 w-5"></i> Thi công Điện nhẹ ELV Đà Nẵng</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#bao-gia" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-file-invoice-dollar text-brand-600 w-5"></i> Yêu cầu tư vấn & Báo giá</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#tin-tuc" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-newspaper text-brand-600 w-5"></i> Tin tức & Kiến thức công nghệ</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
          <li><a href="#lien-he-map" onclick="closeMobileMenu()" class="flex items-center justify-between px-4 py-3 hover:bg-brand-50"><span><i class="fa-solid fa-location-dot text-brand-600 w-5"></i> Bản đồ & Fanpage Tây Việt ELV</span><i class="fa-solid fa-angle-right text-slate-400"></i></a></li>
        </ul>
      </div>

      <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs space-y-1.5">
        <div class="font-bold text-brand-700">TÂY VIỆT ELV - ĐÀ NẴNG</div>
        <div class="text-slate-600"><i class="fa-solid fa-location-dot text-brand-600 mr-1"></i> 54 Đô Đốc Lộc, P. Hòa Xuân, Đà Nẵng</div>
        <div class="text-slate-600"><i class="fa-solid fa-phone text-brand-600 mr-1"></i> Hotline: <a href="tel:0329081555" class="font-bold text-brand-accent">0329.081.555</a></div>
      </div>
    </div>
  </div>

  <!-- ==================== MAIN CONTENT (UX BUILDER FLATSOME STRUCTURE) ==================== -->
  <main id="top" class="flex-1 space-y-6 sm:space-y-8 py-3 sm:py-5">

    <!-- ==================== SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU ==================== -->
    <!-- Thiết kế riêng ảnh banner Điện thoại (md:hidden) khác với ảnh banner Máy tính (hidden md:flex) để chữ nhỏ gọn, nằm trọn bên trong ảnh, tuyệt đối không tràn viền -->
    <section class="flatsome-container">
      <div class="relative w-full rounded-xl overflow-hidden shadow-md bg-brand-900">
        
        <!-- SLIDE CONTAINER: Cố định chiều cao bằng nhau tuyệt đối cho cả 2 Slide -->
        <div id="heroSlider" class="relative w-full h-[185px] sm:h-[200px] md:h-[275px] lg:h-[300px] overflow-hidden">

          <!-- ==================== SLIDE 1 ==================== -->
          <div class="banner-slide slide-active w-full h-full">
            
            <!-- ẢNH BANNER MÁY TÍNH SLIDE 1 (Chỉ hiển thị trên máy tính/tablet ngang md trở lên) -->
            <div class="hidden md:flex w-full h-full relative bg-gradient-to-r from-[#00254d] via-[#004488] to-[#0066b2] items-center justify-between px-12 lg:px-14 py-4 overflow-hidden">
              <!-- Họa tiết kỹ thuật số nền banner máy tính -->
              <svg class="absolute inset-0 w-full h-full opacity-15 pointer-events-none" viewBox="0 0 1200 320" preserveAspectRatio="none">
                <defs>
                  <pattern id="grid1" width="40" height="40" patternUnits="userSpaceOnUse">
                    <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#38bdf8" stroke-width="0.7"/>
                  </pattern>
                </defs>
                <rect width="1200" height="320" fill="url(#grid1)"/>
                <circle cx="1020" cy="160" r="180" fill="none" stroke="#38bdf8" stroke-width="2" stroke-dasharray="8 8"/>
                <circle cx="1020" cy="160" r="130" fill="none" stroke="#7dd3fc" stroke-width="1.5"/>
              </svg>

              <!-- Nội dung chữ thu gọn nằm hoàn toàn bên trong khung an toàn máy tính -->
              <div class="relative z-10 w-[62%] max-w-[62%] text-white pr-3">
                <div class="inline-flex items-center gap-1.5 bg-sky-500/25 border border-sky-300/40 text-sky-200 text-[10px] font-semibold px-2.5 py-0.5 rounded-full mb-1">
                  <i class="fa-solid fa-shield-halved"></i> CÔNG TY TNHH GIẢI PHÁP CÔNG NGHỆ TÂY VIỆT ELV
                </div>
                <div class="tv-pc-title">
                  THIẾT KẾ - TƯ VẤN - THI CÔNG LẮP ĐẶT HỆ THỐNG CAMERA AN NINH, MẠNG & SMARTHOME
                </div>
                <div class="tv-pc-desc max-w-xl">
                  Giải pháp Điện nhẹ (ELV) đồng bộ, thẩm mỹ, chính hãng cho gia đình, văn phòng, khách sạn, nhà xưởng tại Đà Nẵng & Miền Trung.
                </div>
                <div class="pt-1 flex flex-wrap items-center gap-2.5 text-[11px]">
                  <a href="#bao-gia" class="bg-amber-400 hover:bg-amber-300 text-slate-900 font-bold px-3.5 py-1.5 rounded-lg shadow transition">
                    NHẬN BÁO GIÁ NGAY
                  </a>
                  <span class="bg-white/10 border border-white/20 px-2.5 py-1.5 rounded-lg text-sky-100 font-medium">
                    <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i> 54 Đô Đốc Lộc, P. Hòa Xuân, Đà Nẵng | <strong class="text-white">0329.081.555</strong>
                  </span>
                </div>
              </div>

              <!-- Cụm đồ họa + hình thiết bị bên phải trên máy tính -->
              <div class="relative z-10 w-[34%] max-w-[320px] flex items-center justify-center shrink-0">
                <div class="grid grid-cols-2 gap-2 bg-white/10 backdrop-blur-xs p-2.5 rounded-xl border border-white/20 w-full">
                  <div class="bg-white rounded-lg p-1.5 flex flex-col items-center text-center shadow-xs">
                    <img src="https://lh3.googleusercontent.com/d/18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8" onerror="this.src='https://drive.google.com/thumbnail?id=18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8&sz=w300'" alt="Camera AI" class="h-14 object-contain">
                    <span class="text-[10px] font-bold text-brand-800 mt-1">Camera AI 24/7</span>
                  </div>
                  <div class="bg-white rounded-lg p-1.5 flex flex-col items-center text-center shadow-xs">
                    <img src="https://lh3.googleusercontent.com/d/18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6" onerror="this.src='https://drive.google.com/thumbnail?id=18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6&sz=w300'" alt="Hạ tầng mạng" class="h-14 object-contain">
                    <span class="text-[10px] font-bold text-brand-800 mt-1">Mạng & Smarthome</span>
                  </div>
                </div>
              </div>
            </div>

            <!-- ẢNH BANNER ĐIỆN THOẠI SLIDE 1 (Thiết kế mới riêng biệt cho màn hình nhỏ, chữ nhỏ gọn nằm trọn trong ảnh, không tràn viền) -->
            <div class="flex md:hidden w-full h-full relative bg-gradient-to-br from-[#002855] via-[#00468b] to-[#026aa7] items-center justify-between pl-7 pr-7 py-2.5 overflow-hidden">
              <div class="relative z-10 flex-1 min-w-0 pr-2 text-white">
                <span class="tv-mob-badge bg-amber-400 text-slate-900 font-extrabold rounded uppercase">
                  TÂY VIỆT ELV - tayvietelv.com
                </span>
                <div class="tv-mob-title">
                  LẮP ĐẶT CAMERA AN NINH - MẠNG - SMARTHOME ĐÀ NẴNG
                </div>
                <div class="tv-mob-desc">
                  Tư vấn giải pháp & thi công điện nhẹ chuyên nghiệp, tận tâm.
                </div>
                <div class="flex flex-wrap items-center gap-1.5 text-[10px] leading-none">
                  <a href="#bao-gia" class="bg-amber-400 text-slate-950 font-bold px-2 py-1 rounded">Báo giá</a>
                  <span class="text-sky-200 font-bold">0329.081.555</span>
                </div>
              </div>
              <div class="relative z-10 shrink-0 flex items-center justify-center">
                <div class="bg-white p-1 rounded-lg shadow-md w-16 h-16 sm:w-20 sm:h-20 flex items-center justify-center">
                  <img src="https://lh3.googleusercontent.com/d/18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8" onerror="this.src='https://drive.google.com/thumbnail?id=18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8&sz=w300'" alt="Camera Tây Việt ELV" class="max-h-full max-w-full object-contain">
                </div>
              </div>
            </div>

          </div>

          <!-- ==================== SLIDE 2 ==================== -->
          <div class="banner-slide w-full h-full">
            
            <!-- ẢNH BANNER MÁY TÍNH SLIDE 2 (Chỉ hiển thị trên máy tính md trở lên) -->
            <div class="hidden md:flex w-full h-full relative bg-gradient-to-r from-[#0f172a] via-[#0c4a6e] to-[#0369a1] items-center justify-between px-12 lg:px-14 py-4 overflow-hidden">
              <svg class="absolute inset-0 w-full h-full opacity-15 pointer-events-none" viewBox="0 0 1200 320" preserveAspectRatio="none">
                <path d="M0,250 Q300,120 600,220 T1200,140" fill="none" stroke="#38bdf8" stroke-width="3"/>
                <path d="M0,290 Q400,180 800,260 T1200,200" fill="none" stroke="#f59e0b" stroke-width="2"/>
              </svg>

              <div class="relative z-10 w-[62%] max-w-[62%] text-white pr-3">
                <div class="inline-flex items-center gap-1.5 bg-emerald-500/25 border border-emerald-300/40 text-emerald-200 text-[10px] font-semibold px-2.5 py-0.5 rounded-full mb-1">
                  <i class="fa-solid fa-network-wired"></i> GIẢI PHÁP ĐIỆN NHẸ ELV TOÀN DIỆN - VẬN HÀNH ỔN ĐỊNH
                </div>
                <div class="tv-pc-title">
                  PHÂN PHỐI & THI CÔNG MẠNG LAN/WIFI, BÁO CHÁY, KHÓA VÂN TAY, NHÀ THÔNG MINH
                </div>
                <div class="tv-pc-desc max-w-xl">
                  Cam kết thiết bị chính hãng 100% (Hikvision, Imou, Ezviz, Dahua, Ruijie, UniFi, Lumi) - Khảo sát tận nơi miễn phí tại Đà Nẵng.
                </div>
                <div class="pt-1 flex flex-wrap items-center gap-2.5 text-[11px]">
                  <a href="#san-pham-chinh" class="bg-sky-400 hover:bg-sky-300 text-slate-950 font-bold px-3.5 py-1.5 rounded-lg shadow transition">
                    XEM SẢN PHẨM KHUYẾN MÃI
                  </a>
                  <span class="bg-white/10 border border-white/20 px-2.5 py-1.5 rounded-lg text-sky-100 font-medium">
                    <i class="fa-solid fa-globe text-sky-300 mr-1"></i> Website: <strong class="text-white">tayvietelv.com</strong> | Hotline: <strong class="text-amber-300">0329.081.555</strong>
                  </span>
                </div>
              </div>

              <div class="relative z-10 w-[34%] max-w-[320px] flex items-center justify-center shrink-0">
                <div class="grid grid-cols-2 gap-2 bg-white/10 backdrop-blur-xs p-2.5 rounded-xl border border-white/20 w-full">
                  <div class="bg-white rounded-lg p-1.5 flex flex-col items-center text-center shadow-xs">
                    <img src="https://lh3.googleusercontent.com/d/1VrMRzGwAJl-iTDn1YmoC9k2kwoEjElZK" onerror="this.src='https://drive.google.com/thumbnail?id=1VrMRzGwAJl-iTDn1YmoC9k2kwoEjElZK&sz=w300'" alt="Wifi Access Point" class="h-14 object-contain">
                    <span class="text-[10px] font-bold text-brand-800 mt-1">Wifi Chịu Tải Cao</span>
                  </div>
                  <div class="bg-white rounded-lg p-1.5 flex flex-col items-center text-center shadow-xs">
                    <img src="https://lh3.googleusercontent.com/d/118yZJRfMGXLQrTdCY6FmNpxSyqXRQ-Se" onerror="this.src='https://drive.google.com/thumbnail?id=118yZJRfMGXLQrTdCY6FmNpxSyqXRQ-Se&sz=w300'" alt="Smarthome" class="h-14 object-contain">
                    <span class="text-[10px] font-bold text-brand-800 mt-1">Nhà Thông Minh</span>
                  </div>
                </div>
              </div>
            </div>

            <!-- ẢNH BANNER ĐIỆN THOẠI SLIDE 2 (Thiết kế riêng cho điện thoại, chữ nhỏ gọn nằm trọn trong ảnh, không tràn viền) -->
            <div class="flex md:hidden w-full h-full relative bg-gradient-to-br from-[#0f172a] via-[#0c4a6e] to-[#0284c7] items-center justify-between pl-7 pr-7 py-2.5 overflow-hidden">
              <div class="relative z-10 flex-1 min-w-0 pr-2 text-white">
                <span class="tv-mob-badge bg-sky-400 text-slate-950 font-extrabold rounded uppercase">
                  GIẢI PHÁP ĐIỆN NHẸ ELV
                </span>
                <div class="tv-mob-title">
                  THI CÔNG MẠNG WIFI - SWITCH POE - KHÓA VÂN TAY - BÁO CHÁY
                </div>
                <div class="tv-mob-desc">
                  54 Đô Đốc Lộc, P. Hòa Xuân, TP Đà Nẵng. Bảo hành uy tín 24/7.
                </div>
                <div class="flex flex-wrap items-center gap-1.5 text-[10px] leading-none">
                  <a href="#san-pham-chinh" class="bg-sky-400 text-slate-950 font-bold px-2 py-1 rounded">Xem SP</a>
                  <span class="text-amber-300 font-bold">0329.081.555</span>
                </div>
              </div>
              <div class="relative z-10 shrink-0 flex items-center justify-center">
                <div class="bg-white p-1 rounded-lg shadow-md w-16 h-16 sm:w-20 sm:h-20 flex items-center justify-center">
                  <img src="https://lh3.googleusercontent.com/d/1VrMRzGwAJl-iTDn1YmoC9k2kwoEjElZK" onerror="this.src='https://drive.google.com/thumbnail?id=1VrMRzGwAJl-iTDn1YmoC9k2kwoEjElZK&sz=w300'" alt="Thiết bị mạng Tây Việt ELV" class="max-h-full max-w-full object-contain">
                </div>
              </div>
            </div>

          </div>

        </div>

        <!-- Nút chuyển trái/phải & chấm chỉ báo của Banner -->
        <button type="button" onclick="changeSlide(-1)" aria-label="Banner trước" class="absolute left-1 sm:left-2 top-1/2 -translate-y-1/2 z-20 w-5 h-5 sm:w-7 sm:h-7 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-[10px]"></i>
        </button>
        <button type="button" onclick="changeSlide(1)" aria-label="Banner tiếp" class="absolute right-1 sm:right-2 top-1/2 -translate-y-1/2 z-20 w-5 h-5 sm:w-7 sm:h-7 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-[10px]"></i>
        </button>
        <div class="absolute bottom-1.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-1.5">
          <button type="button" onclick="goToSlide(0)" class="slide-dot w-4 h-1 rounded-full bg-amber-400 transition-all"></button>
          <button type="button" onclick="goToSlide(1)" class="slide-dot w-1.5 h-1 rounded-full bg-white/60 transition-all"></button>
        </div>

      </div>
    </section>

    <!-- ==================== SECTION 2: 4 CAM KẾT DỊCH VỤ (CHUẨN MẪU DANASMART / FLATSOME ICON BOX) ==================== -->
    <section class="flatsome-container">
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-2 sm:gap-4">
        <div class="bg-white rounded-xl p-2.5 sm:p-4 border border-slate-200 shadow-2xs flex items-center gap-2 sm:gap-3 min-w-0">
          <div class="w-8 h-8 sm:w-10 sm:h-10 rounded-lg bg-brand-50 text-brand-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-medal text-sm sm:text-lg"></i>
          </div>
          <div class="min-w-0 flex-1">
            <div class="text-[11px] sm:text-sm font-bold text-slate-800 leading-tight">SẢN PHẨM CHÍNH HÃNG</div>
            <div class="text-[10px] sm:text-[11px] text-slate-500 leading-snug mt-0.5">Đầy đủ CO/CQ, bảo hành chuẩn hãng</div>
          </div>
        </div>
        <div class="bg-white rounded-xl p-2.5 sm:p-4 border border-slate-200 shadow-2xs flex items-center gap-2 sm:gap-3 min-w-0">
          <div class="w-8 h-8 sm:w-10 sm:h-10 rounded-lg bg-brand-50 text-brand-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-compass-drafting text-sm sm:text-lg"></i>
          </div>
          <div class="min-w-0 flex-1">
            <div class="text-[11px] sm:text-sm font-bold text-slate-800 leading-tight">GIẢI PHÁP TOÀN DIỆN</div>
            <div class="text-[10px] sm:text-[11px] text-slate-500 leading-snug mt-0.5">Tư vấn - Thiết kế - Thi công trọn gói</div>
          </div>
        </div>
        <div class="bg-white rounded-xl p-2.5 sm:p-4 border border-slate-200 shadow-2xs flex items-center gap-2 sm:gap-3 min-w-0">
          <div class="w-8 h-8 sm:w-10 sm:h-10 rounded-lg bg-brand-50 text-brand-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-shield-halved text-sm sm:text-lg"></i>
          </div>
          <div class="min-w-0 flex-1">
            <div class="text-[11px] sm:text-sm font-bold text-slate-800 leading-tight">BẢO HÀNH UY TÍN</div>
            <div class="text-[10px] sm:text-[11px] text-slate-500 leading-snug mt-0.5">Xử lý sự cố tận nơi nhanh chóng</div>
          </div>
        </div>
        <div class="bg-white rounded-xl p-2.5 sm:p-4 border border-slate-200 shadow-2xs flex items-center gap-2 sm:gap-3 min-w-0">
          <div class="w-8 h-8 sm:w-10 sm:h-10 rounded-lg bg-brand-50 text-brand-600 flex items-center justify-center shrink-0">
            <i class="fa-solid fa-headset text-sm sm:text-lg"></i>
          </div>
          <div class="min-w-0 flex-1">
            <div class="text-[11px] sm:text-sm font-bold text-slate-800 leading-tight">HỖ TRỢ KỸ THUẬT 24/7</div>
            <div class="text-[10px] sm:text-[11px] text-slate-500 leading-snug mt-0.5">Hotline: 0329.081.555</div>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== SECTION 3: DANH MỤC SẢN PHẨM TRANG CHỦ (LẤY TỪ WEB MẪU DANASMART, CHỮ NHỎ GỌN, TRÊN MÁY TÍNH VIẾT LIỀN 1 HÀNG KHÔNG XUỐNG DÒNG) ==================== -->
    <section id="danh-muc-he-thong" class="flatsome-container">
      <div class="bg-white rounded-xl p-3.5 sm:p-5 border border-slate-200 shadow-2xs">
        <div class="flex items-center justify-between border-b border-slate-200 pb-3 mb-4">
          <h2 class="tv-sec-title text-brand-700 uppercase tracking-tight flex items-center gap-2">
            <i class="fa-solid fa-layer-group text-brand-600 shrink-0"></i>
            <span>PHÂN PHỐI & LẮP ĐẶT THIẾT BỊ CÔNG NGHỆ TẠI ĐÀ NẴNG</span>
          </h2>
          <span class="hidden sm:inline text-[11px] text-slate-500 font-medium shrink-0">18 Danh mục chuyên ngành ELV</span>
        </div>

        <!-- Lưới danh mục: Trên điện thoại 3 cột gọn đẹp; Trên máy tính 6 cột, tên danh mục chữ nhỏ gọn viết liền trên 1 hàng (cat-nowrap) -->
        <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-2 sm:gap-2.5">
          
          <a href="#cat-camera" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-video text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Camera An Ninh</span>
          </a>

          <a href="#cat-camera" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-wifi text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Camera IP Wifi</span>
          </a>

          <a href="#cat-camera" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-hard-drive text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Đầu ghi & Ổ cứng</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-ethernet text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Thiết bị Switch</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-tower-broadcast text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Access Point Wifi</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-route text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Router & Gateway</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-shield-virus text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Firewall Tường lửa</span>
          </a>

          <a href="#cat-smarthome" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-house-laptop text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Nhà thông minh</span>
          </a>

          <a href="#cat-smarthome" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-fingerprint text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Khóa cửa vân tay</span>
          </a>

          <a href="#cat-smarthome" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-fire-flame-curved text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Thiết bị báo cháy</span>
          </a>

          <a href="#cat-smarthome" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-bullhorn text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Hệ thống âm thanh</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-phone-volume text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Tổng đài điện thoại</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-id-card-clip text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Máy chấm công</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-server text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Máy chủ Server</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-database text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Lưu trữ NAS</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-car-battery text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Bộ lưu điện UPS</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-solar-panel text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Đèn năng lượng</span>
          </a>

          <a href="#cat-mang" class="group flex flex-col items-center justify-center p-2.5 rounded-lg border border-slate-200 bg-slate-50/70 hover:bg-brand-50 hover:border-brand-500 transition text-center">
            <i class="fa-solid fa-road-barrier text-base sm:text-lg text-brand-600 group-hover:scale-110 transition mb-1.5"></i>
            <span class="text-[11px] font-semibold text-slate-700 group-hover:text-brand-700 lg:whitespace-nowrap">Barie & Cổng từ</span>
          </a>

        </div>
      </div>
    </section>

    <!-- ==================== SECTION 4: DANH MỤC SẢN PHẨM CHÍNH TRANG CHỦ (9 ẢNH SẢN PHẨM THỰC TẾ TỪ GOOGLE DRIVE, CHIA 2 CỘT TRÊN ĐIỆN THOẠI, TÊN KHÔNG TRÀN HAY THIẾU CHỮ, NHÃN % GIẢM GIÁ GÓC TRÊN BÊN TRÁI) ==================== -->
    <div id="san-pham-chinh" class="space-y-6">

      <!-- KHỐI 4.1: HỆ THỐNG CAMERA AN NINH GIÁM SÁT -->
      <section id="cat-camera" class="flatsome-container">
        <div class="bg-white rounded-xl p-3.5 sm:p-5 border border-slate-200 shadow-2xs">
          <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-brand-600 pb-2.5 mb-4">
            <div class="flex items-center gap-2">
              <span class="w-2 h-5 bg-brand-600 rounded-xs shrink-0"></span>
              <h2 class="tv-sec-title text-brand-700 uppercase">
                CAMERA GIÁM SÁT AN NINH CHÍNH HÃNG
              </h2>
            </div>
            <div class="flex items-center gap-2 text-xs">
              <span class="hidden md:inline text-slate-500">Hikvision • Imou • Ezviz • Dahua</span>
              <a href="#bao-gia" class="text-brand-600 hover:text-brand-800 font-bold cat-nowrap">Tư vấn lắp đặt <i class="fa-solid fa-arrow-right text-[10px]"></i></a>
            </div>
          </div>

          <!-- Sản phẩm chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
          <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
            
            <!-- Sản phẩm 1 (Ảnh thực tế Google Drive #1: 18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-28%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8" 
                    onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8&sz=w600';}else{this.onerror=null;this.src='https://placehold.co/400x400/f8fafc/005baa?text=Camera+IMOU';}"
                    alt="Camera Wifi Quay Quét 360 IMOU Cruiser Full Color" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Camera Imou</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Camera IP Wifi Quay Quét 360° IMOU Cruiser Full Color Cảnh Báo AI Thông Minh
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">1.390.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">990.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Camera IP Wifi Quay Quét 360° IMOU Cruiser Full Color')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

            <!-- Sản phẩm 2 (Ảnh thực tế Google Drive #2: 1zAN9BuU4q6SFYjJz8KjraJv6y2lLYAyV) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-28%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1zAN9BuU4q6SFYjJz8KjraJv6y2lLYAyV" 
                    onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=1zAN9BuU4q6SFYjJz8KjraJv6y2lLYAyV&sz=w600';}else{this.onerror=null;this.src='https://placehold.co/400x400/f8fafc/005baa?text=Camera+Hikvision';}"
                    alt="Camera IP Bán Cầu HIKVISION DS-2CD1123G2-LIUF" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Camera Hikvision</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Camera IP 2MP Bán Cầu HIKVISION DS-2CD1123G2-LIUF Có Màu Ban Đêm Tích Hợp Mic
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">1.450.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">1.050.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Camera IP 2MP Bán Cầu HIKVISION DS-2CD1123G2-LIUF')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

            <!-- Sản phẩm 3 (Ảnh thực tế Google Drive #3: 1EGsriYpF4s4_GQbCqPZhH0KvfDkIuZSw) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-31%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1EGsriYpF4s4_GQbCqPZhH0KvfDkIuZSw" 
                    onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=1EGsriYpF4s4_GQbCqPZhH0KvfDkIuZSw&sz=w600';}else{this.onerror=null;this.src='https://placehold.co/400x400/f8fafc/005baa?text=Camera+EZVIZ';}"
                    alt="Camera Wifi Thông Minh EZVIZ Xoay 360 Độ" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Camera Ezviz</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Camera IP Wifi EZVIZ H8C / C6N Xoay 360 Độ Đàm Thoại 2 Chiều Phát Hiện Người AI
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">1.290.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">890.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Camera IP Wifi EZVIZ H8C / C6N Xoay 360 Độ')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

            <!-- Sản phẩm 4 (Ảnh thực tế Google Drive #4: 1x5J5HK9wauz4uTxaCgYs_5N3WucNfnu1) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-37%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1x5J5HK9wauz4uTxaCgYs_5N3WucNfnu1" 
                    onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=1x5J5HK9wauz4uTxaCgYs_5N3WucNfnu1&sz=w600';}else{this.onerror=null;this.src='https://placehold.co/400x400/f8fafc/005baa?text=Camera+Than+Tru';}"
                    alt="Camera Thân Trụ HIKVISION Có Màu Ban Đêm" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Camera Hikvision</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Camera Thân Trụ Có Màu Ban Đêm HIKVISION DS-2CE72KF0T-FS / IP PoE Chuẩn IP67
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">1.690.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">1.060.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Camera Thân Trụ Có Màu Ban Đêm HIKVISION DS-2CE72KF0T-FS')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

          </div>
        </div>
      </section>

      <!-- KHỐI 4.2: HỆ THỐNG MẠNG - SWITCH POE - BỘ PHÁT WIFI -->
      <section id="cat-mang" class="flatsome-container">
        <div class="bg-white rounded-xl p-3.5 sm:p-5 border border-slate-200 shadow-2xs">
          <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-brand-600 pb-2.5 mb-4">
            <div class="flex items-center gap-2">
              <span class="w-2 h-5 bg-brand-600 rounded-xs shrink-0"></span>
              <h2 class="tv-sec-title text-brand-700 uppercase">
                THIẾT BỊ MẠNG - SWITCH POE - WIFI CHỊU TẢI CAO
              </h2>
            </div>
            <div class="flex items-center gap-2 text-xs">
              <span class="hidden md:inline text-slate-500">Ruijie Reyee • UniFi • DrayTek • Fortinet</span>
              <a href="#bao-gia" class="text-brand-600 hover:text-brand-800 font-bold cat-nowrap">Nhận báo giá sỉ <i class="fa-solid fa-arrow-right text-[10px]"></i></a>
            </div>
          </div>

          <!-- Sản phẩm chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
          <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">

            <!-- Sản phẩm 5 (Ảnh thực tế Google Drive #5: 1mP2kNbk9FNezesRC1xcJ35gajd_M9HGj) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-25%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1mP2kNbk9FNezesRC1xcJ35gajd_M9HGj" 
                    onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=1mP2kNbk9FNezesRC1xcJ35gajd_M9HGj&sz=w600';}else{this.onerror=null;this.src='https://placehold.co/400x400/f8fafc/005baa?text=Dau+Ghi+NVR';}"
                    alt="Đầu Ghi Hình Camera IP NVR Chuyên Dụng" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Đầu ghi & Lưu trữ</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Đầu Ghi Hình Camera IP NVR 8/16 Kênh HIKVISION Chuẩn Nén H.265+ Xuất Hình 4K
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">2.650.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">1.990.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Đầu Ghi Hình Camera IP NVR 8/16 Kênh HIKVISION')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

            <!-- Sản phẩm 6 (Ảnh thực tế Google Drive #6: 18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-58%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6" 
                    onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6&sz=w600';}else{this.onerror=null;this.src='https://placehold.co/400x400/f8fafc/005baa?text=Switch+PoE+Ruijie';}"
                    alt="Bộ Chuyển Mạch Switch PoE RUIJIE REYEE" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Bộ chuyển mạch Switch</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Bộ Chuyển Mạch Switch PoE RUIJIE REYEE RG-ES205GC-P Quản Lý Cloud Thông Minh
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">2.900.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">1.225.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Bộ Chuyển Mạch Switch PoE RUIJIE REYEE RG-ES205GC-P')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

            <!-- Sản phẩm 7 (Ảnh thực tế Google Drive #7: 1VrMRzGwAJl-iTDn1YmoC9k2kwoEjElZK) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-24%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1VrMRzGwAJl-iTDn1YmoC9k2kwoEjElZK" 
                    onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=1VrMRzGwAJl-iTDn1YmoC9k2kwoEjElZK&sz=w600';}else{this.onerror=null;this.src='https://placehold.co/400x400/f8fafc/005baa?text=Access+Point+Wifi';}"
                    alt="Bộ Phát Sóng Wifi 6 Ốp Trần UniFi / Ruijie" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Bộ phát Wifi - Access Point</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Bộ Phát Sóng Wifi 6 Ốp Trần RUIJIE / UNIFI AP AC PRO Chịu Tải Cao Cho Khách Sạn
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">3.150.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">2.390.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Bộ Phát Sóng Wifi 6 Ốp Trần RUIJIE / UNIFI AP AC PRO')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

            <!-- Sản phẩm 8 (Ảnh thực tế Google Drive #8: 1rJBiCy6u_-0H7_BulMewm9LSNKtor3VA) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-20%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1rJBiCy6u_-0H7_BulMewm9LSNKtor3VA" 
                    onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=1rJBiCy6u_-0H7_BulMewm9LSNKtor3VA&sz=w600';}else{this.onerror=null;this.src='https://placehold.co/400x400/f8fafc/005baa?text=Router+Gateway';}"
                    alt="Thiết Bị Cân Bằng Tải Router Gateway Chuyên Dụng" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Router & Tủ Mạng ELV</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Router Cân Bằng Tải Nhiều Đường Truyền DrayTek Vigor / Ruijie Gateway Doanh Nghiệp
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">4.200.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">3.360.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Router Cân Bằng Tải DrayTek Vigor / Ruijie Gateway')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

          </div>
        </div>
      </section>

      <!-- KHỐI 4.3: NHÀ THÔNG MINH (SMARTHOME) - KHÓA VÂN TAY - BÁO CHÁY -->
      <section id="cat-smarthome" class="flatsome-container">
        <div class="bg-white rounded-xl p-3.5 sm:p-5 border border-slate-200 shadow-2xs">
          <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-brand-600 pb-2.5 mb-4">
            <div class="flex items-center gap-2">
              <span class="w-2 h-5 bg-brand-600 rounded-xs shrink-0"></span>
              <h2 class="tv-sec-title text-brand-700 uppercase">
                NHÀ THÔNG MINH (SMARTHOME) - KHÓA VÂN TAY - BÁO CHÁY
              </h2>
            </div>
            <div class="flex items-center gap-2 text-xs">
              <span class="hidden md:inline text-slate-500">Lumi • Hafele • Kaadas • Hochiki</span>
              <a href="#bao-gia" class="text-brand-600 hover:text-brand-800 font-bold cat-nowrap">Khảo sát miễn phí <i class="fa-solid fa-arrow-right text-[10px]"></i></a>
            </div>
          </div>

          <!-- Sản phẩm chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
          <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">

            <!-- Sản phẩm 9 (Ảnh thực tế Google Drive #9: 118yZJRfMGXLQrTdCY6FmNpxSyqXRQ-Se) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-22%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/118yZJRfMGXLQrTdCY6FmNpxSyqXRQ-Se" 
                    onerror="if(!this.dataset.fb1){this.dataset.fb1='1';this.src='https://drive.google.com/thumbnail?id=118yZJRfMGXLQrTdCY6FmNpxSyqXRQ-Se&sz=w600';}else{this.onerror=null;this.src='https://placehold.co/400x400/f8fafc/005baa?text=Smarthome+Tay+Viet';}"
                    alt="Thiết Bị Nhà Thông Minh Smarthome & Khóa Vân Tay" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Nhà thông minh Smarthome</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Bộ Thiết Bị Nhà Thông Minh Smarthome & Công Tắc Cảm Ứng Điều Khiển Qua Điện Thoại
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">2.450.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">1.900.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Bộ Thiết Bị Nhà Thông Minh Smarthome & Công Tắc Cảm Ứng')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

            <!-- Sản phẩm 10 (Kết hợp ảnh thực tế Drive cho trọn bộ giải pháp) -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-30%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8" 
                    onerror="this.src='https://drive.google.com/thumbnail?id=18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8&sz=w600'"
                    alt="Trọn Bộ 4 Camera An Ninh Độ Phân Giải Cao" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Trọn gói Camera</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Trọn Bộ Lắp Đặt 4 Camera An Ninh Full Color Kèm Đầu Ghi & Ổ Cứng Chuyên Dụng
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">5.500.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">3.850.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Trọn Bộ Lắp Đặt 4 Camera An Ninh Full Color')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

            <!-- Sản phẩm 11 -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-26%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6" 
                    onerror="this.src='https://drive.google.com/thumbnail?id=18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6&sz=w600'"
                    alt="Hệ Thống Switch PoE 26 Cổng Dự Án Điện Nhẹ" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Switch Ruijie Dự Án</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Switch PoE 26 Cổng Gigabit RUIJIE RG-ES226GC-P Cấp Nguồn Hệ Thống Camera & Wifi
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">7.900.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">5.850.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Switch PoE 26 Cổng Gigabit RUIJIE RG-ES226GC-P')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

            <!-- Sản phẩm 12 -->
            <div class="product-card group bg-white rounded-lg border border-slate-200 hover:border-brand-500 hover:shadow-md transition flex flex-col justify-between relative overflow-hidden">
              <span class="flatsome-sale-badge">-33%</span>
              <div>
                <div class="w-full h-36 sm:h-48 bg-slate-50 p-2 flex items-center justify-center overflow-hidden border-b border-slate-100">
                  <img 
                    src="https://lh3.googleusercontent.com/d/1zAN9BuU4q6SFYjJz8KjraJv6y2lLYAyV" 
                    onerror="this.src='https://drive.google.com/thumbnail?id=1zAN9BuU4q6SFYjJz8KjraJv6y2lLYAyV&sz=w600'"
                    alt="Camera AI Báo Cháy Sớm & Nhận Diện Khuôn Mặt" 
                    class="max-h-full max-w-full object-contain group-hover:scale-105 transition duration-300"
                  >
                </div>
                <div class="p-2.5 sm:p-3">
                  <div class="text-[10px] font-semibold text-slate-400 uppercase mb-1">Camera AI Thông Minh</div>
                  <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand-600">
                    Camera IP AI AcuSense 4MP HIKVISION Cảnh Báo Xâm Nhập & Nhận Diện Phương Tiện
                  </h3>
                </div>
              </div>
              <div class="p-2.5 sm:p-3 pt-0">
                <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
                  <del class="text-[11px] text-slate-400">2.250.000 ₫</del>
                  <span class="text-xs sm:text-sm font-extrabold text-brand-accent">1.490.000 ₫</span>
                </div>
                <button type="button" onclick="selectProductForQuote('Camera IP AI AcuSense 4MP HIKVISION')" class="w-full py-1.5 px-2 rounded bg-brand-50 hover:bg-brand-600 text-brand-700 hover:text-white text-[11px] sm:text-xs font-bold border border-brand-200 transition">
                  Đặt mua / Báo giá
                </button>
              </div>
            </div>

          </div>
        </div>
      </section>

    </div>

    <!-- ==================== SECTION 5: DỊCH VỤ THI CÔNG ĐIỆN NHẸ ELV TOÀN DIỆN (GIỐNG MẪU DANASMART) ==================== -->
    <section id="dich-vu-elv" class="flatsome-container">
      <div class="bg-white rounded-xl p-3.5 sm:p-5 border border-slate-200 shadow-2xs">
        <div class="text-center max-w-2xl mx-auto mb-5">
          <span class="text-[11px] font-extrabold text-brand-600 uppercase tracking-widest">— DỊCH VỤ CHUYÊN NGHIỆP —</span>
          <h2 class="tv-sec-title text-slate-800 mt-1">
            GIẢI PHÁP ĐIỆN NHẸ (ELV) TOÀN DIỆN CHO MỌI CÔNG TRÌNH
          </h2>
          <p class="text-xs text-slate-500 mt-1">
            CÔNG TY TNHH GIẢI PHÁP CÔNG NGHỆ TÂY VIỆT ELV mang đến chất lượng thi công thẩm mỹ, thiết bị chính hãng, tối ưu chi phí và bảo hành tận tâm tại Đà Nẵng.
          </p>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-4">
          <div class="p-4 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:border-brand-500 hover:shadow-sm transition">
            <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
              <i class="fa-solid fa-video"></i>
            </div>
            <h3 class="text-sm font-extrabold text-slate-800 mb-1.5">LẮP ĐẶT CAMERA QUAN SÁT</h3>
            <p class="text-xs text-slate-600 leading-relaxed mb-2.5">
              Tư vấn, thiết kế và thi công hệ thống Camera giám sát an ninh AI, Camera IP PoE, Camera Wifi cho gia đình, cửa hàng, khách sạn, kho xưởng tại Đà Nẵng.
            </p>
            <a href="#bao-gia" class="text-xs font-bold text-brand-600 hover:text-brand-800">Nhận báo giá lắp đặt ➜</a>
          </div>

          <div class="p-4 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:border-brand-500 hover:shadow-sm transition">
            <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
              <i class="fa-solid fa-network-wired"></i>
            </div>
            <h3 class="text-sm font-extrabold text-slate-800 mb-1.5">THI CÔNG HỆ THỐNG MẠNG & WIFI</h3>
            <p class="text-xs text-slate-600 leading-relaxed mb-2.5">
              Triển khai hạ tầng mạng LAN, cáp quang, tủ Rack, Switch PoE, Wifi chuyên dụng chịu tải cao cho tòa nhà, resort, văn phòng công ty và trường học.
            </p>
            <a href="#bao-gia" class="text-xs font-bold text-brand-600 hover:text-brand-800">Nhận báo giá thi công ➜</a>
          </div>

          <div class="p-4 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:border-brand-500 hover:shadow-sm transition">
            <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
              <i class="fa-solid fa-house-signal"></i>
            </div>
            <h3 class="text-sm font-extrabold text-slate-800 mb-1.5">HỆ THỐNG NHÀ THÔNG MINH SMARTHOME</h3>
            <p class="text-xs text-slate-600 leading-relaxed mb-2.5">
              Lắp đặt công tắc cảm ứng thông minh, điều khiển chiếu sáng, rèm tự động, điều hòa, an ninh tự động hóa hiện đại qua Smartphone và giọng nói.
            </p>
            <a href="#bao-gia" class="text-xs font-bold text-brand-600 hover:text-brand-800">Xem giải pháp Smarthome ➜</a>
          </div>

          <div class="p-4 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:border-brand-500 hover:shadow-sm transition">
            <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
              <i class="fa-solid fa-fingerprint"></i>
            </div>
            <h3 class="text-sm font-extrabold text-slate-800 mb-1.5">KHÓA CỬA VÂN TAY & KIỂM SOÁT RA VÀO</h3>
            <p class="text-xs text-slate-600 leading-relaxed mb-2.5">
              Phân phối và lắp đặt khóa vân tay, thẻ từ, khuôn mặt chính hãng cho cửa gỗ, cửa nhôm Xingfa, cửa kính và máy chấm công kiểm soát cửa văn phòng.
            </p>
            <a href="#bao-gia" class="text-xs font-bold text-brand-600 hover:text-brand-800">Tư vấn chọn khóa ➜</a>
          </div>

          <div class="p-4 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:border-brand-500 hover:shadow-sm transition">
            <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
              <i class="fa-solid fa-bell"></i>
            </div>
            <h3 class="text-sm font-extrabold text-slate-800 mb-1.5">HỆ THỐNG BÁO CHÁY & ÂM THANH</h3>
            <p class="text-xs text-slate-600 leading-relaxed mb-2.5">
              Cung cấp, lắp đặt tủ trung tâm báo cháy, đầu báo khói/nhiệt, âm thanh thông báo công cộng, loa âm trần cho tòa nhà, quán cafe, nhà xưởng.
            </p>
            <a href="#bao-gia" class="text-xs font-bold text-brand-600 hover:text-brand-800">Nhận tư vấn kỹ thuật ➜</a>
          </div>

          <div class="p-4 rounded-xl border border-slate-200 bg-slate-50/60 hover:bg-white hover:border-brand-500 hover:shadow-sm transition">
            <div class="w-10 h-10 rounded-lg bg-brand-600 text-white flex items-center justify-center mb-3">
              <i class="fa-solid fa-server"></i>
            </div>
            <h3 class="text-sm font-extrabold text-slate-800 mb-1.5">TỔNG ĐÀI IP, MÁY CHỦ & BẢO TRÌ ELV</h3>
            <p class="text-xs text-slate-600 leading-relaxed mb-2.5">
              Lắp đặt tổng đài điện thoại nội bộ IP, Server lưu trữ dữ liệu NAS, bộ lưu điện UPS và dịch vụ bảo trì hệ thống điện nhẹ định kỳ cho doanh nghiệp.
            </p>
            <a href="#bao-gia" class="text-xs font-bold text-brand-600 hover:text-brand-800">Liên hệ khảo sát ➜</a>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== SECTION 6: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ ==================== -->
    <section id="bao-gia" class="flatsome-container">
      <div class="bg-gradient-to-r from-brand-800 via-brand-700 to-brand-600 rounded-xl p-4 sm:p-6 text-white shadow-md">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
          
          <div class="lg:col-span-5 space-y-3">
            <span class="inline-block bg-amber-400 text-slate-950 text-[10px] font-extrabold px-2.5 py-1 rounded uppercase">
              SOLUTION • CONSULTING • QUOTATION
            </span>
            <h2 class="text-base sm:text-xl font-extrabold leading-snug">
              YÊU CẦU TƯ VẤN GIẢI PHÁP & NHẬN BÁO GIÁ TRỌN GÓI
            </h2>
            <p class="text-xs sm:text-sm text-sky-100 leading-relaxed">
              Quý khách cần lắp đặt Camera An Ninh, thi công Mạng LAN/Wifi, Smarthome hay hệ thống Điện nhẹ ELV tại Đà Nẵng? Để lại thông tin, kỹ thuật viên Tây Việt ELV sẽ liên hệ báo giá tối ưu trong 5 phút!
            </p>
            <div class="space-y-1.5 text-xs text-sky-100 pt-1">
              <div><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i> Khảo sát thực tế & lên phương án hoàn toàn miễn phí</div>
              <div><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i> Báo giá minh bạch, cam kết không phát sinh chi phí</div>
              <div><i class="fa-solid fa-phone-volume text-amber-400 mr-1.5"></i> Hotline/Zalo trực tiếp: <strong class="text-white text-sm">0329.081.555</strong></div>
            </div>
          </div>

          <div class="lg:col-span-7">
            <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 rounded-xl p-4 sm:p-5 shadow-lg space-y-3">
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                  <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-600">
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                  <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905xxxxxx" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-600">
                </div>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần tư vấn & báo giá *</label>
                  <select id="qCategory" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-600 bg-white">
                    <option value="Lắp đặt Hệ thống Camera An Ninh">Lắp đặt Hệ thống Camera An Ninh</option>
                    <option value="Thi công Hệ thống Mạng LAN / Wifi / Switch">Thi công Hệ thống Mạng LAN / Wifi / Switch</option>
                    <option value="Giải pháp Nhà thông minh (Smarthome)">Giải pháp Nhà thông minh (Smarthome)</option>
                    <option value="Lắp đặt Khóa cửa vân tay / Máy chấm công">Lắp đặt Khóa cửa vân tay / Máy chấm công</option>
                    <option value="Hệ thống Báo cháy / Âm thanh thông báo">Hệ thống Báo cháy / Âm thanh thông báo</option>
                    <option value="Thi công Điện nhẹ ELV trọn gói công trình">Thi công Điện nhẹ ELV trọn gói công trình</option>
                  </select>
                </div>
                <div>
                  <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ công trình</label>
                  <input id="qAddress" type="text" placeholder="Quận/Huyện tại Đà Nẵng..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-600">
                </div>
              </div>

              <div>
                <label class="block text-xs font-bold text-slate-700 mb-1">Yêu cầu chi tiết hoặc Mã sản phẩm quan tâm</label>
                <textarea id="qNote" rows="2" placeholder="Nhập số lượng camera, diện tích mạng wifi hoặc yêu cầu cụ thể..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-600"></textarea>
              </div>

              <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                <button type="submit" class="w-full sm:w-auto bg-brand-600 hover:bg-brand-700 text-white font-extrabold text-xs sm:text-sm px-6 py-2.5 rounded-lg shadow transition cursor-pointer">
                  <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                </button>
                <a href="https://zalo.me/0329081555" target="_blank" rel="noopener" class="w-full sm:w-auto text-center bg-sky-50 hover:bg-sky-100 text-brand-700 border border-brand-200 font-bold text-xs px-4 py-2.5 rounded-lg transition">
                  <i class="fa-solid fa-comment-dots text-brand-600 mr-1"></i> Chat Zalo: 0329.081.555
                </a>
              </div>

              <div id="quoteSuccessBox" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-semibold"></div>
            </form>
          </div>

        </div>
      </div>
    </section>

    <!-- ==================== SECTION 7: DANH MỤC CÁC BÀI VIẾT TIN TỨC & KIẾN THỨC TRANG CHỦ ==================== -->
    <section id="tin-tuc" class="flatsome-container">
      <div class="bg-white rounded-xl p-3.5 sm:p-5 border border-slate-200 shadow-2xs">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-200 pb-3 mb-4">
          <div>
            <h2 class="tv-sec-title text-brand-700 uppercase flex items-center gap-2">
              <i class="fa-solid fa-newspaper text-brand-600 shrink-0"></i>
              <span>TIN TỨC & KIẾN THỨC CÔNG NGHỆ ELV</span>
            </h2>
            <p class="text-[11px] text-slate-500 mt-0.5">Cập nhật giải pháp lắp đặt Camera An Ninh, Mạng Wifi và Smarthome mới nhất tại Đà Nẵng</p>
          </div>
          <!-- Danh mục bài viết trang chủ -->
          <div class="flex flex-wrap items-center gap-1.5 text-[11px] font-semibold">
            <span class="px-2.5 py-1 rounded bg-brand-600 text-white cat-nowrap">Tất cả bài viết</span>
            <span class="px-2.5 py-1 rounded bg-slate-100 text-slate-700 cat-nowrap">Giải pháp Camera</span>
            <span class="px-2.5 py-1 rounded bg-slate-100 text-slate-700 cat-nowrap">Hạ tầng Mạng - Wifi</span>
            <span class="px-2.5 py-1 rounded bg-slate-100 text-slate-700 cat-nowrap">Nhà thông minh Smarthome</span>
          </div>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
          
          <!-- Bài viết 1 -->
          <article class="bg-white rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between">
            <div>
              <div class="h-36 bg-slate-100 p-2 flex items-center justify-center relative border-b border-slate-100">
                <img src="https://lh3.googleusercontent.com/d/18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8" onerror="this.src='https://drive.google.com/thumbnail?id=18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8&sz=w500'" alt="Lắp đặt Camera Đà Nẵng" class="max-h-full max-w-full object-contain">
                <span class="absolute top-2 left-2 bg-brand-600 text-white text-[10px] font-bold px-2 py-0.5 rounded">Giải pháp Camera</span>
              </div>
              <div class="p-3">
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand-600 leading-snug mb-1.5">
                  Lắp Đặt Camera An Ninh Tại Hòa Xuân, Đà Nẵng Trọn Gói Chính Hãng Giá Tốt
                </h3>
                <p class="text-[11px] text-slate-500 leading-relaxed">
                  Tây Việt ELV chuyên khảo sát, tư vấn và lắp đặt trọn bộ camera quan sát sắc nét Full Color ban đêm, cảnh báo chống trộm thông minh qua điện thoại.
                </p>
              </div>
            </div>
            <div class="px-3 pb-3 pt-1 flex items-center justify-between text-[11px] text-slate-400">
              <span><i class="fa-regular fa-calendar mr-1"></i>Tây Việt ELV</span>
              <a href="#bao-gia" class="text-brand-600 font-bold">Xem chi tiết ➜</a>
            </div>
          </article>

          <!-- Bài viết 2 -->
          <article class="bg-white rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between">
            <div>
              <div class="h-36 bg-slate-100 p-2 flex items-center justify-center relative border-b border-slate-100">
                <img src="https://lh3.googleusercontent.com/d/18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6" onerror="this.src='https://drive.google.com/thumbnail?id=18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6&sz=w500'" alt="Thi công mạng LAN Wifi" class="max-h-full max-w-full object-contain">
                <span class="absolute top-2 left-2 bg-brand-600 text-white text-[10px] font-bold px-2 py-0.5 rounded">Hạ tầng Mạng</span>
              </div>
              <div class="p-3">
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand-600 leading-snug mb-1.5">
                  Giải Pháp Thi Công Mạng LAN, Switch PoE & Wifi Chịu Tải Cao Cho Khách Sạn, Văn Phòng
                </h3>
                <p class="text-[11px] text-slate-500 leading-relaxed">
                  Thiết kế hệ thống mạng cấu trúc chuẩn kỹ thuật, sử dụng Switch PoE Ruijie và Access Point UniFi giúp kết nối liền mạch, ổn định 24/7.
                </p>
              </div>
            </div>
            <div class="px-3 pb-3 pt-1 flex items-center justify-between text-[11px] text-slate-400">
              <span><i class="fa-regular fa-calendar mr-1"></i>Tây Việt ELV</span>
              <a href="#bao-gia" class="text-brand-600 font-bold">Xem chi tiết ➜</a>
            </div>
          </article>

          <!-- Bài viết 3 -->
          <article class="bg-white rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between">
            <div>
              <div class="h-36 bg-slate-100 p-2 flex items-center justify-center relative border-b border-slate-100">
                <img src="https://lh3.googleusercontent.com/d/118yZJRfMGXLQrTdCY6FmNpxSyqXRQ-Se" onerror="this.src='https://drive.google.com/thumbnail?id=118yZJRfMGXLQrTdCY6FmNpxSyqXRQ-Se&sz=w500'" alt="Nhà thông minh Smarthome Đà Nẵng" class="max-h-full max-w-full object-contain">
                <span class="absolute top-2 left-2 bg-brand-600 text-white text-[10px] font-bold px-2 py-0.5 rounded">Smarthome</span>
              </div>
              <div class="p-3">
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand-600 leading-snug mb-1.5">
                  Xu Hướng Lắp Đặt Nhà Thông Minh Smarthome & Khóa Cửa Vân Tay Cho Nhà Phố, Biệt Thự
                </h3>
                <p class="text-[11px] text-slate-500 leading-relaxed">
                  Nâng tầm tiện nghi và an toàn với hệ sinh thái công tắc thông minh, khóa cửa vân tay và kịch bản tự động hóa ngôi nhà chỉ với một chạm.
                </p>
              </div>
            </div>
            <div class="px-3 pb-3 pt-1 flex items-center justify-between text-[11px] text-slate-400">
              <span><i class="fa-regular fa-calendar mr-1"></i>Tây Việt ELV</span>
              <a href="#bao-gia" class="text-brand-600 font-bold">Xem chi tiết ➜</a>
            </div>
          </article>

          <!-- Bài viết 4 -->
          <article class="bg-white rounded-lg border border-slate-200 overflow-hidden hover:shadow-md transition flex flex-col justify-between">
            <div>
              <div class="h-36 bg-slate-100 p-2 flex items-center justify-center relative border-b border-slate-100">
                <img src="https://lh3.googleusercontent.com/d/1zAN9BuU4q6SFYjJz8KjraJv6y2lLYAyV" onerror="this.src='https://drive.google.com/thumbnail?id=1zAN9BuU4q6SFYjJz8KjraJv6y2lLYAyV&sz=w500'" alt="Camera AI nhận diện người" class="max-h-full max-w-full object-contain">
                <span class="absolute top-2 left-2 bg-brand-600 text-white text-[10px] font-bold px-2 py-0.5 rounded">Kiến thức ELV</span>
              </div>
              <div class="p-3">
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 hover:text-brand-600 leading-snug mb-1.5">
                  Kinh Nghiệm Chọn Camera IP Có Màu Ban Đêm & Đầu Ghi NVR Cho Kho Xưởng, Cửa Hàng
                </h3>
                <p class="text-[11px] text-slate-500 leading-relaxed">
                  Hướng dẫn lựa chọn độ phân giải, chuẩn nén H.265+ và dung lượng ổ cứng chuyên dụng giúp hệ thống giám sát lưu trữ dài ngày, sắc nét.
                </p>
              </div>
            </div>
            <div class="px-3 pb-3 pt-1 flex items-center justify-between text-[11px] text-slate-400">
              <span><i class="fa-regular fa-calendar mr-1"></i>Tây Việt ELV</span>
              <a href="#bao-gia" class="text-brand-600 font-bold">Xem chi tiết ➜</a>
            </div>
          </article>

        </div>
      </div>
    </section>

    <!-- ==================== SECTION 8: DANH MỤC CÁC ĐỐI TÁC CHIẾN LƯỢC ==================== -->
    <section id="doi-tac" class="flatsome-container">
      <div class="bg-white rounded-xl p-3.5 sm:p-5 border border-slate-200 shadow-2xs">
        <div class="text-center mb-4">
          <h2 class="tv-sec-title text-brand-700 uppercase tracking-wider">
            ✦ CÁC ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI CHÍNH HÃNG ✦
          </h2>
        </div>

        <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 gap-2.5 sm:gap-3">
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#d90429]">HIKVISION</span>
            <span class="text-[9px] text-slate-400">Camera & Security</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#004482]">DAHUA</span>
            <span class="text-[9px] text-slate-400">Technology</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#f97316]">IMOU</span>
            <span class="text-[9px] text-slate-400">Smart IoT</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#0284c7]">EZVIZ</span>
            <span class="text-[9px] text-slate-400">Smart Home Camera</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#e11d48]">RUIJIE</span>
            <span class="text-[9px] text-slate-400">Reyee Networks</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#005baa]">UNIFI</span>
            <span class="text-[9px] text-slate-400">Ubiquiti Enterprise</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#b91c1c]">DRAYTEK</span>
            <span class="text-[9px] text-slate-400">Router & VPN</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#0369a1]">KBVISION</span>
            <span class="text-[9px] text-slate-400">USA Brand</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#047857]">LUMI</span>
            <span class="text-[9px] text-slate-400">Smarthome Vietnam</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#1e293b]">HAFELE</span>
            <span class="text-[9px] text-slate-400">Smart Lock</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#dc2626]">HOCHIKI</span>
            <span class="text-[9px] text-slate-400">Fire Alarm</span>
          </div>
          <div class="h-14 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center px-2 hover:border-brand-500 transition">
            <span class="font-black text-sm sm:text-base tracking-wider text-[#0d9488]">TP-LINK</span>
            <span class="text-[9px] text-slate-400">Networking</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ==================== SECTION 9: ĐƯA FANPAGE FACEBOOK & ẢNH BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ ==================== -->
    <section id="lien-he-map" class="flatsome-container">
      <div class="bg-white rounded-xl p-3.5 sm:p-5 border border-slate-200 shadow-2xs">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-200 pb-3 mb-4">
          <h2 class="tv-sec-title text-brand-700 uppercase flex items-center gap-2">
            <i class="fa-solid fa-map-location-dot text-brand-600 shrink-0"></i>
            <span>KẾT NỐI FANPAGE & BẢN ĐỒ ĐỊA CHỈ TÂY VIỆT ELV TRÊN TRANG CHỦ</span>
          </h2>
          <span class="text-xs font-semibold text-slate-500">54 Đô Đốc Lộc, Phường Hòa Xuân, TP Đà Nẵng</span>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-4 sm:gap-6">
          
          <!-- CỘT 1: FANPAGE FACEBOOK TÂY VIỆT ELV NGOÀI TRANG CHỦ -->
          <div class="rounded-xl border border-slate-200 bg-slate-50 p-3.5 sm:p-4 flex flex-col justify-between space-y-3">
            <div class="flex items-start gap-3">
              <img 
                src="https://lh3.googleusercontent.com/d/1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3" 
                onerror="this.src='https://drive.google.com/thumbnail?id=1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3&sz=w300'"
                alt="Logo Fanpage Tây Việt ELV" 
                class="w-14 h-14 rounded-lg bg-white border border-slate-200 p-1 object-contain shrink-0"
              >
              <div class="min-w-0 flex-1">
                <div class="inline-flex items-center gap-1 text-[10px] font-bold text-[#1877F2] bg-blue-50 px-2 py-0.5 rounded mb-1">
                  <i class="fa-brands fa-facebook"></i> FACEBOOK FANPAGE CHÍNH THỨC
                </div>
                <h3 class="text-xs sm:text-sm font-extrabold text-slate-800 leading-snug">
                  CÔNG TY TNHH GIẢI PHÁP CÔNG NGHỆ TÂY VIỆT ELV - Camera An Ninh Đà Nẵng
                </h3>
                <p class="text-[11px] text-slate-500 mt-0.5">
                  Chuyên thiết kế - tư vấn giải pháp - thi công lắp đặt hệ thống Camera An Ninh - Mạng - Smarthome
                </p>
              </div>
            </div>

            <!-- Khung Plugin Facebook Fanpage trực tiếp + Hình ảnh thực tế trên Fanpage -->
            <div class="w-full rounded-lg overflow-hidden border border-slate-200 bg-white p-2.5 space-y-2.5">
              <div class="grid grid-cols-3 gap-2">
                <img src="https://lh3.googleusercontent.com/d/18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8" onerror="this.src='https://drive.google.com/thumbnail?id=18JsN4BtvKVH0BVgdzqQQUWyaGP1JhtY8&sz=w300'" alt="Ảnh thực tế 1" class="h-20 w-full object-contain bg-slate-50 rounded border border-slate-100 p-1">
                <img src="https://lh3.googleusercontent.com/d/1EGsriYpF4s4_GQbCqPZhH0KvfDkIuZSw" onerror="this.src='https://drive.google.com/thumbnail?id=1EGsriYpF4s4_GQbCqPZhH0KvfDkIuZSw&sz=w300'" alt="Ảnh thực tế 2" class="h-20 w-full object-contain bg-slate-50 rounded border border-slate-100 p-1">
                <img src="https://lh3.googleusercontent.com/d/18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6" onerror="this.src='https://drive.google.com/thumbnail?id=18G-P8zl0ur88Q-wIC5qi0vm9aOBgKev6&sz=w300'" alt="Ảnh thực tế 3" class="h-20 w-full object-contain bg-slate-50 rounded border border-slate-100 p-1">
              </div>

              <div class="w-full overflow-hidden rounded border border-slate-100">
                <iframe 
                  title="Fanpage Camera An Ninh Đà Nẵng Tây Việt ELV"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fcameraanninhdanang.tayviet&tabs=timeline&width=300&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                  width="100%" 
                  height="180" 
                  style="border:none;overflow:hidden;width:100%;max-width:100%;" 
                  scrolling="no" 
                  frameborder="0" 
                  allowfullscreen="true" 
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                </iframe>
              </div>
            </div>

            <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
              <a href="https://www.facebook.com/cameraanninhdanang.tayviet" target="_blank" rel="noopener" class="inline-flex items-center gap-1.5 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold px-4 py-2 rounded-lg shadow-xs transition">
                <i class="fa-brands fa-facebook-f"></i> Truy cập Fanpage Tây Việt ELV
              </a>
              <a href="https://www.facebook.com/cameraanninhdanang.tayviet" target="_blank" rel="noopener" class="inline-flex items-center gap-1.5 bg-white hover:bg-slate-100 text-slate-700 border border-slate-300 text-xs font-bold px-3.5 py-2 rounded-lg transition">
                <i class="fa-brands fa-facebook-messenger text-[#1877F2]"></i> Nhắn tin Fanpage
              </a>
            </div>
          </div>

          <!-- CỘT 2: ẢNH & BẢN ĐỒ GOOGLE MAP NGOÀI TRANG CHỦ -->
          <div class="rounded-xl border border-slate-200 bg-slate-50 p-3.5 sm:p-4 flex flex-col justify-between space-y-3">
            <div class="flex items-start justify-between gap-2">
              <div>
                <div class="inline-flex items-center gap-1 text-[10px] font-bold text-emerald-700 bg-emerald-50 px-2 py-0.5 rounded mb-1">
                  <i class="fa-solid fa-location-dot"></i> VỊ TRÍ GOOGLE MAPS TRỤ SỞ
                </div>
                <h3 class="text-xs sm:text-sm font-extrabold text-slate-800">
                  54 Đô Đốc Lộc, Phường Hòa Xuân, TP Đà Nẵng
                </h3>
                <p class="text-[11px] text-slate-500 mt-0.5">
                  Hotline: <strong class="text-brand-accent">0329.081.555</strong> — Website: <strong class="text-brand-700">tayvietelv.com</strong>
                </p>
              </div>
              <a href="https://share.google/XoNAIU2KHmQN96VWT" target="_blank" rel="noopener" class="shrink-0 bg-brand-600 hover:bg-brand-700 text-white text-[11px] font-bold px-3 py-1.5 rounded-lg shadow-xs transition">
                <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Google Map
              </a>
            </div>

            <!-- Bản đồ Google Maps trực quan tại 54 Đô Đốc Lộc, Hòa Xuân, Đà Nẵng -->
            <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-slate-300 bg-white relative">
              <iframe 
                title="Bản đồ 54 Đô Đốc Lộc, Phường Hòa Xuân, TP Đà Nẵng"
                src="https://maps.google.com/maps?q=54%20%C4%90%C3%B4%20%C4%90%E1%BB%91c%20L%E1%BB%99c,%20H%C3%B2a%20Xu%C3%A2n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                width="100%" 
                height="100%" 
                style="border:0;" 
                allowfullscreen="" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>

            <div class="flex flex-wrap items-center justify-between gap-2 text-xs">
              <span class="text-slate-600"><i class="fa-solid fa-map-pin text-brand-accent mr-1"></i> Đ/c: 54 Đô Đốc Lộc, Phường Hòa Xuân, TP Đà Nẵng</span>
              <a href="https://share.google/XoNAIU2KHmQN96VWT" target="_blank" rel="noopener" class="font-bold text-brand-600 hover:underline">
                Xem chỉ đường trên Google Maps ➜
              </a>
            </div>
          </div>

        </div>
      </div>
    </section>

  </main>

  <!-- ==================== FOOTER CHUẨN FLATSOME (GIỐNG MẪU DANASMART) ==================== -->
  <footer class="bg-brand-900 text-slate-200 pt-8 pb-20 lg:pb-8 border-t-4 border-brand-600 text-xs">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-slate-700/80">
        
        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-2.5">
          <div class="flex items-center gap-2.5">
            <img src="https://lh3.googleusercontent.com/d/1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3" onerror="this.src='https://drive.google.com/thumbnail?id=1JAsz3qQXYYQi9ZLj7xz85fYdGOOcu8y3&sz=w200'" alt="Logo Tây Việt ELV" class="w-10 h-10 rounded-lg bg-white p-1 object-contain shrink-0">
            <div>
              <div class="font-extrabold text-white text-sm">TÂY VIỆT ELV</div>
              <div class="text-[11px] text-sky-300">tayvietelv.com</div>
            </div>
          </div>
          <h3 class="font-bold text-white text-xs leading-snug">
            CÔNG TY TNHH GIẢI PHÁP CÔNG NGHỆ TÂY VIỆT ELV
          </h3>
          <p class="text-slate-300 leading-relaxed">
            Chuyên thiết kế - tư vấn giải pháp - thi công lắp đặt hệ thống Camera An Ninh - Mạng - Smarthome uy tín hàng đầu tại Đà Nẵng.
          </p>
          <ul class="space-y-1.5 text-slate-300">
            <li><i class="fa-solid fa-location-dot text-amber-400 w-4"></i> Địa chỉ: 54 Đô Đốc Lộc, Phường Hòa Xuân, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-amber-400 w-4"></i> Hotline / Zalo: <a href="tel:0329081555" class="text-white font-bold">0329.081.555</a></li>
            <li><i class="fa-solid fa-globe text-amber-400 w-4"></i> Website: <a href="https://tayvietelv.com" class="text-sky-300 hover:underline">https://tayvietelv.com</a></li>
            <li><i class="fa-brands fa-facebook text-amber-400 w-4"></i> Fanpage: <a href="https://www.facebook.com/cameraanninhdanang.tayviet" target="_blank" rel="noopener" class="text-sky-300 hover:underline">fb.com/cameraanninhdanang.tayviet</a></li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm chính -->
        <div class="space-y-2">
          <h4 class="font-extrabold text-white text-xs uppercase tracking-wider border-b border-slate-700 pb-2">
            DANH MỤC SẢN PHẨM
          </h4>
          <ul class="space-y-1.5 text-slate-300">
            <li><a href="#cat-camera" class="hover:text-white">› Hệ thống Camera Giám Sát An Ninh</a></li>
            <li><a href="#cat-mang" class="hover:text-white">› Bộ chuyển mạch Switch PoE / Gigabit</a></li>
            <li><a href="#cat-mang" class="hover:text-white">› Bộ phát sóng Wifi – Access Point</a></li>
            <li><a href="#cat-mang" class="hover:text-white">› Router Cân bằng tải & Firewall Tường lửa</a></li>
            <li><a href="#cat-smarthome" class="hover:text-white">› Nhà thông minh (Smarthome) & Khóa vân tay</a></li>
            <li><a href="#cat-smarthome" class="hover:text-white">› Hệ thống Báo cháy & Âm thanh thông báo</a></li>
            <li><a href="#cat-mang" class="hover:text-white">› Tổng đài IP, Máy chấm công, Server NAS</a></li>
          </ul>
        </div>

        <!-- Cột 3: Chính sách & Hỗ trợ khách hàng -->
        <div class="space-y-2">
          <h4 class="font-extrabold text-white text-xs uppercase tracking-wider border-b border-slate-700 pb-2">
            THÔNG TIN - CHÍNH SÁCH
          </h4>
          <ul class="space-y-1.5 text-slate-300">
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách bảo hành chính hãng tận nơi</a></li>
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách vận chuyển & lắp đặt</a></li>
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách đổi trả & hoàn tiền</a></li>
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách thanh toán & xuất hóa đơn VAT</a></li>
            <li><a href="#bao-gia" class="hover:text-white">› Chính sách bảo mật thông tin khách hàng</a></li>
            <li><a href="#dich-vu-elv" class="hover:text-white">› Quy trình khảo sát & thi công Điện nhẹ ELV</a></li>
          </ul>
        </div>

        <!-- Cột 4: Kết nối nhanh -->
        <div class="space-y-2.5">
          <h4 class="font-extrabold text-white text-xs uppercase tracking-wider border-b border-slate-700 pb-2">
            LIÊN HỆ KHẢO SÁT NHANH
          </h4>
          <p class="text-slate-300 leading-relaxed">
            Hỗ trợ tư vấn giải pháp kỹ thuật, khảo sát tận nơi miễn phí tại Đà Nẵng & khu vực Miền Trung.
          </p>
          <div class="p-3 rounded-lg bg-brand-800 border border-brand-700 space-y-2">
            <div class="text-amber-300 font-bold">HOTLINE KỸ THUẬT & BÁO GIÁ:</div>
            <a href="tel:0329081555" class="block text-lg font-extrabold text-white hover:text-amber-300">
              <i class="fa-solid fa-phone-volume mr-1.5"></i> 0329.081.555
            </a>
            <div class="flex items-center gap-2 pt-1">
              <a href="https://zalo.me/0329081555" target="_blank" rel="noopener" class="flex-1 text-center py-1.5 rounded bg-sky-500 hover:bg-sky-400 text-white font-bold">Chat Zalo</a>
              <a href="https://share.google/XoNAIU2KHmQN96VWT" target="_blank" rel="noopener" class="flex-1 text-center py-1.5 rounded bg-emerald-600 hover:bg-emerald-500 text-white font-bold">Chỉ đường</a>
            </div>
          </div>
        </div>

      </div>

      <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400">
        <div>© Bản quyền thuộc về <strong>CÔNG TY TNHH GIẢI PHÁP CÔNG NGHỆ TÂY VIỆT ELV</strong> (tayvietelv.com)</div>
        <div>Địa chỉ: 54 Đô Đốc Lộc, Phường Hòa Xuân, TP Đà Nẵng | ĐT: 0329.081.555</div>
      </div>
    </div>
  </footer>

  <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ==================== -->
  <div class="fixed right-2.5 bottom-3 z-50 flex flex-col items-end gap-2">
    
    <!-- Nút Facebook Fanpage -->
    <a 
      href="https://www.facebook.com/cameraanninhdanang.tayviet" 
      target="_blank" 
      rel="noopener" 
      aria-label="Facebook Fanpage Tây Việt ELV"
      class="flex items-center gap-1.5 bg-[#1877F2] hover:bg-blue-700 text-white px-2.5 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
    >
      <i class="fa-brands fa-facebook-f text-xs w-4 text-center"></i>
      <span class="hidden sm:inline text-xs font-bold">Fanpage</span>
    </a>

    <!-- Nút Chat Zalo -->
    <a 
      href="https://zalo.me/0329081555" 
      target="_blank" 
      rel="noopener" 
      aria-label="Chat Zalo 0329.081.555"
      class="flex items-center gap-1.5 bg-[#0068ff] hover:bg-blue-600 text-white px-2.5 py-1.5 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
    >
      <span class="font-extrabold text-[10px] bg-white text-[#0068ff] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold">Chat Zalo</span>
    </a>

    <!-- Nút Gọi Hotline nổi bật -->
    <a 
      href="tel:0329081555" 
      aria-label="Gọi Hotline 0329.081.555"
      class="pulse-hotline flex items-center gap-1.5 bg-brand-accent hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-xl transition"
    >
      <i class="fa-solid fa-phone-volume text-xs"></i>
      <span class="text-[11px] sm:text-xs font-extrabold tracking-wide">0329.081.555</span>
    </a>

  </div>

</div>

  <!-- ==================== JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, MENU MOBILE & FORM BÁO GIÁ ==================== -->
  <script>
    // 0. Tự động xóa toàn bộ padding/margin của các khung bọc ngoài WordPress/Flatsome gây lệch phải trên điện thoại
    function fixParentAlignment() {
      const wrapper = document.querySelector('.tv-site-wrapper');
      if (!wrapper) return;
      let parent = wrapper.parentElement;
      while (parent && parent !== document.documentElement) {
        parent.style.setProperty('padding-left', '0px', 'important');
        parent.style.setProperty('padding-right', '0px', 'important');
        parent.style.setProperty('margin-left', '0px', 'important');
        parent.style.setProperty('margin-right', '0px', 'important');
        parent.style.setProperty('width', '100%', 'important');
        parent.style.setProperty('max-width', '100%', 'important');
        parent.style.setProperty('min-width', '0px', 'important');
        parent.style.setProperty('box-sizing', 'border-box', 'important');
        parent = parent.parentElement;
      }
    }
    fixParentAlignment();
    document.addEventListener('DOMContentLoaded', fixParentAlignment);
    window.addEventListener('resize', fixParentAlignment);

    // 1. Điều khiển 2 Banner tự trượt kích thước bằng nhau
    let currentSlideIndex = 0;
    const slides = document.querySelectorAll('.banner-slide');
    const dots = document.querySelectorAll('.slide-dot');
    let slideInterval = null;

    function renderSlide(index) {
      if (!slides.length) return;
      currentSlideIndex = (index + slides.length) % slides.length;
      slides.forEach((slide, i) => {
        if (i === currentSlideIndex) {
          slide.classList.add('slide-active');
        } else {
          slide.classList.remove('slide-active');
        }
      });
      dots.forEach((dot, i) => {
        if (i === currentSlideIndex) {
          dot.className = 'slide-dot w-4 h-1 rounded-full bg-amber-400 transition-all';
        } else {
          dot.className = 'slide-dot w-1.5 h-1 rounded-full bg-white/60 transition-all';
        }
      });
    }

    function changeSlide(step) {
      renderSlide(currentSlideIndex + step);
      resetAutoSlide();
    }

    function goToSlide(index) {
      renderSlide(index);
      resetAutoSlide();
    }

    function resetAutoSlide() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        renderSlide(currentSlideIndex + 1);
      }, 4500);
    }

    // 2. Điều khiển Drawer Menu trên điện thoại
    const mobileMenuBtn = document.getElementById('mobileMenuBtn');
    const closeMobileMenuBtn = document.getElementById('closeMobileMenuBtn');
    const mobileMenuOverlay = document.getElementById('mobileMenuOverlay');

    function openMobileMenu() {
      mobileMenuOverlay.classList.remove('hidden');
    }
    function closeMobileMenu() {
      mobileMenuOverlay.classList.add('hidden');
    }

    if (mobileMenuBtn) mobileMenuBtn.addEventListener('click', openMobileMenu);
    if (closeMobileMenuBtn) closeMobileMenuBtn.addEventListener('click', closeMobileMenu);
    if (mobileMenuOverlay) {
      mobileMenuOverlay.addEventListener('click', function(e) {
        if (e.target === mobileMenuOverlay) closeMobileMenu();
      });
    }

    // 3. Chọn sản phẩm đưa xuống Form Báo Giá & tăng giỏ hàng
    let cartCount = 0;
    function selectProductForQuote(productName) {
      cartCount++;
      const badge = document.getElementById('cartCountBadge');
      if (badge) badge.textContent = cartCount;

      const noteInput = document.getElementById('qNote');
      if (noteInput) {
        noteInput.value = 'Tôi cần tư vấn & báo giá sản phẩm: ' + productName;
      }
      const quoteSection = document.getElementById('bao-gia');
      if (quoteSection) {
        quoteSection.scrollIntoView({ behavior: 'smooth' });
      }
    }

    // 4. Tìm kiếm nhanh sản phẩm trên trang chủ
    function handleSearch(e) {
      e.preventDefault();
      const keyword = (document.getElementById('searchInput').value || '').trim().toLowerCase();
      const cards = document.querySelectorAll('.product-card');
      if (!keyword) {
        cards.forEach(c => c.style.display = '');
        return;
      }
      let firstMatch = null;
      cards.forEach(card => {
        const text = card.innerText.toLowerCase();
        if (text.includes(keyword)) {
          card.style.display = '';
          if (!firstMatch) firstMatch = card;
        } else {
          card.style.display = 'none';
        }
      });
      if (firstMatch) {
        firstMatch.scrollIntoView({ behavior: 'smooth', block: 'center' });
      } else {
        cards.forEach(c => c.style.display = '');
        document.getElementById('san-pham-chinh').scrollIntoView({ behavior: 'smooth' });
      }
    }

    // 5. Gửi Form Yêu Cầu Báo Giá
    function submitQuoteForm(e) {
      e.preventDefault();
      const name = document.getElementById('qName').value.trim();
      const phone = document.getElementById('qPhone').value.trim();
      const category = document.getElementById('qCategory').value;
      const address = document.getElementById('qAddress').value.trim();
      const note = document.getElementById('qNote').value.trim();

      const successBox = document.getElementById('quoteSuccessBox');
      successBox.classList.remove('hidden');
      successBox.innerHTML = `
        <div class="flex items-start gap-2">
          <i class="fa-solid fa-circle-check text-emerald-600 text-base mt-0.5"></i>
          <div>
            <div>Đã ghi nhận yêu cầu báo giá của <strong>${name}</strong> (SĐT: <strong>${phone}</strong>) cho hạng mục <strong>${category}</strong>${address ? ' tại ' + address : ''}.</div>
            <div class="mt-1">Bộ phận kỹ thuật <strong>Tây Việt ELV (0329.081.555)</strong> sẽ liên hệ tư vấn ngay!</div>
          </div>
        </div>
      `;
      document.getElementById('quoteForm').reset();
      if (note) document.getElementById('qNote').value = note;
    }

    window.onload = function() {
      fixParentAlignment();
      resetAutoSlide();
    };
  </script>
</body>
</html>
