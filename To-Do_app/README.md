# 📝 To-Do App

A simple and clean To-Do application built with Django. Perfect for beginners learning Django web development.

## ✨ Features

- ✅ Create, read, update, and delete tasks
- ✅ Mark tasks as complete/incomplete
- ✅ Clean and simple user interface
- ✅ Admin panel for managing tasks

## 🛠️ Tech Stack

- **Backend:** Django 4.x
- **Database:** SQLite (default)
- **Frontend:** HTML, CSS, Bootstrap

---

## 🚀 Local Development Setup

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Django-Projects-for-beginners.git
   cd Django-Projects-for-beginners/To-Do_app
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirement.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the app:**
   - Open http://localhost:8000 in your browser
   - Admin panel: http://localhost:8000/admin

---

## 🐳 Docker Setup (Recommended for Beginners)

This project includes Docker support for one-command setup — no need to install Python or dependencies manually!

### Prerequisites
- Docker and Docker Compose installed

### Steps

1. **Build and run the container:**
   ```bash
   docker-compose up --build
   ```

2. **Apply database migrations:**
   ```bash
   docker-compose exec web python manage.py migrate
   ```

3. **Create a superuser (optional):**
   ```bash
   docker-compose exec web python manage.py createsuperuser
   ```

4. **Access the application:**
   - Open http://localhost:8000 in your browser
   - Admin panel: http://localhost:8000/admin

### Stopping the container
```bash
docker-compose down
```

### Why Docker?
- ✅ **One-command setup** – No manual installation
- ✅ **Consistent environment** – Works the same on any OS
- ✅ **Beginner-friendly** – Perfect for learning Django without environment headaches

---

## 📁 Project Structure

```
To-Do_app/
├── todo/               # Main application
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── To_Do/              # Project settings
│   ├── settings.py
│   └── urls.py
├── manage.py
├── requirement.txt
├── Dockerfile
├── docker-compose.yml
├── .env.example
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing`)
5. Open a Pull Request

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

**Happy Coding!** 🚀
