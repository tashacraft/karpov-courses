# Информация о продажах продуктов через телемаркетинг и их подключениях в системе

## Описание данных

Есть несколько файлов с продажами продуктов с одинаковыми колонками. И есть файл с логами по подключениям в системе.

## Задачи
1. Объединить файлы по продажам в один датасет.
2. Отфильтровать датасеты с продажами и с логами по заданным условиям.
3. Проверить подключения продуктов определенным пользователям, соединив файлы о продажах с логами по подключениям в системе.

## Используемые библиотеки
- pandas
- OS

## Результаты
- объединены файлы по продажам в один датасет
- предобработан и отфильтрован датасет с продажами
- предобработан и отфильтрован файл с логами
- объединены файл по продажам и файл с логами в один датасет только с нужными подключениями
- итоговый датасет сохранен в файл .csv