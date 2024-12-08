<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Расписание билетов - КТЖ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 1em;
        }
        .schedule-container {
            max-width: 1200px;
            margin: 2em auto;
            background: white;
            padding: 1.5em;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #003366;
        }
        .schedule-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1em;
        }
            .schedule-table th, .schedule-table td {
                border: 1px solid #ddd;
                text-align: center;
                padding: 0.8em;
            }
            .schedule-table th {
                background-color: #005599;
                color: white;
            }
            .schedule-table tr:nth-child(even) {
                background-color: #f9f9f9;
            }
            .schedule-table tr:hover {
                background-color: #f1f1f1;
            }
        .btn-book {
            background-color: #007acc;
            color: white;
            padding: 0.5em 1em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
            .btn-book:hover {
                background-color: #005f99;
            }
    </style>
</head>
<body>
    <header>
        <h1>Расписание билетов</h1>
    </header>
    <div class="schedule-container">
        <h2>Результаты поиска</h2>
        <table class="schedule-table">
            <thead>
                <tr>
                    <th>№ Поезда</th>
                    <th>Тип</th>
                    <th>Отправление</th>
                    <th>Прибытие</th>
                    <th>Продолжительность</th>
                    <th>Свободные места</th>
                    <th>Цена</th>
                    <th></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>001А</td>
                    <td>Пассажирский</td>
                    <td>03.12.2024 18:00</td>
                    <td>04.12.2024 08:30</td>
                    <td>14ч 30м</td>
                    <td>12</td>
                    <td>10 000 ₸</td>
                    <td><button class="btn-book">Забронировать</button></td>
                </tr>
                <tr>
                    <td>025Б</td>
                    <td>Скорый</td>
                    <td>03.12.2024 21:00</td>
                    <td>04.12.2024 06:00</td>
                    <td>9ч 00м</td>
                    <td>5</td>
                    <td>15 000 ₸</td>
                    <td><button class="btn-book">Забронировать</button></td>
                </tr>
                <tr>
                    <td>102К</td>
                    <td>Люкс</td>
                    <td>03.12.2024 22:00</td>
                    <td>04.12.2024 05:00</td>
                    <td>7ч 00м</td>
                    <td>8</td>
                    <td>20 000 ₸</td>
                    <td><button class="btn-book">Забронировать</button></td>
                </tr>
            </tbody>
        </table>
    </div>

</body>
</html>
