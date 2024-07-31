# Учебный проект

## Описание:

### Это учебный мини-проект по созданию серверной части виджета банковских операций

## Установка:

1. Клонируйте репозиторий:

```
git clone https://github.com/AlexandrPavlushenko/python-mini-project-lesson3.git
```

2. Установите зависимости:

```
poetry update
```

## Тестирование

Этот проект использует для тестирования фреймверк pytest.Покрыт тестами code coverage.
Чтобы запустить тесты с оценкой покрытия, можно воспользоваться следующей командой:

```
poetry run pytest --cov
```

## Использование:

* Откройте приложение
* Создайте новый проект и начните добавлять задачи.
* В проект добавлены функции для работы с массивами транзакций,а
  так же генератор номеров карт из 16 цифр
* В проект добавлен декоратор для логирования вызовов функций
* В проект добавлено логирование выполнения функций в пакетах masks и utils
* Добавлены функции преобразования csv и xlsx файлов в список словарей