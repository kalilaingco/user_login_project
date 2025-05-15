## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- **Python 3.8+**
- **Git**
- **Virtual Environment**
- **pip**

## Getting Started

### 1. Set Up a Virtual Environment

Create a virtual environment to isolate your project dependencies:

```bash
python3 -m venv venv
```

Activate the virtual environment:

- On Windows:

```bash
venv\Scripts\activate

```

- On macOS/Linux

```bash
source venv/bin/activate

```

### 3. Install Dependencies

```bash
pip install django pillow
```

### 4. Navigate to the Project Directory

```bash
cd user_login_project
```


### 6. Apply Database Migrations

Apply the database migrations to set up the database schema:

```bash
python3 manage.py makemigrations
python3 manage.py migrate
```

### 7. Create a superuser
```bash
python3 manage.py createsuperuser

```

### 8. Run the Application

Run the Django development server:

```bash
python3 manage.py runserver
```