# Front-end da Aplicação ScreenMatch

Este projeto é o front-end da aplicação ScreenMatch. Ele interage com uma API para exibir informações sobre séries, incluindo lançamentos, títulos populares e séries por categoria.

## Visão Geral do Projeto

ScreenMatch Front-end é uma aplicação web que permite aos usuários visualizar detalhes de séries, como pôster, título, sinopse, avaliação e atores. Também é possível selecionar temporadas para ver os episódios correspondentes.

A aplicação consiste em:
* **`index.html`**: A página principal que exibe os lançamentos, títulos populares e uma lista de séries. Permite filtrar séries por categoria.
* **`detalhes.html`**: A página de detalhes de uma série específica, onde são mostradas informações detalhadas da série e seus episódios por temporada.
* **`styles.css`**: Contém estilos globais para a aplicação.
* **`css/home.css`**: Estilos específicos para a página inicial (`index.html`).
* **`css/detalhes.css`**: Estilos específicos para a página de detalhes (`detalhes.html`).
* **`scripts/getDados.js`**: Módulo JavaScript responsável por fazer requisições à API (`http://localhost:8080`).
* **`scripts/index.js`**: Lógica JavaScript para a página inicial, incluindo a exibição de séries e o filtro por categoria.
* **`scripts/series.js`**: Lógica JavaScript para a página de detalhes, carregando informações da série, temporadas e episódios.

## Como Visualizar o Projeto

Para visualizar este projeto, siga os passos abaixo:

1.  **Download ou Clone**: Baixe ou clone o repositório do projeto para sua máquina local.
2.  **Abrir com VS Code**: Abra a pasta do projeto no VS Code.
3.  **Instalar Live Server**: Caso ainda não tenha, instale a extensão "Live Server" no VS Code.
4.  **Abrir `index.html`**: Clique com o botão direito no arquivo `index.html` e selecione "Open with Live Server".

## Observações

* Para que as informações sejam exibidas completamente no frontend, é necessário que a aplicação ScreenMatch (API) esteja inicializada.
