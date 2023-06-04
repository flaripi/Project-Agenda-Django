-- Obs: comandos para Windows Powershell

cria maquina virtual
```
python -m venv venv
```

Inicia
```
.\venv\Scripts\activate
```

Install Django
```
pip install Django
```

Caso necessario efetuar upgrado do Django
```
python -m pip install --upgrade pip
```

Verifica instalacoes
```
pip freeze
```
Criar Projeto no Django ( comando cria projeto na raiz ".")
```
django-admin startproject project .
python .\manage.py startapp contact
```

Após criar o app, nao esquecer de ir em project/settings.py e adicionar o app.
```
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'contact', #app contact adicionado
]
```


Inicia projeto Django
```
python manage.py runserver
```

