# Poetry + Django Walkthrough on Windows

## PreReq

-   A computer
-   Python 2.7+ || 3.4+
-   etc?

### Poetry Install

-   Follow instructions on https://python-poetry.org/docs/

### Base Poetry Setup

-   in shell (shell1)

```
mkdir {fileName}
cd {fileName}
poetry init
```

-Follow prompts in command prompt

### Install Django

```
poetry add django
```

### Make Django project

-   in seperate command prompt (shell2)

```
poetry shell
django-admin startproject {projectName}
```

### Start Project Server

-   (shell2)

```
cd {projectName}
py manage.py runserver
```

-   will be on `http://127.0.0.1:8000/`
