# 🛒 E-Commerce Backend (FastAPI)

A fully functional **E-Commerce REST API** built using **FastAPI**, **SQLAlchemy**, and **PostgreSQL**.  
This backend handles user authentication, product management, orders, shipping, and more — all modularized and production-ready.

---

## 🚀 Features

✅ **User Management**
- Signup / Login  
- Password hashing with bcrypt  
- Role-based access (Admin / Customer)

✅ **Product Management**
- Create, update, delete, and list products  
- Admin-only product modification

✅ **Order System**
- Create and manage customer orders  
- Automatic shipping record creation  
- Order-item relationships handled via ORM

✅ **Shipping Management**
- Create, view, update, and delete shipping details  
- Linked with orders automatically

✅ **Authentication & Authorization**
- JWT-based authentication  
- Secure endpoints for both admin and regular users

✅ **Database**
- PostgreSQL with SQLAlchemy ORM  
- Clean relational model with Foreign Keys

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| Framework | FastAPI |
| ORM | SQLAlchemy |
| Database | PostgreSQL |
| Auth | JWT (PyJWT) |
| Password Hashing | Passlib (bcrypt) |
| Environment Management | python-dotenv |
| Server | Uvicorn |

---
2️⃣ Create and Activate Virtual Environment
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Configure Environment Variables

Create a .env file in the project root:

DATABASE_URL=postgresql://postgres:yourpassword@localhost/ecommerce_db
SECRET_KEY=your_secret_key
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=60
5️⃣ Run the Server
uvicorn app.main:app --reload --port 8088
📘 API Documentation

Once running, open your browser and visit:

Swagger UI → http://127.0.0.1:8088/docs
🧪 Example Endpoints
Create User (Signup)

POST /users/signup

Create Product

POST /products/

Place Order

POST /orders/

Get All Products

GET /products/

🧰 Development Tools

🐍 Python 3.11+

🧩 FastAPI

🗄️ SQLAlchemy

🧾 Alembic (optional for migrations)

🔐 JWT Authentication

💻 Author

👤 Aryan Tyagi
📧 aryantyagi0

🌐 GitHub: https://github.com/aryantyagi0

