<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Дисциплина</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #0b0b0b;
  color: white;
}

/* HEADER */
header {
  padding: 20px 50px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-weight: bold;
  font-size: 20px;
  letter-spacing: 2px;
}

nav a {
  color: #aaa;
  margin-left: 20px;
  text-decoration: none;
  transition: 0.3s;
}

nav a:hover {
  color: white;
}

/* HERO */
.hero {
  height: 90vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: linear-gradient(180deg, #0b0b0b, #111);
}

.hero h1 {
  font-size: 52px;
  margin-bottom: 20px;
}

.hero p {
  color: #aaa;
  margin-bottom: 30px;
}

/* BUTTON */
.btn {
  display: inline-block;
  padding: 15px 30px;
  background: white;
  color: black;
  border-radius: 12px;
  font-weight: bold;
  text-decoration: none;
  transition: 0.3s;
}

.btn:hover {
  background: #ddd;
  transform: scale(1.05);
}

/* SECTION */
.section {
  padding: 80px 50px;
  text-align: center;
}

.cards {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 40px;
  flex-wrap: wrap;
}

.card {
  background: #111;
  padding: 30px;
  width: 250px;
  border-radius: 15px;
  transition: 0.3s;
}

.card:hover {
  transform: translateY(-10px);
  background: #1a1a1a;
}

/* CTA BLOCK */
.cta {
  background: linear-gradient(180deg, #111, #000);
}

/* FOOTER */
footer {
  padding: 30px;
  text-align: center;
  color: #666;
}
</style>
</head>

<body>

<header>
  <div class="logo">DISCIPLINE</div>
  <nav>
    <a href="#">Главная</a>
    <a href="#">О нас</a>
    <a href="#">Контакты</a>
  </nav>
</header>

<section class="hero">
  <div>
    <h1>Контроль. Сила. Дисциплина.</h1>
    <p>Ты либо управляешь собой, либо тебя контролирует жизнь</p>

    <a href="https://www.instagram.com/hekliiye?igsh=bTJhc2c5NXpvM21n" target="_blank" class="btn">
      Начать
    </a>
  </div>
</section>

<section class="section">
  <h2>Почему дисциплина решает</h2>

  <div class="cards">
    <div class="card">
      <h3>Фокус</h3>
      <p>Ты перестаёшь тратить энергию на мусор</p>
    </div>

    <div class="card">
      <h3>Контроль</h3>
      <p>Ты управляешь действиями, а не эмоциями</p>
    </div>

    <div class="card">
      <h3>Рост</h3>
      <p>Каждый день ты становишься лучше</p>
    </div>
  </div>
</section>

<section class="section cta">
  <h2>Начни сейчас</h2>
  <p>Дисциплина — это не выбор, это стандарт</p>

  <a href="https://www.instagram.com/hekliiye?igsh=bTJhc2c5NXpvM21n" target="_blank" class="btn">
    Действовать
  </a>
</section>

<footer>
  © 2026 Discipline Project
</footer>

</body>
</html>
