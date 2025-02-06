# Desafio: Controle de Fluxo - Bootcamp Bradesco Java Cloud Native

Este repositório contém a solução para o desafio **Controle de Fluxo**, parte do **Bootcamp Bradesco Java Cloud Native** na plataforma **[DIO (Digital Innovation One)](https://www.dio.me/)**.

## Descrição do Desafio

O desafio consiste na implementação de um programa Java que recebe dois números inteiros como entrada e imprime uma contagem baseada na diferença entre eles. Caso o primeiro número seja maior que o segundo, o programa deve lançar uma exceção personalizada.

## Implementação

O programa está dividido em duas classes principais:

### 1. `Contador.java`

Esta classe principal solicita ao usuário que insira dois números, realiza a contagem entre eles e trata exceções quando necessário.

### 2. `ParametrosInvalidosException.java`

Esta classe define uma exceção personalizada para lidar com erros de entrada de dados.

## Como Executar o Programa

1. Clone este repositório ou copie os arquivos para o seu ambiente local.
2. Compile os arquivos Java:
   ```sh
   javac Contador.java ParametrosInvalidosException.java
   ```
3. Execute o programa:
   ```sh
   java Contador
   ```
4. Insira os valores solicitados pelo terminal.

## Problema Resolvido

- O programa garante que o segundo número seja sempre maior que o primeiro, evitando entradas inválidas.
- A exceção personalizada `ParametrosInvalidosException` melhora a legibilidade do código e facilita a depuração.

## Tecnologias Utilizadas

- Java 21
- IDE recomendada: IntelliJ IDEA, VS Code ou Eclipse

## Autor
Desafio proposto pelo Bootcamp **Bradesco Java Cloud Native** na plataforma **DIO**.

---

Qualquer sugestão ou melhoria é bem-vinda! 🚀

