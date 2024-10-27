# BelukhaPaleogeography
Paleogeographic analysis of chemical distribution by Belukha mountain ice core data

## Идея
Ледники содержат в себе данные об изменении климата за последние 800000 лет. Если пробурить скважину в леднике и взять образцы, проанализировав изотопный состав можно восстановить многое о прошлом. 
По графикам распределения химических соединений в образце можно выделить годовые слои: сезонные колебания изотопного состава и содержания примесей образуют основу для четкого годового сигнала в снежном покрове, который  может сохраняться во льду при благоприятных условиях.
В этом проекте были взяты данные по леднику на одной из высочайших горных вершин России - горе Белуха, высшей точке Алтайских гор и Сибири (4506 м). Были построены графики распределения химических соединений по глубине и выявлены некоторые закономерности.

## Задачи *

1. Скачать датасеты по концентрации изотопа кислорода и содержанию различных ионов с сайта ncei.noaa.gov.
2. Выделить нужные колонки данных для построения графика концентрации изотопа кислорода. 
3. Выделить нужные колонки данных для построения графиков содержания ионов. 
4. Написать функцию по сглаживанию графика при помощи метода скользящего среднего для увеличения читаемости итогового рисунка.
5. Наложить графики на один рисунок.
6. Привести код к чистовому варианту - написать, что делает каждая ячейка, исправить недочёты, проверить на стилистический стандарт.
7. Оформить итоговый рисунок - сделать графики различающимися по отображению, добавить подписи осей, легенду.
8. Привести репозиторий к чистовому варианту - выгрузить и обозначить все файлы, задействованные в работе, написать README.
   
## Ход работы 
С сайта ncei.noaa.gov (National Centers for Environmental Information) были взяты данные по керну на горе Белуха в формате txt. Были выбраны интересующие показатели: кислород, аммоний, а также хлориды, нитраты и сульфаты.

![](https://github.com/SoakedSanity/BelukhaPaleogeography/blob/main/pics/graph1.png)


![](https://github.com/SoakedSanity/BelukhaPaleogeography/blob/main/pics/graph2.png)


![](https://github.com/SoakedSanity/BelukhaPaleogeography/blob/main/pics/graph3.png)
## Итоги работы 
Построенные графики: 
Описание 

## Список авторов 

### * Цифрами выделены выполненные человеком задачи (зоны ответственности)
- Дубинина Василиса - 1, 7, 8
- Сахтарьек Зачерий - 2, 4, 6, 7, 8
- Трофимов Роман - 3, 5, 8

## Источники данных:

- Eichler, A., et al. 2012. 
Altai, Siberia 750 Year Ice Core d18O and Temperature Reconstruction. 
IGBP PAGES/World Data Center for Paleoclimatology 
Data Contribution Series # 2012-032. 
NOAA/NCDC Paleoclimatology Program, Boulder CO, USA. 
(ftp://ftp.ncdc.noaa.gov/pub/data/paleo/trop/belukha/belukha2009.txt)
Date accesed: 23.10.2024

- Eichler, A., et al. 2012. 
Belukha Glacier, Siberian Altai 750 Year Major Ions Data. 
IGBP PAGES/World Data Center for Paleoclimatology 
Data Contribution Series # 2012-071. 
NOAA/NCDC Paleoclimatology Program, Boulder CO, USA. 
(ftp://ftp.ncdc.noaa.gov/pub/data/paleo/icecore/trop/belukha/belukha2009ions.txt)
Date accesed: 25.10.2024


