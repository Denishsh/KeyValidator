# Отчёт о тестировании <KeyValidator>

## Краткое описание
21.07.2021 было проведено тестирование приложения KeyValidator.

На тестирование затрачено: 1ч
  

В результате тестирования выявлены следующие дефекты:
* [IllegalArgumentException при вводе длинного или короткого UUID](https://github.com/CrazyCoderilla/KeyValidator/issues/1)
* [Некорректный результат валидации](https://github.com/CrazyCoderilla/KeyValidator/issues/2)
  
## Описание процесса тестирования

Тестовые данные взяты взяты из руководства пользователя:
* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md
  
Тестирование производилось в следующем окружении:
* Java 11
