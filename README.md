# project-testAPI-QA

Состав проекта

- `project_test_cases_QA.xlsx` — 29 позитивных и негативных тест-кейсов для `/auth`, `/booking`, `/booking/:id` и `/ping`.
- `restful_booker.postman_collection.json` — коллекция Postman с проверками
- `bug_report.md` — реестр подтверждённых дефектов и готовая структура баг-репорта.

## Запуск Postman-коллекции

1. Импортировать JSON-файл в Postman.
2. Запустить коллекцию целиком и строго сверху вниз: запрос `AUTH-001` сохранит `token`, а `BOOK-POST-001` — `bookingId` в переменных коллекции.
