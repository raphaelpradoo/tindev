<h1 align="center">
  <img alt="Tindev" height="215" title="Tindev" src="logo.png" />
</h1>

<p align="center">Aplicação desenvolvida durante a Semana Omnistack da Rocketseat.</p>

<p align="center">
 <a href="#rocket-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#computer-instalação-execução-e-desenvolvimento">Instalação, execução e desenvolvimento</a>
</p>

## :rocket: Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [MongoDB](https://www.mongodb.com/)
- [Express](https://github.com/expressjs/express)

## :computer: Instalação, execução e desenvolvimento

Faça um clone desse repositório.

### Pré-requisitos

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

### Backend

- A partir da raiz do projeto, entre na pasta rodando `cd backend/`;
- Rode `yarn` para instalar sua dependências;
- Rode `docker-compose up -d` para montar o ambiente;
- Rode `yarn dev` para iniciar o servidor 

### Web

_ps: Antes de executar, lembre-se de iniciar o backend deste projeto_

- A partir da raiz do projeto, entre na pasta do frontend web rodando `cd frontend/`;
- Rode `yarn` para instalar as dependências;
- Rode `yarn start` para iniciar o client web;

### Mobile

Obs.: Esse projeto mobile foi testado apenas no **iOS**.

_ps: Antes de executar, lembre-se de iniciar o backend deste projeto_

- A partir da raiz do projeto, entre na pasta do frontend mobile rodando `cd tindev/`;
- Rode `yarn` para instalar as dependências;
- Execute o comando `react-native run-ios` para o aplicativo abrir no emulador do Iphone;

---

Desenvolvido por [Raphael Souza Prado](https://www.linkedin.com/in/raphaelpradooliveira/)
