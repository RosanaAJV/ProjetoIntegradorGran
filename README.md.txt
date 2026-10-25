Faculdade Gran

Link: https://faculdade.grancursosonline.com.br/

Curso: Análise e Desenvolvimento de Sistemas

Disciplina: Projeto Integrador

📌 Descrição do Projeto

Este projeto consiste no desenvolvimento de uma aplicação web completa (Full Stack) com arquitetura dividida em Backend (API REST em Node.js com SQLite) e Frontend (Interface web) para gestão de Produtos, Fornecedores e Associação de Produtos com Fornecedores.

🚀 Guia de Inicialização do Projeto

1. Inicializar o Projeto Node.js

Para iniciar a estrutura do projeto no Backend, execute o comando abaixo no terminal da pasta raiz:

npm init -y


Nota: Esse comando iniciará um assistente (ou gerará automaticamente com a flag -y) para a criação do arquivo package.json, que guarda as meta-informações do projeto e a lista de dependências exigidas.

2. Estrutura Principal

Crie o arquivo principal da aplicação chamado app.js na raiz do projeto.

🛠️ Backend - Estrutura de Controladores (Controllers)

O backend utiliza a base de dados SQLite para testes locais rápidos e armazena os dados através das seguintes entidades e seus respectivos controllers: