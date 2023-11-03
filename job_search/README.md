Курсовая работа №4 ООП

Приложение для работы с API HeadHunter и SuperJob

Запускается из файла main.py

Описание: программа, которая получает информацию о вакансиях с 
платформ в России, сохранять ее в файл и позволять удобно 
работать с ней (добавлять, фильтровать, удалять).
Набор команд для получения и фильтрации вакансий с сервисов 
hh.ru и superjob.ru. Запросы отправляются через api с помощью
библиотеки requests. Хранение осуществляется в файле 
vacancies.json.

Подготовка:

Для работы с SuperJob:
1. Зарегистрироваться на сервисе по ссылке https://www.superjob.ru/auth/login/?returnUrl=https://api.superjob.ru/register/
2. Сохранить Secret Key приложения в .env, 
либо воспользоваться существующим

Настройка Poetry:
1. установить poetry командой pip install poetry
2. создать и активировать виртуальное окружение командой poetry shell 
3. установить зависимости командой poetry install