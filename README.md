# api_final
api final
Cоциальная сеть для публикации личных дневников. Она дает пользователям возможность создать учетную запись, создать свою страницу. Публиковать записи, заходить на чужие страницы, подписываться на любимых авторов и отмечать понравившиеся записи.


### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/yandex-praktikum/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

* Если у вас Linux/macOS

    ```
    source venv/bin/activate
    ```

* Если у вас windows

    ```
    source venv/scripts/activate
    ```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 -m pip install Pillow
```

```
cd yatube_api
```

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```