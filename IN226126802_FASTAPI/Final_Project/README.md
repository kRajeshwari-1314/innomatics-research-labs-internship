# 🍽️ Food Delivery API – FastAPI Project

## 📖 Project Overview
This project is a backend application developed using FastAPI as part of internship training. It represents a simple food delivery system where users can browse menu items, add food to a cart, and place orders. The project demonstrates how real-world backend systems work using REST APIs.

---

## 🚀 Key Features
- Menu management (Add, Update, Delete food items)
- View all food items and get item by ID
- Filter menu by category and availability
- Search food items using keywords
- Sort menu based on price
- Pagination for large data
- Cart system (Add, Update, Remove items)
- Order system (Checkout and view orders)
- Input validation using Pydantic
- API testing using Swagger UI

---

## 🛠️ Technologies Used
- Python 3
- FastAPI
- Pydantic
- Uvicorn

---

## ⚙️ How to Run the Project

### 1. Install Dependencies
pip install -r requirements.txt

### 2. Run the Server
uvicorn main:app --reload

### 3. Open in Browser
http://127.0.0.1:8000/docs

---

## 📂 Project Structure
FINAL_PROJECT/
├── main.py
├── requirements.txt
├── README.md
└── screenshots/

---

## 🔗 API Endpoints

### Menu APIs
- GET /menu → Get all items  
- GET /menu/{id} → Get item by ID  
- POST /menu → Add new item  
- PUT /menu/{id} → Update item  
- DELETE /menu/{id} → Delete item  

### Advanced APIs
- GET /menu/filter → Filter items  
- GET /menu/search → Search items  
- GET /menu/sort → Sort by price  
- GET /menu/paginate → Pagination  

### Cart APIs
- POST /cart/add → Add item to cart  
- GET /cart → View cart  
- PUT /cart/update → Update cart  
- DELETE /cart/{id} → Remove item  
- DELETE /cart/clear → Clear cart  

### Order APIs
- POST /cart/checkout → Place order  
- GET /orders → View all orders  
- GET /orders/{id} → View single order  

---

## 🔄 Workflow
1. User views menu  
2. Adds items to cart  
3. Updates or removes items  
4. Proceeds to checkout  
5. Order is created and stored  

---

## 📸 Screenshots
All API outputs are available in the **screenshots** folder.

---

## 🎯 Learning Outcomes
- Understanding FastAPI framework  
- Building RESTful APIs  
- Implementing CRUD operations  
- Designing real-world workflows  
- Testing APIs using Swagger UI  

---

## 👩‍💻 Author
**Kuruva Rajeshwari**
