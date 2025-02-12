# Проект "Виджеты для клиента банка"

## Описание:

Данный проект осуществляет принятие информации от клиента и сортирует по дате, определенным условиям.

## Установка:

1. Клонируйте репозиторий:
```
git clone https://github.com/Marina_84/bank_10.1.git
```
2. Установите зависимости:
```
pip install -r requirements.txt
```

## Структура проекта:

1. tests/ - папка, в которой содержатся тесты проекта.
2. src/ - папка, содержащая файлы с функциями проекта.
3. .venv - виртуальное окружение, содержащее библиотеки и скрипты.

## Использование:

1. Откройте приложение в вашем веб-браузере.
2. Создайте новый проект и начните добавлять задачи.
3. Назначайте сроки выполнения и приоритеты для задач, чтобы эффективно управлять проектами.
4. Виджет включает в себя функцию маскировки ваших входных банковских данных.
5. Модуль masks.py принимает на вход номер карты или счета и маскирует их.
6. Модуль widget.py принимает наименование карты или счет и номер и возвращает замаскированный номер.
7. Модуль processing.py принимает список операций и возвращает отсортированные списки.
8. Модуль generators.py принимает список транзакций и реализует работу генераторов для обработки данных.
9. В модуле read_transactions.py содержатся функции read_csv_transactions и read_xlsx_transactions, которые позволяют считывать данные о финансовых операциях из файлов csv и excel.
10. Функция filter_by_request сортирует транзакции по заданному пользователем слову в поле description.
11. Функция count_transaction_categories считает количество транзакций по категориям.
12. Функция main в модуле main.py воспроизводит основной функционал банковского приложения. 
