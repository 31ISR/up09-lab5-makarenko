
# (Название проекта)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![Django](https://img.shields.io/badge/Django-4.0%2B-green)](https://djangoproject.com)

Социальная платформа для создания постов, сообществ.

## Основные функции

- 🏠 Главная страница
- 📝 Создание и редактирование постов
- 🗂 Сообщества (группы) по интересам
- 👤 Персональные профили пользователей
- 🔐 Система регистрации и авторизации
- ⚙️ Админ-панель для управления контентом
- 🛠 Создание новых сообществ и постов
- 📄 Страница "Обо мне"

## Технологии

- Python 3.8+
- Django 4.0+
- PostgreSQL
- HTML5
- JavaScript

## Установка и запуск

1. Клонировать репозиторий:
```bash
git clone https://github.com/31ISR/up09-lab5-makarenko.git
cd up-09-lab5-makarenko
```

2. Создать и активировать виртуальное окружение:
```bash
python -m venv venv
source venv/bin/activate  # Linux/MacOS
venv\Scripts\activate.bat  # Windows
```

3. Установить зависимости:
```bash
pip install -r requirements.txt
```

4. Настройка окружения:
Создать файл `.env` в корне проекта с содержанием:
```ini
SECRET_KEY=ваш-secret-key
DEBUG=True
DATABASE_URL=postgres:///ваша-бд
```

5. Применить миграции:
```bash
python manage.py migrate
```

6. Создать суперпользователя:
```bash
python manage.py createsuperuser
```

7. Запустить сервер:
```bash
python manage.py runserver
```

## Доступные страницы

- `/` - Главная страница
- `/post_page/` - Все посты
- `/communities/` - Список сообществ
- `/post_new/` - Создать пост
- `/communities_new/` - Создать сообщество
- `/register/` - Регистрация
- `/login/` - Авторизация
- `/about/` - Обо мне

## Админ-панель

Админка доступна по адресу `/admin/`. Для доступа необходимо:
1. Выполнить команду `createsuperuser`
2. Войти с логином/паролем суперпользователя

Возможности админки:
- Управление пользователями
- Модерация постов
- Управление сообществами
- Просмотр статистики
- Редактирование любых моделей


---

**Автор**: marmelad444  
**Поддержка**: 1111marmelad1111@gmail.com
