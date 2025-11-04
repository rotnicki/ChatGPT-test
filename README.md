<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Biografia i CV – Mikołaj Nowak</title>
  <style>
    :root {
      --primary-color: #003366;
      --secondary-color: #ffffff;
      --accent-color: #007acc;
      --font-main: 'Segoe UI', sans-serif;
    }

    body {
      margin: 0;
      font-family: var(--font-main);
      background-color: var(--secondary-color);
      color: var(--primary-color);
      line-height: 1.6;
    }

    header {
      background-color: var(--primary-color);
      color: var(--secondary-color);
      padding: 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
    }

    nav {
      background-color: var(--accent-color);
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    nav a {
      color: var(--secondary-color);
      text-decoration: none;
      padding: 1rem;
    }

    nav a:focus,
    nav a:hover {
      background-color: #005fa3;
      outline: none;
    }

    main {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }

    section {
      margin-bottom: 2rem;
    }

    h2 {
      border-bottom: 2px solid var(--accent-color);
      padding-bottom: 0.5rem;
    }

    ul {
      padding-left: 1.5rem;
    }

    footer {
      background-color: var(--primary-color);
      color: var(--secondary-color);
      text-align: center;
      padding: 1rem;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Mikołaj Nowak</h1>
    <p>Specjalista ds. UX | Frontend Developer | Entuzjasta dostępności</p>
  </header>

  <nav aria-label="Główna nawigacja">
    <a href="#biografia">Biografia</a>
    <a href="#doswiadczenie">Doświadczenie</a>
    <a href="#edukacja">Edukacja</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

  <main>
    <section id="biografia">
      <h2>Biografia</h2>
      <p>Jestem pasjonatem projektowania dostępnych interfejsów, z ponad 5-letnim doświadczeniem w tworzeniu aplikacji webowych. Moim celem jest budowanie produktów, które są intuicyjne i dostępne dla każdego użytkownika.</p>
    </section>

    <section id="doswiadczenie">
      <h2>Doświadczenie zawodowe</h2>
      <ul>
        <li><strong>UX Designer – Firma X</strong> (2022–2025)</li>
        <li><strong>Frontend Developer – Studio Y</strong> (2019–2022)</li>
      </ul>
    </section>

    <section id="edukacja">
      <h2>Edukacja</h2>
      <ul>
        <li>Politechnika Poznańska – Informatyka (mgr)</li>
        <li>Kursy: WCAG, React, TypeScript</li>
      </ul>
    </section>

    <section id="kontakt">
      <h2>Kontakt</h2>
      <p>Email
