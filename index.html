<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Услуги манипулятора | Профессиональные грузоперевозки</title>
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');
        
        :root {
            --primary: #007AFF;
            --secondary: #5856D6;
            --accent: #FF9500;
            --success: #34C759;
            --glass-bg: rgba(255, 255, 255, 0.25);
            --glass-border: rgba(255, 255, 255, 0.3);
            --glass-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
            --text: #1c1c1e;
        }
        
        body.dark {
            --glass-bg: rgba(28, 28, 30, 0.65);
            --glass-border: rgba(255, 255, 255, 0.1);
            --text: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: var(--text);
            overflow-x: hidden;
            min-height: 100vh;
        }

        /* Animated Sky Background */
        .sky-background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(180deg, #1e3c72 0%, #2a5298 50%, #7e8ba3 100%);
            z-index: -3;
            overflow: hidden;
        }

        .cloud {
            position: absolute;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 100px;
            animation: float 20s infinite ease-in-out;
        }

        .cloud:nth-child(1) { width: 200px; height: 60px; top: 20%; left: -200px; animation-delay: 0s; }
        .cloud:nth-child(2) { width: 300px; height: 80px; top: 40%; left: -300px; animation-delay: 5s; }
        .cloud:nth-child(3) { width: 250px; height: 70px; top: 60%; left: -250px; animation-delay: 10s; }
        .cloud:nth-child(4) { width: 180px; height: 50px; top: 10%; left: -180px; animation-delay: 15s; }

        @keyframes float {
            0% { transform: translateX(0) translateY(0); }
            50% { transform: translateX(calc(100vw + 300px)) translateY(-20px); }
            100% { transform: translateX(0) translateY(0); }
        }

        /* Glassmorphism Cards */
        .glass {
            background: var(--glass-bg);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid var(--glass-border);
            box-shadow: var(--glass-shadow);
            border-radius: 24px;
        }

        /* Navigation */
        nav {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            z-index: 1000;
            padding: 20px 40px;
            transition: all 0.3s ease;
        }

        nav.scrolled {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(20px);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
        }

        .nav-container {
            max-width: 1400px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 800;
            background: linear-gradient(135deg, #fff 0%, #a8edea 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            display: flex;
            align-items: center;
            gap: 10px;
            animation: fadeInLeft 1s ease;
        }

        .nav-links {
            display: flex;
            gap: 30px;
            align-items: center;
            animation: fadeInRight 1s ease;
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            position: relative;
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 0;
            height: 2px;
            background: white;
            transition: width 0.3s ease;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        /* Hero Section */
        .hero {
            margin-top: 100px;
            padding: 80px 40px;
            text-align: center;
            color: white;
            animation: fadeInUp 1s ease;
        }

        .hero h1 {
            font-size: 4rem;
            font-weight: 800;
            margin-bottom: 20px;
            text-shadow: 0 4px 30px rgba(0,0,0,0.3);
            animation: slideInDown 1s ease;
        }

        .hero p {
            font-size: 1.5rem;
            margin-bottom: 40px;
            opacity: 0.95;
            animation: slideInUp 1s ease;
        }

        .cta-buttons {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
            animation: fadeIn 1.5s ease;
        }

        .btn {
            padding: 16px 40px;
            border-radius: 50px;
            border: none;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
            display: inline-block;
        }

        .btn-primary {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.5);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(102, 126, 234, 0.6);
        }

        .btn-secondary {
            background: rgba(255, 255, 255, 0.2);
            color: white;
            border: 2px solid white;
        }

        .btn-secondary:hover {
            background: white;
            color: #667eea;
        }

        /* Sections */
        section {
            padding: 80px 40px;
            max-width: 1400px;
            margin: 0 auto;
        }

        .section-title {
            font-size: 3rem;
            font-weight: 800;
            text-align: center;
            margin-bottom: 60px;
            color: white;
            text-shadow: 0 4px 30px rgba(0,0,0,0.3);
        }

        /* Features Grid */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 60px;
        }

        .feature-card {
            padding: 40px;
            text-align: center;
            transition: all 0.3s ease;
            animation: fadeInUp 0.8s ease;
            animation-fill-mode: both;
        }

        .feature-card:nth-child(1) { animation-delay: 0.1s; }
        .feature-card:nth-child(2) { animation-delay: 0.2s; }
        .feature-card:nth-child(3) { animation-delay: 0.3s; }
        .feature-card:nth-child(4) { animation-delay: 0.4s; }

        .feature-card:hover {
            transform: translateY(-10px) scale(1.02);
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
        }

        .feature-icon {
            font-size: 3.5rem;
            margin-bottom: 20px;
            background: linear-gradient(135deg, #fff 0%, #a8edea 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .feature-card h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: white;
        }

        .feature-card p {
            color: rgba(255,255,255,0.9);
            line-height: 1.6;
        }

        /* Gallery */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin-bottom: 60px;
        }

        .gallery-item {
            border-radius: 20px;
            overflow: hidden;
            position: relative;
            height: 300px;
            animation: fadeInUp 0.8s ease;
            animation-fill-mode: both;
        }

        .gallery-item:nth-child(1) { animation-delay: 0.1s; }
        .gallery-item:nth-child(2) { animation-delay: 0.2s; }
        .gallery-item:nth-child(3) { animation-delay: 0.3s; }

        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }

        .gallery-item:hover img {
            transform: scale(1.1);
        }

        .gallery-overlay {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
            padding: 30px;
            color: white;
        }

        /* Calculator Section */
        .calculator-section {
            margin: 60px auto;
        }

        .calculator-container {
            padding: 40px;
        }

        .truck-showcase {
            width: 100%;
            max-height: 400px;
            object-fit: contain;
            border-radius: 20px;
            margin-bottom: 30px;
            background: rgba(255,255,255,0.1);
        }

        #map {
            height: 450px;
            width: 100%;
            border-radius: 20px;
            margin: 20px 0;
            box-shadow: 0 10px 40px rgba(0,0,0,0.2);
        }

        .calc-result {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
            padding: 20px;
            background: rgba(255,255,255,0.1);
            border-radius: 15px;
        }

        .price-display {
            font-size: 2.5rem;
            font-weight: 800;
            background: linear-gradient(135deg, #fff 0%, #ffd700 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .reset-btn {
            padding: 12px 30px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .reset-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.5);
        }

        /* About Section */
        .about-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }

        .about-text {
            color: white;
        }

        .about-text h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .about-text p {
            font-size: 1.1rem;
            line-height: 1.8;
            margin-bottom: 20px;
            opacity: 0.95;
        }

        .about-image {
            border-radius: 30px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
        }

        .about-image img {
            width: 100%;
            height: auto;
            display: block;
        }

        /* Contact Section */
        .contact-section {
            text-align: center;
            margin-bottom: 100px;
        }

        .contact-card {
            padding: 60px 40px;
            display: inline-block;
        }

        .contact-phone {
            font-size: 3rem;
            font-weight: 800;
            color: white;
            text-decoration: none;
            display: block;
            margin: 20px 0;
            transition: transform 0.3s ease;
        }

        .contact-phone:hover {
            transform: scale(1.05);
        }

        .contact-name {
            font-size: 1.5rem;
            color: rgba(255,255,255,0.9);
        }

        /* Admin Panel */
        .admin-section {
            display: none;
            margin: 40px auto;
            max-width: 1200px;
            animation: fadeInUp 0.5s ease;
        }

        .admin-section.active {
            display: block;
        }

        .admin-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 30px;
            padding: 20px;
        }

        .admin-header h2 {
            color: white;
            font-size: 2rem;
        }

        .admin-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .admin-card {
            padding: 30px;
        }

        .admin-card h3 {
            color: white;
            margin-bottom: 20px;
            font-size: 1.3rem;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            color: white;
            margin-bottom: 8px;
            font-weight: 500;
        }

        .form-group input {
            width: 100%;
            padding: 12px;
            border-radius: 12px;
            border: 1px solid rgba(255,255,255,0.3);
            background: rgba(255,255,255,0.1);
            color: white;
            font-size: 1rem;
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
        }

        .stat-box {
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 15px;
            text-align: center;
        }

        .stat-value {
            font-size: 2rem;
            font-weight: 800;
            color: white;
        }

        .stat-label {
            color: rgba(255,255,255,0.8);
            font-size: 0.9rem;
            margin-top: 5px;
        }

        .admin-access {
            margin-top: 30px;
            text-align: center;
        }

        .admin-access input {
            padding: 12px 20px;
            border-radius: 50px;
            border: 2px solid rgba(255,255,255,0.3);
            background: rgba(255,255,255,0.1);
            color: white;
            margin-right: 10px;
            width: 200px;
        }

        .admin-access input::placeholder {
            color: rgba(255,255,255,0.6);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 40px;
            color: rgba(255,255,255,0.8);
            border-top: 1px solid rgba(255,255,255,0.1);
        }

        /* Theme Toggle */
        .theme-toggle {
            background: rgba(255,255,255,0.2);
            border: 2px solid white;
            color: white;
            padding: 10px 20px;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .theme-toggle:hover {
            background: white;
            color: #667eea;
        }

        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInLeft {
            from {
                opacity: 0;
                transform: translateX(-30px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes fadeInRight {
            from {
                opacity: 0;
                transform: translateX(30px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes slideInDown {
            from {
                opacity: 0;
                transform: translateY(-50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes slideInUp {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .hero p { font-size: 1.2rem; }
            .section-title { font-size: 2rem; }
            .about-content { grid-template-columns: 1fr; }
            .nav-links { display: none; }
            .features-grid, .gallery-grid { grid-template-columns: 1fr; }
            .stats-grid { grid-template-columns: 1fr; }
            .contact-phone { font-size: 2rem; }
        }

        /* Scroll animations */
        .scroll-reveal {
            opacity: 0;
            transform: translateY(50px);
            transition: all 0.8s ease;
        }

        .scroll-reveal.active {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body>
    <!-- Animated Sky Background -->
    <div class="sky-background">
        <div class="cloud"></div>
        <div class="cloud"></div>
        <div class="cloud"></div>
        <div class="cloud"></div>
    </div>

    <!-- Navigation -->
    <nav id="navbar">
        <div class="nav-container">
            <div class="logo">
                <i class="fas fa-truck-monster"></i>
                EXEKTOR
            </div>
            <div class="nav-links">
                <a href="#home">Главная</a>
                <a href="#about">О нас</a>
                <a href="#services">Услуги</a>
                <a href="#gallery">Техника</a>
                <a href="#calculator">Калькулятор</a>
                <a href="#contact">Контакты</a>
                <button class="theme-toggle" id="themeToggle">🌙</button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <h1>Профессиональные услуги манипулятора</h1>
        <p>Быстрая доставка грузов любой сложности по Белгороду и области</p>
        <div class="cta-buttons">
            <a href="#calculator" class="btn btn-primary">Рассчитать стоимость</a>
            <a href="tel:+79155680828" class="btn btn-secondary">
                <i class="fas fa-phone"></i> Позвонить
            </a>
        </div>
    </section>

    <!-- Features Section -->
    <section id="services">
        <h2 class="section-title scroll-reveal">Почему выбирают нас</h2>
        <div class="features-grid">
            <div class="feature-card glass scroll-reveal">
                <div class="feature-icon">
                    <i class="fas fa-bolt"></i>
                </div>
                <h3>Быстрая подача</h3>
                <p>Подача манипулятора от 30 минут. Работаем 24/7 без выходных и праздников</p>
            </div>
            <div class="feature-card glass scroll-reveal">
                <div class="feature-icon">
                    <i class="fas fa-ruble-sign"></i>
                </div>
                <h3>Честные цены</h3>
                <p>Прозрачное ценообразование. Оплата по факту выполненных работ</p>
            </div>
            <div class="feature-card glass scroll-reveal">
                <div class="feature-icon">
                    <i class="fas fa-shield-alt"></i>
                </div>
                <h3>Гарантия безопасности</h3>
                <p>Опытные операторы. Вся техника проходит регулярное ТО</p>
            </div>
            <div class="feature-card glass scroll-reveal">
                <div class="feature-icon">
                    <i class="fas fa-weight-hanging"></i>
                </div>
                <h3>Грузоподъемность до 15 тонн</h3>
                <p>Современные манипуляторы с вылетом стрелы до 20 метров</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="about-content">
            <div class="about-text scroll-reveal">
                <h2>Надежный партнер в сфере грузоперевозок</h2>
                <p>Мы предоставляем услуги автомобильных манипуляторов более 10 лет. За это время выполнили тысячи заказов различной сложности — от перевозки стройматериалов до монтажа строительных конструкций.</p>
                <p>Наш парк техники включает современные манипуляторы грузоподъемностью от 3 до 15 тонн с различной длиной стрелы. Это позволяет нам решать задачи любой сложности.</p>
                <p>Работаем с физическими и юридическими лицами. Предоставляем полный пакет документов. Возможна оплата наличными и безналичным расчетом.</p>
                <div class="cta-buttons" style="margin-top: 30px;">
                    <a href="tel:+79155680828" class="btn btn-primary">
                        <i class="fas fa-phone"></i> +7 (915) 568-08-28
                    </a>
                </div>
            </div>
            <div class="about-image glass scroll-reveal">
                <img src="https://m.media-amazon.com/images/I/71K8qKWXzjL._AC_SL1500_.jpg" alt="Манипулятор в работе">
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery">
        <h2 class="section-title scroll-reveal">Наша техника</h2>
        <div class="gallery-grid">
            <div class="gallery-item glass scroll-reveal">
                <img src="https://image.qwenlm.ai/public_source/fe6bddfd-7561-486f-b991-d4e71f0ee2d4/7d80f4997-d7c5-40ac-9143-f97b77675d623284.png" alt="Манипулятор 1">
                <div class="gallery-overlay">
                    <h3>Манипулятор 5 тонн</h3>
                    <p>Вылет стрелы: 8 метров</p>
                </div>
            </div>
            <div class="gallery-item glass scroll-reveal">
                <img src="https://image.qwenlm.ai/public_source/fe6bddfd-7561-486f-b991-d4e71f0ee2d4/2d80f4997-d7c5-40ac-9143-f97b77675d623124.png" alt="Манипулятор 2">
                <div class="gallery-overlay">
                    <h3>Манипулятор 7 тонн</h3>
                    <p>Вылет стрелы: 12 метров</p>
                </div>
            </div>
            <div class="gallery-item glass scroll-reveal">
                <img src="https://image.qwenlm.ai/public_source/fe6bddfd-7561-486f-b991-d4e71f0ee2d4/6d80f4997-d7c5-40ac-9143-f97b77675d626080.png" alt="Манипулятор 3">
                <div class="gallery-overlay">
                    <h3>Манипулятор 10 тонн</h3>
                    <p>Вылет стрелы: 15 метров</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Calculator Section -->
    <section class="calculator-section" id="calculator">
        <h2 class="section-title scroll-reveal">Калькулятор стоимости</h2>
        <div class="calculator-container glass scroll-reveal">
            <img src="https://image.qwenlm.ai/public_source/fe6bddfd-7561-486f-b991-d4e71f0ee2d4/1d80f4997-d7c5-40ac-9143-f97b77675d622298.png" alt="Манипулятор" class="truck-showcase">
            
            <div class="calc-result">
                <div>
                    <div style="color: white; font-size: 1.2rem; margin-bottom: 10px;">
                        <i class="fas fa-route"></i> Расстояние: <span id="dist">0</span> км
                    </div>
                    <div style="color: rgba(255,255,255,0.8); font-size: 0.9rem;">
                        Кликните дважды по карте: откуда → куда
                    </div>
                </div>
                <div class="price-display">
                    💰 <span id="price">0</span> ₽
                </div>
            </div>
            
            <div id="map"></div>
            
            <button class="reset-btn" onclick="resetMap()" style="display: block; margin: 20px auto;">
                <i class="fas fa-redo"></i> Сбросить маршрут
            </button>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact-section" id="contact">
        <div class="contact-card glass scroll-reveal">
            <h2 style="color: white; font-size: 2.5rem; margin-bottom: 20px;">Свяжитесь с нами</h2>
            <p style="color: rgba(255,255,255,0.9); font-size: 1.2rem; margin-bottom: 20px;">
                Готовы ответить на ваши вопросы и принять заказ
            </p>
            <a href="tel:+79155680828" class="contact-phone">
                <i class="fas fa-phone"></i> +7 (915) 568-08-28
            </a>
            <div class="contact-name">Александр</div>
            <div style="margin-top: 30px; display: flex; gap: 20px; justify-content: center; flex-wrap: wrap;">
                <a href="https://wa.me/79155680828" class="btn btn-primary" style="text-decoration: none;">
                    <i class="fab fa-whatsapp"></i> WhatsApp
                </a>
                <a href="https://t.me/+79155680828" class="btn btn-secondary" style="text-decoration: none;">
                    <i class="fab fa-telegram"></i> Telegram
                </a>
            </div>
        </div>
    </section>

    <!-- Admin Access -->
    <div class="admin-access">
        <input type="password" id="adminPassword" placeholder="🔐 Доступ">
        <button class="btn btn-secondary" onclick="checkAdmin()">Войти</button>
    </div>

    <!-- Admin Panel -->
    <section class="admin-section" id="adminPanel">
        <div class="admin-header glass">
            <h2><i class="fas fa-cog"></i> Панель разработчика</h2>
            <button class="btn btn-secondary" onclick="logoutAdmin()">Выйти</button>
        </div>
        
        <div class="admin-grid">
            <div class="admin-card glass">
                <h3><i class="fas fa-ruble-sign"></i> Настройки тарифа</h3>
                <div class="form-group">
                    <label>Цена за километр (₽):</label>
                    <input type="number" id="adminRate" value="45" min="1">
                </div>
                <button class="btn btn-primary" onclick="saveRate()" style="width: 100%;">
                    <i class="fas fa-save"></i> Сохранить тариф
                </button>
            </div>

            <div class="admin-card glass">
                <h3><i class="fas fa-chart-bar"></i> Статистика</h3>
                <div class="stats-grid">
                    <div class="stat-box">
                        <div class="stat-value" id="totalRides">0</div>
                        <div class="stat-label">Поездок</div>
                    </div>
                    <div class="stat-box">
                        <div class="stat-value" id="totalKm">0</div>
                        <div class="stat-label">Всего км</div>
                    </div>
                    <div class="stat-box">
                        <div class="stat-value" id="totalRevenue">0</div>
                        <div class="stat-label">Выручка ₽</div>
                    </div>
                </div>
                <button class="btn btn-secondary" onclick="resetStats()" style="width: 100%; margin-top: 20px;">
                    <i class="fas fa-trash"></i> Сбросить статистику
                </button>
            </div>

            <div class="admin-card glass">
                <h3><i class="fas fa-info-circle"></i> Информация</h3>
                <p style="color: rgba(255,255,255,0.9); margin-bottom: 10px;">
                    <strong>Текущий тариф:</strong> <span id="currentRate">45</span> ₽/км
                </p>
                <p style="color: rgba(255,255,255,0.9); margin-bottom: 10px;">
                    <strong>Версия сайта:</strong> 2.0.0
                </p>
                <p style="color: rgba(255,255,255,0.9);">
                    <strong>Последнее обновление:</strong> 2026
                </p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Услуги манипулятора EXEKTOR. Все права защищены.</p>
        <p style="margin-top: 10px; font-size: 0.9rem;">
            <i class="fas fa-map-marker-alt"></i> г. Белгород и Белгородская область
        </p>
    </footer>

    <script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
    <script>
        // Theme Toggle
        const body = document.body;
        const themeToggle = document.getElementById('themeToggle');
        let mapLayer = null;
        let isAdmin = false;
        
        if(localStorage.getItem('theme') === 'dark') body.classList.add('dark');
        
        themeToggle.onclick = () => {
            body.classList.toggle('dark');
            localStorage.setItem('theme', body.classList.contains('dark') ? 'dark' : 'light');
            themeToggle.textContent = body.classList.contains('dark') ? '☀️' : '🌙';
        };

        // Navbar scroll effect
        window.addEventListener('scroll', () => {
            const navbar = document.getElementById('navbar');
            if(window.scrollY > 50) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });

        // Scroll reveal animation
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -100px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if(entry.isIntersecting) {
                    entry.target.classList.add('active');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.scroll-reveal').forEach(el => {
            observer.observe(el);
        });

        // Map initialization
        const map = L.map('map').setView([50.5951, 36.5878], 12);
        
        function setMapLayer() {
            if(mapLayer) map.removeLayer(mapLayer);
            mapLayer = L.tileLayer('https://server.arcgisonline.com/ArcGIS/rest/services/World_Street_Map/MapServer/tile/{z}/{y}/{x}', {
                attribution: '© ESRI',
                maxZoom: 19
            }).addTo(map);
        }

        setMapLayer();

        let markers = [];
        let routeLine = null;
        const distEl = document.getElementById('dist');
        const priceEl = document.getElementById('price');
        
        let stats = JSON.parse(localStorage.getItem('stats')) || { rides: 0, totalKm: 0, totalRevenue: 0 };

        function updateStats(km, price) {
            stats.rides++;
            stats.totalKm += parseFloat(km);
            stats.totalRevenue += price;
            localStorage.setItem('stats', JSON.stringify(stats));
            updateAdminStats();
        }

        function updateAdminStats() {
            document.getElementById('totalRides').textContent = stats.rides;
            document.getElementById('totalKm').textContent = stats.totalKm.toFixed(2);
            document.getElementById('totalRevenue').textContent = stats.totalRevenue;
        }

        function resetStats() {
            if(confirm('Сброс
