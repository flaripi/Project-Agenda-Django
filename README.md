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
```

Inicia projeto Django
```
python manage.py runserver
```

