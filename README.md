# 🧠 SQL Developer Internship – Task 7: Creating Views

This task focuses on the use of **SQL Views** to abstract complex queries, improve security, and make code reusable and readable in the context of an **Online Bookstore** database.

---

## 🎯 Objective

- Learn to create and use SQL views.
- Use `CREATE VIEW` to simplify SELECT statements.
- Apply `WITH CHECK OPTION` to enforce data constraints.
- Query from views like regular tables.

---

## 🧩 Domain: Online Bookstore

This task uses the following tables from the bookstore schema:

- `Users`
- `Orders`
- `Books`
- `Authors`
- `Payments`

---

## 📁 Views Overview

| View Name            | Description                                   |
|----------------------|-----------------------------------------------|
| `UserOrderSummary`   | Shows user name with count of their orders    |
| `BookAuthorView`     | Displays books with their respective authors  |
| `PaidOrdersView`     | Lists orders that have payments made          |
| `TopExpensiveBooks`  | Lists the top 3 most expensive books          |
| `ValidBooksView`     | Books with price > 100 and `WITH CHECK OPTION`|

---
