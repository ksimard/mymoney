# mymoney

A way to track money for kids without an actual account

```mermaid
erDiagram
  FAMILY ||--o{ MEMBER : has
  MEMBER ||--o{ ACCOUNT : has
  ACCOUNT ||--o{ ENTRY : has
  MEMBER ||--o{ ENTRY : has
  MEMBER ||--|| ALLOWANCE : has
  ALLOWANCE ||--o{ ALLOCATION : has
  ALLOCATION ||--|| ACCOUNT : has
```

