# api_final
# api_yatube
Проект api_yatube реализован с целью освоит написание API для джанго проектов
С помощью этого API можно получать список объектов, или один объект, создавать новые объекты и 
менять объекты, если вы автор.
Как развернуть проект локально: Установите Python 3.9:
...
Склонируйте этот репозиторий в рабочую папку (ссылка https://github.com/Kirill-Svitsov/api_yatube)
...
Создайте виртуальное окружение python3 -m venv venv.
...
Активируйте виртуальное окружение: source venv/bin/activate (Linux), venv\Scripts\activate (Windows).
...
Обновите менеджер пакетов: python3 -m pip install --upgrade pip
...
Установите зависимости: pip install -r requirements.txt
...
Примените миграции: python3 manage.py migrate
...
Запустите проект: python3 manage.py runserver (Из директории с файлом manage.py)
...
Документация API примерами запросов и ответов доступна по ссылке: http://127.0.0.1:8000/redoc/
...
