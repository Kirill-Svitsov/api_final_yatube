# api_final_yatube

Проект api_yatube реализован с целью освоить написание API для джанго проектов.
С помощью этого API можно получать список объектов, или один объект, создавать новые объекты и
менять объекты, если вы автор.
Как развернуть проект локально: Установите Python 3.9:

### Как запустить проект:

```
Установите Python 3.9
```

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Kirill-Svitsov/api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

Обновите менеджер пакетов:

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 yatube_api/manage.py migrate
```

Запустить проект:

```
python3 yatube_api/manage.py runserver
```

Документация API примерами запросов и ответов доступна по ссылке:

```
http://127.0.0.1:8000/redoc/
```
