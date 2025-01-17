# Library Management System

## Project Setup

### 1. Clone the Repository
```bash
git clone <repo-url>
cd library_management_env
```

### 2. Create and Activate a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Migrations
```bash
python manage.py migrate
```

### 5. Start the Development Server
```bash
python manage.py runserver
```

### 6. Create a Superuser (Optional)
```bash
python manage.py createsuperuser
```
Follow the prompts to set up an admin user.

### 7. Access the Application
- Open `http://127.0.0.1:8000/` in your browser.
- Admin panel: `http://127.0.0.1:8000/admin/` (login with superuser credentials).

## Project Structure
```
library_management_env/
│── manage.py
│── library_management_env/  # Django project settings
│── myapp/  # Initial Django app
│── venv/  # Virtual environment
│── requirements.txt
│── .gitignore
│── README.md
```

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License.

