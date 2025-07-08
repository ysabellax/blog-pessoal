
# 💗 Blog Pessoal - NestJS API

API REST desenvolvida com **NestJS**, estruturada seguindo o padrão **MVC (Model-View-Controller)** e utilizando **TypeORM** para acesso ao banco de dados relacional.

---

## 🚀 Tecnologias utilizadas

- [NestJS](https://nestjs.com/)
- [TypeORM](https://typeorm.io/)
- [MySQL / PostgreSQL / SQLite](https://www.npmjs.com/package/mysql2)
- [JWT (Autenticação)](https://jwt.io/)
- [Swagger (Documentação)](https://swagger.io/tools/swagger-ui/)
- [Jest (Testes)](https://jestjs.io/)
- ESLint + Prettier

---

## 📁 Estrutura do Projeto

```
src/
├── auth/                 # Módulo de autenticação (JWT, login)
├── data/services/        # Configurações de ambiente (prod/dev)
├── postagem/             # CRUD de postagens
│   ├── controllers/
│   ├── entities/
│   └── services/
├── tema/                 # CRUD de temas
├── usuario/              # CRUD de usuários
├── app.module.ts         # Módulo principal
├── main.ts               # Arquivo de bootstrap
test/                     # Testes unitários e e2e
```

---

## ⚙️ Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (recomendado: versão 18 ou superior)
- [npm](https://www.npmjs.com/) 
- Banco de dados:
  - MySQL / PostgreSQL / SQLite 

---

## 📦 Instalação

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/blogpessoal.git
cd blogpessoal

# 2. Instale as dependências
npm install

---

## ▶️ Executando o projeto

### Ambiente de desenvolvimento:
```bash
npm run start:dev
```

## 📄 Documentação Swagger

Após iniciar o servidor, acesse:

```
http://localhost:4000
```

Lá você poderá testar todos os endpoints da API com autenticação JWT e ver descrições das rotas.

---

## ✅ Testes

- Testes unitários:
```bash
npm run test
```

```bash
npm run test:cov
```

- Testes e2e (end-to-end):
```bash
npm run test:e2e
```

---

## 🧠 Funcionalidades

- Cadastro e login de usuários
- Autenticação com JWT
- CRUD de Postagens
- CRUD de Temas
- Relacionamento entre Postagem e Tema
- Documentação automática com Swagger
- Validação com `class-validator`
- Suporte para múltiplos bancos (MySQL, PostgreSQL, SQLite)

---

## 📌 Boas práticas adotadas

- Separação por módulos (estrutura modularizada)
- Uso de `services` para regra de negócio
- Configuração dinâmica do TypeORM (`prod.service.ts`, `dev.service.ts`)

---

## 👩🏼‍💻 Autora

**Ysabella Santos**  
Desenvolvedora Full Stack | NestJS • TypeScript • SQL  
[LinkedIn](https://www.linkedin.com/in/ysa-santos/) 

---

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

---

## 📃 Licença

Este projeto está sob a licença **UNLICENSED** (projeto acadêmico ou privado).

