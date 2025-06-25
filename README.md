<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Meniu Sinaia</title>

  <style>
    body {
      margin: 0;
      font-family: 'Times New Roman', Times, serif;
      background: linear-gradient(to bottom,#02340a , #021907 );
      display: flex;
      flex-direction: column;
      min-height: 100vh;
      align-items: center;
      text-align: center;
      position: relative;
    }

    .logo {
      margin-top: 40px;
    }

    .logo img {
      width: 100%;
      max-width: 400px;
      height: auto;
      display: block;
      margin: 0 auto;
    }
    .menu-buttons {
      display: flex;
      gap: 60px;
      margin-top: 80px; /* MAI MULT SPAȚIU între logo și butoane */
      justify-content: center;
    }

    .menu-buttons a {
      padding: 20px 40px;
      font-size: 2.0em;
      background-color: #c98a0a;
      color: rgb(255, 255, 255);
      text-decoration: none;
      border-radius: 10px;
      border: 2px solid #8a5d00;
      box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.5);
      transition: all 0.3s ease;
    }

    .menu-buttons a:hover {
      background-color: #b8860b;
      transform: scale(1.05);
    }

   footer {
      position: absolute;
      bottom: 60px;
      width: 100%;
      text-align: center;
      color: rgb(0, 0, 0);
      font-size: 1.4em;
      font-weight: 800;
    }
  </style>
</head>

<body>

  <!-- Logo -->
  <div class="logo">
    <img src="C:\Users\Iulia\Documents\GitHub\Jules-crep.github.io\SiteScheletCreparie\media\imagine PNG.png" />
  </div>

  <!-- Butoane meniu -->
  <div class="menu-buttons">
    <a href="menu-ro.html">MENIU</a>
    <a href="menu-en.html">MENU</a>
  </div>

  <!-- Footer cu adresă -->
  <footer>
    STR. OCTAVIAN GOGA, NR 2, SINAIA, PRAHOVA - PARCUL DIMITRIE GHICA
  </footer>

</body>

</html>