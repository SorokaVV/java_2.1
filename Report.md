# Отчёт о тестировании функциональности сервиса пополнения клиентского счета
## Краткое описание
Тестирование было проведено: 30.10.2020.
Была проверена функцианальность сервиса пополнения клиентского счета.

На тестирование затрачено: 30 минут.

### В результате тестирования выявлены следующие дефекты:

* [Неверный подсчет остатка в функцианале при переводе на счет клиента](https://github.com/SorokaVV/java_2.1/issues/1)


## Описание процесса тестирования
В качестве тестовых данных использовались значения, предоставленные при пополнении на текущий счет
* текущий баланс счёта клиента - 2_000_000_000 (два миллиарда рублей) 
* сумма перевода - 500_000_000 (пятьсот миллионов рублей)


### Тестирование производилось в следующем окружении:
* Win10 x64
* openjdk version "11.0.9" 2020-10-20
