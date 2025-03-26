# Job Portal - Django Project

A comprehensive **Job Portal** built with Django, offering features for job seekers and employers, including job listings, applications, and user management.

## Features

- User Authentication (Signup, Login, Logout)
- Job Listings (Create, View, Edit, Delete)
- Apply for Jobs
- Admin Dashboard for CRUD Operations
- Responsive UI with HTML, CSS, and JavaScript

## Project Structure

```
JobPortal/
├── account/          # User authentication and management
├── jobapp/           # Job-related functionality
├── static/           # CSS, JS, Images
├── template/         # HTML templates
├── manage.py         # Django management script
└── db.sqlite3        # Database file
```

## Installation Guide

1. **Clone the repository:**

   ```bash
   git clone <repository_url>
   cd Project_Zip/JobPortal
   ```

2. **Create a virtual environment and activate it:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (for admin access):**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the server:**

   ```bash
   python manage.py runserver
   ```

Access the portal at: [http://localhost:8000](http://localhost:8000)

## Admin Panel

- URL: `/admin/`
- Use the superuser credentials to log in.

## Screenshots
Check the `screenshots` folder for UI previews.


