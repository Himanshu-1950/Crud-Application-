
# 🧑‍💼 Employee CRUD App

A simple Django-based web application for performing CRUD (Create, Read, Update, Delete) operations on employee records.

## 🚀 Features

- Add new employees
- View employee list
- Edit employee details
- Delete employee records
- MySQL database integration
- Clean and responsive UI

## 🛠️ Tech Stack

- Python 3
- Django
- MySQL
- HTML, CSS
- Bootstrap (optional, if you used it)

## 🔧 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/employee-crud-app.git
   cd employee-crud-app
   ```

2. **Create & activate virtual environment**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Update Database Configuration**
   - Open `settings.py`
   - Update `DATABASES` section with your MySQL credentials

5. **Run Migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. **Start Development Server**
   ```bash
   python manage.py runserver
   ```

7. **Visit the App**
   ```
   http://127.0.0.1:8000/
   ```

## 📂 Project Structure

```
employee-crud-app/
│
├── app/                # Main Django app
├── project/            # Project settings
├── templates/          # HTML files
├── static/             # CSS/JS/static files
├── db.sqlite3          # Database (if using SQLite)
├── manage.py
└── README.md
```

## 💡 Future Enhancements

- Add user authentication
- Search and filter employee records
- Deploy on cloud (Render / PythonAnywhere / Heroku)

---

## 📷 Screenshots

### ➕ Add Employee Page  
![add employee](https://github.com/user-attachments/assets/7ae5f54c-3db6-4168-8667-088bb1fe0bfd)


### 📋 Employee List Page  
![employee list](https://github.com/user-attachments/assets/d1087a0a-ad4c-4220-9aea-c4ae4afa0c13)


### ✏️ Update Employee Page  
![update details](https://github.com/user-attachments/assets/19bf2060-d1a8-4b3b-8fbf-4c67acbf4d80)



---

> Built with 💻 using Django.
