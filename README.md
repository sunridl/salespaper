# Доска объявлений о купле-продаже
Доска структурированных объявлений с возможностью поиска по характеристкам.

## Инструкция
1. git clone git@github.com:LitRidl/salespaper.git
2. Установить Python и связанные утилиты:
  1. sudo apt-get install python-setuptools python-dev build-essential
  2. sudo easy_install pip
3. Установить веб-фреймворк Flask: pip install Flask
4. Перейти в директорию и запустить сервер:
  1. cd salespaper
  2. python run.py
5. Перейти в браузере на страницу http://localhost:5000/

## Исходная постановка задачи
Сайт купли-продажи авто:
- возможность размещать объявления о продаже авто с некими характеристиками - достатоно взять 4-5 характеристик
- управление-модерирование (CRUD) всеми объявлениями в админке
- иерархия доступа к объявлениям - зарегистрированный пользователь может редактировать только свои объявления.
- поиск авто по неким фильтрам, напр, год выпуска, КПП и пр


## Функциональность
- размещение пользователем объявлений о продаже авто с указанием характеристик.
- возможность регистрации пользователя.
- объявления можно просматривать.
- объявления можно фильтровать по заявленным в них характеристикам.
- разделение зарегистрированных пользователей на простых и администраторов.
- пользователь может изменять и обновлять свои объявления.
- администатор может изменять и удалять все объявления в панели администрирования.
