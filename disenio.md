
# Diagrama de Clases

```mermaid
classDiagram
    class BankAccount {
        -string m_customerName
        -double m_balance
        +Debit(double amount)
        +Credit(double amount)
        +CustomerName
        +Balance
    }
```
