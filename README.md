                                                                 Skymarket - рекламный сайт

Реализация

Backend: django restframework

DateBase: postgresql

Веб-сервер: nginx (из образа докера)

Frontend: react (было предоставлено)

интерфейс доступен по адресу: localhost:3000 серверная часть по адресу: localhost:8000

Для запуска проекта локально, используя докер для каждого сервиса

Проект настроен на запуск всех необходимых контейнеров докеров и заполнение базы данных с помощью одной команды. Просто выполните следующую команду: docker compose up --build -d

