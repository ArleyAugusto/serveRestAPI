🧪 Testes de API - Serverest com Postman

Este projeto contém uma coleção de testes automatizados para a API [Serverest](https://serverest.dev/), desenvolvidos no **Postman** com foco na validação de endpoints REST com diferentes cenários, utilizando boas práticas de testes de software.

## 🔧 Ferramentas Utilizadas

- **Postman Vers. WEB** – Criação e execução dos testes de API.
- **Newman** – Execução dos testes via linha de comando.
- **HTMLExtra Reporter** – Geração de relatórios personalizados em HTML.
- **FakerAPI** – Geração dinâmica de massa de testes (e-mails e nomes aleatórios).
- **CSV (Collection Runner)** – Exemplo de execução com massa de testes externa (código comentado, apenas como referência).

---

## 🔗 Endpoints Testados

| Recurso     | Método            | Descrição                             |
|-------------|-------------------|---------------------------------------|
| `/login`    | POST              | Realiza autenticação e retorna token |
| `/usuarios` | POST, GET, PUT, DELETE | CRUD de usuários                   |
| `/produtos` | POST, GET, DELETE | Cadastro e listagem de produtos       |
| `/carrinhos`| POST, GET, DELETE | Criação e remoção de carrinhos        |

---

## ✅ Testes Implementados

- **Validação de Status Code**  
  Confirma se os códigos HTTP estão de acordo com as respostas esperadas.

- **Validação de Schema**  
  Verifica se a estrutura da resposta segue o schema esperado (usando scripts no Postman).

- **Validação de Mensagens**  
  Confirma mensagens de sucesso (ex: "Cadastro realizado com sucesso") e mensagens de erro.

- **Token Dinâmico com Variáveis**  
  O token gerado no login é armazenado e utilizado automaticamente nos demais endpoints que exigem autenticação.

- **Geração de Massa com FakerAPI**  
  Dados dinâmicos são criados para cada execução, evitando conflitos com e-mails e usuários já cadastrados.

- **Execução com CSV**  
  Código comentado incluído na coleção como exemplo de criação em massa

##
E-mail: arley.it@icloud.com
LinkedIn: www.linkedin.com/in/arleyaugusto

