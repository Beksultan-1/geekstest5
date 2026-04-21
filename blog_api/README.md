# Blog API Project

Тестовое задание для Python/Django разработчика. 

## Функционал
* CRUD для постов и комментариев.
* Автоматическая документация Swagger/ReDoc.
* Аутентификация через Token-Auth.
* Права доступа: только автор может редактировать или удалять свои посты.

## Стек
* Python 3.13+
* Django 5.1+
* Django Rest Framework
* drf-spectacular (Swagger)

## Установка и запуск

1. Клонировать репозиторий:
```bash
git clone https://github.com
cd Geeks_Blog
```

2. Установить зависимости:
```bash
pip install django djangorestframework drf-spectacular
```

3. Выполнить миграции:
```bash
python manage.py migrate
```

4. Запустить сервер:
```bash
python manage.py runserver
```

## Документация
Swagger UI доступен по адресу: `http://127.0.0`
