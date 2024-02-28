Install the following versions to avoid conflicts


pip install Django==2.2.4
python -m pip install django-allauth==0.40.0
pip install django-crispy-forms==1.7.2
pip install django-countries==5.5
pip install stripe==2.37.1
pip install Pillow

`python manage.py makemigrations`

`python manage.py migrate`

`python manage.py runserver`

# For Administrator login

```python
python manage.py createsuperuser
`set you superuser email and password and also username`

