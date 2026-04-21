# Smart Inventory Management System (Backend)

### 🚀 Project Overview
This is a robust **RESTful API** built with **Java Spring Boot** designed to automate inventory tracking. The system features "Smart" stock monitoring, which identifies products falling below a specific safety threshold and prepares data for automated alerts.

### ✨ Key Features
* **Inventory CRUD:** Full ability to Create, Read, Update, and Delete products.
* **Smart Low-Stock Filter:** A specialized endpoint that automatically identifies items requiring restock based on a `minThreshold`.
* **Global Exception Handling:** Clean, professional error responses using `@ControllerAdvice` for enhanced API reliability (404 Not Found handling).
* **Automated Logic:** Integrated service logic to trigger alerts when stock levels are critical.

### 🛠️ Tech Stack
* **Backend:** Java 17+, Spring Boot 3.x
* **Data:** Spring Data JPA, Hibernate
* **Database:** MySQL
* **Testing:** Postman

### 📂 API Endpoints
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `POST` | `/api/products` | Add a new item to inventory |
| `GET` | `/api/products` | Retrieve all inventory items |
| `GET` | `/api/products/{id}` | Get specific product details by ID |
| `GET` | `/api/products/low-stock` | **Smart Feature:** Filter all low-stock items |
| `DELETE` | `/api/products/{id}` | Remove an item from the database |

### ⚙️ Setup & Installation
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/dikshabhor02/smart-inventory-backend.git](https://github.com/dikshabhor02/smart-inventory-backend.git)
