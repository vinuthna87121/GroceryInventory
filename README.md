# 🛒 Grocery Inventory API

This is a Spring Boot REST API for managing a grocery inventory system. It allows CRUD operations on grocery items, supports category-based queries, and includes aggregation endpoints like group-by-category.

---

## ✨ Features

- Add, update, delete grocery items
- Get groceries by category or ID
- Bulk insert support
- Group groceries by category
- JSON-based RESTful API

---

## 🔗 API Endpoints

| Method | URL                        | Description                         |
|--------|----------------------------|-------------------------------------|
| GET    | `/grocery`                 | Get all grocery items               |
| GET    | `/grocery/id/{id}`         | Get grocery item by ID              |
| GET    | `/grocery/category/{category}` | Get groceries by category     |
| POST   | `/grocery/add`             | Add a single grocery item           |
| POST   | `/grocery/addbulk`         | Add multiple grocery items          |
| PUT    | `/grocery/update/{id}`     | Update grocery item by ID           |
| DELETE | `/grocery/delete/{id}`     | Delete grocery item by ID           |
| GET    | `/grocery/groupByCategory` | Get count of groceries by category  |

---

