Проект приложения для сохранения заметок

Используется Python версии 3.10.8

Инструкция:

Создаем виртуально окружение:

    python -m venv env

Переключаемся на него:

OS Windows:

    env/Scripts/Activate

*nix:

    source env/bin/activate

Устанавливаем зависимости:

    pip install -r requirements.txt

Выполняем миграции:

    python manage.py migrate

Запускаем приложение:

    python manage.py runserver

Вы восхитительны! Теперь приложение можно открыть по адресу:

http://127.0.0.1:8000