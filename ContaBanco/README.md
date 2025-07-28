# 🏦 ContaTerminal - Simulador de Criação de Conta Bancária

Bem-vindo ao projeto **ContaTerminal**! Este é um desafio prático de Java desenvolvido como parte da trilha de cursos da **Digital Innovation One (DIO)**.

<p align="center">
  <img src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png" alt="Logo da DIO" width="150"/>
</p>

## 🚀 Sobre o Projeto

O `ContaTerminal` é um programa Java simples que simula o processo de abertura de uma conta bancária através de uma interação direta via terminal (console). Ele solicita ao usuário informações essenciais como número da conta, agência, nome do cliente e saldo inicial, e em seguida, exibe uma mensagem de boas-vindas formatada com todos os dados inseridos.

Este projeto é ideal para quem está dando os primeiros passos em Java e deseja solidificar conhecimentos sobre:

* **Sintaxe Básica de Java**: Declaração de variáveis, tipos de dados (`int`, `String`, `double`).
* **Interação com o Usuário**: Utilização da classe `Scanner` para leitura de dados do terminal.
* **Manipulação de Strings**: Concatenação e formatação de mensagens.
* **Boas Práticas**: Uso do `try-with-resources` para gerenciamento seguro de recursos (como o `Scanner`).

## ✨ Funcionalidades

* Solicitação interativa de dados da conta (Número, Agência, Nome do Cliente, Saldo).
* Exibição de uma mensagem de confirmação personalizada com os dados inseridos.

## 🛠️ Tecnologias Utilizadas

* **Java 11+** (ou versão compatível)
* **IDE de Desenvolvimento**: VS Code, IntelliJ IDEA ou Eclipse

## ▶️ Como Executar o Projeto

1.  **Clone o Repositório** (se estiver em um repositório Git) ou baixe os arquivos do projeto.
2.  **Abra o Projeto** em sua IDE Java favorita.
3.  **Compile a classe `ContaTerminal.java`**.
4.  **Execute a classe `ContaTerminal`** (método `main`).

Você será guiado pelo terminal para inserir as informações da conta.

```bash
# Exemplo de execução via terminal (após compilação)
$ java ContaTerminal

# Saída esperada no início:
Por favor, digite o número da Conta !
# ... e assim por diante