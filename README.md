# 🛒 E-Commerce Website with Django

This is a basic e-commerce platform developed using Python and the Django web framework. It allows users to browse products, manage a shopping cart, register/login, and place orders.

## 🌟 Features

- Product catalog with images and details
- Shopping cart (add/remove items)
- User registration and login
- Order placement and confirmation
- Admin panel for managing products and orders

## 🛠️ Technologies Used

- Python 3.x
- Django 3.x or higher
- SQLite (default Django database)
- HTML5, CSS3, Bootstrap 4
- JavaScript (for interactivity)

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system
- pip (Python package installer)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ani-dilanyan/e-commerce-website-with-djago.git
   cd e-commerce-website-with-djago

2. **Create a virtual environment:**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt

4. **Apply migrations:**

   ```bash
   python manage.py migrate

5. **Create a superuser:**

   ```bash
   python manage.py createsuperuser

6. **Run the development server:**

   ```bash
   python manage.py runserver

7. **Access the application:**
   - Open your browser and navigate to http://127.0.0.1:8000/ to view the website.
   - Access the admin panel at http://127.0.0.1:8000/admin/.
  
  ## 📁 Project Structure
  ```csharp
  e-commerce-website-with-djago/
├── manage.py
├── requirements.txt
├── db.sqlite3
├── ecommerce/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── store/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
└── README.md

