
```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : 주문
    ORDER ||--|{ ITEM : 주문상품
    ITEM ||--o{ SUPPLIER : 공급업체
