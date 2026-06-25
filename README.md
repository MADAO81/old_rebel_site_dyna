# Old Rebel

Энциклопедия мотоциклов Harley-Davidson Dyna (1971–2017)

## О проекте
Сайт посвящен семейству мотоциклов Dyna — от создания до конца выпуска в 2017 году.
Здесь собрана информация о моделях Super Glide, Fat Bob, Switchback и других,
с фотографиями, техническими характеристиками и интересными фактами.

## Технологии
- Python 3.10+
- Django 4.2+
- PostgreSQL (или SQLite для разработки)
- Bootstrap 5
- Gunicorn + Nginx (для продакшена)

## Установка для разработки

```bash
# Клонировать репозиторий
git clone https://github.com/MADAO81/old_rebel_site_dyna.git
cd old_rebel_site_dyna

# Создать виртуальное окружение
python -m venv venv

# Активировать (Windows)
venv\Scripts\activate

# Активировать (Linux/Mac)
source venv/bin/activate

# Установить зависимости
pip install -r requirements.txt

# Применить миграции
python manage.py migrate

# Создать суперпользователя
python manage.py createsuperuser

# Запустить сервер
python manage.py runserver
Лицензия
© 2025 MADAO81. Все права защищены.
