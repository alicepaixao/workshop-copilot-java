# LAB 6 - Implementando o Método `DELETE` para Remover um Livro

## Objetivo
Utilizar o GitHub Copilot para criar um endpoint que exclua livros.

## Passos

1. Adicione um método `DELETE` no `BookController.java`.
    - O método deve excluir um livro com base no seu `id`.

2. Utilize o `BookRepository` para remover o livro.
    - Deixe o Copilot sugerir a lógica para deletar o livro pelo `id`.

3. Teste a API.
    - Use o Postman ou `curl` para enviar uma requisição `DELETE` para `/livros/{id}`.
    - Verifique se o livro foi removido do banco de dados.

---

## Resultado Esperado
Um endpoint funcional `DELETE /livros/{id}` que remove um livro do banco de dados.
