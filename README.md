<h1 align="center">Find Your Duo - NLW eSports</h1>
<p align="center">
  <img width="350" src="https://user-images.githubusercontent.com/44277956/190904595-7a9577c0-fad4-461f-8269-2f8b3f1fd440.svg" />
</p>  
<p align="center">
  <img src="https://img.shields.io/badge/Prisma-4.3.1-2D3748?style=for-the-badge&logo=Prisma" />
  <img src="https://img.shields.io/badge/Express-4.18.1-000000?style=for-the-badge&logo=Express" />
  <img src="https://img.shields.io/badge/NPM-8.5.5-CB3837?style=for-the-badge&logo=npm" />
  <img src="https://img.shields.io/badge/NodeJs-16.15.1-339933?style=for-the-badge&logo=Node.js" />
</p>
<h4 align="center">Projeto desenvolvido durante a Next Level Week</h4>

<img width="1000" height="490" src="https://user-images.githubusercontent.com/44277956/190920173-3f2fae21-32a4-4791-b2dd-67834ef68587.png"/>
<img width="1000" height="490" src="https://user-images.githubusercontent.com/44277956/190920175-ba79ddbb-393e-45a6-bee1-12d7b9675988.png"/>

Projeto de uma aplicação completa, web client, mobile e backend, com o intuito de criar uma plataforma de integração social dos usuários para jogar em Hub em uma sala do discord previamente escolhida.
  

## Objetivo

Criação de uma API utilizando NodeJs, Express, Prisma e SQLite no intuito de servir o front-end web e mobile com os dados para consumo.

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) na versão *16.15.1* e [NPM](https://www.npmjs.com/) na versão *8.5.5*. É possível instalar as ferramentas utilizando os gerenciadores de pacote [Chocolatey](https://chocolatey.org/) em máquinas windows e o [Homebrew](https://brew.sh/index_pt-br) em máquinas MacOS. Faz-se necessário também a instalação de uma aplicação para testes da API criada. As mais conhecidas são [Insomnia](https://insomnia.rest/download) e [Postman](https://www.postman.com/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

## Entidades

- Game
- Ad

### Game

- id
- title
- bannerUrl

### Ad

- id
- gameId
- name
- yearsPlaying
- discord
- weekDays
- hourStart
- hourEnd
- useVoiceChannel
- createdAt

## Casos de uso

- [x] Listagem de games com contagem de anúncios
- [x] Criação de novo anúncio
- [x] Listagem de anúncios por game
- [x] Buscar discord pelo ID do anúncio

### 🎲 Rodando o projeto localmente

```bash
# Clone este repositório
$ git clone https://github.com/Welber33/find_your_duo_server.git

# Acesse a pasta do projeto via terminal/cmd
$ cd pasta_destino_do_do_projeto_clonado

# Abra o projeto no vscode via terminal/cmd
$ code .

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# Execute o comando para fazer as migrations: 
$ npx prisma migrate dev

# Para ter acesso as migrations e os dados do banco, execute:
$ npx prisma studio
```

## Tecnologias 

Foram utilizadas neste projeto as seguintes tecnologias: 

- [NodeJs](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [NPM](https://www.npmjs.com/)
- [Prisma](https://www.prisma.io/)
- [SQLite](https://www.npmjs.com/package/sqlite-ts)


## :memo: License

This project is under the MIT license. See the [LICENSE](LICENSE) for details.