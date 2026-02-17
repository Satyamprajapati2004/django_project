# Employee Management System

Yeh ek web-based **Employee Management System** hai jise **Django** framework ka use karke banaya gaya hai. Is application ka main maqsad organization mein employees ki details, departments, aur unke roles ko efficiently manage karna hai.



## 🚀 Features

* **Employee Management:** Employees ko add, update, delete aur view karna.
* **Department Management:** Departments ko manage karna aur employees ko assign karna.
* **Authentication:** Admin dashboard secure karne ke liye login/logout functionality.
* **Search & Filter:** Naam ya department ke hisaab se employees ko jaldi dhoondna.
* **User-Friendly Interface:** Saaf aur samajhne mein aasaan UI.

## 🛠️ Tech Stack

* **Backend:** Python Django
* **Database:** SQLite (Development ke liye) / PostgreSQL (Production ke liye)
* **Frontend:** HTML5, CSS3, Bootstrap (responsive design ke liye)

## 📋 Prerequisites

Is project ko chalane ke liye aapke system mein ye installed hona chahiye:

* Python (3.x)
* pip (Python package manager)

## ⚙️ Installation Steps

1.  **Repository Clone karein:**
    ```bash
    git clone [https://github.com/yourusername/employee-management-system.git](https://github.com/yourusername/employee-management-system.git)
    cd employee-management-system
    ```

2.  **Virtual Environment banayein aur activate karein:**
    ```bash
    python -m venv venv
    # Windows ke liye:
    venv\Scripts\activate
    # Linux/Mac ke liye:
    source venv/bin/activate
    ```

3.  **Dependencies install karein:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Database Migrations run karein:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5.  **Admin User banayein:**
    ```bash
    python manage.py createsuperuser
    ```

6.  **Development Server chalayein:**
    ```bash
    python manage.py runserver
    ```



7.  **Browser mein check karein:**
    Ab aap browser mein `http://127.0.0.1:8000/` open karke app ko use kar sakte hain.

## 👥 Usage

* **Admin Panel:** Aap `/admin` URL par jaakar database records ko manage kar sakte hain.
* **Frontend:** Main UI ke zariye aap employees ki details manage kar sakte hain.

---
Made with ❤️ using Django.
