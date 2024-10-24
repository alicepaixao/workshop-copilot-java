# LAB 3 - Implementando o Método `POST` para Adicionar um Livro

## Objetivo
Utilizar o GitHub Copilot para criar um endpoint que permita adicionar um novo livro.

## Passos

1. Adicione um método `POST` no `BookController.java`.
    - O método deve aceitar um objeto `Livro` no corpo da requisição.
    - Deixe o Copilot sugerir a implementação do método.

2. Persista o novo livro utilizando o `BookRepository`.
    - Salve o novo livro no banco de dados H2.

3. Teste a API.
    - Use o Postman ou `curl` para enviar uma requisição `POST` para `/livros` com os dados de um novo livro.
    - Verifique se o livro foi adicionado ao banco de dados.

---

## Resultado Esperado
Um endpoint funcional `POST /livros` que adiciona um novo livro ao banco de dados.

