# Отчет по итогам автоматизации
## Что было запланировано и что было сделано
В ходе автоматизации тестирования туристического веб-сервиса было запланировано 8 позитивных и 16 негативных тестовых сценариев.  
Дополнительно были написаны автотесты для проверки логичности надписей под полями при заполнении полей некорректными значениями, поскольку для данного фукционала были выявлены ошибки.

### В ходе работы было реализовано:
* 44 автотеста пользовательского интерфейса
* 10 автотестов для проверки записей в СУБД
* Выгрузка отчетов автотестов в Allure Report

## Время, затраченное на реализацию
Примерно 20 рабочих дней по 5 часов в день (≈100 часов)

## Сработавшие риски
* В связи с отсутствием какой-либо документации не всегда было понятно, какое именно поведение SUT должно считаться ошибкой (в особенности это связано с надписями под полями)
* Возникли сложности с настройкой необходимого для проведения тестирования окружения (возникли проблемы с подключением к СУБД при реализации через Docker-Compose)


  