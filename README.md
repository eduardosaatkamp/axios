<h1>Sobre o projeto</h1>
Este repositório consiste em um tutorial que demonstra o uso do Axios para integração com APIs em projetos React. Ele apresenta um exemplo simples de uma aplicação que consome uma API externa para exibir informações de um usuário específico. O tutorial aborda conceitos básicos de requisições HTTP, uso de hooks do React (como useState e useEffect), além de fornecer uma introdução prática ao uso do Axios para fazer chamadas assíncronas à API. O objetivo é fornecer uma base sólida para iniciantes em React que desejam aprender a realizar integrações com APIs externas de forma eficiente e organizado. 

<h1>Estrutura do projeto</h1>
Este projeto utiliza React para criar uma aplicação web que consome a API fornecida pelo serviço "api" localizado em "./services/api.js". A aplicação faz uma requisição GET para obter informações do usuário e exibe seu nome de usuário e biografia. A requisição é feita utilizando o hook useEffect para realizar chamadas à API e o hook useState para armazenar o estado do usuário.
- src/App.js: é o arquivo principal da aplicação, que contém o componente principal App responsável por renderizar as informações do usuário.
- src/services/api.js: Este arquivo define uma instância do Axios para fazer requisições HTTP à API externa.
- public/index.html: O arquivo HTML base da aplicação.
- package.json: Arquivo de configuração do projeto, contendo as dependências, scripts e informações sobre o projeto.

