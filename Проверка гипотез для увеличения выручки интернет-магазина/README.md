# Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста

## Описание проекта
Контекст Вы — аналитик крупного интернет-магазина. Вместе с отделом маркетинга вы подготовили список гипотез для увеличения выручки.

## Описание данных
1. Таблица с гипотезами.
- краткое описание гипотезы;
- охват пользователей по 10-балльной шкале;
- влияние на пользователей по 10-балльной шкале;
- уверенность в гипотезе по 10-балльной шкале;
- затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.

2. Таблица с заказами.
- идентификатор заказа;
- идентификатор пользователя, совершившего заказ;
- дата, когда был совершён заказ;
- выручка заказа;
- группа A/B-теста, в которую попал заказ.

3. Таблица с пользователями.
- дата;
- группа A/B-теста;
- количество пользователей в указанную дату в указанной группе A/B-теста.

## Задачи
Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами.  

## Используемые библиотеки
Python, Pandas, matplotlib, scipy

## Итог 
Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.
