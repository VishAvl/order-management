# Order Management API

A simple **end-to-end backend application** built using **Java and Spring Boot**.
It exposes REST APIs to create and fetch orders and stores data in a **PostgreSQL (Neon) cloud database**.

---

## 🛠 Tech Stack

* Java 17
* Spring Boot
* Spring Data JPA (Hibernate)
* Maven
* PostgreSQL (Neon)
* GitHub Codespaces
* Postman

---

## 🚀 API Endpoints

### Create Order

* **POST** `/orders`

```json
{
  "productName": "Phone",
  "quantity": 2,
  "price": 500
}
```

### Get All Orders

* **GET** `/orders`

---

## ▶ Run the Application

```bash
./mvnw spring-boot:run
```

Codespaces URL:

```
https://<codespace-name>-8080.app.github.dev
```

---

## 🧪 Testing

* APIs tested using **Postman**
* `/` returns 404 (expected for backend-only apps)

---

## 👤 Author

**Vishruti**
