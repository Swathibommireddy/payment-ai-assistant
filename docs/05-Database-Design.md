# Database Design

## Tables

### USER

| Column | Type |
|---------|------|
| id | BIGINT |
| name | VARCHAR |
| email | VARCHAR |
| mobile | VARCHAR |
| created_at | TIMESTAMP |

---

### PAYMENT

| Column | Type |
|---------|------|
| id | BIGINT |
| transaction_id | VARCHAR |
| amount | DECIMAL |
| currency | VARCHAR |
| merchant | VARCHAR |
| status | VARCHAR |
| payment_date | TIMESTAMP |

---

### REFUND

| Column | Type |
|---------|------|
| id | BIGINT |
| payment_id | BIGINT |
| refund_amount | DECIMAL |
| refund_status | VARCHAR |
| refund_date | TIMESTAMP |
