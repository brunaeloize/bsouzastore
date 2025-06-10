<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>B. Souza Store - Catálogo</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      /* Fundo rosa bebê com padrão dourado discreto */
      background-color: #F8E6E0;
      background-image: radial-gradient(circle, #D4AF37 3px, transparent 4px);
      background-size: 40px 40px;
      color: #333;
    }

    header {
      background: linear-gradient(90deg, #c69c6d, #8c6a47);
      color: white;
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      letter-spacing: 2px;
    }

    header p {
      font-style: italic;
      font-size: 1.1rem;
    }

    .catalogo {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .produto {
      background-color: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      padding: 20px;
      text-align: center;
      transition: transform 0.3s;
    }

    .produto:hover {
      transform: translateY(-5px);
    }

    .produto img {
      width: 100%;
      max-height: 200px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 15px;
    }

    .produto h2 {
      font-size: 1.2rem;
      margin: 10px 0;
      color: #8c6a47;
    }

    .produto p {
      font-size: 1rem;
      font-weight: bold;
    }

    .whatsapp {
      display: block;
      width: fit-content;
      margin: 40px auto;
      padding: 15px 30px;
      background-color: #25D366;
      color: white;
      font-size: 1.1rem;
      border: none;
      border-radius: 50px;
      text-decoration: none;
      transition: background-color 0.3s;
    }

    .whatsapp:hover {
      background-color: #1ebe5c;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #777;
    }
  </style>
</head>
<body>

  <header>
    <h1>B. Souza Store</h1>
    <p
