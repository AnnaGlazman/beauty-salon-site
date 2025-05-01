<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Belle Vie — Салон красоты</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fdf6f0;
      color: #3d2b1f;
    }
    header {
      background-color: #f0e1d2;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      letter-spacing: 2px;
    }
    nav {
      background-color: #e8d6c3;
      padding: 10px 0;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #3d2b1f;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .service {
      background-color: #fff8f1;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    .btn {
      display: inline-block;
      margin-top: 30px;
      background-color: #c19e85;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 30px;
      font-size: 1em;
      text-decoration: none;
      transition: background-color 0.3s;
    }
    .btn:hover {
      background-color: #b0896b;
    }
    footer {
      background-color: #e8d6c3;
      padding: 20px;
      text-align: center;
      font-size: 0.9em;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2em;
      }
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Belle Vie</h1>
    <p>Твоя красивая жизнь начинается здесь</p>
  </header>

  <nav>
    <a href="#about">О нас</a>
    <a href="#services">Услуги</a>
    <a href="#contacts">Контакты</a>
  </nav>

  <section id="about">
    <h2>О нас</h2>
    <p>
      Belle Vie — уютный салон красоты в самом сердце города. Мы предлагаем первоклассные процедуры по уходу за собой в расслабляющей атмосфере.
    </p>
    <a class="btn" href="#contacts">Записаться на приём</a>
  </section>

  <section id="services">
    <h2>Наши услуги</h2>
    <div class="services">
      <div class="service">
        <h3>Маникюр и педикюр</h3>
        <p>Современные техники и большой выбор покрытий.</p>
      </div>
      <div class="service">
        <h3>Парикмахерские услуги</h3>
        <p>Стрижки, укладки, окрашивания и уход за волосами.</p>
      </div>
      <div class="service">
        <h3>Косметология</h3>
        <p>Профессиональные уходовые процедуры для лица.</p>
      </div>
    </div>
  </section>

  <section id="contacts">
    <h2>Контакты</h2>
    <p>
      Адрес: г. Москва, ул. Красоты, 10<br />
      Телефон: +7 (999) 123-45-67<br />
      Instagram: @bellevie_salon
    </p>
  </section>

  <footer>
    &copy; 2025 Belle Vie — Все права защищены
  </footer>

</body>
</html>