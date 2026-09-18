<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bloom store — Косметика и бытовая химия в Сокулуке</title>
    <link href="https://googleapis.com" rel="stylesheet">
    <style>
        :root { --bg: #f4f8fa; --blue: #e3edf2; --pink: #f7e1e3; --dark: #2c3e50; --muted: #627280; }
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Montserrat', sans-serif; scroll-behavior: smooth; }
        body { background: var(--bg); color: var(--dark); line-height: 1.6; }
        h1, h2, h3, .logo { font-family: 'Playfair Display', serif; }
        .container { max-width: 1100px; margin: 0 auto; padding: 0 20px; }
        
        header { background: rgba(244, 248, 250, 0.9); backdrop-filter: blur(5px); position: fixed; top: 0; width: 100%; z-index: 10; border-bottom: 1px solid rgba(0,0,0,0.05); }
        nav { display: flex; justify-content: space-between; align-items: center; height: 70px; }
        .logo { font-size: 24px; text-decoration: none; color: var(--dark); font-weight: 600; }
        .nav-links a { text-decoration: none; color: var(--dark); font-size: 13px; text-transform: uppercase; margin-left: 20px; }

        .hero { min-height: 85vh; display: flex; align-items: center; background: linear-gradient(135deg, var(--blue), var(--pink)); padding-top: 70px; }
        .hero h1 { font-size: 42px; margin-bottom: 15px; font-weight: 400; }
        .hero p { color: var(--muted); margin-bottom: 30px; }
        .btn { display: inline-block; padding: 12px 30px; text-decoration: none; border-radius: 25px; text-transform: uppercase; font-size: 13px; transition: 0.3s; }
        .btn-p { background: var(--dark); color: #fff; margin-right: 10px; }
        .btn-p:hover { background: transparent; color: var(--dark); border: 1px solid var(--dark); }
        .btn-s { border: 1px solid var(--dark); color: var(--dark); }

        section { padding: 70px 0; }
        .title { font-size: 32px; text-align: center; margin-bottom: 40px; font-weight: 400; }
        
        .about { background: #fff; }
        .about-grid, .contacts-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 40px; align-items: center; }
        .placeholder { background: linear-gradient(45deg, #eef5f8, #fbf5f5); border-radius: 15px; height: 250px; display: flex; align-items: center; justify-content: center; color: var(--muted); font-style: italic; }

        .cat-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
        .cat-card { background: #fff; padding: 30px; border-radius: 15px; text-align: center; border: 1px solid rgba(0,0,0,0.02); }
        .cat-card h3 { margin: 15px 0 10px; }

        .service-box { background: var(--blue); border-radius: 20px; padding: 40px; text-align: center; }
        .badge { display: inline-block; background: #fff; padding: 5px 15px; border-radius: 20px; font-size: 11px; text-transform: uppercase; margin-bottom: 15px; font-weight: 600; }

        .info-box { background: #fff; padding: 30px; border-radius: 15px; }
        .item { margin-bottom: 20px; }
        .item label { font-size: 11px; text-transform: uppercase; color: var(--muted); display: block; }
        .item p, .item a { font-size: 15px; font-weight: 600; color: var(--dark); text-decoration: none; }
        
        footer { background: var(--dark); color: #fff; padding: 30px 0; text-align: center; font-size: 14px; }
        footer a { color: #fff; text-decoration: underline; margin-top: 10px; display: inline-block; opacity: 0.8; }

        @media (max-width: 768px) {
            .about-grid, .contacts-grid { grid-template-columns: 1fr; }
            .hero h1 { font-size: 32px; }
            .nav-links { display: none; }
        }
    </style>
</head>
<body>

    <header>
        <div class="container"><nav>
            <a href="#" class="logo">Bloom store</a>
            <div class="nav-links">
                <a href="#about">О нас</a>
                <a href="#cat">Каталог</a>
                <a href="#service">Диагностика</a>
                <a href="#contacts">Контакты</a>
            </div>
        </nav></div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Оазис чистоты и заботы о коже</h1>
            <p>Оригинальная корейская косметика, средства гигиены и бытовая химия премиум-уровня в Сокулуке.</p>
            <a href="https://instagram.com" target="_blank" class="btn btn-p">Instagram</a>
            <a href="#contacts" class="btn btn-s">Где мы?</a>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container"><div class="about-grid">
            <div>
                <h2 style="font-weight:400; margin-bottom:15px;">Бережный уход за вами</h2>
                <p style="color:var(--muted);">Мы подбираем безопасную уходовую косметику и бытовую химию («мыломойку»), которая приносит пользу вашей коже и создаёт уют в доме. В приоритете — качество и оригинальность брендов.</p>
            </div>
            <div class="placeholder">✨ Эстетика & Чистота</div>
        </div></div>
    </section>

    <section id="cat">
        <div class="container">
            <h2 class="title">Категории товаров</h2>
            <div class="cat-grid">
                <div class="cat-card"><h3>🧴 Уходовая косметика</h3><p style="color:var(--muted); font-size:14px;">Корейские тонеры, сыворотки и кремы для идеального сияния кожи.</p></div>
                <div class="cat-card" style="background:var(--pink);"><h3>🌸 Бренд Kelissy</h3><p style="color:var(--muted); font-size:14px;">Премиальные линейки средств для глубокого восстановления кожи.</p></div>
                <div class="cat-card"><h3>🧼 Средства гигиены</h3><p style="color:var(--muted); font-size:14px;">Качественная бытовая химия и мягкие средства личной гигиены.</p></div>
            </div>
        </div>
    </section>

    <section id="service" style="background:#fff;">
        <div class="container"><div class="service-box">
            <span class="badge">Бесплатно</span>
            <h2 style="font-weight:400; margin-bottom:15px;">Аппаратная диагностика кожи</h2>
            <p style="margin-bottom:20px; color:var(--muted);">Пройдите тестирование на передовых аппаратах прямо в магазине. Эксперты бесплатно подберут индивидуальный уход под ваш тип кожи.</p>
            <a href="https://instagram.com" target="_blank" class="btn btn-p">Записаться на визит</a>
        </div></div>
    </section>

    <section id="contacts">
        <div class="container">
            <h2 class="title">Контакты</h2>
            <div class="contacts-grid">
                <div class="info-box">
                    <div class="item"><label>Адрес</label><p>Кыргызстан, с. Сокулук, ул. Фрунзе, 117<br><span style="font-weight:normal; font-size:13px; color:var(--muted);">(вход с ул. Кайназарова)</span></p></div>
                    <div class="item"><label>Социальные сети</label><a href="https://instagram.com" target="_blank">@bloom._storre</a></div>
                    <div class="item"><label>Режим работы</label><p>Ежедневно, без выходных</p></div>
                </div>
                <div style="border-radius:15px; overflow:hidden; height:250px;">
                    <iframe src="https://google.com" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2026 Bloom store. Все права защищены.</p>
            <a href="https://instagram.com" target="_blank">Наш Instagram</a>
        </div>
    </footer>

</body>
</html>
