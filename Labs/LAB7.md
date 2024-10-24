# LAB 7 - Buscando Livros por Título

## Objetivo
Utilizar o GitHub Copilot para criar um endpoint que permita buscar livros pelo título.

## Passos

1. Adicione um método `GET` no `BookController.java`.
    - O método deve aceitar um parâmetro `title` e retornar livros com títulos correspondentes.

2. Modifique o `BookRepository.java` para adicionar um método de consulta.
    - Use o Copilot para sugerir uma consulta que encontre livros pelo título.

3. Teste a API.
    - Use o Postman ou `curl` para enviar uma requisição `GET` para `/livros/search?title=palavra-chave`.
    - Verifique se a API retorna livros com títulos correspondentes.

---

## Resultado Esperado
Um endpoint funcional `GET /livros/search` que busca livros pelo título.
