# Отчёт о тестировании приложения Money Transfer

## Краткое описание

В ходе тестирования программы были выполнены позитивные и негативныетесты функциональности. 
По результатам проверки было выявлено, что система неверно обрабатывает целочисленные значения данных более 2_147_483_647.
Неверно указантип данных переменных - int.    

## Описание тестов

Проведено [позитивное](https://monosnap.com/file/Kyw2Bbs1Uk7nJ3lpGm2DYxF8XlqNyJ) и [негативное тестирование](https://monosnap.com/file/yJqEYW2TukDLHrHGNwfNgLhfvOW5rQ) (результаты которого указаны отдельно). Проводилось тестирование функции суммирования остатка денежных средств клиента.    

## Обнаруженные ошибки

[Issue](https://github.com/MikhailUsachev-Piter/Money-Transfer/issues/1) 

## Общие рекомендации

Нужно использовать другой тип переменных - long, чтобы использвать значения данных больше 2 147 483 647.
