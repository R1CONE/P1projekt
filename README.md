* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
  html, body {
    width: 100%;
    max-width: 100%;
    overflow-x: hidden;
    font-family: Arial, sans-serif;
    background-color: #ffffff;
    color: #333;
  }
  
  .container {
    width: 100%;
    max-width: 100%;
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
  
  .header-banner {
    width: 100%;
    background-color: #5d3a22;
  }
  
  .header-banner img {
    width: 100%;
    max-height: 280px;
    object-fit: cover;
    display: block;
  }
  
  .main-content {
    display: flex;
    flex: 1;
    gap: 30px;
    padding: 25px;
    width: 100%;
    max-width: 100%;
  }
  
  .sidebar {
    width: 220px;
    flex-shrink: 0;
  }
  
  .nav-menu {
    display: flex;
    flex-direction: column;
    gap: 6px;
  }
  
  .nav-item {
    background-color: #a89f32;
    color: #111;
    padding: 12px 15px;
    text-decoration: none;
    font-size: 14px;
    font-weight: bold;
    display: block;
  }
  
  .content-article {
    flex: 1;
    min-width: 0;
  }
  
  .main-heading {
    font-size: 26px;
    font-weight: bold;
    color: #111;
    margin-bottom: 20px;
    line-height: 1.3;
  }
  
  .content-article p {
    font-size: 14px;
    line-height: 1.6;
    color: #333;
    margin-bottom: 18px;
    text-align: justify;
  }
  
  .footer-banner {
    width: 100%;
    background-color: #5d3a22;
    color: #ccc;
    padding: 12px 25px;
    font-size: 13px;
    margin-top: auto;
  }
  
  @media (max-width: 768px) {
    .main-content {
      flex-direction: column;
      padding: 15px;
    }
  
    .sidebar {
      width: 100%;
    }
  
    .nav-menu {
      flex-direction: row;
      flex-wrap: wrap;
    }
  
    .nav-item {
      flex: 1 1 auto;
      text-align: center;
    }
  
    .header-banner img {
      max-height: 160px;
    }
  }


  <!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kawiarnia</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    <header class="header-banner">
      <img src="zrob_napis_kawiarnia_na_brazowym_tle.webp" alt="kawiarnia">
    </header>

    <div class="main-content">
      <aside class="sidebar">
        <nav class="nav-menu">
          <a href="#" class="nav-item">Start</a>
          <a href="#" class="nav-item">O firmie</a>
          <a href="#" class="nav-item">Oferta</a>
          <a href="#" class="nav-item">Cennik</a>
          <a href="#" class="nav-item">Portfolio</a>
          <a href="#" class="nav-item">Kontakt</a>
        </nav>
      </aside>

      <main class="content-article">
        <h1 class="main-heading">Kawa kawa kawa kawa aaaaa kawaaaa kawaa kawa</h1>

        <p>Kawiarnia to miejsce stworzone dla prawdziwych fanów kawy, którzy szukają wyjątkowych smaków, aromatu i chwili relaksu. Naszą pasją jest kawiarniana kultura, a naszym celem jest dostarczanie gościom jak najlepszych wrażeń. Niezależnie od tego, czy lubisz klasyczne espresso, kremowe cappuccino, czy wspólną kawę ze znajomymi, nasza kawiarnia to przestrzeń, w której każdy znajdzie coś dla siebie.</p>

        <p>Wierzymy, że picie kawy to coś więcej niż tylko codzienny rytuał. To sposób na celebrowanie chwil, rozwijanie rozmów i nawiązywanie relacji z ludźmi o podobnych pasjach. Stawiamy na dobrą atmosferę, przyjazną obsługę i nieustanne odkrywanie nowych mieszanek ziaren. Każda filiżanka to nowa historia, wyjątkowy aromat i szansa na chwilę wytchnienia.</p>

        <p>Naszą misją jest rozwijanie pasji do dobrej kawy i tworzenie miejsca, do którego goście będą chcieli wracać. To połączenie starannie wyselekcjonowanych ziaren, zaangażowania naszych baristów i niepowtarzalnego klimatu. Niezależnie od tego, czy wpadasz tylko na szybkie espresso, czy spędzasz u nas całe popołudnie, zapraszamy Cię do wspólnego odkrywania smaków. Przekonaj się, że najlepsze chwile zaczynają się od dobrej kawy!</p>
      </main>
    </div>

    <footer class="footer-banner">
      © Kawiarnia
    </footer>
  </div>

</body>
</html>
