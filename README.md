## Django — MayaCMS

```sh
# Clone Repository
git clone https://github.com/mayacms/mayacms-quickstart.git 

# Installation
python -m venv .venv && source .venv/bin/activate
python -m pip install -r requirements.txt

# Django Application
python manage.py makemigrations     # Make Database Migration
python manage.py migrate            # Run Database Migration
python manage.py runserver          # Run Development Server
python manage.py createsuperuser    # Create Admin User
```
