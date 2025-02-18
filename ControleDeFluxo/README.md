## Desafio Controle de Fluxo

Este projeto é um contador de números em Java que recebe dois parâmetros e imprime uma contagem de números entre esses parâmetros.

### Estrutura do Projeto

- `src`: Pasta que contém os arquivos fonte (`Contador.java` e `ParametrosInvalidosException.java`)
- `lib`: Pasta para dependências
- `bin`: Pasta onde os arquivos compilados serão gerados


### Lógica do Programa

1. Solicita ao usuário dois parâmetros inteiros.
2. Verifica se o segundo parâmetro é maior que o primeiro.
3. Se o segundo parâmetro for menor ou igual ao primeiro, lança uma exceção `ParametrosInvalidosException`.
4. Caso contrário, imprime uma contagem de números do primeiro parâmetro até o segundo.