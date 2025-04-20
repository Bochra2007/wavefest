<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wave Fest 2025</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: radial-gradient(circle, #ffe6f0, #ffddee, #fff5f9);
      color: #111;
      overflow-x: hidden;
    }
    header {
      background: url('https://nightcruiser.com.au/wp-content/uploads/2018/03/concert-on-beach01.jpg') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      position: relative;
    }
    header::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(255, 192, 203, 0.3);
    }
    header h1, header h2 {
      z-index: 1;
      text-shadow: 0 0 10px #fff, 0 0 20px #ffccff;
    }
    header h1 {
      font-size: 4rem;
      color: #ff33cc;
    }
    header h2 {
      font-size: 2rem;
      color: #ff99ff;
    }
    .section {
      padding: 4rem 2rem;
      text-align: center;
    }
    .artists {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2rem;
      background: linear-gradient(135deg, #ffcce5, #ccffff);
      padding: 2rem;
      border-radius: 2rem;
      box-shadow: 0 0 30px rgba(255, 192, 203, 0.5);
    }
    .artist {
      background: rgba(255, 255, 255, 0.4);
      padding: 1rem;
      border-radius: 1rem;
      width: 250px;
      height: 350px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      box-shadow: 0 0 15px rgba(255, 200, 255, 0.6);
    }
    .artist img {
      width: 200px;
      height: 250px;
      object-fit: cover;
      border-radius: 1rem;
      margin-bottom: 1rem;
    }
    .footer {
      background: linear-gradient(to right, #ffccff, #ccffff);
      padding: 2rem;
      text-align: center;
      color: #555;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1rem;
      margin-top: 2rem;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 1rem;
      box-shadow: 0 0 25px #ffccff;
    }
    a {
      color: #ff66cc;
    }
    .lasers {
      background: repeating-linear-gradient(90deg, #ffccff 0, #ccffff 10%, #ffccff 20%);
      height: 12px;
      animation: glitter 1s linear infinite;
    }
    @keyframes glitter {
      0% { filter: brightness(1); }
      50% { filter: brightness(1.5); }
      100% { filter: brightness(1); }
    }
    .ticket-section {
      background: linear-gradient(135deg, rgba(255,255,255,0.4), rgba(255,230,255,0.4));
      color: #222;
      padding: 3rem 2rem;
      text-align: center;
      border-top-left-radius: 2rem;
      border-top-right-radius: 2rem;
      backdrop-filter: blur(10px);
    }
    .ticket-section h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .ticket-prices {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 2rem;
    }
    .ticket {
      background: linear-gradient(145deg, #fff0f5, #e6ffff);
      color: #111;
      padding: 1.5rem;
      border-radius: 1rem;
      width: 250px;
      box-shadow: 0 0 20px rgba(255, 200, 255, 0.3);
    }
  </style>
</head>
<body>
  <header>
    <h1>WAVE FEST</h1>
    <h2>July 20-21, 2025 | Miami Beach</h2>
  </header>

  <div class="lasers"></div>

  <section class="section">
    <h2>Special Guests</h2>
    <div class="artists">
      <div class="artist">
        <img src="https://i.pinimg.com/736x/31/22/68/3122687b81bf56453e7dd5343ead9b39.jpg" alt="Tyla">
        <h3>Tyla</h3>
      </div>
      <div class="artist">
        <img src="https://i.pinimg.com/736x/82/7d/d9/827dd928ba5eed24e4d26c52dbfc5c84.jpg" alt="Rosalía">
        <h3>Rosalía</h3>
      </div>
      <div class="artist">
        <img src="https://i.pinimg.com/736x/82/86/69/828669f0f9b764d71c74e4fdbe7ece28.jpg" alt="Travis Scott">
        <h3>Travis Scott</h3>
      </div>
      <div class="artist">
        <img src="https://i.pinimg.com/736x/2a/ce/d6/2aced68232fc65687b865bafd9835110.jpg" alt="Calvin Harris">
        <h3>Calvin Harris</h3>
      </div>
    </div>
  </section>

  <section class="section">
    <h2>A Colorful Eco-Friendly Festival</h2>
    <p>Located on the vibrant Miami Beach, Wave Fest is 100% eco-conscious. Powered by solar panels and wind turbines, this festival combines sustainable energy with unforgettable Afrobeat rhythms and tropical vibes.</p>
  </section>

  <section class="section">
    <h2>Vibes & Lights</h2>
    <div class="gallery">
      <img src="https://i.pinimg.com/736x/59/4e/bc/594ebc0dc4b72b42e572c7b66aed9ed8.jpg" alt="Colorful festival 1">
      <img src="https://i.pinimg.com/736x/e4/cd/75/e4cd752f632a08909b991f0b95dc72ed.jpg" alt="Beach lights vibe">
      <img src="https://i.pinimg.com/736x/b8/e0/62/b8e062c5bd135a8efda1561cb7ab2a31.jpg" alt="Stage with neon">
    </div>
  </section>

  <section class="ticket-section">
    <h2>Tickets</h2>
    <div class="ticket-prices">
      <div class="ticket">
        <h3>General Admission</h3>
        <p>$149 / 2 days</p>
      </div>
      <div class="ticket">
        <h3>VIP Experience</h3>
        <p>$349 / 2 days + backstage access</p>
      </div>
      <div class="ticket">
        <h3>Group Pass</h3>
        <p>$499 / 4 people</p>
      </div>
    </div>
    <p style="margin-top: 2rem;"><a href="#" style="color: #ff33cc; font-size: 1.5rem; text-decoration: underline;">Buy Tickets Now</a></p>
  </section>

  <footer class="footer">
    <p>© 2025 Wave Fest. Organized by THYNK UNLIMITED.</p>
    <p>www.reallygreatsite.com</p>
  </footer>
</body>
</html>
