# Отчёт о тестировании приложения Money Transfer
## Краткое описание

22 декабря 2020 г было проведено тестирование приложения Money Transfer. Главная функция приложения - перевод денежных средств между счетами. 

Продолжительность тестирования - 2 часа. 

Проводилось функциональное тестирование.

В результате тестирования с заданными переменными приложение свою функцию не выполняет, сумма двух слагаемых выводится неверно.

## Ссылки на баг-репорты:
  <p> <a href="https://github.com/TestDiana/java-2.1/issues/1">Приложение неверно считает итоговое значение</a></p>


## Общие рекомендации

Необходимо переписать код, тип int для переменной для хранения итогового значения задан неверно, полученное число выходит за его границы.