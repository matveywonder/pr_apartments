# pr_apartments
Исследование объявлений о продаже квартир

В моем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно определить рыночную стоимость объектов недвижимости. Моя задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

Цель иследования:

Установить параметры для автоматизированной системы.
Определить рыночную стоимость квартир.

Ход иследования:

Данные о недвижимости я получу из файла - '/datasets/real_estate_data.csv'. О данных ничего не известно. Поэтому перед тем, как приступать к целям иследования, понадобится обзор данных.

Я проверю данные на ошибки и оценю их влияние на иследование. Затем, на этапе предобработки я исправлю все ошибки данных, которые не приведут к искажению конечного результата. Далее создам необходимые столбцы, и приступлю к проведению иследовательского анализа.

Таким образом, моё иследование пройдет в пять этапов:

1. Обзор данных.
2. Предобработка данных.
3. Добавление новых данных в таблицу.
4. Проведение иследовательского анализа данных.
5. Общий вывод.
