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
