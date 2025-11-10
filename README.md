# 🚀 **Node.js Express CRUD API**

This repository sets up a **RESTful API** using **Express.js**, demonstrating basic **CRUD** operations for user resources.

---

## 🛠️ **Key Features**

| **Topic** | **Key Functionality** |
| :--- | :--- |
| **Server** | **Express.js** setup (`app.js`). |
| **Routing** | Dedicated **CRUD** routes (`/users`, `/users/:id`). |
| **Data Parsing** | `express.json()` **middleware** for processing incoming JSON data into `req.body`. |
| **Architecture** | **Controllers** (`usersController.js`) for separating logic. |

---

## 💻 **Endpoints Overview**

| **Method** | **Route** | **Action** |
| :--- | :--- | :--- |
| **POST** | `/users` | Create User |
| **GET** | `/users` | Get All Users |
| **GET** | `/users/:id` | Get User by ID |
| **PATCH** | `/users/:id` | Update User by ID |
| **DELETE** | `/users/:id` | Delete User by ID |

---

## ⚙️ **Quick Run**

To start the server for development or production, use the scripts defined in `package.json`.

### **1. Setup**

Install project dependencies:
```bash
npm install
```
2. Start Server (Development Mode)
Use the dev script, which typically runs nodemon for hot reloading:
```bash
npm run dev
```
3. Testing
Use the *requests/usersCrud.http* file to test all endpoints (requires the **REST Client** extension in VS Code).
