
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
Add Employee![Screenshot 2025-04-10 202640](https://github.com/user-attachments/assets/2c287246-d168-4484-99a1-50c3f4da63e8)



### 📋 Employee List Page  
Employee List![Screenshot 2025-04-10 202820](https://github.com/user-attachments/assets/289ee903-a34c-43a0-818b-8a4307ea8a4f)



### ✏️ Update Employee Page  
Update Details![Screenshot 2025-04-10 202842](https://github.com/user-attachments/assets/1681fa27-b7e0-4c57-8429-b382c671d96a)




---

> Built with 💻 using Django.
