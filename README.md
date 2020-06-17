<h3 align="center">
    <img alt="Imagem da aplicação" src="/web/src/assets/WebScreen.png">
    <br><br>
    <b>Projeto desenvolvido na Next Level Week #1 da Rocketseat</b>  
    <br>
    
</h3>
<br>
<div align="center">
    <img src="https://img.shields.io/badge/web-react-blue">
    <img src="https://img.shields.io/badge/mobile-react%20native-blue">
    <img src="https://img.shields.io/badge/server-nodejs-success">
    <img src="https://img.shields.io/badge/%3C%3E-typescript-blueviolet">
</div>
<br>

<div align="center">
    <a href="#sobre">Sobre</a> | <a href="#tecnologias">Tecnologias</a> | <a href="#run">Rodando o projeto</a> | <a href="#contato">Contato</a>
  
</div>

<a id="sobre"></a>

## :recycle: Sobre Projeto Ecoleta

<strong>Ecoleta</strong> é um projeto de desenvolvimento <strong>fullstack</strong> (API REST + Web front-end + Mobile). Trata-se de um marketplace para auxiliar as pessoas a encontrarem pontos de coleta de resíduos.

Esta versão foi desenvolvida acompanhando as cinco aulas da trilha <strong>Booster</strong> da <strong>Next Level Week #1</strong>. O tema do app foi proposto pela **[Rocketseat](https://rocketseat.com.br/)** em comemoração à Semana do Meio Ambiente.

Professor: **[Diego Fernandes](https://github.com/diego3g)**

<a id="tecnologias"></a>

## :computer: Tecnologias

O projeto foi desenvolvido utilizando as tecnologias:

- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)

Principais bibliotecas utilizadas (lista completa nas dependências listadas no arquivo package.json na raíz de cada uma das três pastas - [server](/server/package.json), [web](web/package.json) e [mobile](mobile/package.json)):

- [Express](https://expressjs.com/)
- [Knex](https://knexjs.org)
- [Sqlite3](https://www.sqlite.org/)
- [Multer](https://github.com/expressjs/multer)
- [Axios](https://github.com/axios/axios)
- [Leaflet](https://leafletjs.com/)
- [React-dropzone](https://react-dropzone.js.org/)
- [React-icons](https://react-icons.github.io/react-icons/)
- [Expo](https://expo.io/)

<a id="run"></a>

## :running: Rodando o projeto

1. Pré-requisitos:

- **[Node.js](https://nodejs.org/en/)**, **[Git](https://git-scm.com/)** e um gerenciador de pacotes (**[NPM](https://www.npmjs.com/)** ou **[Yarn](https://yarnpkg.com/)**) instalados na máquina.

2. Clonar o repositório:

```sh
  $ git clone https://github.com/testtzlaffe/nlw1.git
```

3. Rodar os ambientes de desenvolvimento do app:

```sh
  # Instalar as bibliotecas e as dependências
  $ npm install (ou yarn)

  # Criar e popular o banco de dados
  $ cd server
  $ npm run knex:migrate
  $ npm run knex:seed

  # Iniciar o servidor
  $ cd server
  $ npm run dev (ou yarn dev)

  # Iniciar a versão mobile
  $ cd mobile
  $ npm start (ou yarn start)

  # Iniciar a versão web
  $ cd web
  $ npm start (ou yarn start)

```

<a id="contato"></a>

## :coffee: Contato

<h4>
    Gostou do projeto? Fique a vontade para mandar issues, pull requests, críticas ou sugestões. Se quiser iniciar um papo, conversar sobre este trabalho ou qualquer outro assunto, me chame no <a href="https://www.linkedin.com/in/christian-testtzlaffe-alpoim/" target="_blank">Linkedin</a>.
</h4>

---

<h4 align="center">
    Desenvolvido com 💜 por <a href="https://www.linkedin.com/in/christian-testtzlaffe-alpoim/" target="_blank">Christian Testtzlaffe Alpoim</a>
</h4>
