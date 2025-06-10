<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>B. Souza Store Londrina - Catálogo</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fdeff4;
      color: #4b3b2a;
    }

    header {
      background: linear-gradient(90deg, #f9d3e3, #fce4ec);
      color: #a67c52;
      padding: 50px 20px;
      text-align: center;
      border-bottom: 3px solid #d4af37;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
      letter-spacing: 2px;
      font-weight: bold;
    }

    header p {
      font-style: italic;
      font-size: 1.2rem;
    }

    .catalogo {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .produto {
      background-color: #fff;
      border-radius: 14px;
      box-shadow: 0 6px 18px rgba(212, 175, 55, 0.2);
      padding: 25px;
      text-align: center;
      border: 2px solid #f5e1dc;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .produto:hover {
      transform: translateY(-6px);
      box-shadow: 0 8px 22px rgba(212, 175, 55, 0.3);
    }

    .produto img {
      width: 100%;
      max-height: 220px;
      object-fit: cover;
      border-radius: 12px;
      margin-bottom: 15px;
    }

    .produto h2 {
      font-size: 1.4rem;
      color: #a67c52;
      margin: 10px 0;
    }

    .produto p {
      font-size: 1.1rem;
      font-weight: bold;
      color: #4b3b2a;
    }

    .whatsapp {
      display: block;
      width: fit-content;
      margin: 40px auto;
      padding: 15px 35px;
      background-color: #25D366;
      color: white;
      font-size: 1.2rem;
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
      color: #7b6a58;
      border-top: 1px solid #e8d4c8;
    }
  </style>
</head>
<body>

  <header>
    <h1>B. Souza Store Londrina</h1>
    <p>Catálogo de Produtos - Elegância e Cuidado</p>
  </header>

  <section class="catalogo">
    <div class="produto">
      <img src="https://via.placeholder.com/300x200?text=Hidratante+Lyra" alt="Hidratante Lyra">
      <h2>Hidratante Lyra</h2>
      <p>R$ 39,90</p>
    </div>
    <div class="produto">
      <img src="https://via.placeholder.com/300x200?text=Hidratante+Imensi+Alive" alt="Hidratante Imensi Alive">
      <h2>Hidratante Imensi Alive</h2>
      <p>R$ 39,90</p>
    </div>
  </section>

  <a class="whatsapp" href="https://wa.me/5543984369699" target="_blank">
    💬 Fale comigo no WhatsApp
  </a>

  <footer>
    &copy; 2025 B. Souza Store Londrina - Todos os direitos reservados.
  </footer>

</body>
</html>
