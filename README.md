### Описание
Проект api_final_yatube это бекэнд приложение с API, в котором:
* можно зарегистрироваться;
* анонимные пользователи могут читать посты зарегистрированных пользователей и комментарии к ним;
* зарегистрированные пользователи могут создават собственные посты и комментарии к ним и к постам других пользователей;
* зарегистрированные пользователи могут редактировать собственные посты и комментарии; 
* зарегистрированные пользователи могут подписываться на других пользователей;
* зарегистрированные пользователи могут просматривать свои подписки;

Проект можно использовать как cтартовую точку для создания бекэнд приложения - сервиса для блогеров.
Использованный стек: Python, SQLite, Django ORM, DjangoRestFeamework, Swagger

### Установка

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/khadakhan/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
### Примеры
Запустите сервер разработчика и перейдите на страницу с документацией в формате Swagger: http://127.0.0.1:8000/swagger/.
Вот она - документация с примерами в интерактивном формате. Здесь можно оправлять и получать запросы.

Автор проекта: [khadakhan](https://github.com/khadakhan/)
