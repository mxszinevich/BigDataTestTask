# BIGDATA_TestTask

Сервис доступен по ссылке: http://80.78.246.69/api/docs/

Тестовый пользователь:

username: test_user   
password: Test#Pass

[Для тестирования можно воспользоваться postman коллекцией](https://github.com/mxszinevich/BIGDATA_TestTask/tree/master/postman)

---

Локальная установка:
- Переименовать фаил .env.dist в .env
- Выполнить команду: docker-compose up -d --build
- Документация к api будет доступна по ссылке: http://localhost/api/docs/


---
### Тестовое задание в компанию BigData

Описание:

Базовая структура:
    • Пользователи (Логин, Полное имя, Пароль)
    • Задачи ([ID исполнителя/ей], Название задачи, Описание задачи, Дата завершения задачи, Прикрепленный файл [Изображение/Документ] *)
*Не обязательно

Необходимые методы:

    • Регистрация пользователя
    • Авторизация пользователя
    • Добавление новой задачи
    • Изменение задачи
    • Удаление задачи
    • Список задач
    • Список задач, созданных текущим пользователем


Уточнения:
В задании должны быть учтены базовые принципы безопасности, защита от SQL инъекций, разграничение прав, валидация принимаемых данных. Изменять и удалять задачи могут только их создатели.

Требования к задаче:
    • JWT авторизация
    • Open API спецификация, с возможностью ручного взаимодействия (e.g., Swagger)
    • Пагинатор для списков данных
    • Решение размещено на публичном репозитории
    • Решение доступно из интернета, либо имеет инструкции для Docker Compose
		
Правила хорошего тона:
    • Меньше сторонних модулей == лучше.
    • Тесты.
    • Простота чтения.
    • Чистота кода.
    • DRY.