<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Корпоративный сайт АО НК «Қазақстан темір жолы» (КТЖ)">
    <title>Қазақстан темір жолы</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f5f5f5;
        }
        header {
            background: #003366;
            color: white;
            padding: 2em 1em;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            display: flex;
            justify-content: space-between;
            background: #005599;
            padding: 1em;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1em;
            font-weight: bold;
            padding: 0.5em 1em;
        }
        nav a:hover {
            background: #007acc;
            border-radius: 5px;
        }
        .hero {
            background-image: url('https://a.d-cd.net/b3106a1s-1920.jpg');
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 0 2px 5px rgba(0, 0, 0, 0.7);
        }
        .hero h2 {
            font-size: 2.5em;
        }
        .content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2em;
        }
        .section {
            margin-bottom: 2em;
            background: white;
            padding: 1.5em;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .section img {
            width: 100%;
            border-radius: 8px;
            margin-top: 1em;
        }
        footer {
            background: #003366;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        button {
            background: #005599;
            color: white;
            padding: 0.8em 1.5em;
            border: none;
            border-radius: 5px;
            font-size: 1em;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Қазақстан темір жолы</h1>
    </header>
    <nav>
        <a href="#about">О компании</a>
        <a href="#tickets">Купить билеты</a>
        <a href="#services">История</a>
        <a href="#contact">Контакты</a>
    </nav>
    <div class="hero">
        <h2>Новые маршруты и достижения</h2>
    </div>
    <div class="content">
        <section id="about" class="section">
            <h2>О компании</h2>
            <p>АО НК «Қазақстан темір жолы» – крупнейшая транспортная компания Казахстана...</p>
            <img src="https://www.gov.kz/uploads/2023/8/4/9eba58cda55389cd839ff5b22e072ca9_original.246958.jpg" alt="Инфраструктура КТЖ">
        </section>
        <section id="tickets" class="section">
            <h2>Купить билеты</h2>
            <p>Вы можете приобрести билеты онлайн через нашу платформу...</p>
            <form action="#" method="get" style="display: flex; flex-wrap: wrap; gap: 1em;">
                <div style="flex: 1;">
                    <label for="departure">Откуда:</label>
                    <input type="text" id="departure" name="departure" placeholder="Введите город отправления" style="width: 100%;">
                </div>
                <div style="flex: 1;">
                    <label for="arrival">Куда:</label>
                    <input type="text" id="arrival" name="arrival" placeholder="Введите город прибытия" style="width: 100%;">
                </div>
                <div style="flex: 1;">
                    <label for="date">Дата поездки:</label>
                    <input type="date" id="date" name="date" style="width: 100%;">
                </div>
                <div style="flex-basis: 100%; text-align: center;">
                    <button type="submit">Найти билеты</button>
                </div>
            </form>
        </section>
        <section id="services" class="section">
            <h2>История</h2>
            <p>С тех пор как в 1804 году британский изобретатель Ричард Тревитик показал в Мертир-Тидвил (Великобритания) первый поезд на паровой тяге, а в России в 1837 году был презентован первый участок Царскосельской железной дороги, железнодрожный транспорт на паровом ходу начал активно развиваться во всех промышленно развитых странах Старого и Нового Света. И вот на пороге XX века по землям, составляющим ныне территорию независимого Казахстана, проложили первые железнодорожные пути.  В настоящее время на стальных магистралях страны работает около 1 процента всего населения Казахстана, часть из них — представители железнодорожных династий, воспитавших несколько поколений железнодорожников. Сегодня АО «НК «ҚТЖ» — транспортно-логистический холдинг, оператор магистральной железнодорожной сети Республики Казахстан, национальный железнодорожный перевозчик грузов и пассажиров.</p>
        </section>
        <section id="contact" class="section">
            <h2>Контакты</h2>
            <p>Свяжитесь с нами для получения дополнительной информации:</p>
            <ul>
                <li>Email: support@railways.kz</li>
                <li>Телефон: +7 7172 600 111</li>
                <li>Адрес: г. Астана, ул. Абая, 10</li>
            </ul>
        </section>
    </div>
    <footer>
        <p>© 2024 Қазақстан темір жолы. Все права защищены.</p>
    </footer>
</body>
</html>
