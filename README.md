# Cash Machine

Este é um projeto de simulador de caixa eletrônico desenvolvido em Python. O projeto permite a criação de clientes, abertura de contas correntes, depósitos, saques e visualização de extratos.

O projeto é estruturado em classes Python para representar clientes, contas correntes, transações e histórico de transações. Utiliza herança e classes abstratas para manter o código organizado e reutilizável.

### Classes Principais:

Cliente: Representa um cliente com informações pessoais e lista de contas associadas.

Conta: Classe base para contas correntes, com métodos para sacar, depositar e consultar saldo.

ContaCorrente: Subclasse de Conta que adiciona limites específicos de saque.

Transacao: Classe abstrata para representar transações, com subclasses como Deposito e Saque.

## 🚀 Tecnologia

- ⚡ Python é uma linguagem de programação de alto nível, interpretada de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte.

## ✋🏻 Pré-requisitos

- [git](https://git-scm.com/downloads): Ferramenta para gerenciar o código-fonte

- [Visual Studio Code](https://code.visualstudio.com/): Editor de Código Fonte

- [Python 3.x](https://www.python.org/downloads/release/python-3100/): Versão do python

## :hammer_and_wrench: Antes de iniciar o projeto.

No diretório do projeto, execute o script:

- `python3 cash.py`

## Funcionalidades

O simulador de caixa eletrônico bancário permite ao usuário:

- Cadastro de Clientes: Permite cadastrar novos clientes informando nome, CPF, data de nascimento e endereço.

- Abertura de Contas: Clientes podem abrir novas contas correntes associadas ao seu cadastro.

- Depósitos: Realização de depósitos em uma conta corrente específica.

- Saques: Realização de saques, considerando limites de saque e saldo disponível na conta.

- Extrato: Exibição do extrato da conta corrente, mostrando todas as transações realizadas.