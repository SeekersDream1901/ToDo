# ToDo
    Приложение для отслеживания выполнения задач

Стек технологий
    
    asgiref==3.6.0
    Django==4.2.1
    django-environ==0.10.0
    djangorestframework==3.14.0
    envparse==0.2.0
    psycopg2-binary==2.9.6
    pytz==2023.3
    sqlparse==0.4.4
    typing_extensions==4.5.0
    tzdata==2023.3
    env==0.1.0
    environ==1.0
    gunicorn==20.1.0
    idna==3.4
    pycparser==2.21
    PyJWT==2.6.0
    python3-openid==3.2.0
    requests==2.30.0
    requests-oauthlib==1.3.1
    social-auth-app-django==5.2.0
    social-auth-core==4.4.2
    urllib3==2.0.2

Виртуальное окружение

    1. Создание окружения - python -m venv venv
    2. Активация виртуального окружения - source venv/bin/activate
    3. Выход из виртуального окружения - deactivate

Установка зависимостей

    pip install -r requirements.txt

POSTGRES

    docker images | grep postgres - postgres latest version
    docker-compose config - конфигурация 

Запуск и просмотр запущенной базы

    docker-compose up -d db - запуск    
    docker-compose ps -a - просмотр

Миграции

    ./manage.py makemigrations --dry-run - что произайдет, если мы сделаем миграцию
    ./manage.py makemigrations- создаем миграции
    ./manage.py migrate - накатываем миграции

Runserver

    python manage.py runserver
