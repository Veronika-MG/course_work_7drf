# Курсовая 8. Docker

Контекст
Для быстрого масштабирования проекта применяется контейнеризация. Для этого вам предстоит «завернуть» 
ваш проект в Docker и настроить на самостоятельный запуск.

Критерии приемки курсовой работы
Для разных сервисов создали отдельные контейнеры (django, postgresql, redis, celery, при необходимости 
список можно самостоятельно расширять).
Всё оформили в файле docker-compose, при необходимости создали вспомогательные Dockerfiles.
Проект готов быть размещенным на удаленном сервере:
его можно запустить по инструкции, приложенной в Readme-файл;
для запуска не требуется дополнительных настроек.
Решение выложили на GitHub.
Для выполнения задания используйте курсовой проект, над которым вы работали в курсе DRF.

Задание
Cоздайте отдельные контейнеры для сервисов в проекте.

Как минимум для следующих сервисов:

Django,
PostrgeSQL,
Redis,
Celery.
Как максимум — для всех сервисов проекта.

Весь проект должен запускаться одной командой и при этом иметь возможность быть перенесенным на 
тдельный удаленный сервер для запуска на нём.


# # Для запуска:
1. Заполнить файл .env.sample, изменить его название на .env
2. ввести команду "docker compose up"
- python manage.py runserver