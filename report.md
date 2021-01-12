# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

12/01/2021 - было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [При вводе карты 0000000000000000 валидатор выдает fail](https://github.com/YuliyaMuraveva/lesson-1.2/issues/1#issue-784117420)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* IntelliJ IDEA Community 2020.3
* Credit Card Number Validator


В качестве тестовых данных использовались данные c [www.freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)
* Result for 4532278346289060: OK
* Result for 5397216153083722: OK
* Result for 5020351512866114: OK
* Result for 5461825869829656: OK
* Result for 0000000000000000: OK
* Result for 4532278346289061: FAIL
* Result for 5397216153083721 FAIL
* Result for 1020351512866114: FAIL
* Result for 3461825869829656: FAIL
* Result for 453227834628906: FAIL
* Result for 45322783462890600: FAIL

Тестирование производилось в следующем окружении:
* Fedora 32 x86_64
* OpenJDK version 11.0.9
* IntelliJ IDEA Community 2020.3
