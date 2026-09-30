# project-testAPI-QA

Состав проекта

- `project_test_cases_QA.xlsx` — 29 позитивных и негативных тест-кейсов для `/auth`, `/booking`, `/booking/:id` и `/ping` из документации https://restful-booker.herokuapp.com/apidoc/index.html
- `project_test_QA.postman_collection` — коллекция Postman с проверками
- `bug_reports.xlsx` - найденные Баги в процессе выполнения ранов коллекции 

## Запуск Postman-коллекции

1. Импортировать JSON-файл в Postman.
2. Запустить коллекцию целиком и строго сверху вниз: запрос `AUTH-001` из папки 1.CreateToken сохранит `token`, а `BOOK-POST-001` из папки 2.CreateBooking — `bookingId` в переменных коллекции.
