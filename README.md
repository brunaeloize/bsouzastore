<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>B. Souza Store Londrina - Catálogo</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
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
      margin: 0 0 10px 0;
      letter-spacing: 2px;
    }
    header p {
      font-style: italic;
      font-size: 1.2rem;
      margin: 0;
    }
    .catalogo {
      max-width: 900px;
      margin: 40px auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      padding: 0 20px 40px 20px;
    }
    .produto {
      background-color: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
      transition: transform 0.3s ease;
      cursor: default;
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
    .produto h2
