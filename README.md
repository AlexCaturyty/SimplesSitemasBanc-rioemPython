# Simulador Bancário Simples em Python

Este é um projeto simples de um simulador bancário desenvolvido em Python, onde o usuário pode realizar operações como depósitos, saques e visualizar o extrato da conta.

## Funcionalidades

O simulador oferece as seguintes funcionalidades:

- **Depositar:** Permite ao usuário depositar valores na conta.
- **Sacar:** Permite ao usuário sacar dinheiro da conta, respeitando o saldo disponível, limite de saque e número máximo de saques permitidos por dia.
- **Extrato:** Exibe um extrato detalhado das operações realizadas (depósitos e saques), além do saldo disponível na conta.
- **Sair:** Finaliza o simulador.

### Regras de Negócio

1. O saldo inicial da conta é de R$ 0,00.
2. O usuário pode realizar até **3 saques** por dia.
3. O limite de saque por operação é de **R$ 500,00**.
4. Caso o saldo da conta seja insuficiente ou o limite de saques seja excedido, o simulador exibe mensagens apropriadas.
