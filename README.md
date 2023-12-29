# mymoney

A way to track money for kids without an actual account

```mermaid
erDiagram
  FAMILY ||--|{ MEMBER : has
  MEMBER ||--o{ ACCOUNT : has
  ACCOUNT ||--o{ ENTRY : has
  MEMBER ||--o{ ENTRY : has
  MEMBER ||--|| SCHEDULE : has
  SCHEDULE ||--|{ ALLOCATION : has
  ALLOCATION |o--|| ACCOUNT : has
  MEMBER ||--o{ WISH : has
  WISH ||--o| ACCOUNT : has
  WISH }o--o{ LIST : has
```

- Lists can be shared via secure link (no need for viewer to sign up for account)
- Wishlist feature can be standalone
- Wishlist looks like a store? link to actual sites, but don't have to
- schedule can be flat dollar value, or percentage (to teach about insurance)
