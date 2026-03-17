# Database Documentation

The database stores user and invoice information.

## Users Table
Fields:
- user_id
- name
- email
- password

## Invoices Table
Fields:
- invoice_id
- user_id
- invoice_number
- invoice_date
- total_amount

## Items Table
Fields:
- item_id
- invoice_id
- item_name
- quantity
- price

Relationships:
One user can upload multiple invoices.
One invoice can contain multiple items.
