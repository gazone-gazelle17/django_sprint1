# **Blogicum**
## **Описание**
___

Данный проект представляет собой блоговое приложение, разработанное с использованием фреймворка Django. Приложение состоит из двух основных частей:

+ pages: Приложение для работы со статическими страницами проекта, такими как "О нас" и "Правила".
+ blog: Приложение для работы с публикациями пользователей.
Проект предоставляет возможность просмотра и редактирования страниц блога, а также управления ими через административный интерфейс Django.

## **Маршруты и View-функции**
___

| Адрес                        | Приложение | Функция-обработчик | Имя шаблона |
|------------------------------|------------|--------------------|-------------|
| ''                           | blog       | index              | index.html  |
| posts/int:id/                | blog       | post_detail        | detail.html |
| category/slug:category_slug/ | blog       | category_posts     | category.html |
| pages/about/                 | pages      | about              | about.html  |
| pages/rules/                 | pages      | rules              | rules.html  |

## **Установка и запуск проекта**
___

Клонируйте репозиторий на свой локальный компьютер:
git clone https://github.com/your_username/blog_app.git

Создайте и активируйте виртуальное окружение:
python3 -m venv venv
source venv/bin/activate

Установите зависимости из файла requirements.txt:
pip install -r requirements.txt

Запустите локальный сервер:
python manage.py runserver

Откройте браузер и перейдите по адресу http://127.0.0.1:8000/ для просмотра приложения.

## **Автор**
___

Саша Гасымов

