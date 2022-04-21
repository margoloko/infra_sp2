## Проект YamDB

### О проекте:

    Проект YaMD* собирает отзывы пользователей на различные произведения.





### Используемые технологии:
- Python
- Django
- Django Rest Framework
- Docker
- Postgres

### Заполнение .env файла:
В директории infra_sp2/infra/ необходимо создать файл .env и указать следующие значения:

- SECRET_KEY
- SERVERNAMES
- DB_ENGINE
- DB_NAME
- POSTGRES_USER
- POSTGRES_PASSWORD
- DB_HOST
- DB_PORT

### Для запуска приложения в контейнерах:
- Установите Docker
- Клонируйте репозиторий
'''git clone https://github.com/margoloko/api_yamdb.git'''
- Запустите docker-compose командой
''' docker-compose up -d --build '''


### Автор:
Марина
