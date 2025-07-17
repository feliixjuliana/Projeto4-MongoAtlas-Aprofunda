# 🚀 Biblioteca TypeScript com conexão MongoDB

Este projeto tem como objetivo aprofundar os conceitos de **MongoDB**, aplicando-os em uma estrutura de projeto robusta e escalável, com foco na criação de um **sistema de biblioteca**. 

## Funcionalidades
A API oferece os seguintes endpoints para interação com a biblioteca:

GET /books: Lista todas os livros.

POST /books: Cria um novo livro.

UPDATE /book:id Edita uma parte do livro

Delete /book:id Apaga um livro cadastrado

🛠️ Conteúdo e Tecnologias

O projeto foi estruturado com base nos seguintes conceitos e ferramentas:

* MongoDB

* Clean Architecture

* TypeScript

* Express.js: Framework web para Node.js, utilizado para configurar o servidor e as rotas.

* Uuid: Usado para gerar ids aleatórios nos livros cadastrados.

* Cors

* Testes com Thunder Client/Postman: As funcionalidades da API foram testadas utilizando clientes HTTP como Thunder Client ou Postman.

-----

## Acessando: 

Siga estas instruções para ter uma cópia do projeto funcionando na sua máquina local para desenvolvimento e testes.

### Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas:

  * **Node.js** (versão LTS recomendada)
  * **npm** ou **Yarn** (gerenciador de pacotes)
  * **TypeScript** (geralmente instalado junto com o Node.js ou via npm)

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/feliixjuliana/Projeto2-Clean-Architecture-Aprofunda.git
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd Projeto2-Clean-Architecture-Aprofunda
    ```
3.  **Navegue até o projeto:**
    ```bash
    cd api-clean-architecture
    ```
4.  **Instale as dependências:**
    ```bash
    npm install
    ```
5.  **Execute o projeto:**
    ```bash
    npm run start
    ```
    O servidor deverá iniciar, geralmente em `http://localhost:3000`.

-----

## 📸 Demonstração

### Enviando para o banco

  * **Endpoint:** `http://localhost:3000/books`
  * <img width="1349" height="695" alt="image" src="https://github.com/user-attachments/assets/48bac792-655a-4050-bebf-029c45a63a52" />

### No banco

  * **Endpoint:** `http://localhost:3000/books`
  * <img width="1702" height="641" alt="image" src="https://github.com/user-attachments/assets/f89f3e72-b68a-4f81-a3f5-5897cda19854" />



