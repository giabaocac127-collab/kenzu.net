<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KenZu-444 - Trang Chia Sẻ Mod</title>
    <style>
        /* ================= CẤU HÌNH GIAO DIỆN CHUNG ================= */
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }

        /* Thanh điều hướng Navbar */
        .navbar {
            background-color: #1f1f1f;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 2px solid #ff4757;
        }

        .navbar .logo {
            font-size: 20px;
            font-weight: bold;
            color: #ff4757;
        }

        .navbar nav a {
            color: #ffffff;
            text-decoration: none;
            margin-left: 15px;
            font-size: 14px;
        }

        .navbar nav a:hover {
            color: #ff4757;
        }

        /* Khung chứa nội dung chính */
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 0 15px;
        }

        /* ================= BANNER YOUTUBE KENZU-444 ================= */
        .yt-banner {
            background: linear-gradient(135deg, #1f1f1f 0%, #2d0000 100%);
            border: 1px solid #ff0000;
            border-radius: 10px;
            padding: 12px 20px;
            margin-bottom: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 15px rgba(255, 0, 0, 0.2);
            flex-wrap: wrap;
            gap: 10px;
        }

        .yt-content {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .yt-icon {
            font-size: 20px;
        }

        .yt-content p {
            margin: 0;
            color: #ffffff;
            font-size: 14px;
            line-height: 1.4;
        }

        .yt-content strong {
            color: #ff4d4d;
        }

        .yt-btn {
            background-color: #ff0000;
            color: #ffffff !important;
            padding: 8px 16px;
            border-radius: 6px;
            text-decoration: none;
            font-weight: bold;
            font-size: 13px;
            display: flex;
            align-items: center;
            gap: 6px;
            transition: all 0.3s ease;
            white-space: nowrap;
        }

        .yt-btn:hover {
            background-color: #cc0000;
            transform: translateY(-2px);
            box-shadow: 0 4px 10px rgba(255, 0, 0, 0.4);
        }

        .yt-svg {
            width: 18px;
            height: 18px;
        }

        /* ================= THẺ BÀI VIẾT (CARD MOD) ================= */
        .card {
            background-color: #1e1e1e;
            border: 1px solid #333;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 15px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
        }

        .card-title {
            font-size: 16px;
            font-weight: bold;
            color: #00d2d3;
            margin-bottom: 10px;
        }

        .card-info p {
            margin: 5px 0;
            font-size: 13px;
            color: #ccc;
        }

        .btn-download {
            display: inline-block;
            margin-top: 10px;
            padding: 8px 16px;
            background-color: #ff4757;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
            font-size: 13px;
            font-weight: bold;
        }

        .btn-download:hover {
            background-color: #ff6b81;
        }

        /* Chân trang Footer */
        footer {
            text-align: center;
            padding: 15px;
            font-size: 12px;
            color: #777;
            background-color: #1f1f1f;
            margin-top: 30px;
        }

        /* Tối ưu giao diện trên Điện thoại */
        @media (max-width: 600px) {
            .yt-banner {
                flex-direction: column;
                text-align: center;
            }
            .yt-content {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>

    <header class="navbar">
        <div class="logo">KENZU-444</div>
        <nav>
            <a href="#">Trang chủ</a>
            <a href="#">Hướng dẫn</a>
            <a href="https://www.youtube.com/@kenzu-444" target="_blank">Youtube</a>
        </nav>
    </header>

    <main class="container">
        
        <div class="yt-banner">
            <div class="yt-content">
                <span class="yt-icon">📢</span>
                <p>Kênh YouTube chính thức của <strong>KenZu-444</strong> — Nhấn <strong>ĐĂNG KÝ KÊNH</strong> ủng hộ mình nhé!</p>
            </div>
            <a href="https://www.youtube.com/@kenzu-444?sub_confirmation=1" target="_blank" class="yt-btn">
                <svg viewBox="0 0 24 24" class="yt-svg"><path fill="currentColor" d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/></svg>
                ĐĂNG KÝ KHEN
            </a>
        </div>

        <div class="card">
            <div class="card-title">Mod Skin OB54 V1 - Set Đồ Bá Sàn</div>
            <div class="card-info">
                <p><strong>Nhân Vật:</strong> Alok thức tỉnh hoặc Ignis</p>
            </div>
            <a href="#" class="btn-download">Tải Về Ngay</a>
        </div>

        <div class="card">
            <div class="card-title">Mod Skin OB54 V2 - Combo Súng Phong Xà</div>
            <div class="card-info">
                <p><strong>Súng:</strong> M1887 / Phong Xà</p>
            </div>
            <a href="#" class="btn-download">Tải Về Ngay</a>
        </div>

    </main>

    <footer>
        <p>© 2026 KenZu-444. Tất cả quyền được bảo lưu.</p>
    </footer>

</body>
</html>
