<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Arraiá da Família Elias</title>
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <style>
    body {
      background-image: url('https://github.com/NadjanSF/Festa-Elias/blob/main/festa1Capa.jpg');
      background-size: cover;
      background-position: center;
  background-repeat: no-repeat;
      color: white;
      text-shadow: 1px 1px 2px black;
    }
    .w3-container {
      background-color: rgba(0, 0, 0, 0.6);
      padding: 20px;
      margin-bottom: 20px;
      border-radius: 8px;
    }
    a, a:visited {
      color: #FFD700;
    }
    input[type="text"] {
      padding: 5px;
      margin-left: 10px;
    }
  </style>
</head>
<body>
  <div class="w3-container w3-center">
    <h1>Bem-vindos ao Arraiá dos Elias!</h1>
    <p class="w3-large">Uma festança boa demais da conta, sô!</p>
  </div>

  <div class="w3-container">
    <h2>Menu</h2>
    <ul class="w3-ul">
      <li><a href="#endereco">Endereço</a></li>
      <li><a href="#galeria">Galeria</a></li>
      <li><a href="#pratos">Lista de Pratos</a></li>
      <li><a href="https://wa.me/qr/MZ7VGLOF4LVVE1" target="_blank">Fale conosco no WhatsApp</a></li>
    </ul>
  </div>

  <div class="w3-container" id="endereco">
    <h2>Endereço</h2>
    <p>Casa da Dani?!,- SP</p>
    <p>Data: á definir - a partir das 19h</p>
  </div>

  <div class="w3-container" id="galeria">
    <h2>Galeria de Festas Anteriores</h2>
<div class="w3-row-padding">
  <div class="w3-third">
    <a href="https://github.com/NadjanSF/Festa-Elias/blob/main/festa.001.jpg" target="_blank">
      <img src="festa.001.jpg" class="w3-image w3-border w3-hover-opacity">
    </a>
  </div>
  <div class="w3-third">
    <a href="https://github.com/NadjanSF/Festa-Elias/blob/main/festa1.1.jpg" target="_blank">
      <img src="festa1.1.jpg" class="w3-image w3-border w3-hover-opacity">
    </a>
  </div>
  <div class="w3-third">
    <a href="https://github.com/NadjanSF/Festa-Elias/blob/main/festa1.jpg" target="_blank">
      <img src="festa1.jpg" class="w3-image w3-border w3-hover-opacity">
    </a>
  </div>
  <div class="w3-container">
  <h2>Vídeo da Festa</h2>
  <video width="50%" height="auto" controls>
    <source src="https://github.com/NadjanSF/Festa-Elias/blob/main/video.mp4" type="video/mp4">
    Seu navegador não suporta o vídeo.
  </video>
</div>
</div>
  <div class="w3-container" id="pratos">
    <h2>Lista de Pratos</h2>
    <p>Escolha um prato e coloque seu nome:</p>
    <ul class="w3-ul">
      <li>
        <input type="checkbox" id="Arroz doce"> Arroz doce
        <input type="text" placeholder="Seu nome">
      </li>
      <li>
        <input type="checkbox" id="bolo"> Bolo de milho
        <input type="text" placeholder="Seu nome">
      </li>
      <li>
        <input type="checkbox" id="cuscuz"> Cuscuz
        <input type="text" placeholder="Seu nome">
      </li>
      <li>
        <input type="checkbox" id="quentao"> Quentão
        <input type="text" placeholder="Seu nome">
      </li>
      <li>
        <input type="checkbox" id="pipoca"> Pipoca
        <input type="text" placeholder="Seu nome">
      </li>
      <li>
        <input type="checkbox" id="doces"> Doces
        <input type="text" placeholder="Seu nome">
      </li>
      <li>
        <input type="checkbox" id="cachorro quente"> Cachorro Quente
        <input type="text" placeholder="Seu nome">
      </li>
    </ul>
  </div>

  <footer class="w3-container w3-center">
    <p>Família Elias &copy; 2025</p>
  </footer>
</body>
</html>
