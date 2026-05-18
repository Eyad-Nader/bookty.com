# Bookty.com 

An online library platform where users can browse, borrow, and read books — built with Django and AJAX.

---

## Screenshots

![Login Page](login.png)
![Book Page](book.png)

---

## Features 

- User authentication and authorization
- Browse and borrow books online
- Read books directly in the browser
- Admin dashboard to manage books
- Smooth experience using AJAX

---

## Installation

```bash
git clone https://github.com/Eyad-Nader/bookty.com.git
cd bookty.com
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open `http://127.0.0.1:8000` in your browser.
