# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

01.10.2020 - 01.10.2020 было проведено функцинальное тестирование приложения Credit Card Number Validator

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [номера карт с 13-15значными значениями и номера карт с 17-19значными значениями не валидируются](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* код приложения [Credit Card Number Validator](https://github.com/GrebenkovaMaria/HW_JavaForQA_1.2/blob/main/src/com/company/Main.java)
* номера карт с [freeformatter](https://www.freeformatter.com/credit-card-number-generator-validator.html)


В качестве тестовых данных использовались данные:
* номера карт с [freeformatter](https://www.freeformatter.com/credit-card-number-generator-validator.html)


Тестирование производилось в следующем окружении:
* Windows 10
* Open JDK11
* IntelliJ IDEA
