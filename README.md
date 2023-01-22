
## Исследование объявлений о продаже квартир

**Цели проекта:** Определить рыночную стоимость объектов недвижимости в Санкт-Петербурге и пригородов. 
Установить параметры для построения автоматизированной системы поиска аномалий и мошеннической деятельности.

## Итоги:
В процессе предобработки и исследования данных мы стремились к максимально объективной оценке рыночной стоимости объектов недвижимости в Санкт-Петербурге и пригородах. 
В исследовании выяснено и подробно описано, какие факторы влияют на стоимость квартиры. 
Влияние очевидных факторов, таких как  площадь, цена, число комнат, высота потолков подтверждается наглядно гистограммами и диаграммами размаха. 
Далее составим список интересных выводов и наблюдений:

- По мере увеличения расстояния от центра снижается цена за м2 недвижимости.
- Цена по всему городу отталкивается от цифры 100 т.р. за м2 как в большую, так и меньшую сторону. Самая высокая средняя стоимость жилья ожидаемо определена в Санкт-Петербурге: 113,8 т.р. за м2. Самая низкая средняя стоимость жилья среди 10 самых населенных пунктов во Всеволожске: 67,4 т.р. за м2.
- Первые и последние этажи оцениваются ниже, чем промежуточные, но наиболее явно это выражено в центральном районе города.
- Интересный провал цен был зафиксирован на границе в 3 км от центра. Это можно объяснить отсутствием развитой инфраструктуры в этих районах, например удаленностью от метро, наличием ограниченного количества современных магазинов, а также старым фондом в конце концов.
- В период с 2014 по 2019г самым депрессивным годом оказался 2014 - цены на недвижимость рухнули. В связи с напряженной политической обстановкой произошли структурные изменения в экономике страны, что неизменно отразилось на поведении потребителей. На фоне неопределенности и нестабильности цена на недвижимость сначала упала, несколько лет находилась в стагнации, но тем не менее постепенно возрастала почти до прежних значений. Наиболее ярко выражен рост цен был в 2019 году, что свидетельствовало о готовности людей вкладываться в недвижимость.
- Также определенное влияние на цену оказывает день недели и месяц размещения публикации. По субботам наблюдаются самые низкие цены продажи, самые высокие цены по вторникам. Разницами между крайними значениями цены составляет порядка 350 т.р. В июне наблюдаются самые низкие цены продажи, самые высокие в апреле. Разницами между крайними значениями цены составляет порядка 400 т.р.
- Большинство квартир продаются в срок от 45 до 232 дней.
- Чаще всего в центре встречаются двух и трехкомнатные квартиры, а по городу однокомнатные и двухкомнатные.

Параметры для построения автоматизированной системы поиска аномалий и мошеннической деятельности для недвижимости Санкт-Петербурга и пригородов:
- Общая площадь 12-200 м2;
- Количество комнат 0-5;
- Высота потолков 2,3-4м;
- Цена за м2 жилья - 15-200 тыс. руб.
- Время продажи - до 500 дней.
