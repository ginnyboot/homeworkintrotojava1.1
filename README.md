# Отчёт о тестировании приложения Credit Card Number Validator

## Краткое описание

14.06.2021 - 14.06.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2.5 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/ginnyboot/homeworkintrotojava1.1/issues/1
* https://github.com/ginnyboot/homeworkintrotojava1.1/issues/2

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Чек-лист](https://docs.google.com/spreadsheets/d/14TK_ndCudkisAiXi_GG97cbveglEBE5LxSQv_tj-Skg/edit?usp=sharing) для проверки номеров карт различных платежных систем


В качестве тестовых данных использовались данные из репозитория [javaqa-homeworks/intro](https://github.com/netology-code/javaqa-homeworks/tree/master/intro), а также номера карт с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html#fakeNumbers):
* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md — руководство позволяет корректно установить JetBrains Toolbox и IntelliJ IDEA;
* https://www.freeformatter.com/credit-card-number-generator-validator.html — приложение Credit Card Number Validator позволяет корректно обработать номера карт от всех брендов платежных систем (фактически — не обрабатываются номера карт с количеством символов !=16 (см. [Issue 2](https://github.com/ginnyboot/homeworkintrotojava1.1/issues/2)) и номера карт платежной системы MIR (см. [Issue 1](https://github.com/ginnyboot/homeworkintrotojava1.1/issues/1)).

Тестирование производилось в следующем окружении:
* Устройство: PC (Windows 10 Pro, x64)
* Java "11.0.11" 2021-04-20
* Браузер: Chrome (91.0.4472.77)