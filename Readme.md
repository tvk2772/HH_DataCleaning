## Учебный проект по очистке данных соискателей агенства HH
##### выполнил: *Кулакова Татьяна*

### Файлы проекта
+ [Project_HH_DataCleaning.ipynb](Project_HH_DataCleaning.ipynb) *- ноутбук проекта*
+ outliers.py - *библиотека процедур поиска выбросов в данных*

### Размещение файлов данных 
*Google Disk,* [*директория /data*](https://drive.google.com/drive/folders/1b_eMqpsUKCyWh0oQ_oRZO4UUDRZwLMpW?usp=share_link), *содержит файлы:*
+ dst-3.0_16_1_hh_database.csv *- данные соискателей HH*
+ ExchangeRates.csv *- курсы обмена валют*

### Используемые инструменты
+ Python 3.10.6
+ pandas 1.5.1
+ numpy 1.23.4
+ matplotlib 3.6.1
+ seaborn 0.12.1
+ plotly 5.11.0

### Инструкция по сборке проекта
1. Создать директорию проекта.
2. Инициировать локальный репозиторий и скачать файлы проекта:
    git init
    git remote add origin https://github.com/tvk2772/HH_DataCleaning.git
    git branch -M master
    git pull origin master
3. Скачать [файлы данных](https://drive.google.com/drive/folders/1b_eMqpsUKCyWh0oQ_oRZO4UUDRZwLMpW?usp=share_link) и разместить их в поддиректории */data* основной директории проекта
4. Запустить проект

### Дополнение
диаграммы проекта, построенные при помощи библиотеки plotly:
+ [*Гистограмма распределения опыта работы соискателей*](https://htmlpreview.github.io/?https://github.com/tvk2772/HH_DataCleaning/blob/master/diagrams/city_earn_box.html)
+ [*Коробчатая диаграмма распределения опыта работы соискателей*](diagrams/experience_box.html)
+ [*Гистограмма распределения желаемой заработной платы*](diagrams/earn_hist.html)
+ [*Коробчатая диаграмма распределения желаемой заработной платы*](diagrams/earn_box.html)
+ [*Диаграмма зависимости медианной зарплаты от готовности к переезду и/или к командировкам*](diagrams/move_trip_bar.html)
+ [*Диаграмма зависимости медианной зарплаты от уровня образования*](diagrams/earn_education_bar.html)
+ [*Диаграмма распределения медианной зарплаты по городам*](diagrams/city_earn_box.html)
+ [*Диаграмма распределения заработной платы в зависимости от пола и возраста*](diagrams/gender_earn_bar.html)



