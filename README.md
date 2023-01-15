# Сборщик статей (Article collector).

Набор инструментов для сбора статей с поддерживаемых новостных сайтов или блогов и манипуляции собранными материалами.

Версия 0.5

## Системные требования.

* Python не ниже 3.11.
* Модули из requirement.txt.

## Состав репозитория.
- Основной код расположен в каталоге [artcollector](artcollector/).
- Модуль [demo.py](demo.py) демонстрирует использование кода. В том числе и все методы, позволяющие извлечь статью с сайта и получить доступ ко всем её свойствам.
-- Файл [demo_urls.txt](demo_urls.txt) содержит ссылки на поддерживаемые сайты, на которых производилось тестирование инструмента.
-- [example.txt](example.txt) содержит результат работы демки на примере указанных ссылок.
- в файле [requirement.txt](requirement.txt) находится информация о модулях Python, необходимых для работы с инструментом.

Перед использованием рекомендуется создать виртуальную среду на основе дистрибутива Python 3.11 и установить все модули из requirement.txt.