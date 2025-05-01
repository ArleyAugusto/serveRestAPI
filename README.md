# 🧪 Testes Automatizados - ServeRest API

Este projeto contém testes automatizados para a API ServeRest, desenvolvidos utilizando o Postman, com execução via Newman e integração com GitHub Actions.

## 🔧 Tecnologias Utilizadas

- **Postman** (para criação das collections de testes)
- **Newman** (para execução via CLI)
- **GitHub Actions** (para CI dos testes)
- **FakerAPI** (geração de massa de dados para usuários)
- **Mockaroo** (geração de massa de dados para produtos)
- **ServeRest** (API utilizada para estudo de testes)

---

## 📌 Endpoints Testados

### 🔹 Usuários

- ✅ Criação de novo usuário com massa de dados gerada via FakerAPI
- ✅ Validação do retorno e status code
- ✅ Atualização do usuário para `administrador: true`
- ✅ Nova busca para verificar alteração aplicada

### 🔹 Login

- ✅ Realização do login com usuário criado
- ✅ Validação de status code
- ✅ Captura do token `authorization` para uso em endpoints protegidos

### 🔹 Produtos

- ✅ Geração de massa com Mockaroo (nome, preço, descrição, quantidade)
- ✅ Cadastro de novo produto com os dados gerados
- ✅ Validação do cadastro e retorno do `_id`
- ✅ Busca do produto cadastrado
- ✅ Exclusão do produto
- ✅ Validação da mensagem de sucesso na exclusão

---

## ⚙️ Execução dos Testes com Newman

O projeto conta com uma action configurada para rodar os testes Newman a cada push. Isso garante que os testes da API sejam executados continuamente e validados automaticamente.

Este projeto foi desenvolvido como parte do meu estudo em testes de API REST. Feedbacks e sugestões são bem-vindos!

Caso queira trocar uma ideia sobre QA, testes automatizados ou a área de qualidade de software:

Arley Augusto - QA em formação
📧 arley.it@icloud.com
💼 www.linkedin.com/in/arleyaugusto

