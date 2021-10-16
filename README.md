git clone: https://github.com/Kaewkamphon62/Selected-Topic-Project.git
62114440046 แก้วกัมพล สื่อศิริธำรงค์

# React + Django

# Create a virtual environment, สร้าง env
* python -m venv env
* env\scripts\activate
* pip install -r requirements.txt

# RUN Project: http://localhost:8000/
* python manage.py runserver

# Development Mode: http://localhost:3000/
* cd frontend
* npm install
* npm start

# DEV Mode Update to http://localhost:8000/
* npm run build

# Update Model
* python manage.py makemigrations api
* python manage.py migrate


# SuperUser
* id:         admin,
* email:      admin@gmail.com,
* password:   admin