# API_FINAL_YATUBE

Социальная сеть для публикаций постов.

## Cтек:
- Python 3
- Django
- REST API Framework
- DRF Simple JWT

## Функционал:

- Позволяет создавать/редактировать/читать посты
- Создавать группы/получать список групп
- Привязывать посты к группам
- Комментировать/просматривать все комментарии поста
- Подписываться/отписыпаться на/от авторов постов
- Получать список своих подписчиков
- Реализована аутентификация по JWT-токену


## Документация:
```http://localhost:8000/redoc/```

## Установка:

Склонировать проект:
```sh
git clone git@github.com:mamasidikova/api_final_yatube.git
```
Установить зависимости::

```sh
pip install -r requirements.txt
```

Создать и применить миграции:

```sh
python manage.py makemigrations
python manage.py migrate
```
Запусить Django сервер:
```sh
python manage.py runserver
```
