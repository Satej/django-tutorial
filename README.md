`pip install django`

`django-admin startproject smartnotes .`

`python manage.py runserver 0.0.0.0:8080`

If you are running on AWS Cloud 9, remember to add your host to ALLOWED_HOSTS in settings.py.

`django-admin startapp home`

`python manage.py createsuperuser`

`python manage.py makemigrations`

`python manage.py migrate`

`python manage.py shell`

`from notes.models import Notes`
`mynote = Notes.objects.get(pk=1)`
`mynote.title`
