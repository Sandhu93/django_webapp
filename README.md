# Django project

## Steps done

- Created virtual environment
- actiavted venv
- installed django using pip
- started new project using `django-admin startproject`
- made migrations
- created superuser
- create templates directory and add followinf lie in TEMPLATES section in settings.py

```
'DIRS': [BASE_DIR / 'templates'],
```

- created a parent app **website** (add to INSTALLED APPS in settings.py)
- searched bootstrap template from startbootstrap.com and downloaded one
- added **assets, css and js** directories in **static** directory in base.
- added index.html in **templates** directory and renamed to **base.html**
- added django tag to base.html and changed all paths using tags

```
{% load static %}
...
href="{% static 'assets/favicon.ico' %}"
...
```

- in settings.py, add following lines at the bottom

```py
STATIC_URL = 'static/'

STATICFILES_DIRS = [
    BASE_DIR / "static",
]
```

-
