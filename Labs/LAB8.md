# LAB 8 - Paginação e Ordenação para Livros

## Objetivo
Utilizar o GitHub Copilot para implementar paginação e ordenação na lista de livros.

## Passos

1. Modifique o método `GET /livros` para suportar paginação e ordenação.
    - Aceite parâmetros de consulta para tamanho da página, número da página e ordem de classificação.

2. Utilize `Pageable` no `BookRepository.java`.
    - Deixe o Copilot sugerir as alterações necessárias para lidar com paginação e ordenação.

3. Teste a API.
    - Use o Postman ou `curl` para testar a paginação e ordenação, enviando requisições como `/livros?page=1&size=5&sort=title`.

---

## Resultado Esperado
Um endpoint funcional `GET /livros` com paginação e ordenação.
