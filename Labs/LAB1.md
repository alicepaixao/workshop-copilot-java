# LAB 1 - Criando uma Nova API de Livros em Java

## Objetivo
Demonstrar o uso do GitHub Copilot para criar uma API básica com Spring Boot e um endpoint inicial.

## Passos

1. Crie um novo projeto Spring Boot.
    - Utilize o Spring Initializr ou sua IDE favorita para criar um novo projeto Spring Boot.
    - Adicione as dependências: Spring Web, Spring Data JPA e H2 Database.

2. Crie um `BookController.java` na pasta `controller`.
    - Use o Copilot para gerar o código de um controlador REST com um endpoint `/livros`.

3. Adicione um método `GET` para retornar uma lista de livros.
    - Adicione um método `List<Book>` e deixe o Copilot sugerir alguns dados de exemplo.

4. Teste a aplicação.
    - Execute a aplicação Spring Boot e use o Postman ou `curl` para testar o endpoint.
    - Verifique se uma lista de livros em formato JSON é retornada.

---

## Resultado Esperado
Uma API básica que retorna uma lista de livros quando o endpoint `/livros` é acessado.
