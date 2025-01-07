# Colour-trading-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Color Trading Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">ColorTrade</div>
    <nav>
      <ul>
        <li><a href="#home">होम</a></li>
        <li><a href="#catalog">कलर कैटलॉग</a></li>
        <li><a href="#about">हमारे बारे में</a></li>
        <li><a href="#contact">संपर्क करें</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero-section">
    <h1>आपका रंग, आपकी पसंद!</h1>
    <p>यहां ट्रेड करें बेहतरीन रंगों के साथ।</p>
    <a href="#catalog" class="btn">अभी शुरू करें</a>
  </section>

  <section id="catalog" class="catalog-section">
    <h2>हमारे रंग</h2>
    <div class="color-grid">
      <div class="color-box" style="background-color: #FF5733;">#FF5733</div>
      <div class="color-box" style="background-color: #33FF57;">#33FF57</div>
      <div class="color-box" style="background-color: #3357FF;">#3357FF</div>
      <div class="color-box" style="background-color: #FFD700;">#FFD700</div>
      <div class="color-box" style="background-color: #800080;">#800080</div>
      <div class="color-box" style="background-color: #00FFFF;">#00FFFF</div>
    </div>
  </section>

  <section id="about" class="about-section">
    <h2>हमारे बारे में</h2>
    <p>ColorTrade एक प्लेटफॉर्म है जो आपको विभिन्न रंगों को खरीदने और बेचने की सुविधा प्रदान करता है।</p>
  </section>

  <section id="contact" class="contact-section">
    <h2>संपर्क करें</h2>
    <form action="#" method="post">
      <label for="name">नाम:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">ईमेल:</label>
      <input type="email" id="email" name="email" required>
      <label for="message">संदेश:</label>
      <textarea id="message" name="message" required></textarea>
      <button type="submit">भेजें</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 ColorTrade. सभी अधिकार सुरक्षित।</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #333;
  color: #fff;
  padding: 10px 20px;
}

header .logo {
  font-size: 24px;
  font-weight: bold;
}

header nav ul {
  list-style: none;
  display: flex;
  gap: 15px;
  margin: 0;
  padding: 0;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
}

.hero-section {
  text-align: center;
  padding: 50px;
  background: linear-gradient(to right, #ff7e5f, #feb47b);
  color: #fff;
}

.hero-section .btn {
  background-color: #333;
  color: #fff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

.catalog-section {
  padding: 50px;
  text-align: center;
}

.color-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.color-box {
  width: 100px;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #fff;
  font-weight: bold;
  border-radius: 8px;
}

.about-section, .contact-section {
  padding: 50px;
  text-align: center;
}

form {
  display: flex;
  flex-direction: column;
  gap: 10px;
  max-width: 400px;
  margin: 0 auto;
}

form input, form textarea, form button {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

footer {
  text-align: center;
  background-color: #333;
  color: #fff;
  padding: 10px;
}
