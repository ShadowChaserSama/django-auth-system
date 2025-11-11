# 🧑‍💻 Django Authentication System

A simple and secure Django authentication system that includes user registration, login, and password reset (forgot password) functionality.<br />
This project is ideal for beginners learning Django authentication or for developers who want to integrate a ready-made auth system into their web applications.

---

# 🚀 Features

✅ User Registration (with email verification optional)<br />
✅ User Login & Logout<br />
✅ Forgot Password (Password Reset via Email)<br />
✅ Secure Password Hashing<br />
✅ Django’s built-in Authentication System<br />
✅ Clean and Responsive Templates (Bootstrap)<br />
✅ Easy to customize and integrate<br />

---

# 🛠️ Technologies Used

Python 3.x<br />
Django 5.x (or compatible version)<br />
SQLite3 (default, can be changed to PostgreSQL/MySQL)<br />
Bootstrap 5 (for frontend)<br />

---

# 📂 Project Structure
```
django-auth-system/
│
├── accounts/                 # App for user authentication
│   ├── templates/accounts/   # HTML templates
│   ├── forms.py              # Custom forms
│   ├── urls.py               # App routes
│   └── views.py              # Logic for register, login, reset
│
├── project/                  # Main Django project folder
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── db.sqlite3                # Default database
├── manage.py
└── README.md
```

---

# ⚙️ Installation & Setup

1.Clone the repository
```
git clone https://github.com/yourusername/django-auth-system.git
cd django-auth-system
```

2.Create a virtual environment
```
python -m venv venv
source venv/bin/activate      # For macOS/Linux
venv\Scripts\activate         # For Windows
```

3.Install dependencies
```
pip install -r requirements.txt
```

4.Run migrations
```
python manage.py makemigrations
python manage.py migrate
```

5.Create a superuser (optional)
```
python manage.py createsuperuser
```

6.Run the development server
```
python manage.py runserver
```

7.Access the app
```
http://127.0.0.1:8000/
```

---

# 📧 Email Configuration (For Password Reset)

In your `settings.py`, configure SMTP to enable the Forgot Password feature.

Go to .env
```
MAIL=your_email
MAIL_PASSWORD=your_app_password
```

Example using Gmail:
```
EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = 'your_email@gmail.com'
EMAIL_HOST_PASSWORD = 'your_app_password'
```

---

**💡 Note:** For Gmail, you must use an App Password, not your normal account password.
Learn more: Google App Passwords Help

---

# 📸 Screenshots
1.**Home Page**
<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/0e71c1f4-920b-4392-944b-01ef55db7af5" />

2.**Login Page**
<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/2a27069e-2345-4cbd-a6e2-58664bfcc5c1" />

3.**Password Reset Page**
<img width="1913" height="1001" alt="image" src="https://github.com/user-attachments/assets/1aa88eb1-18eb-4dd1-81f3-217ab49b38b8" />

4.**Register Page**
<img width="1918" height="1005" alt="image" src="https://github.com/user-attachments/assets/79152328-b412-4ae1-8004-3fba30ce5b98" />

5.**Profile Page**
<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/5de1c668-f386-4a55-86e4-cd619f018ca3" />

**AND MORE...**

---

# 📄 License

This project is licensed under the MIT License — feel free to use and modify it for your own projects.

---

# 👨‍💻 Author

**Əli Zülbalayev**<br />
Simple, clean, and beginner-friendly Django authentication system ❤️


