# CRUD для Yatube

## Технологии:

- Python 3.9.13
- Django 3.2.25
- SQLite
- Django REST Framework
- Postman

## Установка (Windows):

1. Клонирование репозитория

```
git clone https://github.com/Sergey-Tsepilov/api_yatube.git
```

2. Переход в директорию api_yatube

```
cd api_yatube
```

3. Создание виртуального окружения

```
python -m venv venv
```

4. Активация виртуального окружения

```
source venv/Scripts/activate
```

5. Обновите pip

```
python -m pip install --upgrade pip
```

6. Установка зависимостей

```
pip install -r requirements.txt
```

7. Переход в директорию yatube_api

```
cd yatube_api
```

8. Применение миграций

```
python manage.py migrate
```

9. Запуск проекта, введите команду

```
python manage.py runserver
```

10. Отмена

```
Ctrl + C
```

11. Деактивация виртуального окружения

```
deactivate
```
