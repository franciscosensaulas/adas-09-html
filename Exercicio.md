# Exercício: Tela de compra de tickets

Arquivo: `Tela de compra de tickets.html`

## Documentos

### Responsável

| Campo              | Tipo    | Validações                                        |
| ------------------ | ------- | ------------------------------------------------- |
| Nome               | `text`  | `required`, mínimo 5, máximo 50 caracteres        |
| CPF                | `text`  | `required`, mínimo 14, máximo 14, com `pattern`   |
| Telefone           | `tel`   | `required`                                        |
| E-mail             | `email` | `required`                                        |
| Data de nascimento | `date`  | `required`                                        |

### Criança

| Campo              | Tipo   | Validações                                      |
| ------------------ | ------ | ----------------------------------------------- |
| Nome               | `text` | `required`, mínimo 5, máximo 50 caracteres      |
| CPF                | `text` | `required`, mínimo 14, máximo 14, com `pattern` |
| Data de nascimento | `date` | `required`                                      |

## Forma de pagamento

### Cartão de crédito

| Campo            | Tipo     | Validações                                  |
| ---------------- | -------- | ------------------------------------------- |
| Número do cartão | `text`   | com `pattern`                               |
| Validade (mês)   | `number` | mínimo 1, máximo 12                         |
| Validade (ano)   | `number` | mínimo 2026, máximo 2036 (ano atual + 10)   |
| CVC              | `number` | mínimo 1, máximo 999                        |
| Nome no cartão   | `text`   | `required`, mínimo 5, máximo 50 caracteres  |

## Valor

Apresentar o valor total de **R$ 103,97**.
