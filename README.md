# Безопасность веб-приложений. Лабораторка №2

## Вариант 1. Расписания

Сделать аналог раздела https://ssau.ru/rasp?groupId=531030143

Какие нужны возможности:
- справочники групп, табличные данные по расписаниям добывать с настоящего сайта на серверной стороне приложения
- в клиентскую часть подгружать эти сведения динамически по JSON-API
- обеспечить возможность смотреть расписания в разрезе группы или препода
- обеспечить возможность выбора учебной недели (по умолчанию выбирается автоматически)

## Инструкция запуска
1. Установить Python extension
2. Установить библиотеки через терминал: 
    - py -m pip install requests
    - py -m pip install bs4 
    - py -m pip install lxml
3. Запустить файл main.py
4. В браузере зайти на http://127.0.0.1:2000