# MTST
MTST, movimento dos trabalhadores rurais sem teto
<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MTST - O Poder da Resistência</title>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Fredoka One', cursive;
      background-color: #ffe3dc;
      color: #2b2b2b;
    }
    header {
      background: url('https://i.imgur.com/O7t6srf.png') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 20px;
    }
    header h1 {
      font-size: 3.5em;
      color: #ff4f5a;
      text-shadow: 2px 2px #fff;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.5em;
      background: #fff;
      padding: 10px 20px;
      border-radius: 20px;
      box-shadow: 3px 3px #00000033;
    }
    header button {
      margin-top: 20px;
      background: #ff4f5a;
      border: none;
      padding: 15px 30px;
      font-size: 1em;
      color: white;
      cursor: pointer;
      border-radius: 20px;
      transition: background 0.3s;
      box-shadow: 2px 2px #00000033;
    }
    header button:hover {
      background: #e03c47;
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    section h2 {
      font-size: 2.5em;
      color: #ff4f5a;
      margin-bottom: 20px;
      text-shadow: 1px 1px #fff;
    }
    .icones {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 20px;
    }
    .icone {
      background: #fff0eb;
      border: 3px dashed #ff4f5a;
      border-radius: 15px;
      padding: 20px;
      width: 200px;
      text-align: center;
      font-size: 1.2em;
      box-shadow: 2px 2px #00000022;
    }
    .carrossel {
      display: flex;
      overflow-x: auto;
      gap: 20px;
      scroll-snap-type: x mandatory;
    }
    .carrossel div {
      background: #ff4f5a;
      color: white;
      padding: 30px;
      border-radius: 20px;
      min-width: 300px;
      scroll-snap-align: start;
      font-weight: bold;
      font-size: 1.2em;
      box-shadow: 3px 3px #00000033;
    }
    footer {
      background: #2b2b2b;
      color: #fff;
      text-align: center;
      padding: 40px 20px;
      font-size: 1.1em;
      border-top: 5px dotted #ff4f5a;
    }
  </style>
</head>
<body>
  <header>
    <h1>O Poder da Resistência</h1>
    <p>Conheça o MTST e sua importância na luta por moradia no Brasil</p>
    <button onclick="document.getElementById('sobre').scrollIntoView({behavior: 'smooth'})">Ver mais</button>
  </header>  <section id="sobre">
    <h2>O que é o MTST?</h2>
    <p>O MTST (Movimento dos Trabalhadores Sem Teto) é um dos maiores movimentos sociais do Brasil. Ele luta por moradia digna para pessoas que vivem em situação de vulnerabilidade. Surgiu em 1997 e desde então promove ocupações urbanas, ações diretas e propõe soluções concretas para o problema da habitação nas cidades.</p>
    <div class="icones">
      <div class="icone">Direito à moradia</div>
      <div class="icone">Organização popular</div>
      <div class="icone">Justiça social</div>
      <div class="icone">Transformação urbana</div>
    </div>
  </section>  <section>
    <h2>Por que o MTST é importante?</h2>
    <p>O MTST chama atenção para a desigualdade social e o descaso do poder público com milhões de brasileiros sem casa. Suas ações dão visibilidade à luta por moradia e mostram que organização popular pode gerar mudanças reais. Além disso, o movimento atua de forma solidária com outras causas sociais, como saúde, alimentação e educação.</p>
    <div class="carrossel">
      <div>"Não é favela, é resistência."</div>
      <div>"Moradia não é luxo, é direito."</div>
      <div>"Ocupar pra viver."</div>
    </div>
  </section>  <section>
    <h2>Um pouco da história</h2>
    <p>Desde sua criação, o MTST realizou dezenas de ocupações e pressionou governos locais e federais por políticas públicas de habitação. Em várias cidades, o movimento conseguiu a construção de casas populares e também participou ativamente de debates sobre urbanização e reforma urbana.</p>
  </section>  <footer>
    “Enquanto houver injustiça, haverá luta.”<br>
    Trabalho escolar de Sociologia - MTST
  </footer>
</body>
</html>
