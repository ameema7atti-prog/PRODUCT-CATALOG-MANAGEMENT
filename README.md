# Product Catalog Management (Syntecxhub Internship - Week 2)

A feature-rich RESTful API backend built with **Node.js**, **Express**, and **MongoDB** for managing a product catalog, equipped with search filters, pagination, input validation, and advanced MongoDB aggregation pipelines[cite: 5, 7].

This project is part of the **Syntecxhub Web Development Internship Program**[cite: 1, 5].

---

## 🚀 Features
- **CRUD Functionality**: Create, read, update, and delete catalog items[cite: 7].
- **Search & Filtering**: Search products dynamically by name or filter precisely by category[cite: 7].
- **Pagination**: Efficiently control data loading limits using query parameters (`page` and `limit`)[cite: 7].
- **Advanced Querying**: Uses MongoDB Aggregation (`/api/products/stats`) to evaluate category pricing averages and stock totals[cite: 7].
- **Validation**: Strict schema checks and inputs validation[cite: 7].

---

## 📌 API Endpoints Overview

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **POST** | `/api/products` | Add a new product to the catalog |
| **GET** | `/api/products` | Get products with optional search, category filters, and pagination[cite: 7] |
| **GET** | `/api/products/stats` | Get category inventory insights via MongoDB aggregation[cite: 7] |
| **PUT** | `/api/products/:id` | Update product details by ID |
| **DELETE** | `/api/products/:id` | Remove a product by ID |

---

## ⚙️ Setup & Local Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/Syntecxhub_Product_Catalog.gitt](https://github.com/your-username/Syntecxhub_Product_Catalog.gitt)
   cd Syntecxhub_Product_Catalog
