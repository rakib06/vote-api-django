# Additional Requirements setup 
```bash
sudo apt install pipenv
```
## Creating Virtualenv 


```bash
pipenv --three
source $(pipenv --venv)/bin/activate
```

# Installation Requirements packages 

## option 1

```bash
pipenv install django
pipenv install django-rest-framework
python manage.py runserver
```
