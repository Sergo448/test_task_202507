Для того чтобы все заработало надо выполнить 4 действия:

1) Сделать git clone этого репозитория
2) Выполнить команды для создания рабочего варината виртуальной среды:
    2.1) Создание окружения
    python -m venv venv

    2.2) Активация 
    source venv/bin/activate  (Linux/macOS)
    venv\Scripts\activate     (в CMD или PowerShell на windows)

    2.3) Установка зависимостей
    pip install -r requirements.txt

    2.4) Проверка
    pip list

    2.5) Деактивация
    deactivate
3) docker-compose up -d для запуска бд Postgresql
4) Переместиться с папку notebooks и поднять сервис с юпитером:
    4.1) Активация 
        source venv/bin/activate  (Linux/macOS)
        venv\Scripts\activate     (в CMD или PowerShell на windows)
    4.2) cd notebooks
    4.3) jupyter notebook


Теперь все предварительне действия сделаны.
В ноутбуе находятся решенные задания разбитые с помощью макросов по пунктам как в ТЗ.
Все 5 заданий сделаны, некоторые с комментариями и дополнениями, поскольку ТЗ можно было толковать двояко.
