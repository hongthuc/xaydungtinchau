<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>XÂY DỰNG TÍN CHÂU - Thiết Kế & Thi Công Trọn Gói Đà Nẵng | xaydungtinchau.com</title>
    <meta name="description" content="CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG TÍN CHÂU chuyên Thiết kế - Xây dựng - Nội thất các công trình Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố tại Đà Nẵng. Địa chỉ: 125 Thanh Lương 16, Hoà Xuân, TP. Đà Nẵng. Hotline: 0935.090.716 - 0905.636.159">

    <!-- Open Graph Thumbnail là Logo của trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://xaydungtinchau.com/">
    <meta property="og:title" content="XÂY DỰNG TÍN CHÂU - Thiết Kế & Thi Công Xây Dựng Trọn Gói Đà Nẵng">
    <meta property="og:description" content="Chuyên Thiết kế Kiến trúc - Thi công Phần thô - Thi công Hoàn thiện - Nội thất Nhà phố, Biệt thự, Căn hộ, Khách sạn tại Đà Nẵng. Hotline: 0935.090.716 - 0905.636.159">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1SW4EducCl-I9N9Ooj3N-fpKXo9pdQ5Er&sz=w1200">
    <meta property="og:image:alt" content="Logo Xây Dựng Tín Châu">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1SW4EducCl-I9N9Ooj3N-fpKXo9pdQ5Er&sz=w1200">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1SW4EducCl-I9N9Ooj3N-fpKXo9pdQ5Er&sz=w200">

    <!-- Tailwind CSS & Font Awesome & Google Fonts (Inter) -->
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
                            navy: '#0f2942',
                            dark: '#091a2b',
                            gold: '#c88a2b',
                            goldLight: '#e3a84b',
                            accent: '#1a446c',
                            bg: '#f8fafc'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Khắc phục triệt để tràn viền hoặc lệch sang phải trên mọi thiết bị */
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
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Chuẩn khung giao diện Flatsome: Chiều ngang 95% trên máy tính */
        .flatsome-container {
            width: 100%;
            padding-left: 12px;
            padding-right: 12px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu chữ danh mục trên máy tính: nhỏ gọn, viết liền trên 1 hàng, không ngắt dòng tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px 6px;
        }
        .desktop-nav-item {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            letter-spacing: -0.01em;
            padding: 6px 8px;
            border-radius: 6px;
            transition: all 0.2s ease;
            color: #0f2942;
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }
        @media (min-width: 1280px) {
            .desktop-nav-item {
                font-size: 13px;
                padding: 7px 10px;
            }
        }
        .desktop-nav-item:hover, .desktop-nav-item.active {
            color: #c88a2b;
            background-color: rgba(200, 138, 43, 0.08);
        }

        /* Dropdown menu kiểu Flatsome */
        .nav-dropdown-parent {
            position: relative;
        }
        .nav-dropdown-menu {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #ffffff;
            border-top: 3px solid #c88a2b;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.12);
            border-radius: 0 0 8px 8px;
            padding: 6px 0;
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
            z-index: 100;
        }
        .nav-dropdown-parent:hover .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }
        .nav-dropdown-menu a {
            display: block;
            padding: 8px 16px;
            font-size: 12.5px;
            font-weight: 500;
            color: #1e293b;
            white-space: nowrap;
            transition: all 0.15s ease;
        }
        .nav-dropdown-menu a:hover {
            background-color: #f1f5f9;
            color: #c88a2b;
            padding-left: 20px;
        }

        /* Nút danh mục nhỏ gọn ở trang chủ */
        .cat-filter-btn {
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 12px;
            border-radius: 6px;
            border: 1px solid #cbd5e1;
            background-color: #ffffff;
            color: #334155;
            transition: all 0.2s ease;
            cursor: pointer;
        }
        .cat-filter-btn:hover, .cat-filter-btn.active {
            background-color: #0f2942;
            color: #ffffff;
            border-color: #0f2942;
        }

        /* Thiết kế 2 Banner tự trượt kích thước bằng nhau tuyệt đối, chữ cách xa viền */
        .banner-slider-wrapper {
            position: relative;
            width: 100%;
            height: 360px;
            overflow: hidden;
            border-radius: 10px;
            background-color: #091a2b;
        }
        @media (min-width: 640px) {
            .banner-slider-wrapper {
                height: 420px;
            }
        }
        @media (min-width: 1024px) {
            .banner-slider-wrapper {
                height: 480px;
            }
        }
        .banner-slide {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            visibility: hidden;
            transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
        }
        .banner-slide.active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }

        /* Tiêu đề section kiểu Flatsome */
        .section-title-container {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 20px;
            text-align: center;
        }
        .section-title-line {
            flex: 1;
            height: 2px;
            background-color: #e2e8f0;
            max-width: 120px;
        }
        .section-title-main {
            padding: 0 16px;
            font-weight: 800;
            color: #0f2942;
            text-transform: uppercase;
            letter-spacing: 0.02em;
        }

        /* Box sản phẩm/công trình Flatsome: Đảm bảo tên sản phẩm hiển thị đầy đủ 100%, không bị cắt chữ */
        .ux-product-box {
            background: #ffffff;
            border-radius: 8px;
            overflow: hidden;
            border: 1px solid #e2e8f0;
            transition: transform 0.25s ease, box-shadow 0.25s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        .ux-product-box:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 24px -6px rgba(15, 41, 66, 0.14);
        }
        .ux-box-image {
            position: relative;
            width: 100%;
            padding-top: 72%;
            overflow: hidden;
            background-color: #e2e8f0;
        }
        .ux-box-image img {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        .ux-product-box:hover .ux-box-image img {
            transform: scale(1.06);
        }
        .ux-box-text {
            padding: 10px 10px 12px;
            text-align: center;
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .ux-box-title {
            font-size: 13px;
            line-height: 1.4;
            font-weight: 700;
            color: #0f2942;
            word-wrap: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            margin-bottom: 4px;
        }
        @media (min-width: 768px) {
            .ux-box-title {
                font-size: 14.5px;
            }
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 138, 43, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(200, 138, 43, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 138, 43, 0); }
        }
        .floating-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ================= TOP BAR (FLATSOME TOPBAR) ================= -->
    <div class="bg-brand-navy text-white text-xs py-2 border-b border-white/10">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center flex-wrap gap-x-4 gap-y-1">
                <span><i class="fa-solid fa-location-dot text-brand-gold mr-1.5"></i>125 Thanh Lương 16, Hoà Xuân, TP. Đà Nẵng</span>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:inline"><i class="fa-solid fa-globe text-brand-gold mr-1.5"></i>xaydungtinchau.com</span>
            </div>
            <div class="flex items-center gap-3 ml-auto">
                <a href="tel:0935090716" class="hover:text-brand-goldLight transition font-medium">
                    <i class="fa-solid fa-phone-volume text-brand-gold mr-1"></i>0935.090.716 - 0905.636.159
                </a>
                <span class="text-white/30">|</span>
                <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer" class="hover:text-brand-goldLight transition">
                    <i class="fa-brands fa-facebook-f mr-1"></i>Fanpage
                </a>
            </div>
        </div>
    </div>

    <!-- ================= HEADER (LOGO GỌN NHỎ & DANH MỤC 1 HÀNG, KHÔNG ĐỂ NÚT GỌI NGAY) ================= -->
    <header id="header" class="bg-white sticky top-0 z-50 shadow-sm border-b border-slate-200">
        <div class="flatsome-container py-2">
            <div class="flex items-center justify-between gap-3">
                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                    <img 
                        src="https://drive.google.com/thumbnail?id=1SW4EducCl-I9N9Ooj3N-fpKXo9pdQ5Er&sz=w400" 
                        onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1SW4EducCl-I9N9Ooj3N-fpKXo9pdQ5Er';"
                        alt="Logo Xây Dựng Tín Châu" 
                        class="h-9 sm:h-11 w-auto object-contain rounded border border-slate-100 p-0.5 bg-white"
                    >
                    <div class="leading-tight">
                        <span class="block text-sm sm:text-base font-extrabold text-brand-navy tracking-tight group-hover:text-brand-gold transition">XÂY DỰNG TÍN CHÂU</span>
                        <span class="block text-[10px] sm:text-[11px] font-medium text-slate-500">xaydungtinchau.com</span>
                    </div>
                </a>

                <!-- Menu Danh mục trên Máy tính: Viết liền trên 1 hàng chữ nhỏ gọn, không xuống dòng từng chữ -->
                <nav class="hidden lg:block flex-1">
                    <ul class="desktop-nav-list">
                        <li><a href="#trang-chu" class="desktop-nav-item active">Trang chủ</a></li>
                        <li><a href="#gioi-thieu" class="desktop-nav-item">Giới thiệu</a></li>
                        <li class="nav-dropdown-parent">
                            <a href="#cong-trinh-thuc-te" class="desktop-nav-item">Công trình thực tế <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i></a>
                            <div class="nav-dropdown-menu">
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san-can-ho')">Khách sạn – Căn hộ – Phòng trọ</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')">Biệt thự</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')">Nhà phố</a>
                                <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')">Văn phòng</a>
                            </div>
                        </li>
                        <li class="nav-dropdown-parent">
                            <a href="#linh-vuc-hoat-dong" class="desktop-nav-item">Lĩnh vực hoạt động <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i></a>
                            <div class="nav-dropdown-menu">
                                <a href="#linh-vuc-hoat-dong">Thiết kế Kiến trúc – Nội thất</a>
                                <a href="#linh-vuc-hoat-dong">Thi công phần thô</a>
                                <a href="#linh-vuc-hoat-dong">Thi công hoàn thiện</a>
                                <a href="#linh-vuc-hoat-dong">Thi công nội thất</a>
                            </div>
                        </li>
                        <li class="nav-dropdown-parent">
                            <a href="#du-an-da-nang" class="desktop-nav-item">Dự án Đà Nẵng <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i></a>
                            <div class="nav-dropdown-menu">
                                <a href="#du-an-da-nang" onclick="filterDanang('all')">Tất cả dự án Đà Nẵng</a>
                                <a href="#du-an-da-nang" onclick="filterDanang('mau-nha-pho')">Mẫu thiết kế nhà phố</a>
                                <a href="#du-an-da-nang" onclick="filterDanang('mau-biet-thu')">Mẫu thiết kế biệt thự</a>
                                <a href="#du-an-da-nang" onclick="filterDanang('mau-noi-that')">Mẫu thiết kế nội thất</a>
                            </div>
                        </li>
                        <li class="nav-dropdown-parent">
                            <a href="#bao-gia" class="desktop-nav-item">Báo giá <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i></a>
                            <div class="nav-dropdown-menu">
                                <a href="#bao-gia">Báo giá thiết kế kiến trúc</a>
                                <a href="#bao-gia">Báo giá thi công phần thô</a>
                                <a href="#bao-gia">Báo giá thi công hoàn thiện</a>
                                <a href="#bao-gia">Báo giá thi công trọn gói</a>
                            </div>
                        </li>
                        <li><a href="#doi-tac" class="desktop-nav-item">Đối tác</a></li>
                        <li><a href="#tin-tuc" class="desktop-nav-item">Tin tức</a></li>
                        <li><a href="#lien-he" class="desktop-nav-item">Liên hệ</a></li>
                    </ul>
                </nav>

                <!-- Nút mở Menu trên Điện thoại (Không để nút gọi ngay trên Header để tránh tràn viền) -->
                <button id="mobile-menu-btn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg text-brand-navy hover:bg-slate-100 border border-slate-200">
                    <i id="mobile-menu-icon" class="fa-solid fa-bars text-lg"></i>
                </button>
            </div>

            <!-- Thanh danh mục cuộn ngang gọn đẹp trên Điện thoại -->
            <div class="lg:hidden mt-2 pt-2 border-t border-slate-100 flex items-center gap-1.5 overflow-x-auto no-scrollbar pb-1">
                <a href="#trang-chu" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-brand-navy text-white">Trang chủ</a>
                <a href="#cong-trinh-thuc-te" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-brand-navy">Công trình thực tế</a>
                <a href="#du-an-da-nang" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-brand-navy">Dự án Đà Nẵng</a>
                <a href="#linh-vuc-hoat-dong" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-brand-navy">Lĩnh vực hoạt động</a>
                <a href="#bao-gia" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-brand-navy">Báo giá</a>
                <a href="#doi-tac" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-brand-navy">Đối tác</a>
                <a href="#tin-tuc" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-brand-navy">Tin tức</a>
                <a href="#lien-he" class="whitespace-nowrap text-[11.5px] font-semibold px-2.5 py-1 rounded bg-slate-100 text-brand-navy">Liên hệ</a>
            </div>
        </div>

        <!-- Menu xổ xuống đầy đủ danh mục trên Điện thoại -->
        <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="flatsome-container py-3 space-y-1 text-xs font-semibold text-brand-navy">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">Trang chủ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">Giới thiệu Xây Dựng Tín Châu</a>
                <div class="py-1 px-3">
                    <div class="text-brand-gold font-bold mb-1">Công trình thực tế</div>
                    <div class="grid grid-cols-2 gap-1.5 pl-2 font-medium text-slate-700">
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san-can-ho'); toggleMobileMenu()" class="py-1 hover:text-brand-gold">• Khách sạn – Căn hộ</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu'); toggleMobileMenu()" class="py-1 hover:text-brand-gold">• Biệt thự</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho'); toggleMobileMenu()" class="py-1 hover:text-brand-gold">• Nhà phố</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong'); toggleMobileMenu()" class="py-1 hover:text-brand-gold">• Văn phòng</a>
                    </div>
                </div>
                <div class="py-1 px-3">
                    <div class="text-brand-gold font-bold mb-1">Lĩnh vực hoạt động & Báo giá</div>
                    <div class="grid grid-cols-2 gap-1.5 pl-2 font-medium text-slate-700">
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-brand-gold">• Thiết kế Kiến trúc</a>
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-brand-gold">• Thi công phần thô</a>
                        <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="py-1 hover:text-brand-gold">• Thi công hoàn thiện</a>
                        <a href="#bao-gia" onclick="toggleMobileMenu()" class="py-1 hover:text-brand-gold">• Báo giá trọn gói</a>
                    </div>
                </div>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">Dự án tiêu biểu tại Đà Nẵng</a>
                <a href="#doi-tac" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">Đối tác vật tư</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">Tin tức & Kinh nghiệm</a>
                <a href="#lien-he" onclick="toggleMobileMenu()" class="block py-2 px-3 rounded hover:bg-slate-100">Liên hệ & Bản đồ</a>
            </div>
        </div>
    </header>

    <!-- ================= MAIN CONTENT (CHUẨN CẤU TRÚC SECTION FLATSOME) ================= -->
    <main id="trang-chu">

        <!-- SECTION 1: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU, CHỮ CÁCH XA VIỀN, KHÔNG THIẾU CHỮ -->
        <section class="py-3 sm:py-4">
            <div class="flatsome-container">
                <div class="banner-slider-wrapper shadow-md">

                    <!-- SLIDE 1 -->
                    <div class="banner-slide active" data-slide="0">
                        <img 
                            src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT';"
                            alt="Banner Thiết Kế Thi Công Trọn Gói Xây Dựng Tín Châu" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/90 via-brand-navy/80 to-brand-dark/65"></div>
                        
                        <!-- Khung nội dung chữ & ảnh nằm gọn bên trong và cách xa viền banner -->
                        <div class="absolute inset-0 flex items-center justify-between px-8 py-6 sm:px-16 md:px-20 lg:px-24">
                            <div class="w-full lg:w-7/12 text-white space-y-2.5 sm:space-y-3.5">
                                <div class="inline-block bg-brand-gold text-white text-[11px] sm:text-xs font-bold px-3 py-1 rounded uppercase tracking-wider">
                                    CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG TÍN CHÂU
                                </div>
                                <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                    THIẾT KẾ & THI CÔNG XÂY DỰNG TRỌN GÓI TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                                    Chuyên Thiết kế Kiến trúc – Thi công Phần thô – Hoàn thiện – Nội thất Nhà phố, Biệt thự, Khách sạn, Căn hộ. Cam kết An toàn – Chất lượng – Đúng tiến độ.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-2.5 text-xs sm:text-sm">
                                    <a href="#form-bao-gia" class="bg-brand-gold hover:bg-brand-goldLight text-white font-bold px-4 py-2 rounded transition shadow">
                                        Nhận Báo Giá Ngay
                                    </a>
                                    <a href="#cong-trinh-thuc-te" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold px-4 py-2 rounded transition">
                                        Xem Công Trình Thực Tế
                                    </a>
                                </div>
                            </div>
                            <!-- Hình ảnh công trình phụ nằm gọn trong banner trên máy tính -->
                            <div class="hidden lg:grid grid-cols-2 gap-3 w-4/12">
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36">
                                    <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff';" alt="Dự án Tín Châu 1" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36">
                                    <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz';" alt="Thi công thực tế Tín Châu" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- SLIDE 2 -->
                    <div class="banner-slide" data-slide="1">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w1600" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz';"
                            alt="Banner Kiến Trúc & Nội Thất Xây Dựng Tín Châu" 
                            class="w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/90 via-brand-navy/80 to-brand-dark/65"></div>

                        <!-- Khung nội dung chữ & ảnh nằm gọn bên trong và cách xa viền banner -->
                        <div class="absolute inset-0 flex items-center justify-between px-8 py-6 sm:px-16 md:px-20 lg:px-24">
                            <div class="w-full lg:w-7/12 text-white space-y-2.5 sm:space-y-3.5">
                                <div class="inline-block bg-brand-gold text-white text-[11px] sm:text-xs font-bold px-3 py-1 rounded uppercase tracking-wider">
                                    ANCI DESIGN & BUILDING - XÂY DỰNG TÍN CHÂU
                                </div>
                                <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold leading-snug">
                                    KIẾN TẠO KHÔNG GIAN SỐNG ĐẲNG CẤP & BỀN VỮNG
                                </h2>
                                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                                    Trụ sở: 125 Thanh Lương 16, Hoà Xuân, TP. Đà Nẵng | Hotline: 0935.090.716 - 0905.636.159. Miễn phí 100% chi phí thiết kế khi ký hợp đồng thi công trọn gói.
                                </p>
                                <div class="pt-1 flex flex-wrap items-center gap-2.5 text-xs sm:text-sm">
                                    <a href="tel:0935090716" class="bg-brand-gold hover:bg-brand-goldLight text-white font-bold px-4 py-2 rounded transition shadow">
                                        Tư Vấn: 0935.090.716
                                    </a>
                                    <a href="#du-an-da-nang" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-semibold px-4 py-2 rounded transition">
                                        Dự Án Tại Đà Nẵng
                                    </a>
                                </div>
                            </div>
                            <!-- Hình ảnh công trình phụ nằm gọn trong banner trên máy tính -->
                            <div class="hidden lg:grid grid-cols-2 gap-3 w-4/12">
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36">
                                    <img src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k';" alt="Dự án Đà Nẵng Tín Châu" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-36">
                                    <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_';" alt="Thi công Tín Châu" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Nút chuyển Slide Trái / Phải nằm gọn trong viền -->
                    <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-gold text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                    </button>
                    <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-brand-gold text-white flex items-center justify-center transition">
                        <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                    </button>

                    <!-- Dấu chấm chỉ báo Slide -->
                    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                        <button onclick="goToSlide(0)" class="banner-dot w-6 h-2 rounded-full bg-brand-gold transition-all" aria-label="Banner 1"></button>
                        <button onclick="goToSlide(1)" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 2: LĨNH VỰC HOẠT ĐỘNG TIÊU BIỂU (GIỐNG WEB MẪU TINTRUONGTHINH.COM) -->
        <section id="linh-vuc-hoat-dong" class="py-8 bg-white border-y border-slate-200/80">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="section-title-main text-base sm:text-xl">LĨNH VỰC HOẠT ĐỘNG</h2>
                    <span class="section-title-line"></span>
                </div>

                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <div class="ux-product-box p-4 text-center">
                        <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-brand-navy text-brand-gold flex items-center justify-center text-xl">
                            <i class="fa-solid fa-compass-drafting"></i>
                        </div>
                        <h3 class="ux-box-title">Thiết Kế Kiến Trúc – Nội Thất</h3>
                        <p class="text-xs text-slate-600 leading-relaxed mt-1">
                            Thiết kế mặt bằng công năng, phối cảnh 3D kiến trúc và nội thất nhà phố, biệt thự, căn hộ, khách sạn tối ưu diện tích và phong thủy.
                        </p>
                    </div>

                    <div class="ux-product-box p-4 text-center">
                        <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-brand-navy text-brand-gold flex items-center justify-center text-xl">
                            <i class="fa-solid fa-helmet-safety"></i>
                        </div>
                        <h3 class="ux-box-title">Thi Công Phần Thô</h3>
                        <p class="text-xs text-slate-600 leading-relaxed mt-1">
                            Thi công móng, kết cấu bê tông cốt thép, xây tô tường đúng tiêu chuẩn kỹ thuật với vật tư chính hãng Đà Nẵng.
                        </p>
                    </div>

                    <div class="ux-product-box p-4 text-center">
                        <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-brand-navy text-brand-gold flex items-center justify-center text-xl">
                            <i class="fa-solid fa-paint-roller"></i>
                        </div>
                        <h3 class="ux-box-title">Thi Công Hoàn Thiện</h3>
                        <p class="text-xs text-slate-600 leading-relaxed mt-1">
                            Ốp lát gạch đá, sơn bả, trần thạch cao, lắp đặt hệ thống điện nước, cửa nhôm kính và bàn giao nhà chìa khóa trao tay.
                        </p>
                    </div>

                    <div class="ux-product-box p-4 text-center">
                        <div class="w-12 h-12 mx-auto mb-3 rounded-full bg-brand-navy text-brand-gold flex items-center justify-center text-xl">
                            <i class="fa-solid fa-couch"></i>
                        </div>
                        <h3 class="ux-box-title">Thi Công Nội Thất</h3>
                        <p class="text-xs text-slate-600 leading-relaxed mt-1">
                            Sản xuất và lắp đặt nội thất gỗ công nghiệp An Cường, gỗ tự nhiên sắc nét cho phòng khách, bếp, phòng ngủ, văn phòng.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 3: GIỚI THIỆU CÔNG TY & 6 THẾ MẠNH (THEO MẪU TINTRUONGTHINH & ANCI DESIGN) -->
        <section id="gioi-thieu" class="py-8 sm:py-10">
            <div class="flatsome-container">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-white p-4 sm:p-6 rounded-xl border border-slate-200 shadow-sm">
                    <div class="lg:col-span-7 space-y-3">
                        <div class="text-xs font-bold text-brand-gold uppercase tracking-wider">VỀ CHÚNG TÔI • XAYDUNGTINCHAU.COM</div>
                        <h2 class="text-lg sm:text-2xl font-extrabold text-brand-navy">
                            CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG TÍN CHÂU
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            <strong>XÂY DỰNG TÍN CHÂU</strong> (kết hợp cùng đội ngũ <strong>Anci Design & Building</strong>) chuyên Thiết kế – Xây dựng – Nội thất các công trình <strong>Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố</strong> tại khu vực TP. Đà Nẵng và miền Trung.
                        </p>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu, mỗi công trình do Tín Châu thực hiện luôn tuân thủ nghiêm ngặt tiêu chí: <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>. Công ty đã được cấp Chứng chỉ năng lực hoạt động xây dựng (Mã số: 00069740 - MST: 0402131771), đảm bảo năng lực pháp lý và kỹ thuật vững chắc cho mọi dự án.
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-3 gap-3 pt-2">
                            <div class="p-3 rounded-lg bg-slate-50 border border-slate-200">
                                <div class="font-bold text-brand-navy text-xs sm:text-sm"><i class="fa-solid fa-user-tie text-brand-gold mr-1.5"></i>Kỹ sư giàu kinh nghiệm</div>
                                <p class="text-[11px] text-slate-500 mt-1">Kiến trúc sư sáng tạo, đội thợ lành nghề lâu năm.</p>
                            </div>
                            <div class="p-3 rounded-lg bg-slate-50 border border-slate-200">
                                <div class="font-bold text-brand-navy text-xs sm:text-sm"><i class="fa-solid fa-clipboard-check text-brand-gold mr-1.5"></i>Giám sát chuẩn xác</div>
                                <p class="text-[11px] text-slate-500 mt-1">Báo cáo nhật ký công trình trực quan mỗi ngày.</p>
                            </div>
                            <div class="p-3 rounded-lg bg-slate-50 border border-slate-200 col-span-2 sm:col-span-1">
                                <div class="font-bold text-brand-navy text-xs sm:text-sm"><i class="fa-solid fa-shield-halved text-brand-gold mr-1.5"></i>Bảo hành dài hạn</div>
                                <p class="text-[11px] text-slate-500 mt-1">Bảo hành kết cấu lên đến 5-10 năm, hỗ trợ 24/7.</p>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5 grid grid-cols-2 gap-3">
                        <div class="rounded-lg overflow-hidden border border-slate-200 h-44 sm:h-52">
                            <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR';" alt="Thi công thực tế Xây Dựng Tín Châu" class="w-full h-full object-cover">
                        </div>
                        <div class="rounded-lg overflow-hidden border border-slate-200 h-44 sm:h-52">
                            <img src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N';" alt="Dự án Xây Dựng Tín Châu Đà Nẵng" class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 4: 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, KHÔNG NHÃN DÁN, KHÔNG CẮT CHỮ) -->
        <section id="cong-trinh-thuc-te" class="py-8 bg-white border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="section-title-main text-base sm:text-xl">CÔNG TRÌNH THỰC TẾ THI CÔNG XÂY DỰNG</h2>
                    <span class="section-title-line"></span>
                </div>

                <!-- Danh mục lọc nhỏ gọn trên máy tính và điện thoại -->
                <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                    <button onclick="filterConstruction('all')" data-cat="all" class="cons-tab cat-filter-btn active">Tất cả (9)</button>
                    <button onclick="filterConstruction('nha-pho')" data-cat="nha-pho" class="cons-tab cat-filter-btn">Nhà phố</button>
                    <button onclick="filterConstruction('biet-thu')" data-cat="biet-thu" class="cons-tab cat-filter-btn">Biệt thự</button>
                    <button onclick="filterConstruction('khach-san-can-ho')" data-cat="khach-san-can-ho" class="cons-tab cat-filter-btn">Khách sạn – Căn hộ – Phòng trọ</button>
                    <button onclick="filterConstruction('van-phong')" data-cat="van-phong" class="cons-tab cat-filter-btn">Văn phòng & Hoàn thiện</button>
                </div>

                <!-- Grid 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính -->
                <div id="construction-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                    <!-- 1. 13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz -->
                    <div class="ux-product-box cons-item" data-category="nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz';" alt="Thi công phần thô và kết cấu Nhà phố 3 tầng Hòa Xuân">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi công phần thô và kết cấu Nhà phố 3 tầng Hòa Xuân</h3>
                            <div class="text-[11px] text-slate-500">Danh mục: Nhà phố – Thi công phần thô</div>
                        </div>
                    </div>

                    <!-- 2. 1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR -->
                    <div class="ux-product-box cons-item" data-category="nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR';" alt="Thi công cốt thép sàn và đổ bê tông Nhà phố Cẩm Lệ">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi công cốt thép sàn và đổ bê tông Nhà phố Cẩm Lệ</h3>
                            <div class="text-[11px] text-slate-500">Danh mục: Nhà phố – Thi công phần thô</div>
                        </div>
                    </div>

                    <!-- 3. 1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv -->
                    <div class="ux-product-box cons-item" data-category="biet-thu">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv';" alt="Thi công xây tô tường và hoàn thiện mặt tiền Biệt thự">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi công xây tô tường và hoàn thiện mặt tiền Biệt thự</h3>
                            <div class="text-[11px] text-slate-500">Danh mục: Biệt thự – Thi công hoàn thiện</div>
                        </div>
                    </div>

                    <!-- 4. 1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_ -->
                    <div class="ux-product-box cons-item" data-category="khach-san-can-ho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_';" alt="Thi công kết cấu móng và khung cột Căn hộ cho thuê">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi công kết cấu móng và khung cột Căn hộ cho thuê</h3>
                            <div class="text-[11px] text-slate-500">Danh mục: Khách sạn – Căn hộ – Phòng trọ</div>
                        </div>
                    </div>

                    <!-- 5. 1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO -->
                    <div class="ux-product-box cons-item" data-category="nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO';" alt="Thi công trọn gói Nhà phố hiện đại Khu đô thị Nam Hòa Xuân">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi công trọn gói Nhà phố hiện đại Khu đô thị Nam Hòa Xuân</h3>
                            <div class="text-[11px] text-slate-500">Danh mục: Nhà phố – Thi công trọn gói</div>
                        </div>
                    </div>

                    <!-- 6. 1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t -->
                    <div class="ux-product-box cons-item" data-category="biet-thu">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t';" alt="Thi công lắp đặt hệ thống cơ điện và chống thấm Biệt thự">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi công lắp đặt hệ thống cơ điện và chống thấm Biệt thự</h3>
                            <div class="text-[11px] text-slate-500">Danh mục: Biệt thự – Thi công hoàn thiện</div>
                        </div>
                    </div>

                    <!-- 7. 1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_ -->
                    <div class="ux-product-box cons-item" data-category="khach-san-can-ho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_';" alt="Thi công phần thô tòa Căn hộ dịch vụ 5 tầng tại Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi công phần thô tòa Căn hộ dịch vụ 5 tầng tại Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Danh mục: Khách sạn – Căn hộ – Phòng trọ</div>
                        </div>
                    </div>

                    <!-- 8. 1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT -->
                    <div class="ux-product-box cons-item" data-category="van-phong">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT';" alt="Thi công hoàn thiện mặt tiền và nội thất Văn phòng công ty">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Thi công hoàn thiện mặt tiền và nội thất Văn phòng công ty</h3>
                            <div class="text-[11px] text-slate-500">Danh mục: Văn phòng – Thi công hoàn thiện</div>
                        </div>
                    </div>

                    <!-- 9. 1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn -->
                    <div class="ux-product-box cons-item" data-category="van-phong">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn';" alt="Nghiệm thu hoàn thiện kiến trúc và nội thất bàn giao công trình">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Nghiệm thu hoàn thiện kiến trúc và nội thất bàn giao công trình</h3>
                            <div class="text-[11px] text-slate-500">Danh mục: Thi công nội thất & Hoàn thiện</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 5: DANH MỤC 10 DỰ ÁN Ở ĐÀ NẴNG TRÊN TRANG CHỦ (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, KHÔNG NHÃN DÁN) -->
        <section id="du-an-da-nang" class="py-8 sm:py-10">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="section-title-main text-base sm:text-xl">DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG</h2>
                    <span class="section-title-line"></span>
                </div>

                <!-- Danh mục lọc nhỏ gọn -->
                <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6">
                    <button onclick="filterDanang('all')" data-dncat="all" class="dn-tab cat-filter-btn active">Tất cả dự án Đà Nẵng (10)</button>
                    <button onclick="filterDanang('mau-nha-pho')" data-dncat="mau-nha-pho" class="dn-tab cat-filter-btn">Mẫu thiết kế nhà phố</button>
                    <button onclick="filterDanang('mau-biet-thu')" data-dncat="mau-biet-thu" class="dn-tab cat-filter-btn">Mẫu thiết kế biệt thự</button>
                    <button onclick="filterDanang('mau-noi-that')" data-dncat="mau-noi-that" class="dn-tab cat-filter-btn">Khách sạn – Căn hộ & Nội thất</button>
                </div>

                <!-- Grid 2 cột trên điện thoại (grid-cols-2), 5 cột trên màn hình lớn -->
                <div id="danang-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                    <!-- Dự án 1: 157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT';" alt="Dự án Nhà phố hiện đại 3 tầng Khu đô thị Hòa Xuân, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Nhà phố hiện đại 3 tầng Khu đô thị Hòa Xuân, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: Hòa Xuân, Cẩm Lệ</div>
                        </div>
                    </div>

                    <!-- Dự án 2: 1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-biet-thu">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff';" alt="Dự án Biệt thự phố 2 mặt tiền sang trọng tại Ngũ Hành Sơn, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Biệt thự phố 2 mặt tiền sang trọng tại Ngũ Hành Sơn, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: Ngũ Hành Sơn, Đà Nẵng</div>
                        </div>
                    </div>

                    <!-- Dự án 3: 1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz';" alt="Dự án Nhà phố lệch tầng thông thoáng tại Quận Hải Châu, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Nhà phố lệch tầng thông thoáng tại Quận Hải Châu, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: Hải Châu, Đà Nẵng</div>
                        </div>
                    </div>

                    <!-- Dự án 4: 1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-biet-thu">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k';" alt="Dự án Biệt thự nghỉ dưỡng sân vườn Euro Village, Sơn Trà, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Biệt thự nghỉ dưỡng sân vườn Euro Village, Sơn Trà, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: Sơn Trà, Đà Nẵng</div>
                        </div>
                    </div>

                    <!-- Dự án 5: 1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-noi-that">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N';" alt="Dự án Tòa nhà Căn hộ cho thuê & Khách sạn ven biển Mỹ Khê, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Tòa nhà Căn hộ cho thuê & Khách sạn ven biển Mỹ Khê, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: Mỹ Khê, Đà Nẵng</div>
                        </div>
                    </div>

                    <!-- Dự án 6: 1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML';" alt="Dự án Nhà phố 3 tầng 1 tum phong cách Tropical tại Hòa Xuân, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Nhà phố 3 tầng 1 tum phong cách Tropical tại Hòa Xuân, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: Hòa Xuân, Đà Nẵng</div>
                        </div>
                    </div>

                    <!-- Dự án 7: 1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-nha-pho">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF';" alt="Dự án Nhà phố kết hợp kinh doanh mặt tiền Khu Nam Việt Á, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Nhà phố kết hợp kinh doanh mặt tiền Khu Nam Việt Á, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: Nam Việt Á, Đà Nẵng</div>
                        </div>
                    </div>

                    <!-- Dự án 8: 1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-biet-thu">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A';" alt="Dự án Biệt thự hiện đại mái bằng tại Khu đô thị FPT City, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Biệt thự hiện đại mái bằng tại Khu đô thị FPT City, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: FPT City, Đà Nẵng</div>
                        </div>
                    </div>

                    <!-- Dự án 9: 1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80 -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-noi-that">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80';" alt="Dự án Thiết kế và thi công Nội thất gỗ cao cấp Nhà phố Thanh Khê, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Thiết kế và thi công Nội thất gỗ cao cấp Nhà phố Thanh Khê, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: Thanh Khê, Đà Nẵng</div>
                        </div>
                    </div>

                    <!-- Dự án 10: 1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4 -->
                    <div class="ux-product-box dn-item" data-dncategory="mau-noi-that">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4&sz=w800" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4';" alt="Dự án Tổ hợp Văn phòng và Căn hộ cao cấp tại Liên Chiểu, Đà Nẵng">
                        </div>
                        <div class="ux-box-text">
                            <h3 class="ux-box-title">Dự án Tổ hợp Văn phòng và Căn hộ cao cấp tại Liên Chiểu, Đà Nẵng</h3>
                            <div class="text-[11px] text-slate-500">Khu vực: Liên Chiểu, Đà Nẵng</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 6: BẢNG BÁO GIÁ & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ (CHUẨN WEB MẪU) -->
        <section id="bao-gia" class="py-8 sm:py-10 bg-white border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="section-title-main text-base sm:text-xl">BÁO GIÁ THIẾT KẾ & THI CÔNG XÂY DỰNG</h2>
                    <span class="section-title-line"></span>
                </div>

                <!-- 4 Gói Báo Giá Chia 2 Cột Trên Điện Thoại -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5 mb-8">
                    <div class="ux-product-box p-4 border-t-4 border-t-brand-navy">
                        <h3 class="ux-box-title text-left">Báo giá thiết kế kiến trúc</h3>
                        <div class="text-base sm:text-lg font-extrabold text-brand-gold my-1.5">120.000đ – 180.000đ/m²</div>
                        <ul class="text-[11.5px] text-slate-600 space-y-1 mb-3">
                            <li>• Hồ sơ kiến trúc & phối cảnh 3D</li>
                            <li>• Hồ sơ kết cấu & điện nước M&E</li>
                            <li>• Miễn phí 100% khi thi công trọn gói</li>
                        </ul>
                        <a href="#form-bao-gia" class="mt-auto block text-center text-xs font-bold py-2 px-3 rounded bg-slate-100 hover:bg-brand-navy hover:text-white text-brand-navy transition">Đăng ký nhận báo giá</a>
                    </div>

                    <div class="ux-product-box p-4 border-t-4 border-t-brand-gold">
                        <h3 class="ux-box-title text-left">Báo giá thi công phần thô</h3>
                        <div class="text-base sm:text-lg font-extrabold text-brand-gold my-1.5">3.600.000đ – 3.950.000đ/m²</div>
                        <ul class="text-[11.5px] text-slate-600 space-y-1 mb-3">
                            <li>• Vật tư phần thô chuẩn chính hãng</li>
                            <li>• Nhân công hoàn thiện toàn bộ</li>
                            <li>• Giám sát kỹ sư trực tiếp tại công trình</li>
                        </ul>
                        <a href="#form-bao-gia" class="mt-auto block text-center text-xs font-bold py-2 px-3 rounded bg-slate-100 hover:bg-brand-navy hover:text-white text-brand-navy transition">Đăng ký nhận báo giá</a>
                    </div>

                    <div class="ux-product-box p-4 border-t-4 border-t-brand-navy">
                        <h3 class="ux-box-title text-left">Báo giá thi công hoàn thiện</h3>
                        <div class="text-base sm:text-lg font-extrabold text-brand-gold my-1.5">2.200.000đ – 3.200.000đ/m²</div>
                        <ul class="text-[11.5px] text-slate-600 space-y-1 mb-3">
                            <li>• Gạch ốp lát, sơn nước, trần thạch cao</li>
                            <li>• Thiết bị vệ sinh, hệ thống cửa, cầu thang</li>
                            <li>• Tùy chọn gói vật tư Khá – Tốt – Cao cấp</li>
                        </ul>
                        <a href="#form-bao-gia" class="mt-auto block text-center text-xs font-bold py-2 px-3 rounded bg-slate-100 hover:bg-brand-navy hover:text-white text-brand-navy transition">Đăng ký nhận báo giá</a>
                    </div>

                    <div class="ux-product-box p-4 border-t-4 border-t-brand-gold">
                        <h3 class="ux-box-title text-left">Báo giá thi công trọn gói</h3>
                        <div class="text-base sm:text-lg font-extrabold text-brand-gold my-1.5">5.800.000đ – 7.500.000đ/m²</div>
                        <ul class="text-[11.5px] text-slate-600 space-y-1 mb-3">
                            <li>• Chìa khóa trao tay – Không phát sinh</li>
                            <li>• Hỗ trợ xin giấy phép xây dựng Đà Nẵng</li>
                            <li>• Bảo hành kết cấu 10 năm, chống thấm 3 năm</li>
                        </ul>
                        <a href="#form-bao-gia" class="mt-auto block text-center text-xs font-bold py-2 px-3 rounded bg-brand-gold text-white hover:bg-brand-goldLight transition">Đăng ký nhận báo giá</a>
                    </div>
                </div>

                <!-- FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ TRANG CHỦ (THEO MẪU TINTRUONGTHINH.COM) -->
                <div id="form-bao-gia" class="bg-brand-navy text-white rounded-xl p-5 sm:p-8 shadow-md">
                    <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                        <div class="lg:col-span-5 space-y-3">
                            <span class="inline-block bg-brand-gold text-white text-xs font-bold px-3 py-1 rounded uppercase">HỖ TRỢ TƯ VẤN 24/7</span>
                            <h3 class="text-lg sm:text-2xl font-extrabold">ĐĂNG KÝ YÊU CẦU & NHẬN BÁO GIÁ MIỄN PHÍ</h3>
                            <p class="text-xs sm:text-sm text-slate-300 leading-relaxed">
                                Quý khách vui lòng để lại thông tin công trình dự kiến. Đội ngũ kỹ sư và kiến trúc sư <strong>Xây Dựng Tín Châu</strong> sẽ liên hệ khảo sát và lập bảng dự toán chi tiết trong vòng 30 phút.
                            </p>
                            <div class="space-y-1.5 text-xs sm:text-sm pt-1">
                                <div><i class="fa-solid fa-phone text-brand-gold mr-2"></i>Hotline: <strong>0935.090.716 - 0905.636.159</strong></div>
                                <div><i class="fa-solid fa-location-dot text-brand-gold mr-2"></i>Địa chỉ: <strong>125 Thanh Lương 16, Hoà Xuân, TP. Đà Nẵng</strong></div>
                                <div><i class="fa-solid fa-globe text-brand-gold mr-2"></i>Website: <strong>xaydungtinchau.com</strong></div>
                            </div>
                        </div>

                        <div class="lg:col-span-7">
                            <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 p-4 sm:p-6 rounded-lg space-y-3">
                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                    <div>
                                        <label class="block text-xs font-bold text-brand-navy mb-1">Họ và tên *</label>
                                        <input type="text" id="q_name" required placeholder="Nhập họ và tên của bạn" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-gold">
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-brand-navy mb-1">Số điện thoại *</label>
                                        <input type="tel" id="q_phone" required placeholder="Nhập số điện thoại liên hệ" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-gold">
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-3 gap-3">
                                    <div>
                                        <label class="block text-xs font-bold text-brand-navy mb-1">Loại công trình</label>
                                        <select id="q_type" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-gold bg-white">
                                            <option value="Nhà phố">Nhà phố</option>
                                            <option value="Biệt thự">Biệt thự</option>
                                            <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                                            <option value="Văn phòng">Văn phòng</option>
                                            <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-brand-navy mb-1">Mức đầu tư dự kiến</label>
                                        <select id="q_budget" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-gold bg-white">
                                            <option value="Dưới 1 tỷ">Dưới 1 tỷ</option>
                                            <option value="1 - 2 tỷ" selected>1 - 2 tỷ</option>
                                            <option value="2 - 3 tỷ">2 - 3 tỷ</option>
                                            <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                            <option value="Chưa xác định">Chưa xác định</option>
                                        </select>
                                    </div>
                                    <div>
                                        <label class="block text-xs font-bold text-brand-navy mb-1">Diện tích đất / Số tầng</label>
                                        <input type="text" id="q_area" placeholder="VD: 5x20m, 3 tầng" class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-gold">
                                    </div>
                                </div>

                                <div>
                                    <label class="block text-xs font-bold text-brand-navy mb-1">Yêu cầu chi tiết (Khu vực xây dựng, nhu cầu thiết kế/thi công...)</label>
                                    <textarea id="q_note" rows="2" placeholder="Nhập địa chỉ lô đất tại Đà Nẵng và nhu cầu của Quý khách..." class="w-full px-3 py-2 text-xs sm:text-sm border border-slate-300 rounded focus:outline-none focus:border-brand-gold"></textarea>
                                </div>

                                <div id="quoteSuccessMsg" class="hidden p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>

                                <button type="submit" class="w-full bg-brand-gold hover:bg-brand-goldLight text-white font-extrabold text-xs sm:text-sm py-2.5 px-4 rounded transition shadow uppercase tracking-wide">
                                    <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU TƯ VẤN & BÁO GIÁ NGAY
                                </button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 7: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM XÂY DỰNG) -->
        <section id="tin-tuc" class="py-8 sm:py-10">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="section-title-main text-base sm:text-xl">TIN TỨC & KINH NGHIỆM XÂY DỰNG</h2>
                    <span class="section-title-line"></span>
                </div>

                <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                    <article class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz';" alt="Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật">
                        </div>
                        <div class="ux-box-text text-left">
                            <h3 class="ux-box-title text-left">Hướng dẫn bảo dưỡng bê tông móng và sàn đúng kỹ thuật</h3>
                            <p class="text-[11.5px] text-slate-600 mt-1 leading-relaxed">
                                Quy trình tưới nước giữ ẩm và kiểm tra cường độ bê tông tươi sau khi đổ giúp kết cấu ngôi nhà bền vững hàng chục năm.
                            </p>
                        </div>
                    </article>

                    <article class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT';" alt="Kinh nghiệm xây nhà trọn gói tại Đà Nẵng tiết kiệm chi phí">
                        </div>
                        <div class="ux-box-text text-left">
                            <h3 class="ux-box-title text-left">Kinh nghiệm xây nhà trọn gói tại Đà Nẵng tiết kiệm chi phí</h3>
                            <p class="text-[11.5px] text-slate-600 mt-1 leading-relaxed">
                                Giải pháp lập bảng dự toán chi tiết ngay từ khâu thiết kế kiến trúc giúp chủ đầu tư kiểm soát 100% ngân sách, không lo phát sinh.
                            </p>
                        </div>
                    </article>

                    <article class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80';" alt="Tâm lý học không gian: Thiết kế nội thất tối ưu ánh sáng và thông gió">
                        </div>
                        <div class="ux-box-text text-left">
                            <h3 class="ux-box-title text-left">Tâm lý học không gian: Thiết kế nội thất tối ưu ánh sáng và thông gió</h3>
                            <p class="text-[11.5px] text-slate-600 mt-1 leading-relaxed">
                                Cách bố trí giếng trời, thông tầng và vật liệu nội thất hiện đại phù hợp với khí hậu nhiệt đới ven biển Đà Nẵng.
                            </p>
                        </div>
                    </article>

                    <article class="ux-product-box">
                        <div class="ux-box-image">
                            <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR';" alt="Thủ tục xin giấy phép xây dựng và chứng chỉ năng lực thi công tại Đà Nẵng">
                        </div>
                        <div class="ux-box-text text-left">
                            <h3 class="ux-box-title text-left">Thủ tục xin giấy phép xây dựng và chứng chỉ năng lực thi công tại Đà Nẵng</h3>
                            <p class="text-[11.5px] text-slate-600 mt-1 leading-relaxed">
                                Tổng hợp hồ sơ pháp lý cần chuẩn bị khi xây dựng nhà phố, biệt thự tại Hòa Xuân, Cẩm Lệ, Hải Châu, Sơn Trà, Ngũ Hành Sơn.
                            </p>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!-- SECTION 8: DANH MỤC CÁC ĐỐI TÁC & VẬT TƯ CHÍNH HÃNG -->
        <section id="doi-tac" class="py-8 bg-white border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="section-title-main text-base sm:text-xl">ĐỐI TÁC & THƯƠNG HIỆU VẬT TƯ ĐỒNG HÀNH</h2>
                    <span class="section-title-line"></span>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                    <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand-gold transition">
                        <div class="font-extrabold text-brand-navy text-xs sm:text-sm">THÉP HÒA PHÁT</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thép kết cấu xây dựng</div>
                    </div>
                    <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand-gold transition">
                        <div class="font-extrabold text-brand-navy text-xs sm:text-sm">XI MĂNG KIM ĐỈNH</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Xi măng bê tông & xây tô</div>
                    </div>
                    <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand-gold transition">
                        <div class="font-extrabold text-brand-navy text-xs sm:text-sm">SƠN DULUX & JOTUN</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Sơn ngoại thất & nội thất</div>
                    </div>
                    <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand-gold transition">
                        <div class="font-extrabold text-brand-navy text-xs sm:text-sm">GỖ AN CƯỜNG</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Vật liệu nội thất cao cấp</div>
                    </div>
                    <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand-gold transition">
                        <div class="font-extrabold text-brand-navy text-xs sm:text-sm">INAX & TOTO</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị vệ sinh chính hãng</div>
                    </div>
                    <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center hover:border-brand-gold transition">
                        <div class="font-extrabold text-brand-navy text-xs sm:text-sm">PANASONIC & XINGFA</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện & Nhôm kính</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 9: FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAPS NGOÀI TRANG CHỦ -->
        <section id="lien-he" class="py-8 sm:py-10 border-t border-slate-200">
            <div class="flatsome-container">
                <div class="section-title-container">
                    <span class="section-title-line"></span>
                    <h2 class="section-title-main text-base sm:text-xl">KẾT NỐI FANPAGE & BẢN ĐỒ CHỈ ĐƯỜNG</h2>
                    <span class="section-title-line"></span>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                    <!-- Đưa Fanpage ra ngoài trang chủ -->
                    <div class="lg:col-span-5 bg-white p-4 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-between">
                        <div>
                            <div class="flex items-center justify-between border-b border-slate-100 pb-3 mb-3">
                                <div class="flex items-center gap-2.5">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=1SW4EducCl-I9N9Ooj3N-fpKXo9pdQ5Er&sz=w200" 
                                        onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1SW4EducCl-I9N9Ooj3N-fpKXo9pdQ5Er';"
                                        alt="Logo Fanpage Xây Dựng Tín Châu" 
                                        class="w-10 h-10 object-contain rounded border border-slate-200 p-0.5"
                                    >
                                    <div>
                                        <h3 class="text-xs sm:text-sm font-extrabold text-brand-navy">FANPAGE: ANCI DESIGN & BUILDING - XÂY DỰNG TÍN CHÂU</h3>
                                        <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer" class="text-[11px] text-blue-600 hover:underline">
                                            facebook.com/Ancidesignandbuilding
                                        </a>
                                    </div>
                                </div>
                            </div>

                            <!-- Facebook Page Plugin Iframe Kết hợp Khung Trực Quan -->
                            <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-slate-50 flex justify-center py-2">
                                <iframe 
                                    title="Fanpage Facebook Xây Dựng Tín Châu"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FAncidesignandbuilding&tabs=timeline&width=340&height=260&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                    width="340" 
                                    height="260" 
                                    style="border:none;overflow:hidden;max-width:100%;" 
                                    scrolling="no" 
                                    frameborder="0" 
                                    allowfullscreen="true" 
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                </iframe>
                            </div>
                        </div>

                        <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2">
                            <span class="text-xs text-slate-600 font-medium">Theo dõi hình ảnh thi công cập nhật hàng ngày:</span>
                            <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold px-3.5 py-2 rounded transition">
                                <i class="fa-brands fa-facebook-f"></i>Mở Fanpage Facebook
                            </a>
                        </div>
                    </div>

                    <!-- Đưa Google Map ra ngoài trang chủ -->
                    <div class="lg:col-span-7 bg-white p-4 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-between">
                        <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-100 pb-3 mb-3">
                            <div>
                                <h3 class="text-xs sm:text-sm font-extrabold text-brand-navy">
                                    <i class="fa-solid fa-map-location-dot text-brand-gold mr-1.5"></i>BẢN ĐỒ TRỤ SỞ: 125 THANH LƯƠNG 16, HOÀ XUÂN, TP. ĐÀ NẴNG
                                </h3>
                                <p class="text-[11px] text-slate-500 mt-0.5">Hotline chỉ đường: 0935.090.716 - 0905.636.159</p>
                            </div>
                            <a href="https://www.google.com/maps/search/?api=1&query=125+Thanh+Lương+16,+Hoà+Xuân,+Đà+Nẵng" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-brand-navy hover:text-brand-gold bg-slate-100 px-3 py-1.5 rounded transition">
                                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Xem trên Google Maps
                            </a>
                        </div>

                        <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-slate-200">
                            <iframe 
                                title="Bản đồ Google Maps Xây Dựng Tín Châu 125 Thanh Lương 16 Hòa Xuân Đà Nẵng"
                                src="https://maps.google.com/maps?q=125%20Thanh%20L%C6%B0%C6%A1ng%2016,%20H%C3%B2a%20Xu%C3%A2n,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                                width="100%" 
                                height="100%" 
                                style="border:0;" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ================= FOOTER (CHÂN TRANG CHUẨN FLATSOME) ================= -->
    <footer class="bg-brand-dark text-slate-300 pt-10 pb-20 lg:pb-8 border-t-4 border-brand-gold">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="flex items-center gap-3">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1SW4EducCl-I9N9Ooj3N-fpKXo9pdQ5Er&sz=w300" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1SW4EducCl-I9N9Ooj3N-fpKXo9pdQ5Er';"
                            alt="Logo Xây Dựng Tín Châu" 
                            class="h-10 w-auto object-contain bg-white p-1 rounded"
                        >
                        <div>
                            <div class="text-sm sm:text-base font-extrabold text-white">CÔNG TY TNHH THIẾT KẾ VÀ XÂY DỰNG TÍN CHÂU</div>
                            <div class="text-xs text-brand-gold font-semibold">Website: xaydungtinchau.com</div>
                        </div>
                    </div>
                    <ul class="text-xs space-y-2 text-slate-300">
                        <li><i class="fa-solid fa-location-dot text-brand-gold w-5"></i><strong>Địa chỉ:</strong> 125 Thanh Lương 16, Hoà Xuân, TP. Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-brand-gold w-5"></i><strong>Điện thoại:</strong> <a href="tel:0935090716" class="text-white font-bold hover:text-brand-gold">0935.090.716</a> - <a href="tel:0905636159" class="text-white font-bold hover:text-brand-gold">0905.636.159</a></li>
                        <li><i class="fa-solid fa-certificate text-brand-gold w-5"></i><strong>Mã số thuế:</strong> 0402131771 | <strong>Chứng chỉ HĐXD:</strong> 00069740</li>
                        <li><i class="fa-brands fa-facebook text-brand-gold w-5"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">facebook.com/Ancidesignandbuilding</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-4 space-y-2.5">
                    <h4 class="text-xs sm:text-sm font-extrabold text-white uppercase tracking-wider border-b border-white/10 pb-2">LĨNH VỰC HOẠT ĐỘNG</h4>
                    <ul class="text-xs space-y-2">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">• Thi công phần thô Nhà phố, Biệt thự, Căn hộ</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">• Thi công hoàn thiện – Xây nhà trọn gói Đà Nẵng</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-gold transition">• Sản xuất & Thi công nội thất trọn gói</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-gold transition">• Báo giá thiết kế & thi công xây dựng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình -->
                <div class="lg:col-span-3 space-y-2.5">
                    <h4 class="text-xs sm:text-sm font-extrabold text-white uppercase tracking-wider border-b border-white/10 pb-2">CÔNG TRÌNH TIÊU BIỂU</h4>
                    <ul class="text-xs space-y-2">
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('khach-san-can-ho')" class="hover:text-brand-gold transition">• Khách sạn – Căn hộ – Phòng trọ</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('biet-thu')" class="hover:text-brand-gold transition">• Biệt thự hiện đại & sân vườn</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('nha-pho')" class="hover:text-brand-gold transition">• Nhà phố Đà Nẵng</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterConstruction('van-phong')" class="hover:text-brand-gold transition">• Văn phòng & Showroom</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-gold transition">• Dự án tại Hòa Xuân, Đà Nẵng</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-400">
                <div>Copyright © 2026 <strong>XÂY DỰNG TÍN CHÂU (xaydungtinchau.com)</strong>. All rights reserved.</div>
                <div>Thiết kế chuẩn giao diện Flatsome UX Builder</div>
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI ================= -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/Ancidesignandbuilding" target="_blank" rel="noopener noreferrer" aria-label="Chat Facebook Fanpage" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105">
            <i class="fa-brands fa-facebook-messenger text-base sm:text-lg"></i>
            <span class="text-xs font-bold hidden sm:inline">Fanpage</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0935090716" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0935.090.716" class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105">
            <span class="font-extrabold text-xs bg-white text-[#0068ff] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
            <span class="text-xs font-bold hidden sm:inline">0935.090.716</span>
        </a>

        <!-- Nút Hotline 1 -->
        <a href="tel:0935090716" aria-label="Gọi 0935.090.716" class="floating-pulse flex items-center gap-2 bg-brand-gold hover:bg-brand-goldLight text-white px-3.5 py-2 rounded-full shadow-lg transition">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            <span class="text-xs font-extrabold">0935.090.716</span>
        </a>

        <!-- Nút Hotline 2 -->
        <a href="tel:0905636159" aria-label="Gọi 0905.636.159" class="flex items-center gap-2 bg-brand-navy hover:bg-brand-accent text-white px-3.5 py-2 rounded-full shadow-lg border border-white/20 transition">
            <i class="fa-solid fa-phone text-sm"></i>
            <span class="text-xs font-extrabold">0905.636.159</span>
        </a>
    </div>

    <!-- ================= JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, LỌC DANH MỤC & FORM ================= -->
    <script>
        // 1. Điều khiển 2 Banner tự trượt chuyên nghiệp
        let currentBannerIndex = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dots = document.querySelectorAll('.banner-dot');
        let bannerInterval = null;

        function showSlide(index) {
            if (index >= slides.length) currentBannerIndex = 0;
            else if (index < 0) currentBannerIndex = slides.length - 1;
            else currentBannerIndex = index;

            slides.forEach((slide, i) => {
                if (i === currentBannerIndex) {
                    slide.classList.add('active');
                } else {
                    slide.classList.remove('active');
                }
            });

            dots.forEach((dot, i) => {
                if (i === currentBannerIndex) {
                    dot.className = 'banner-dot w-6 h-2 rounded-full bg-brand-gold transition-all';
                } else {
                    dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            });
        }

        function changeSlide(step) {
            showSlide(currentBannerIndex + step);
            resetBannerTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetBannerTimer();
        }

        function startBannerTimer() {
            bannerInterval = setInterval(() => {
                showSlide(currentBannerIndex + 1);
            }, 5000);
        }

        function resetBannerTimer() {
            clearInterval(bannerInterval);
            startBannerTimer();
        }

        // 2. Menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobile-menu-drawer');
            const icon = document.getElementById('mobile-menu-icon');
            drawer.classList.toggle('hidden');
            if (drawer.classList.contains('hidden')) {
                icon.className = 'fa-solid fa-bars text-lg';
            } else {
                icon.className = 'fa-solid fa-xmark text-lg';
            }
        }

        // 3. Lọc danh mục Công trình thực tế (9 ảnh)
        function filterConstruction(category) {
            const items = document.querySelectorAll('.cons-item');
            const tabs = document.querySelectorAll('.cons-tab');

            tabs.forEach(tab => {
                if (tab.getAttribute('data-cat') === category) {
                    tab.classList.add('active');
                } else {
                    tab.classList.remove('active');
                }
            });

            items.forEach(item => {
                const itemCat = item.getAttribute('data-category');
                if (category === 'all' || itemCat === category) {
                    item.classList.remove('hidden');
                } else {
                    item.classList.add('hidden');
                }
            });
        }

        // 4. Lọc danh mục Dự án tại Đà Nẵng (10 ảnh)
        function filterDanang(category) {
            const items = document.querySelectorAll('.dn-item');
            const tabs = document.querySelectorAll('.dn-tab');

            tabs.forEach(tab => {
                if (tab.getAttribute('data-dncat') === category) {
                    tab.classList.add('active');
                } else {
                    tab.classList.remove('active');
                }
            });

            items.forEach(item => {
                const itemCat = item.getAttribute('data-dncategory');
                if (category === 'all' || itemCat === category) {
                    item.classList.remove('hidden');
                } else {
                    item.classList.add('hidden');
                }
            });
        }

        // 5. Xử lý gửi Form Yêu cầu & Báo giá trang chủ
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('q_name').value.trim();
            const phone = document.getElementById('q_phone').value.trim();
            const type = document.getElementById('q_type').value;
            const budget = document.getElementById('q_budget').value;
            const msgBox = document.getElementById('quoteSuccessMsg');

            msgBox.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá <strong>${type}</strong> (Mức đầu tư: ${budget}) đã được ghi nhận. Bộ phận kỹ thuật Xây Dựng Tín Châu (0935.090.716 - 0905.636.159) sẽ liên hệ tư vấn ngay.`;
            msgBox.classList.remove('hidden');
            document.getElementById('quoteRequestForm').reset();
        }

        window.onload = function () {
            startBannerTimer();
        };
    </script>
</body>
</html>
