## Краткое описание

11.08.2021 было проведено функциональное тестирование методом белого ящика приложения Credit card number validator

На тестирование затрачено: 30 минут

В результате выявлены следующие дефекты:
[Некорректно расчитывается итоговое значение банковского счета](https://github.com/evgenijstr/javaMoneyTransfer/issues/1)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* [тест-кейс](https://docs.google.com/spreadsheets/d/1tgjnCL7GrxQjA1airLScGuvjCoKJ2HIyEaB3u-jAh3o/edit?usp=sharing)
* [образец кода](https://github.com/netology-code/javaqa-code/blob/master/1.2_programming/variables/src/Main.java)
  

В качестве тестовых данных использовались следующие контейнеры и переменные
* int currentAmount = 2000000000
* long currentAmount = 2000000000
* int total = 2500000000
* long total = 2500000000


  Тестирование проводилось в следующем окружении
* Ubuntu 20.04.2 LTS, 64 bit
* Java 11.0.11
* IntelliJ IDEA 2021.2 (Community Edition) Build #IC-212.4746.92
* IntelliJ IDEA 2021.2 (Community Edition) Build #IC-212.4746.92