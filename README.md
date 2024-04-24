# blog_Django

shell
mkdir django-blog \n
cd django-blog\n\n

windows power shell
python -m venv venv
.\venv\Scripts\activate

shell
python -m pip install Django
django-admin startproject personal_blog .
python manage.py runserver
python manage.py startapp blog

python manage.py makemigrations blog
python manage.py migrate blog
python manage.py migrate
python manage.py createsuperuser
