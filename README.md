# Laravel_crm
проект, мини CRM, по управлению компаниями и её сотрудниками

Должна быть реализована базовая авторизация +

Применение сидеров (seeds) для создания первого пользователя с данными для входа (email - admin@local.in и паролем password)

Создать миграции для компаний: name, email, phone, website, logo (минимум 100х100 пикселей)

Создать миграции для сотрудников компании: first name, last name, company (используя внешний ключ для связи (foreign)), email, phone

Создать CRUD (Create, Read, Update, Delete) панели для Компаний и Сотрудников

Сохранять логотипы компаний в папке storage/app/public/companies, и сделать её доступной из папки public

Для создания CRUD-ов нужно применить Laravel resource маршруты

Для валидации использовать Request классы

Использовать встроенную пагинацию, с выводом 15 последних созданных элементов на страницу
