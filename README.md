# django-rest-api

A REST api written in Django for people with deadlines

## Technologies used

- [Django](https://www.djangoproject.com/): The web framework for perfectionists with deadlines (Django builds better web apps with less code).
- [DRF](https://www.django-rest-framework.org/): A powerful and flexible toolkit for building Web APIs

## Installation

- If you wish to run your own build, first ensure you have python globally installed in your computer. If not, you can get python [here](https://www.python.org).
- After doing this, confirm that you have installed virtualenv globally as well. If not, run this:
  ```bash
      $ pip install virtualenv
  ```
- Then, Git clone this repo to your PC

  ```bash
      $ git clone https://github.com/Sujoy-2811/django_api.git
  ```

- #### Dependencies

  1. Cd into your the cloned repo as such:
     ```bash
         $ cd django_api
     ```
  2. Create and fire up your virtual environment:
     ```bash
         $ pip install virtualenv
         $ virtualenv venv
         $ .\venv\Scripts\activate
     ```
  3. Install the dependencies needed to run the app:
     ```bash
         $ pip install -r requirements.txt
     ```
  4. Make those migrations work
     ```bash
         $ python manage.py makemigrations
         $ python manage.py migrate
     ```
  5. Creating an admin user
     ```bash
         $ python manage.py createsuperuser
     ```

- #### Run It
  Fire up the server using this one simple command:
  ```bash
      $ python manage.py runserver
  ```
  You can now access the file api service on your browser by using
  ```
      http://localhost:8000/admin/
  ```
