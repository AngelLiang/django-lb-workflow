## 快速开始
    
    pipenv install
    pipenv shell

    cd testproject
    python manage.py bower_install
    python wfgen.py
    python manage.py makemigrations
    python manage.py createsuperuser
    python manage.py runserver

访问 http://127.0.0.1:9091/ 即可
