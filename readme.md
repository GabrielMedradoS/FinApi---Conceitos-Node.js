## FinApi - Financeiro

#### Lembrando de conceito basicos do node.js

### Requisitos

- [x] Deve ser possível criar uma conta
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível realizar um deposito
- [x] Deve ser possível buscar o extrato bancário do cliente por data
- [x] Deve ser possível atualizar dados da conta do cliente
- [] Deve ser possível deletar uma conta

### Regras de négocio

- [x] Não deve ser possível cadastra uma conta com CPF já existente
- [x] Não deve ser possível fazer deposito em uma conta nao existente
- [x] Não deve ser possível buscar extrato em uma conta nao existente
- [x] Não deve ser possível fazer saque em uma conta nao existente
- [x] Não deve ser possível excluir uma conta não existente
- [x] Não deve ser possível fazer saque quando o saldo for insuficiente
