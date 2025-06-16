<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>WS Bebidas</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f8f8f8;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    header {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 20px;
    }

    main {
      padding: 20px;
      flex-grow: 1;
    }

    section {
      margin-bottom: 50px;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .card {
      background: white;
      width: 250px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: 0.3s;
    }

    .card:hover {
      transform: scale(1.02);
    }

    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .card-content {
      padding: 10px;
      text-align: center;
    }

    .card-content h3 {
      margin: 10px 0;
    }

    .btn-comprar {
      background-color: #25D366;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 14px;
      text-decoration: none;
      display: inline-block;
      margin-top: 10px;
    }

    .btn-comprar:hover {
      background-color: #1ebe5b;
    }

    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 15px 10px;
      font-size: 16px;
    }
  </style>
</head>
<body>

  <header>
    <h1>WS Bebidas</h1>
    <p>Desde 2017 entregando qualidade e sabor!</p>
  </header>

  <main>
    <section>
      <h2>Refrigerantes</h2>
      <div class="products">
        <div class="card">
          <img src="https://cdn.pixabay.com/photo/2015/05/31/12/14/cola-791045_1280.jpg" alt="Coca-Cola">
          <div class="card-content">
            <h3>Coca-Cola 2L</h3>
            <a class="btn-comprar" href="https://wa.me/5581985780510?text=Olá!%20Gostaria%20de%20comprar%20Coca-Cola%202L." target="_blank">Comprar</a>
          </div>
        </div>
        <div class="card">
          <img src="https://cdn.pixabay.com/photo/2016/04/10/21/04/beverage-1324986_1280.jpg" alt="Guaraná">
          <div class="card-content">
            <h3>Guaraná Antarctica 2L</h3>
            <a class="btn-comprar" href="https://wa.me/5581985780510?text=Olá!%20Gostaria%20de%20comprar%20Guaraná%20Antarctica%202L." target="_blank">Comprar</a>
          </div>
        </div>
      </div>
    </section>

    <section>
      <h2>Cervejas</h2>
      <div class="products">
        <div class="card">
          <img src="https://cdn.pixabay.com/photo/2017/09/26/13/25/beer-2789147_1280.jpg" alt="Skol">
          <div class="card-content">
            <h3>Skol Pilsen 350ml</h3>
            <a class="btn-comprar" href="https://wa.me/5581985780510?text=Olá!%20Gostaria%20de%20comprar%20Skol%20Pilsen%20350ml." target="_blank">Comprar</a>
          </div>
        </div>
      </div>
    </section>

    <section>
      <h2>Sucos</h2>
      <div class="products">
        <div class="card">
          <img src="https://cdn.pixabay.com/photo/2015/07/02/10/28/orange-828408_1280.jpg" alt="Suco de Laranja">
          <div class="card-content">
            <h3>Suco de Laranja Natural</h3>
            <a class="btn-comprar" href="https://wa.me/5581985780510?text=Olá!%20Gostaria%20de%20comprar%20Suco%20de%20Laranja%20Natural." target="_blank">Comprar</a>
          </div>
        </div>
      </div>
    </section>

    <section>
      <h2>Destilados</h2>
      <div class="products">
        <div class="card">
          <img src="https://cdn.pixabay.com/photo/2017/01/20/00/30/drink-1995953_1280.jpg" alt="Whisky">
          <div class="card-content">
            <h3>Whisky Johnnie Walker</h3>
            <a class="btn-comprar" href="https://wa.me/5581985780510?text=Olá!%20Gostaria%20de%20comprar%20Whisky%20Johnnie%20Walker." target="_blank">Comprar</a>
          </div>
        </div>
        <div class="card">
          <img src="https://cdn.pixabay.com/photo/2014/12/21/23/28/wine-576419_1280.png" alt="Vinho">
          <div class="card-content">
            <h3>Vinho Tinto Seco</h3>
            <a class="btn-comprar" href="https://wa.me/5581985780510?text=Olá!%20Gostaria%20de%20comprar%20Vinho%20Tinto%20Seco." target="_blank">Comprar</a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    Contato: <a href="https://wa.me/5581985780510" target="_blank" style="color:#25D366; text-decoration:none;">+55 81 98578-0510 (WhatsApp)</a>
  </footer>

</body>
</html>
