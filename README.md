```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py migrate jet
python manage.py migrate dashboard
python manage.py createsuperuser
python manage.py runserver
```