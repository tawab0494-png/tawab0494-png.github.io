<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tawab Movies & Drama</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #080808;
      color: white;
    }

    header {
      background: linear-gradient(90deg, #000, #1a0000);
      padding: 18px 20px;
      position: sticky;
      top: 0;
      z-index: 10;
      border-bottom: 1px solid #333;
    }

    .logo {
      font-size: 26px;
      font-weight: bold;
      color: #e50914;
    }

    nav {
      margin-top: 12px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-right: 18px;
      font-size: 14px;
    }

    .hero {
      min-height: 430px;
      padding: 90px 25px;
      background:
        linear-gradient(to right, #000 15%, rgba(0,0,0,.75), rgba(0,0,0,.2)),
        url("https://images.unsplash.com/photo-1489599849927-2ee91cede3ba?auto=format&fit=crop&w=1400&q=80")
        center/cover;
    }

    .hero h1 {
      font-size: 45px;
      max-width: 600px;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 550px;
      color: #ddd;
      line-height: 1.6;
      margin-bottom: 25px;
    }

    .btn {
      display: inline-block;
      background: #e50914;
      color: white;
      padding: 13px 22px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 35px 20px;
    }

    section h2 {
      margin-bottom: 20px;
      font-size: 25px;
    }

    .movies {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
      gap: 18px;
    }

    .card {
      background: #151515;
      border-radius: 10px;
      overflow: hidden;
      transition: .3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 240px;
      object-fit: cover;
    }

    .card-content {
      padding: 13px;
    }

    .card h3 {
      margin-bottom: 8px;
    }

    .card p {
      color: #aaa;
      font-size: 13px;
      margin-bottom: 12px;
    }

    .watch {
      color: #e50914;
      text-decoration: none;
      font-weight: bold;
      font-size: 14px;
    }

    footer {
      text-align: center;
      padding: 30px;
      background: #050505;
      color: #777;
      margin-top: 20px;
    }
  </style>
</head>

<body>

<header>
  <div class="logo">🎬 TAWAB MOVIES</div>

  <nav>
    <a href="#home">Home</a>
    <a href="#movies">Movies</a>
    <a href="#drama">Drama</a>
    <a href="#about">About</a>
  </nav>
</header>

<section class="hero" id="home">
  <h1>Welcome to Tawab Movies & Drama</h1>

  <p>
    Discover exciting movies, upcoming dramas, romantic stories,
    action adventures and the latest entertainment.
  </p>

  <a href="#movies" class="btn">Explore Now</a>
</section>

<section id="movies">
  <h2>🔥 Latest Movies</h2>

  <div class="movies">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1489599849927-2ee91cede3ba?auto=format&fit=crop&w=600&q=80">
      <div class="card-content">
        <h3>Coming Soon</h3>
        <p>New movie • Action • Drama</p>
        <a class="watch" href="#">View Details →</a>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1517604931442-7e0c8ed2963c?auto=format&fit=crop&w=600&q=80">
      <div class="card-content">
        <h3>The New Story</h3>
        <p>Romance • Drama</p>
        <a class="watch" href="#">View Details →</a>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=600&q=80">
      <div class="card-content">
        <h3>Dark Mystery</h3>
        <p>Mystery • Thriller</p>
        <a class="watch" href="#">View Details →</a>
      </div>
    </div>

  </div>
</section>

<section id="drama">
  <h2>❤️ Latest Drama</h2>

  <div class="movies">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9?auto=format&fit=crop&w=600&q=80">
      <div class="card-content">
        <h3>Love Story</h3>
        <p>Romantic Drama • Coming Soon</p>
        <a class="watch" href="#">Watch Trailer →</a>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1485846234645-a62644f84728?auto=format&fit=crop&w=600&q=80">
      <div class="card-content">
        <h3>Broken Hearts</h3>
        <p>Drama • Romance</p>
        <a class="watch" href="#">View Details →</a>
      </div>
    </div>

  </div>
</section>

<section id="about">
  <h2>About Us</h2>
  <p style="color:#aaa; line-height:1.7;">
    Welcome to Tawab Movies & Drama — your entertainment destination
    for original movies, dramas, trailers and upcoming stories.
  </p>
</section>

<footer>
  © 2026 Tawab Movies & Drama. All Rights Reserved.
</footer>

</body>
</html>
