# Django tutorial 4

Follows this tutorial [here](https://docs.djangoproject.com/en/4.0/intro/)

## How To Run It ?

The root of this project, then execute the following command:

```
$ python manage.py runserver
```

## How To Setup PostgreSQL ?

Enter GNU Bash:
```
$ sudo su - postgres
```

Enter psql, the command-line interface for PostgreSQL:
```
$ psql
```

Create DB for Django:
```
# CREATE DATABASE mydatabase;
```

Check that DB was created:
```
postgres=# \l
                                  List of databases
    Name    |  Owner   | Encoding |   Collate   |    Ctype    |  
------------+----------+----------+-------------+-------------+
 mydatabase | postgres | UTF8     | en_US.UTF-8 | en_US.UTF-8 | 

```

## How To Create Python Virtual Env ?

Create virtual environment in folder 'my_env' inside your project folder
```
python -m venv my_env
```

Activates the virtual environment:
```
source my_env/bin/activate
```