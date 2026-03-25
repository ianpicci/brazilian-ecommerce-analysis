# Modelo de Dados - Olist E-commerce

## Visão Geral

Dataset de e-commerce brasileiro contendo pedidos, clientes, produtos, vendedores e avaliações.

---

## Tabelas

### orders

Tabela principal de pedidos

- order_id (PK)
- customer_id (FK)
- order_status
- order_purchase_timestamp

---

### order_items

Itens de cada pedido

- order_id (FK)
- product_id (FK)
- seller_id (FK)
- price
- freight_value

---

### customers

Informações dos clientes

- customer_id (PK)
- customer_city
- customer_state

---

### products

Informações dos produtos

- product_id (PK)
- product_category_name

---

### sellers

Informações dos vendedores

- seller_id (PK)
- seller_city
- seller_state

---

### order_payments

Pagamentos dos pedidos

- order_id (FK)
- payment_type
- payment_value

---

### order_reviews

Avaliações dos pedidos

- order_id (FK)
- review_score
