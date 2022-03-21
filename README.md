### django-api-template
# Django Rest API Template


## Virtualenv

### Setup virtualenv

```bash
$ virtualenv venv
$ source venv/bin/activate
```
This assumes that python3 is linked to valid installation of python 3 and that pip is installed and pip3is valid for installing python 3 packages.


Installing inside virtualenv is recommended, however you can start your project without virtualenv too.

```bash
$ pip3 install django
```
And then:

```bash
$ python3 -m django startproject \
--template=https://github.com/chandu00007/django-api-template/zipball/master \
--extension=py,md \
<project_name>
```

After that just install the local dependencies
```bash
$ cd {{project_name}}
$ pip3 install -r requirements.txt
```

Run migrations
```bash
$ python3 manage.py makemigrations
$ python3 manage.py migrate
```

Run server
```bash
$ python3 manage.py runserver
```





