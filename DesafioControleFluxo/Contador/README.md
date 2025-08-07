# Desafio Controle de Fluxo

Este projeto é uma solução para o desafio do módulo de **Controle de Fluxo** da trilha **Java Básico** da DIO (Digital Innovation One). O objetivo é criar um programa que receba dois números inteiros via terminal, valide se o segundo número é maior que o primeiro e imprima os números incrementados com base na diferença entre eles.

## Estrutura do Projeto

- **Contador.java**: Classe principal que contém a lógica do programa, incluindo a leitura dos parâmetros via terminal, validação e impressão dos números incrementados.
- **ParametrosInvalidosException.java**: Classe que define uma exceção personalizada para tratar casos em que o primeiro parâmetro é maior que o segundo.

## Funcionalidades

1. **Leitura de Parâmetros**: O programa solicita dois números inteiros do usuário via terminal.
2. **Validação**: Verifica se o primeiro número é maior que o segundo. Caso seja, lança a exceção `ParametrosInvalidosException` com a mensagem: "O segundo parâmetro deve ser maior que o primeiro".
3. **Contagem e Impressão**: Calcula a diferença entre os dois números e imprime os números de 1 até o valor da diferença, no formato "Imprimindo o número X".

## Como Executar

1. Certifique-se de ter o Java (JDK) instalado em sua máquina.
2. Clone ou baixe este projeto para sua máquina.
3. Compile os arquivos Java:
   ```bash
   javac Contador.java ParametrosInvalidosException.java

## Execute o programa:

``` java Contador ```

**Insira os dois números inteiros quando solicitado pelo programa.**

## Exemplo de Uso

**Entrada:**
```bash 
Digite o primeiro parâmetro:
12 
Digite o segundo parâmetro:
30 
```
**Saída:**
```bash 
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18
```
**Entrada Inválida:**
```bash
Digite o primeiro parâmetro:
30
Digite o segundo parâmetro:
12
```
**Saída:**
```bash
O segundo parâmetro deve ser maior que o primeiro
```
## Tecnologias Utilizadas
**Java:** Linguagem de programação utilizada para implementar a lógica do programa.

**Scanner:** Classe do Java para leitura de entrada do usuário via terminal.

## Autor
**Desenvolvido com base no desafio proposto por Gleyson Sampaio na plataforma DIO.**
## Licença
**Este projeto é apenas para fins educacionais e segue as diretrizes da plataforma DIO.**

## Desafio vencido por João Cruz ☕









