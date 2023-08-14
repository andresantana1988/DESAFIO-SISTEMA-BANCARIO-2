### DESAFIO-SISTEMA-BANCARIO-2
Requisitos

Criar uma função para cada operação disponível
Criar uma função de cadastro de cliente
Criar a funcionalidade de conta corrente para ser vinculada ao cliente

A função saque deve receber os argumentos apenas por nome ( Keyword Only). Sugestão: saldo, valor , extrato, limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrato.

A função de depósito deve receber os argumentos apenas por posição(position Only). Sugestão de argumentos: saldo, valor extrato. Sugestão de retorno: saldo, extrato.

A função de extrato deve receber os argumentos por posição e nome ( position Only e Keyword Only). Argumentos posicionais: saldo e argumentos nomeados: extrato.

Função criar usuário.
O programa deve armazenar o usuário em uma lista. O usuário é composto por nome, data de nascimento, CPF e endereço.   O endereço é uma string com o formato: logradouro, número – bairro – cidade/sigla uf. Deve ser armazenados somente números no CPF . Não podemos cadastrar dois usuários com o mesmo CPF.

Função de conta corrente:
O programa deve armazenar a conta em uma lista, uma conta é composta por uma agencia, numero da conta e usuário. O número da conta é sequencial , iniciando em 1. O número da agencia é fixo : “0001”. Um usuário pode ter mais de uma conta, mas uma conta pertence a apenas um usuário.
