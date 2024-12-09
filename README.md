<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Поиск билетов - КТЖ</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 1.5em;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 1.8em;
        }
        .main-container {
            max-width: 1200px;
            margin: 2em auto;
            background-color: white;
            padding: 2em;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #003366;
            margin-bottom: 1em;
        }
        .form-group {
            margin-bottom: 1em;
        }
        .form-group label {
            display: block;
            margin-bottom: 0.5em;
            font-weight: bold;
        }
        .form-group input {
            width: 100%;
            padding: 0.8em;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .search-btn {
            display: inline-block;
            padding: 0.8em 1.5em;
            background-color: #007acc;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1em;
            text-align: center;
            cursor: pointer;
        }
        .search-btn:hover {
            background-color: #005f99;
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 1em;
            margin-top: 2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Казахстан Темір Жолы - Поиск билетов</h1>
    </header>
    <div class="main-container">
        <h2>Найти поезд</h2>
        <div class="form-group">
            <label for="departureStation">Откуда:</label>
            <input type="text" id="departureStation" name="departureStation" placeholder="Введите станцию отправления">
        </div>
        <div class="form-group">
            <label for="arrivalStation">Куда:</label>
            <input type="text" id="arrivalStation" name="arrivalStation" placeholder="Введите станцию прибытия">
        </div>
        <div class="form-group">
            <label for="departureDate">Дата отправления:</label>
            <input type="date" id="departureDate" name="departureDate">
        </div>
        <div class="form-group">
            <label for="returnDate">Обратная дата:</label>
            <input type="date" id="returnDate" name="returnDate">
        </div>
        <div style="text-align: center; margin-top: 1em;">
            <a href="https://bktisats.github.io/katejo3/" class="search-btn">Искать билеты</a>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Казахстан Темір Жолы. Все права защищены.</p>
    </footer>
</body>
</html>
