💀 Old Rebel
Энциклопедия мотоциклов Harley-Davidson Dyna (1971–2017)

📖 О проекте
Сайт посвящён легендарному семейству мотоциклов Dyna — от момента создания до завершения выпуска в 2017 году.

Здесь вы найдёте:

📸 Фотографии культовых моделей

⚙️ Технические характеристики

📜 Историю и интересные факты

🔧 Модельный ряд: Super Glide, Fat Bob, Switchback и другие

❤️ Сделано с любовью к двухколёсной классике

🛠️ Технологии
Компонент	Технология
🐍 Язык	Python 3.10+
🌐 Фреймворк	Django 4.2+
🗄️ База данных	PostgreSQL (SQLite — для dev)
🎨 Фронтенд	Bootstrap 5
🚀 Продакшен	Gunicorn + Nginx
⚡ Установка для разработки
1️⃣ Клонируйте репозиторий
bash
git clone https://github.com/MADAO81/old_rebel_site_dyna.git
cd old_rebel_site_dyna
2️⃣ Создайте виртуальное окружение
bash
python -m venv venv
3️⃣ Активируйте его
Windows 🪟

bash
venv\Scripts\activate
Linux / Mac 🐧🍏

bash
source venv/bin/activate
4️⃣ Установите зависимости
bash
pip install -r requirements.txt
5️⃣ Примените миграции БД
bash
python manage.py migrate
6️⃣ Создайте суперпользователя (админку)
bash
python manage.py createsuperuser
7️⃣ Запустите локальный сервер
bash
python manage.py runserver
✅ Готово! Открывайте http://127.0.0.1:8000 и наслаждайтесь 🏁

📜 Лицензия
© 2026 MADAO81. Все права защищены.
🔒 Материалы сайта не могут быть скопированы или распространены без разрешения автора.

🙌 Бонус: быстрые команды
Действие	Команда
Запуск сервера	python manage.py runserver
Создание миграций	python manage.py makemigrations
Применение миграций	python manage.py migrate
Сбор статики	python manage.py collectstatic
Вход в Django shell	python manage.py shell
🧠 Планы по развитию
Базовая структура проекта

Модели мотоциклов

Добавить галерею с большими фото 📷

Реализовать поиск по моделям 🔍

Сделать раздел «История Dyna» с таймлинией 🕰️

Адаптив под мобильные устройства 📱

🤝 Контакты
Если есть вопросы, идеи или баг-репорты — пишите:
📧 chernyshev.evgeniy@gmail.com
🐙 GitHub: MADAO81

💀 Dyna — это не просто мотоцикл, это стиль жизни. Присоединяйтесь! 💀
