<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gabrielle Vital</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #e75480, #8e44ad);
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      padding: 2rem;
    }

    header {
      text-align: center;
      margin-bottom: 2rem;
    }

    header h1 {
      font-size: 3rem;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
    }

    .contacts {
      margin-top: 2rem;
      width: 90%;
      max-width: 800px;
      background-color: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      padding: 1.5rem;
      text-align: center;
    }

    .contacts h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      font-weight: bold;
    }

    .contacts a {
      color: white;
      text-decoration: underline;
      display: block;
      margin: 0.3rem 0;
      font-size: 1.1rem;
    }

    /* Botões para LinkedIn e GitHub */
    .contacts a.btn {
      display: inline-block;
      margin: 0.5rem 0.8rem;
      padding: 0.8rem 1.8rem;
      background-color: rgba(255, 255, 255, 0.2);
      color: white;
      text-decoration: none;
      border-radius: 8px;
      transition: background-color 0.3s;
      font-size: 1.1rem;
    }

    .contacts a.btn:hover {
      background-color: rgba(255, 255, 255, 0.4);
    }

    .presentation, .certificados, .projetos {
      background-color: rgba(255, 255, 255, 0.1);
      padding: 1.5rem;
      border-radius: 10px;
      margin-top: 2rem;
      width: 90%;
      max-width: 800px;
      text-align: center;
    }

    .presentation p, .certificados p, .projetos p {
      font-size: 1.1rem;
      line-height: 1.6;
    }

    .presentation h2, .certificados h2, .projetos h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      font-weight: bold;
    }

    .certificados a, .projetos a {
      display: inline-block;
      margin: 0.5rem;
      padding: 0.8rem 1.5rem;
      background-color: rgba(255, 255, 255, 0.2);
      color: white;
      text-decoration: none;
      border-radius: 8px;
      transition: background-color 0.3s;
      font-size: 1rem;
    }

    .certificados a:hover, .projetos a:hover {
      background-color: rgba(255, 255, 255, 0.4);
    }

    .projeto-detalhes {
      text-align: left;
      margin-top: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gabrielle Vital</h1>
    <p>Esatudante de Ciencia da Computação da CESAR School | Foco em tecnologia e inovação</p>
  </header>

  <div class="presentation">
    <h2>Sobre Mim</h2>
    <p>
      Meu nome é Gabrielle Capezzera Vital de Castro, tenho 19 anos e sou estudante do primeiro semestre de Ciência da Computação na CESAR School. Estou interessada em desenvolvimento Front-End, design de interfaces e desenvolvimneto de software.
    </p>
    <p>
      Escolhi a área de tecnologia porque acredito em seu potencial para transformar o mundo quando aplicada de forma eficaz. Um exemplo disso é o jogo "Recife de Memórias", que desenvolvi recentemente com meu grupo de projetos para estimular a memória de curto e longo prazo de pessoas idosas com demência.
    </p>
  </div>

  <div class="certificados">
    <h2>Meus Certificados</h2>
    <p>
      Durante o meu primeiro período tive a oportunidade de fazer dois cursos da CISCO Networking Academy, cursos que ampliaram meu conhecimento de Pyhton e JavaScript, conhecimentos que são fundamentais na minha carreira dentro e fora do CESAR school.
    </p>
    <a href="https://drive.google.com/file/d/1z0BMUYWlRw5a4oDiZSCfmwwqqbGUtkTK/view?usp=sharing" target="_blank">Certificado de Python</a>
    <a href="https://drive.google.com/file/d/1B8Ay0NWLE6NGGMUvaed5ddTib9VASQzG/view?usp=sharing" target="_blank">Certificado de JavaScript</a>
  </div>

  <div class="projetos">
    <h2>Meus Projetos</h2>
    <a href="#recife">Recife de Memórias</a>
    <a href="#crud">CRUD de Animais</a>

    <div id="recife" class="projeto-detalhes">
      <h3>Recife de Memórias</h3>
      <p><strong>Sobre o que é?</strong><br>
      “Recife de Memórias" é um jogo sensorial interativo que utiliza tecnologia acessível para estimular a cognição e o afeto. Na cidade das pontes, Recife de Memórias também é uma ponte entre o passado e o presente — uma forma de resgatar identidades, honrar histórias e, acima de tudo, cuidar com afeto e tecnologia.</p>
      <p><strong>Como Funciona?</strong><br>
      A experiência é baseada em uma jornada pelos pontos turísticos mais icônicos do "Bairro do Recife", como:
      Marco Zero, Cais do Sertão, Parque das Esculturas, Rua do Bom Jesus, Forte do Brum. Através de uma narração, o jogador deve identificar a localização sendo descrita, encontrá-la no mapa e pressionar o botão de sua cor correspondente. Após identificar corretamente todos os 5 pontos descritos, o usuário deve repetir a sequência de botões pressionados.</p>
      <a href="https://github.com/LHFalcao/Recife_de_Memorias/tree/main" target="_blank">Ver no GitHub</a>
      <a href="https://sites.google.com/cesar.school/g9-site/in%C3%ADcio" target="_blank">Ver no Site</a>
    </div>

    <div id="crud" class="projeto-detalhes">
      <h3>CRUD de Animais — VIDA PET</h3>
      <p>
        Vida Pet, um simulador de programa de PetShop, desenvolvida para oferecer um cuidado completo e afetivo com os pets, auxiliando tutores, como Camila, que tem dificuldade de administrar as necessidades de seus pets. Nosso sistema, o “Vida Pet”, ajuda a acompanhar e registrar o dia a dia dos pets, com funções que vão do cadastro à análise do humor, oferecendo um controle prático da saúde e bem-estar dos pets. São diversas funcionalidades reunidas em um só lugar para tornar o cuidado com os pets mais simples e eficiente no dia a dia dos tutores.
      </p>
      <a href="https://github.com/marianamaliu/Projeto-FP" target="_blank">Ver no GitHub</a>
    </div>
      <div class="contacts">
    <h2>Meus Contatos</h2>
    <a href="mailto:gcvc@cesar.school">gcvc@cesar.school</a>
    <a href="mailto:gabicvcastro@gmail.com">gabicvcastro@gmail.com</a>
    <a href="https://www.linkedin.com/in/gabriellecvital" target="_blank" class="btn">LinkedIn</a>
    <a href="https://github.com/gabriellevitalc" target="_blank" class="btn">GitHub</a>
  </div>

  </div>
</body>
</html>
