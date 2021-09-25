# Отчёт о тестировании Precision

## Краткое описание

25/09/2021 - 25/09/2021 было проведено компонентное позитивное тестирование приложения Precision

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [BugPrecision](https://github.com/ArtemiiShimanovich/Java-2/issues/1)


## Описание процесса тестирования

В качестве тестовых данных использовались данные 
* [Задание 2](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)
* обычный бонус клиента - переменная типа double, значение double regularBonus = 0.3;
* бонус новому клиенту - переменная типа double, значение double specialBonus = 0.6;
* переменная для хранения итогового значения - тип double значение double totalBonus.
* Ожидаемый результат: 0.9;

Тестирование производилось в следующем окружении:
* ОС windows 10 версия 2004, 19041.1165 64 бит
* Версия Java 11
    openjdk version "11.0.11" 2021-04-20
    OpenJDK Runtime Environment AdoptOpenJDK-11.0.11+9 (build 11.0.11+9)
    OpenJDK 64-Bit Server VM AdoptOpenJDK-11.0.11+9 (build 11.0.11+9, mixed mode)
* Chrome browser Версия 94.0.4606.61 (Официальная сборка), (64 бит)