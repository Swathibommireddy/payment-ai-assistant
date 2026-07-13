# API Design

## User APIs

POST /users/register

POST /users/login

GET /users/{id}

---

## Payment APIs

GET /payments

GET /payments/{transactionId}

GET /payments/history

---

## AI APIs

POST /ai/chat

Example

Question

Why did my payment fail?
Response

Your payment failed because the issuing bank declined the transaction due to insufficient balance.

---

## Refund APIs

GET /refunds

GET /refunds/{paymentId}
