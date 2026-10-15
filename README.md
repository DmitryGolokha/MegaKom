<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>МегаКом</title>
  <style>
    :root {
      --primary: #0f4c81;
      --accent: #ff6b00;
      --dark: #1a1a1a;
      --light: #f5f7fa;
      --text: #333;
    }
  </style>
</head>
<body>

  <!-- Параллакс-экран -->
  <header class="hero" id="heroSection">
    <!-- Фон (скролл-параллакс) -->
    <div class="hero-bg" id="bgLayer"></div>
    
    <!-- Слой (курсор-параллакс + градиент) -->
    <div class="hero-overlay" id="overlayLayer"></div>

    <!-- Контент -->
    <div class="hero-content">
      <h1>МегаКом</h1>
      <a href="#contacts" class="btn">Заказать консультацию</a>
    </div>
  </header>

  <!-- О нас -->
  <section class="about">
    <div class="container">
      <h2>О компании</h2>
      <div style="max-width: 800px; margin: 0 auto;">
        <p></p>
      </div>
    </div>
  </section>

  <!-- Услуги -->
  <section class="services">
    <div class="container">
      <h2>Наши услуги</h2>
      <div class="grid">
        <div class="card">
          <h3>Сопровождение 1С</h3>
          <p></p>
        </div>
        <div class="card">
          <h3>Интеграция 1С с сайтом</h3>
          <p></p>
        </div>
        <div class="card">
          <h3>Интеграция с CRM</h3>
          <p></p>
        </div>
      </div>
    </div>
  </section>

  <!-- Преимущества -->
  <section class="advantages">
    <div class="container">
      <h2>Почему выбирают нас</h2>
      <div class="grid">
        <div class="card">
          <h3>Опыт в 1С</h3>
          <p></p>
        </div>
        <div class="card">
          <h3>Прозрачность работ</h3>
          <p></p>
        </div>
        <div class="card">
          <h3>Поддержка</h3>
          <p></p>
        </div>
      </div>
    </div>
  </section>

  <!-- Контакты -->
  <section id="contacts" class="contacts">
    <div class="container">
      <h2>Свяжитесь с нами</h2>
      <div style="max-width: 500px; margin: 0 auto;">
        <p><strong>Телефон:</strong> +7 (4712) 77-31-40</p>
        <p><strong>Email:</strong> client@megkom.ru</p>
        <p><strong>Адрес:</strong> г. Курск, ул. Красной Армии, д. 23 </p>
        <br>
        <form style="display:flex; flex-direction:column; gap:12px;">
          <input type="text" placeholder="Ваше имя" style="padding:12px; border:1px solid #ddd; border-radius:6px;">
          <input type="email" placeholder="Email" style="padding:12px; border:1px solid #ddd; border-radius:6px;">
          <textarea rows="4" placeholder="Сообщение" style="padding:12px; border:1px solid #ddd; border-radius:6px;"></textarea>
          <button type="submit" class="btn" style="cursor:pointer;">Отправить заявку</button>
        </form>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2026 МегаКом. Все права защищены.</p>
    </div>
  </footer>
</body>
</html>
