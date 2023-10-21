# Contador Java

Este é um simples programa Java chamado "Contador" que solicita ao usuário dois parâmetros e, em seguida, imprime números entre esses parâmetros.

## Funcionalidade

- O programa começa importando a classe `Scanner` para receber entrada do usuário.

- Dentro do método `main`:
  - Um objeto `Scanner` chamado `terminal` é criado para ler a entrada do usuário.
  - O usuário é solicitado a inserir o primeiro parâmetro, e o valor é armazenado na variável `parametroUm`.
  - O usuário é solicitado a inserir o segundo parâmetro, e o valor é armazenado na variável `parametroDois`.
  - Em seguida, o programa entra em um bloco `try-catch`, onde verifica se o primeiro parâmetro é maior que o segundo:
    - Se `parametroUm` for maior que `parametroDois`, o programa lança uma exceção personalizada chamada `ParametrosInvalidosException` com a mensagem de erro "O segundo parâmetro deve ser maior que o primeiro".
    - Se a verificação acima não gera uma exceção, o programa chama a função `contar` com os parâmetros fornecidos.
  - O bloco `catch` captura qualquer exceção do tipo `ParametrosInvalidosException` que possa ser lançada e exibe a mensagem de erro correspondente.
  - Finalmente, o objeto `Scanner` é fechado no bloco `finally` para evitar vazamentos de recursos.

- A função `contar` é definida para imprimir números a partir do primeiro parâmetro até o segundo parâmetro, usando um loop `for`.
