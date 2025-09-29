# Accounts CLI

Uma aplicação de linha de comando (CLI) simples para gerenciamento de contas, permitindo criar contas, depositar fundos, sacar e verificar o saldo. Desenvolvido com Node.js, `inquirer` para interação com o usuário e `chalk` para estilização de saída no console.

## Funcionalidades

O sistema oferece as seguintes opções no menu principal:

1.  **Criar conta**: Permite que o usuário crie uma nova conta.
2.  **Consultar Saldo**: Permite verificar o saldo atual de uma conta existente.
3.  **Depositar**: Permite adicionar um valor ao saldo de uma conta.
4.  **Sacar**: Permite retirar um valor do saldo de uma conta (com verificação de saldo).
5.  **Sair**: Encerra a aplicação.

## Pré-requisitos

* [Node.js](https://nodejs.org/) (versão 14 ou superior)

## Instalação

1.  Clone este repositório:
    ```bash
    git clone <URL_DO_SEU_REPOSITÓRIO>
    cd accounts_node
    ```
2.  Instale as dependências do projeto:
    ```bash
    npm install
    ```

## Como Executar

Inicie a aplicação usando o script `start` definido no `package.json`:

```bash
npm start
