
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Студенческие работы на заказ</title>
    <style>
        /* ... (предыдущие стили) ... */
    </style>
</head>
<body>

    <header>
        <h1>Студенческие работы на заказ</h1>
        <p>Надежные и качественные работы от опытных авторов</p>
    </header>

    <section>
        <h2>Добро пожаловать!</h2>
        <p>
            Мы предоставляем услуги по написанию студенческих работ на заказ. Наша команда опытных авторов готова помочь вам
            с выполнением различных задач. Независимо от уровня сложности, у нас вы найдете профессиональную помощь.
        </p>

        <h2>Наши услуги</h2>
        <p>
            Мы выполняем заказы по написанию эссе, курсовых работ, дипломов и других видов студенческих заданий. Наши авторы
            гарантируют уникальность и качество каждой работы.
        </p>

        <h2>Как это работает?</h2>
        <p>
            1. Оставьте заявку на нашем сайте.<br>
            2. Выберите автора, который подходит вам по критериям.<br>
            3. Получите готовую работу в указанный срок.
        </p>
    </section>

    <section>
        <h2>Заказать студенческую работу</h2>
        <p>Заполните форму ниже, чтобы разместить заказ:</p>
        <form action="/submit_order" method="post">
            <label for="name">Ваше имя:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Ваш Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="assignment">Тип работы:</label>
            <select id="assignment" name="assignment" required>
                <option value="essay">Эссе</option>
                <option value="coursework">Курсовая работа</option>
                <option value="thesis">Дипломная работа</option>
                <!-- Добавьте другие варианты по необходимости -->
            </select>

            <label for="instructions">Инструкции:</label>
            <textarea id="instructions" name="instructions" rows="4" required></textarea>

            <button type="submit">Отправить заказ</button>
        </form>
    </section>

    <section>
        <h2>Контакты</h2>
        <p>Если у вас есть вопросы, свяжитесь с нами:</p>
        <address>
            Email: info@example.com<br>
            Телефон: +7 (XXX) XXX-XX-XX
        </address>
    </section>

    <footer>
        <p>&copy; 2023 Студенческие работы на заказ</p>
    </footer>

</body>
</html>
