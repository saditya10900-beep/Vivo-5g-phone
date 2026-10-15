
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aditya Singh | Vivo 5G</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #07152b;
      color: white;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 22px 8%;
      background: #091b35;
    }

    .logo {
      color: #36c5ff;
      font-size: 32px;
      font-weight: bold;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 22px;
    }

    .hero {
      min-height: 85vh;
      padding: 65px 8%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 35px;
      flex-wrap: wrap;
      background: linear-gradient(120deg, #07152b, #103d68);
    }

    .content {
      flex: 1 1 300px;
    }

    .content h1 {
      font-size: clamp(38px, 6vw, 65px);
      margin-bottom: 20px;
    }

    .content h1 span {
      color: #36c5ff;
    }

    .content p {
      color: #c4d6e8;
      font-size: 18px;
      line-height: 1.7;
      margin-bottom: 28px;
    }

    .btn {
      display: inline-block;
      padding: 14px 27px;
      background: #168cff;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }

    .phone {
      flex: 1 1 280px;
      text-align: center;
    }

    .phone img {
      width: 100%;
      max-width: 400px;
      border-radius: 20px;
      filter: drop-shadow(0 0 30px #168cff55);
    }

    .features {
      padding: 65px 8%;
      text-align: center;
    }

    .features h2 {
      font-size: 35px;
      margin-bottom: 30px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(
        auto-fit, minmax(200px, 1fr)
      );
      gap: 20px;
    }

    .card {
      background: #102844;
      padding: 30px 20px;
      border-radius: 14px;
      border: 1px solid #21476c;
    }

    .card h3 {
      color: #36c5ff;
      margin-bottom: 12px;
    }

    .card p {
      color: #c4d6e8;
      line-height: 1.6;
    }

    footer {
      background: #091b35;
      padding: 25px;
      text-align: center;
      color: #a9c0d8;
    }

    @media (max-width: 600px) {
      header {
        padding: 20px 5%;
      }

      nav a {
        margin-left: 8px;
        font-size: 13px;
      }

      .hero {
        padding: 50px 6%;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">vivo</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#features">Features</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div class="content">
      <h1>Experience the <span>Future.</span></h1>

      <p>
        Discover Vivo 5G smartphones with stunning
        design, powerful performance and ultra-fast
        connectivity.
      </p>

      <a href="#features" class="btn">Explore Now</a>
      <button class="btn" onclick="showMessage()">
        Know More
      </button>

      <p id="message"></p>
    </div>

    <div class="phone">
      <img
        src="https://images.unsplash.com/photo-1598327105666-5b89351aff97?auto=format&fit=crop&w=800&q=85"
        alt="Smartphone"
      >
    </div>
  </section>

  <section class="features" id="features">
    <h2>Powerful Features</h2>

    <div class="cards">
      <div class="card">
        <h3>⚡ 5G Speed</h3>
        <p>Enjoy fast connectivity on supported 5G networks.</p>
      </div>

      <div class="card">
        <h3>📸 Amazing Camera</h3>
        <p>Capture beautiful moments with your smartphone.</p>
      </div>

      <div class="card">
        <h3>🔋 Long Battery</h3>
        <p>Stay connected throughout your busy day.</p>
      </div>

      <div class="card">
        <h3>✨ Premium Design</h3>
        <p>Enjoy a modern look and a stylish experience.</p>
      </div>
    </div>
  </section>

  <footer id="contact">
    <p>Website created by Aditya Singh</p>
    <p>© 2026 Vivo 5G Website Demo</p>
  </footer>

  <script>
    function showMessage() {
      document.getElementById("message").textContent =
        "Welcome! Explore the Vivo 5G features below.";
    }
  </script>

</body>
</html>
