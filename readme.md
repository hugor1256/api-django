Neste repositorio foi criado uma API, utilizando Django REST Framework. desenvolvido um CRUD para cadastro de alunos, cursos de realizar a matricula desses alunos nos cursos

Nesse projeto foram usados os modelos, os serialidos, viewsets e registro de URLs para atender às nossas requisições

Inclusao tambem de uma autenticação básica. Mesmo executando o projeto localmente, é necessario estar autenticado.

Comandos do terminal utilizados:

CRIAR AMBIENTE VIRTUAL === virtualenv venv

ATIVAR AMBIENTE VIRTUAL === venv/Scripts/Activate

INSTALAR O DJANGO === pip install django

ATUALIZAR O PIP === pip install --upgrade pip

CRIAR O SETUP === django-admin startproject setup .

RODAR E CRIAR O SQLITE === python manage.py runserver

CRIAR AS VARIAVIES DE AMBIENTE === pip install python-dotenv

LISTA AS DEPENDECNIAS DO PROJETO === pip freeze

COLOCA TODAS AS DEPENDECIAS DO PROJETO EM UM ARQUIVO TXT === pip freeze > requirements.txt

INSTALAR O DJANGO REST FRAMEWORK === pip install djangorestframework

INSTALAR O MARKDOWN (TESTE DE REQUISIÇÕES) === pip install markdown

CRIAR UMA MIGRATION === python manage.py makemigrations

APLICA UMA MIGRATION === python manage.py migrate

CRIA UM USUARIO PARA UTILIZAÇÃO DO DJANGO === python manage.py createsuperuser
