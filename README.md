# A clean Django project

## Setting up a development environment
1. Create your own settings file, ```local_your_name.py``` in the ```src/config/settings/``` folder
2. Install the local requirements ```pip install -r requirements/local.txt```
3. Run ```python manage.py migrate```
4. Create superuser: ```python manage.py createsuperuser```
5. Run ```python manage.py runserver --settings=src.config.settings.local_your_name```. Alternatively, you can set an env variable:
```export DJANGO_SETTINGS_MODULE="src.config.settings.local_your_name"``` and simply run ```python manage.py runserver```.



