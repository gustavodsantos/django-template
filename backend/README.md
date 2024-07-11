## Backend Django

Nessa pasta se encontram os arquivos de backend do projeto Django.

Será usado o Poetry como gestor pacotes.

Por isso, para instalar o projeto, dentro das pasta backend rode

``
poetry install --with dev
``

Para rodar seu servidor Django ative o ambiente virtual:

``
poetry shell
``

Então rode

``
python manage.py runserver
``