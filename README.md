<h1>Sobre o projeto</h1>
Este projeto utiliza React para criar uma aplicação web que consome a API fornecida pelo serviço "api" localizado em "./services/api.js". A aplicação faz uma requisição GET para obter informações do usuário e exibe seu nome de usuário e biografia. A requisição é feita utilizando o hook useEffect para realizar chamadas à API e o hook useState para armazenar o estado do usuário.

<h1>Estrutura do projeto</h1>
src/App.js: é o arquivo principal da aplicação, que contém o componente principal App responsável por renderizar as informações do usuário.
src/services/api.js: Este arquivo define uma instância do Axios para fazer requisições HTTP à API externa.
public/index.html: O arquivo HTML base da aplicação.
package.json: Arquivo de configuração do projeto, contendo as dependências, scripts e informações sobre o projeto.
Contribuindo
