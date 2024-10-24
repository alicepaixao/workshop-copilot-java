# LAB 5 - Implementando o Método `PUT` para Atualizar um Livro

## Objetivo
Utilizar o GitHub Copilot para criar um endpoint que atualize livros existentes.

## Passos

1. Adicione um método `PUT` no `BookController.java`.
    - O método deve aceitar um objeto `Livro` e atualizar um livro existente no banco de dados.

2. Utilize o `BookRepository` para encontrar e atualizar o livro.
    - Deixe o Copilot sugerir a lógica para encontrar o livro pelo `id` e atualizar seus detalhes.

3. Teste a API.
    - Use o Postman ou `curl` para enviar uma requisição `PUT` para `/livros/{id}` para atualizar um livro.
    - Verifique se o livro foi atualizado no banco de dados.

---

## Resultado Esperado
Um endpoint funcional `PUT /livros/{id}` que atualiza um livro existente.
