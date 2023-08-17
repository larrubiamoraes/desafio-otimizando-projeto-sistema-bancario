# desafio-otimizando-projeto-sistema-bancario
Desafio de projeto - Otimizando o Sistema Bancário com Funções Python

Separar as funções existentes de saque, depósito e extrato em funções. Criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária.

- A função saque deve receber os argumentos apenas por nome (keyword only). Sugestão de argumentos: saldo, valor, extrato, limite, numero_saques, limites_saques. Sugestão de retorno: saldo e extrato.
- A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. Sugestão de retorno: saldo e extrato.
- A função extrato deve receber os argumentos por posição e nome (positional only e keyword only). Argumentos posicionais: saldo, argumentos nomeados: extrato.
- Criar usuário (cliente)
O programa deve armazenar os usuários em uma lista, um usuário é composto por:  nome, data de nascimento, CPF e endereço. O endereço é uma string com formato: logradouro, número - bairro - cidade/sigla estado. Deve ser armazenado somente os números do CPF. Não é possível cadastrar 2 usuários com o mesmo CPF.
- Criar conta corrente
O programa deve armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo: "0001". O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.
