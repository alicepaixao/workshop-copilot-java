# LAB 2 - Adicionando uma Entidade Livro e Suporte a Banco de Dados

## Objetivo
Utilizar o GitHub Copilot para criar a entidade `Livro` e persistir dados usando JPA.

## Passos

1. Crie a entidade `Book.java` na pasta `model`.
    - A entidade deve ter campos como `id`, `titulo`, `autor`, e `isbn`.
    - Deixe o Copilot sugerir o código para esta entidade.

2. Adicione o repositório `BookRepository.java` na pasta `repository`.
    - Estenda `JpaRepository<Book, Long>`.
    - Use o Copilot para gerar o código básico do repositório.

3. Modifique o `BookController.java` para utilizar o repositório.
    - Atualize o endpoint `/livros` para retornar livros do banco de dados.

4. Teste a API.
    - Execute a aplicação Spring Boot.
    - Verifique se os livros são recuperados do banco de dados H2.

---

## Resultado Esperado
O endpoint `/livros` agora busca dados do banco de dados.
