<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }

        .about-me {
            flex: 1;
        }

        .about-me h1 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .about-me p {
            font-size: 16px;
            line-height: 1.5;
        }

        .about-me ul {
            list-style: none;
            padding: 0;
        }

        .about-me li::before {
            content: "💼";
            margin-right: 5px;
        }

        .skills {
            flex: 1;
            text-align: center;
        }

        .skills h2 {
            font-size: 20px;
            margin-bottom: 10px;
        }

        .skills ul {
            list-style: none;
            padding: 0;
        }

        .skills li::before {
            content: "🔧";
            margin-right: 5px;
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="about-me">
        <h1>Привет, я [Ваше имя]</h1>
        <p>🎨 Креативный UX/UI Дизайнер с опытом более года и React Разработчик с более чем 2 годами практики. Мое призвание - создавать визуальные и интерактивные решения, которые захватывают воображение и вдохновляют.</p>
        <ul>
            <li>💼 SQB Bank - Где я учился создавать дружелюбные и функциональные интерфейсы для банковских приложений.</li>
            <li>💼 BillX - Где мой дизайн помогал сделать платежи более удобными и безопасными.</li>
            <li>💼 Exxos Agency - Где я совершенствовал навыки дизайна и разработки на разнообразных проектах.</li>
            <li>💼 Vicco - Где я работал над проектами в сфере моды и стиля.</li>
            <li>💼 Uzbektelecom - Где я учился создавать современные интерфейсы для телекоммуникационных услуг.</li>
        </ul>
        <p>Моя страсть - это не только дизайн и код, но и превращение идей в реальность. С удовольствием воплощаю каждый проект с креативностью и вниманием к деталям.</p>
    </div>
    <div class="skills">
        <h2>🔧 Мои навыки:</h2>
        <ul>
            <li>🌐 HTML, CSS, JavaScript</li>
            <li>⚛️ React и Next.js</li>
            <li>🎨 UX/UI Дизайн</li>
            <li>🖥️ WordPress</li>
            <li>🎯 Оптимизация и адаптация для мобильных устройств</li>
        </ul>
    </div>
    <img src="https://ibb.co/8KCMLT8" alt="Ваше фото">
</body>
</html>
