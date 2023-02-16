# Django-API

Criando uma API de clientes utilizando Python e Django Rest Framework
da Alura - https://cursos.alura.com.br/formacao-django-rest


## Criando ambiente virtual

```
python -m venv ./venv
```


## Ativando o ambiente virtual

### Mac / Linux

```
source venv/bin/activate 
```

### Windows
```
venv\Scripts\activate
```


## Verificar os modulos instalados
```
pip freeze
```


## Instalando os modulos a partir de um arquivo txt 
```
pip install -r requirements.txt
```

Obs.: O modulo do requirements.txt precisou ser atualizado, pois o mesmo não estava funcional 
-> typed-ast==1.5.4


## Rodar/executar o servidor 
```
python manage.py runserver
```

## criar as migrations 
```
python manage.py makemigrations
python manage.py migrate
```