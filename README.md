git clone: https://github.com/Kaewkamphon62/Selected-Topic-Project.git
62114440046 แก้วกัมพล สื่อศิริธำรงค์

**RUN Project: http://localhost:8000/**
python manage.py runserver
_______________________________________________________
**Development Mode: http://localhost:3000/**
cd frontend
npm start
**DEV Mode Update to http://localhost:8000/**
npm run build
_______________________________________________________
**Edit Model**
python manage.py makemigrations api
python manage.py migrate
_______________________________________________________
**Create a virtual environment, สร้าง env**
python -m venv env

**เรียกใช้ env ตามระบบปฎิบัติการ Windows or Linux&Mac**
env\Scripts\activate
source env/bin/activate
_______________________________________________________
**SuperUser**
id:         admin,
email:      admin@gmail.com,
password:   admin