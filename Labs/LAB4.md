# LAB 4 - Adicionando Validação para os Dados de Entrada

## Objetivo
Utilizar o GitHub Copilot para implementar validação nos dados do endpoint `POST /livros`.

## Passos

1. Adicione anotações de validação na entidade `Book.java`.
    - Utilize anotações como `@NotBlank`, `@Size` e `@Pattern` para os campos `titulo`, `autor` e `isbn`.

2. Modifique o `BookController.java` para lidar com erros de validação.
    - Adicione tratamento de erros para entradas inválidas.
    - Deixe o Copilot sugerir maneiras de lidar com exceções de validação.

3. Teste a API.
    - Envie uma requisição `POST` com dados inválidos e verifique se a validação funciona corretamente.

---

## Resultado Esperado
A API agora deve rejeitar entradas inválidas no endpoint `POST /livros`.
