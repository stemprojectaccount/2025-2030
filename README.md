<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vinh Danh Học Sinh Xuất Sắc - 20 Năm học</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;800;900&display=swap" rel="stylesheet">
    <style>
        /* ===== RESET & BASE STYLES ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Quicksand', sans-serif;
        }
        
        :root {
            --primary-color: #1a2a6c;
            --secondary-color: #2A4D9B;
            --accent-color: #3a6dc9;
            --gold-color: #FFD700;
            --gold-light: #FFEC8B;
            --orange-color: #FF8C42;
            --text-light: #F8F6F2;
            --text-dark: #0a192f;
            --shadow-light: rgba(255, 255, 255, 0.1);
            --shadow-dark: rgba(0, 0, 0, 0.3);
            --gradient-primary: linear-gradient(135deg, #1a2a6c, #2A4D9B, #3a6dc9);
            --gradient-gold: linear-gradient(45deg, #FFD700, #FFA500, #FFD700);
            --gradient-card: linear-gradient(135deg, rgba(58, 109, 201, 0.8), rgba(42, 77, 155, 0.9));
            --gradient-orange: linear-gradient(135deg, rgba(255, 140, 66, 0.9), rgba(232, 106, 51, 0.9));
            --transition-slow: all 0.8s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            --transition-medium: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            --transition-fast: all 0.3s ease;
        }
        
        body {
            background: 
                linear-gradient(rgba(255, 255, 255, 0.4), rgba(255, 255, 255, 0.4)),
                url('https://i.postimg.cc/yNGwbLmr/DSC08251.jpg') no-repeat center center fixed;
            background-size: cover;
            color: var(--text-light);
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }
        
        /* ===== BACKGROUND EFFECTS ===== */
        .dynamic-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -3;
            background: linear-gradient(-45deg, rgba(26, 42, 108, 0.2), rgba(42, 77, 155, 0.2), rgba(58, 109, 201, 0.2), rgba(77, 138, 230, 0.2), rgba(26, 42, 108, 0.2));
            background-size: 400% 400%;
            animation: gradientShift 20s ease infinite;
        }
        
        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -2;
            overflow: hidden;
        }
        
        .particle {
            position: absolute;
            background: radial-gradient(circle, rgba(255, 215, 0, 0.7) 0%, rgba(255, 215, 0, 0) 70%);
            border-radius: 50%;
            animation: particleFloat 25s infinite linear;
            filter: blur(1px);
        }
        
        @keyframes particleFloat {
            0% {
                transform: translateY(100vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100px) rotate(360deg);
                opacity: 0;
            }
        }
        
        .floating-elements {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }
        
        .floating-element {
            position: absolute;
            background: rgba(255, 215, 0, 0.1);
            border-radius: 50%;
            animation: float 25s infinite linear;
            box-shadow: 0 0 30px rgba(255, 215, 0, 0.3);
        }
        
        @keyframes float {
            0% {
                transform: translateY(0) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-1000px) rotate(360deg);
                opacity: 0;
            }
        }
        
        .spotlight {
            position: fixed;
            width: 300px;
            height: 300px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(255,215,0,0.2) 0%, rgba(255,215,0,0) 70%);
            pointer-events: none;
            z-index: -1;
            animation: spotlightMove 20s infinite linear;
            filter: blur(15px);
        }
        
        @keyframes spotlightMove {
            0% { transform: translate(10vw, 10vh); }
            25% { transform: translate(80vw, 30vh); }
            50% { transform: translate(40vw, 70vh); }
            75% { transform: translate(70vw, 50vh); }
            100% { transform: translate(10vw, 10vh); }
        }
        
        /* ===== CONTAINER & LAYOUT ===== */
        .container {
            width: 100%;
            min-height: 100vh;
            background: rgba(10, 25, 47, 0.3);
            backdrop-filter: blur(2px);
            position: relative;
            overflow: hidden;
        }
        
        .container::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="50" cy="50" r="1" fill="rgba(255,255,255,0.03)"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>'),
                linear-gradient(135deg, transparent 0%, rgba(255, 215, 0, 0.05) 100%);
            pointer-events: none;
            z-index: 0;
        }
        
        /* ===== HEADER STYLES ===== */
        header {
            background: 
                linear-gradient(135deg, rgba(42, 77, 155, 0.4), rgba(58, 109, 201, 0.3)),
                url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none"><path d="M0,0 L100,0 L100,100 Z" fill="rgba(255,215,0,0.1)"/></svg>');
            color: var(--text-light);
            text-align: center;
            padding: 120px 20px 100px;
            position: relative;
            overflow: hidden;
            border-bottom: 1px solid rgba(255, 215, 0, 0.3);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 20% 80%, rgba(255, 215, 0, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(255, 215, 0, 0.1) 0%, transparent 50%);
            z-index: 1;
        }
        
        .header-content {
            position: relative;
            z-index: 2;
        }
        
        .header-logo {
            position: absolute;
            top: 30px;
            left: 50px;
            height: 250px;
            width: auto;
            z-index: 10;
            filter: drop-shadow(0 0 15px rgba(255, 215, 0, 0.7));
            transition: var(--transition-medium);
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            padding: 10px;
            backdrop-filter: blur(10px);
        }
        
        .header-logo:hover {
            transform: scale(1.1) rotate(5deg);
            filter: drop-shadow(0 0 20px rgba(255, 215, 0, 0.9));
        }
        
        .header-icon {
            font-size: 4rem;
            color: var(--gold-color);
            margin-bottom: 30px;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.7);
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }
        
        /* CHỈNH SỬA: Làm chữ VINH DANH to hơn */
        .glowing-text {
            font-size: 7rem; /* Tăng từ 5rem lên 7rem */
            margin-bottom: 20px;
            text-shadow: 0 0 10px rgba(254 , 224 , 255 , 0 ), 0 0 20px rgba(255, 215, 0, 0.5), 0 0 30px rgba(255, 215, 0, 0 );
            position: relative;
            background: linear-gradient(45deg, #FFD700, #FFA500, #FFD700);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
            letter-spacing: 2px;
            animation: glow 3s ease-in-out infinite alternate;
            font-family: 'Playfair Display', serif;
        }
        
        @keyframes glow {
            0% {
                text-shadow: 0 0 10px rgba(255, 215, 0, 0), 0 0 20px rgba(255, 215, 0, 0.5), 0 0 30px rgba(255, 215, 0, 0 );
            }
            100% {
                text-shadow: 0 0 15px rgba(255, 215, 0, 0.8), 0 0 25px rgba(255, 215, 0, 0.6), 0 0 35px rgba(255, 215, 0, 0.4);
            }
        }
        
        .subtitle {
            font-size: 2rem;
            margin-bottom: 10px;
            position: relative;
            color: #e0e0ff;
            font-weight: 500;
        }
        
        .header-decoration {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 20px;
            background: linear-gradient(90deg, transparent, var(--gold-color), transparent);
            opacity: 0.5;
        }
        
        /* ===== MAIN CONTENT STYLES ===== */
        .main-content {
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 80vh;
            padding: 80px 20px;
            flex-direction: column;
            gap: 100px;
        }
        
        .section-title {
            font-size: 3.5rem;
            text-align: center;
            margin-bottom: 60px;
            background: linear-gradient(45deg, #FFD700, #FFA500, #FFD700);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.5);
            font-weight: 700;
            position: relative;
            display: inline-block;
            padding: 0 20px;
            font-family: 'Playfair Display', serif;
        }
        
        .section-title::after {
            content: "";
            position: absolute;
            bottom: -15px;
            left: 20%;
            width: 60%;
            height: 4px;
            background: linear-gradient(90deg, transparent, #FFD700, transparent);
            border-radius: 2px;
        }
        
        .section-title i {
            margin-right: 15px;
            font-size: 3rem;
            vertical-align: middle;
        }
        
        /* ===== YEAR CARDS STYLES ===== */
        .large-years {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            gap: 50px;
            width: 100%;
            max-width: 1600px;
        }
        
        .large-year {
            background: linear-gradient(135deg, rgba(58, 109, 201, 0.8), rgba(42, 77, 155, 0.9));
            border-radius: 25px;
            width: 320px;
            height: 380px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-size: 2.8rem;
            font-weight: bold;
            border: 2px solid rgba(255, 215, 0, 0.4);
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3), 0 0 25px rgba(255, 215, 0, 0.2);
            cursor: pointer;
            text-align: center;
            padding: 30px;
            position: relative;
            overflow: hidden;
        }
        
        .large-year::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
            transform: translateX(-100%) skewX(-15deg);
            transition: transform 0.8s;
        }
        
        .large-year:hover::before {
            transform: translateX(100%) skewX(-15deg);
        }
        
        .large-year:hover {
            transform: translateY(-15px) scale(1.05);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.4), 0 0 40px rgba(255, 215, 0, 0.4);
        }
        
        .large-year .year-icon {
            font-size: 7rem;
            margin-bottom: 30px;
            color: #FFD700;
            text-shadow: 0 0 20px rgba(255, 215, 0, 0.7);
            filter: drop-shadow(0 0 10px rgba(255, 215, 0, 0.5));
            transition: all 0.4s;
        }
        
        .large-year:hover .year-icon {
            transform: scale(1.2) rotate(10deg);
            filter: drop-shadow(0 0 15px rgba(255, 215, 0, 0.8));
        }
        
        .large-year .year-period {
            font-size: 3rem;
            margin-bottom: 15px;
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        
        .large-year .year-label {
            font-size: 1.6rem;
            opacity: 0.9;
            color: #e0e0ff;
            font-weight: 500;
        }
        
        /* ===== MASTERS/PHD BUTTON STYLES ===== */
        .masters-phd-section {
            width: 100%;
            text-align: center;
            margin-top: 30px;
        }
        
        .masters-phd-button {
            background: linear-gradient(135deg, rgba(255, 140, 66, 0.9), rgba(232, 106, 51, 0.9));
            border-radius: 35px;
            width: 650px;
            height: 240px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            font-weight: bold;
            border: 4px solid rgba(255, 215, 0, 0.7);
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            box-shadow: 0 25px 50px rgba(0, 0, 0, 0.5), 0 0 40px rgba(255, 140, 66, 0.6);
            cursor: pointer;
            text-align: center;
            padding: 40px;
            margin: 0 auto;
            position: relative;
            overflow: hidden;
        }
        
        .masters-phd-button::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.2), transparent);
            transform: translateX(-100%) skewX(-15deg);
            transition: transform 0.8s;
        }
        
        .masters-phd-button:hover::before {
            transform: translateX(100%) skewX(-15deg);
        }
        
        .masters-phd-button:hover {
            transform: translateY(-15px) scale(1.1);
            box-shadow: 0 35px 70px rgba(0, 0, 0, 0.6), 0 0 60px rgba(255, 140, 66, 0.8);
        }
        
        .masters-phd-button .button-icon {
            font-size: 5.5rem;
            margin-bottom: 20px;
            color: #FFD700;
            text-shadow: 0 0 30px rgba(255, 215, 0, 0.9);
            filter: drop-shadow(0 0 20px rgba(255, 215, 0, 0.7));
            transition: all 0.4s;
        }
        
        .masters-phd-button:hover .button-icon {
            transform: scale(1.3) rotate(15deg);
            filter: drop-shadow(0 0 25px rgba(255, 215, 0, 1));
        }
        
        .masters-phd-button .button-text {
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 800;
            letter-spacing: 1px;
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.5);
            line-height: 1.2;
        }
        
        /* ===== RESPONSIVE STYLES ===== */
        @media (max-width: 1200px) {
            .large-years {
                gap: 40px;
            }
            
            .large-year {
                width: 280px;
                height: 340px;
            }
            
            .masters-phd-button {
                width: 550px;
                height: 200px;
            }
        }
        
        @media (max-width: 992px) {
            .header-logo {
                position: relative;
                top: auto;
                left: auto;
                margin-bottom: 30px;
            }
            
            .glowing-text {
                font-size: 5rem;
            }
            
            .large-years {
                gap: 30px;
            }
            
            .large-year {
                width: 240px;
                height: 300px;
                font-size: 2.2rem;
            }
            
            .large-year .year-icon {
                font-size: 5rem;
            }
            
            .masters-phd-button {
                width: 450px;
                height: 180px;
                font-size: 2.5rem;
            }
            
            .masters-phd-button .button-icon {
                font-size: 4.5rem;
            }
        }
        
        @media (max-width: 768px) {
            .header-logo {
                height: 120px;
            }
            
            .glowing-text {
                font-size: 3.5rem;
            }
            
            .subtitle {
                font-size: 1.8rem;
            }
            
            .large-years {
                flex-direction: column;
                gap: 30px;
            }
            
            .large-year {
                width: 90%;
                max-width: 320px;
                height: 200px;
                flex-direction: row;
                justify-content: space-around;
            }
            
            .large-year .year-icon {
                margin-bottom: 0;
                font-size: 4rem;
            }
            
            .masters-phd-button {
                width: 90%;
                height: 150px;
                font-size: 2rem;
            }
            
            .masters-phd-button .button-icon {
                font-size: 3.5rem;
            }
            
            .section-title {
                font-size: 2.5rem;
            }
        }
        
        @media (max-width: 576px) {
            .header {
                padding: 80px 20px 60px;
            }
            
            .glowing-text {
                font-size: 2.8rem;
            }
            
            .subtitle {
                font-size: 1.5rem;
            }
            
            .large-year {
                height: 180px;
                font-size: 1.8rem;
            }
            
            .large-year .year-icon {
                font-size: 3.5rem;
            }
            
            .masters-phd-button {
                height: 130px;
                font-size: 1.8rem;
                padding: 20px;
            }
            
            .masters-phd-button .button-icon {
                font-size: 3rem;
            }
            
            .section-title {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <!-- Background Elements -->
    <div class="dynamic-bg"></div>
    <div class="particles" id="particles"></div>
    <div class="floating-elements" id="floatingElements"></div>
    <div class="spotlight"></div>
    
    <div class="container">
        <!-- Header Section -->
        <header>
            <img src="https://i.postimg.cc/zGwcmPH1/image.png" alt="Logo Trường" class="header-logo">
            <div class="header-content">
                <div class="header-icon">
                    <i class="fas fa-graduation-cap"></i>
                </div>
                <h1 class="glowing-text">BẢNG VINH DANH</h1>
                <p class="subtitle">HỌC SINH XUẤT SẮC CÁC NĂM HỌC</p>
                <p class="subtitle">TRƯỜNG THCS NGUYỄN KHUYẾN - XÃ EA KAR - TỈNH ĐẮK LẮK</p>
                <div class="header-decoration"></div>
            </div>
        </header>
        
        <!-- Main Content -->
        <div class="main-content">
            <!-- Year Selection Section -->
            <div class="year-selection" id="yearSelection">
                <h2 class="section-title">
                    <i class="fas fa-calendar-alt"></i>CHỌN NĂM HỌC
                </h2>
                
                <div class="large-years">
                    <!-- Năm học 2025-2026 -->
                    <div class="large-year" onclick="showStudents('2025-2026')">
                        <i class="fas fa-star year-icon"></i>
                        <div class="year-period">2025-2026</div>
                    </div>
                    
                    <!-- Năm học 2026-2027 -->
                    <div class="large-year" onclick="showStudents('2026-2027')">
                        <i class="fas fa-trophy year-icon"></i>
                        <div class="year-period">2026-2027</div>
                    </div>
                    
                    <!-- Năm học 2027-2028 -->
                    <div class="large-year" onclick="showStudents('2027-2028')">
                        <i class="fas fa-award year-icon"></i>
                        <div class="year-period">2027-2028</div>
                    </div>

                    <!-- Năm học 2028-2029 -->
                    <div class="large-year" onclick="showStudents('2028-2029')">
                        <i class="fas fa-medal year-icon"></i>
                        <div class="year-period">2028-2029</div>
                    </div>

                    <!-- Năm học 2029-2030 -->
                    <div class="large-year" onclick="showStudents('2029-2030')">
                        <i class="fas fa-crown year-icon"></i>
                        <div class="year-period">2029-2030</div>
                    </div>
                </div>
            </div>
            
            <!-- Students Section (Hidden by default) -->
            <div class="students-section" id="studentsSection">
                <h2 class="section-title">
                    <i class="fas fa-users"></i>DANH SÁCH HỌC SINH XUẤT SẮC
                </h2>
                
                <h3 class="year-title" id="selectedYearTitle">NĂM HỌC 2025-2026</h3>
                
                <div class="students-grid" id="studentsGrid">
                    <!-- Student cards will be generated here by JavaScript -->
                </div>
                
                <!-- Back Button -->
                <div class="back-section">
                    <div class="back-button" onclick="hideStudents()">
                        <i class="fas fa-arrow-left button-icon"></i>
                        <div class="button-text">QUAY LẠI TRANG CHÍNH</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
        
    <script>
        // ===== DỮ LIỆU HỌC SINH MẪU =====
        // Đã thêm thuộc tính gender để phân biệt ảnh nam/nữ
        const studentsData = {
            "2025-2026": [
                {
                    name: "NGUYỄN VĂN A",
                    class: "12A1",
                    achievement: "Huy chương Vàng Toán Quốc gia, Giải Nhất Tin học",
                    teacher: "Cô Nguyễn Thị B",
                    score: "9.5",
                    gender: "male"
                },
                {
                    name: "TRẦN THỊ B",
                    class: "12A2", 
                    achievement: "Huy chương Bạc Vật lý, Giải Nhì Hóa học",
                    teacher: "Thầy Phạm Văn C",
                    score: "9.2",
                    gender: "female"
                }
            ],
            "2026-2027": [
                {
                    name: "LÊ VĂN C",
                    class: "12A1",
                    achievement: "Huy chương Vàng Olympic Toán, Giải Nhất Vật lý",
                    teacher: "Cô Trần Thị D",
                    score: "9.6",
                    gender: "male"
                },
                {
                    name: "PHẠM THỊ D",
                    class: "12A3",
                    achievement: "Huy chương Bạc Hóa học, Giải Ba Sinh học",
                    teacher: "Thầy Nguyễn Văn E",
                    score: "9.1",
                    gender: "female"
                }
            ],
            "2027-2028": [
                {
                    name: "HOÀNG VĂN E",
                    class: "12A2",
                    achievement: "Giải Nhất Quốc gia môn Toán, Huy chương Vàng Tin học",
                    teacher: "Cô Lê Thị F",
                    score: "9.7",
                    gender: "male"
                },
                {
                    name: "VŨ THỊ F",
                    class: "12A1",
                    achievement: "Huy chương Bạc Vật lý, Giải Nhì Hóa học",
                    teacher: "Thầy Đặng Văn G",
                    score: "9.3",
                    gender: "female"
                }
            ],
            "2028-2029": [
                {
                    name: "ĐẶNG VĂN G",
                    class: "12A3",
                    achievement: "Huy chương Vàng Toán Quốc tế, Giải Nhất Vật lý",
                    teacher: "Cô Phan Thị H",
                    score: "9.8",
                    gender: "male"
                },
                {
                    name: "PHAN THỊ H",
                    class: "12A2",
                    achievement: "Huy chương Bạc Hóa học, Giải Ba Sinh học",
                    teacher: "Thầy Bùi Văn I",
                    score: "9.4",
                    gender: "female"
                }
            ],
            "2029-2030": [
                {
                    name: "BÙI VĂN I",
                    class: "12A1",
                    achievement: "Giải Nhất Quốc gia môn Toán, Huy chương Vàng Tin học",
                    teacher: "Cô Võ Thị K",
                    score: "9.6",
                    gender: "male"
                },
                {
                    name: "VÕ THỊ K",
                    class: "12A3",
                    achievement: "Huy chương Bạc Vật lý, Giải Nhì Hóa học",
                    teacher: "Thầy Ngô Văn L",
                    score: "9.2",
                    gender: "female"
                }
            ]
        };

        // ===== HÀM HIỂN THỊ DANH SÁCH HỌC SINH =====
        function showStudents(year) {
            // Ẩn phần chọn năm học
            document.getElementById('yearSelection').style.display = 'none';
            
            // Hiển thị phần danh sách học sinh
            const studentsSection = document.getElementById('studentsSection');
            studentsSection.style.display = 'block';
            
            // Cập nhật tiêu đề năm học
            document.getElementById('selectedYearTitle').textContent = `NĂM HỌC ${year}`;
            
            // Tạo các card học sinh
            const studentsGrid = document.getElementById('studentsGrid');
            studentsGrid.innerHTML = '';
            
            const students = studentsData[year] || [];
            
            students.forEach((student, index) => {
                const card = document.createElement('div');
                card.classList.add('student-card');
                
                // Xác định ảnh dựa trên giới tính
                const imageUrl = student.gender === 'male' 
                    ? 'https://i.postimg.cc/2Sns9JkF/Chat-GPT-Image-Oct-20-2025-08-20-11-PM.png'
                    : 'https://i.postimg.cc/fRYGqFzc/Chat-GPT-Image-Oct-20-2025-08-20-23-PM.png';
                
                // Lấy thành tích đầu tiên để hiển thị badge
                const firstAchievement = student.achievement.split(',')[0];
                
                card.innerHTML = `
                    <i class="fas fa-user-graduate student-icon"></i>
                    <img src="${imageUrl}" alt="${student.name}" class="student-image">
                    <h3>${student.name}</h3>
                    <div class="achievement-badge">${firstAchievement}</div>
                `;
                
                studentsGrid.appendChild(card);
            });
        }

        // ===== HÀM ẨN DANH SÁCH HỌC SINH =====
        function hideStudents() {
            // Ẩn phần danh sách học sinh
            document.getElementById('studentsSection').style.display = 'none';
            
            // Hiển thị phần chọn năm học
            document.getElementById('yearSelection').style.display = 'block';
        }

        // ===== TẠO HIỆU ỨNG NỀN =====
        function createParticles() {
            const particlesContainer = document.getElementById('particles');
            const particleCount = 50;
            
            for (let i = 0; i < particleCount; i++) {
                const particle = document.createElement('div');
                particle.classList.add('particle');
                
                const size = Math.random() * 100 + 20;
                particle.style.width = `${size}px`;
                particle.style.height = `${size}px`;
                particle.style.left = `${Math.random() * 100}vw`;
                particle.style.animationDuration = `${Math.random() * 30 + 20}s`;
                particle.style.animationDelay = `${Math.random() * 5}s`;
                
                particlesContainer.appendChild(particle);
            }
        }
        
        function createFloatingElements() {
            const container = document.getElementById('floatingElements');
            const elementCount = 15;
            
            for (let i = 0; i < elementCount; i++) {
                const element = document.createElement('div');
                element.classList.add('floating-element');
                
                const size = Math.random() * 150 + 50;
                element.style.width = `${size}px`;
                element.style.height = `${size}px`;
                element.style.left = `${Math.random() * 100}vw`;
                element.style.animationDuration = `${Math.random() * 40 + 30}s`;
                element.style.animationDelay = `${Math.random() * 10}s`;
                
                container.appendChild(element);
            }
        }

        // ===== KHỞI TẠO TRANG =====
        document.addEventListener('DOMContentLoaded', function() {
            createParticles();
            createFloatingElements();
            
            console.log("=== TRANG CHÍNH HỌC SINH XUẤT SẮC ===");
            console.log("Có 5 năm học để lựa chọn:");
            console.log("- 2025-2026");
            console.log("- 2026-2027");
            console.log("- 2027-2028"); 
            console.log("- 2028-2029");
            console.log("- 2029-2030");
            console.log("Mỗi năm học đều có nút QUAY LẠI TRANG CHÍNH");
        });
    </script>
</body>
</html>
