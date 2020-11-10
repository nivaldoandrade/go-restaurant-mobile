<header>
  <h1 align="center">
    GoRestaurant Mobile
  </h1>
  <p align="center">Projeto desenvolvido para uma aplicação mobile de delivery de comida, o GoRestaurant.</p>
  <p align="center">
    <a href="https://reactnative.dev/" rel="nofollow">
        <img src="https://camo.githubusercontent.com/099a86b814c13bf9dbb1ebc651bd48740ba1de1a/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d5265616374266d6573736167653d4e617469766526636f6c6f723d626c75653f7374796c653d706c6173746963266c6f676f3d5265616374" alt="React-Native" data-canonical-src="https://img.shields.io/static/v1?label=React&amp;message=Native&amp;color=blue?style=plastic&amp;logo=React" style="max-width:100%;">
    </a>
  </p>
  <p align="center">
    <img src="https://github.com/nivaldoandrade/go-restaurant-mobile/blob/master/assetsReadme/Capa.png" />
  </p>
  </header>

 <main>
  <h1>Sobre</h1>
  <p>GoRestaurant é um aplicação mobile para delivery de comida. Exibir os pratos de comida, adicionar ao favorito, realizar pedido e adicionar extras.</p>

  <h1>Uso</h1>

  ``` bash
  # clonar o repositório
  git clone https://github.com/nivaldoandrade/go-restaurant-mobile

  # Instalar as dependência
  yarn

  #Iniciando a fake API
  yarn json-server server.json -p 3333

  # Iniciar a aplicação
  yarn start

  ```

  <h1>Rotas da fake API</h1>

  <ul>
    <li><strong>Rota /foods:</strong> Retorna todas as comidas cadastradas na API;</li>
    <li><strong>Rota /foods/:id:</strong> Retorna um prato de comida cadastradas na API baseado no id;</li>
    <li><strong>Rota /categories:</strong> Retorna todas as categorias cadastradas na API;</li>
    <li><strong>Rota /orders:</strong> Retorna todas os pedidos que foram cadastrados na API;</li>
    <li><strong>Rota /favorites:</strong> Retorna todas as comidas favoritas que foram cadastrados na API.</li>
  </ul>

  <h1>Funcionalidades da aplicação</h1>

  <ul>
    <li>Listar os pratos de comida;</li>
    <li>Adicionar pratos ao favorito;</li>
    <li>Realizar pedido de pratos;</li>
    <li>Adicionar extras no prato de comida.</li>
  </ul>

  <h1>Layout</h1>
    <p>
      <a href="https://www.figma.com/file/cHzfYrUBgdzp1XrRuUpggk/GoRestaurant-Mobile">Link Project.</a>
    </p>

  <p style="margin-top: 50px">
    <h6>Desafio feito pela <a href="https://rocketseat.com.br/" target="_blank">RocketSeat.</a></h6>
  </p>
 </main>


