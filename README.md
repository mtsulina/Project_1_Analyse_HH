
![](./images/data_cleaning.png)
# <center> Преобразование, визуализация и очистка данных </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Зависимости](#Зависимости)
4. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование-проекта)
6. [Авторы](#Авторы)
7. [Выводы](Использование-проекта)

## Описание проекта

>**Преобразование данных** - это процесс преобразования данных к виду, удобному для из визуализации и анализа.

**Визуализация данных** – это процесс подготовки данных из исходного набора и собственно их визуализации в виде различного рода диаграмм и графиков. Визуализация данных является инструментом для анализа данных и построения различных моделей.

**Очистка данных** - это процесс поиска и борьбы с некорректными данными, включая пропуски, выбросы и собственно некорректные данные.


Основные этапы преобразования данных:
* Получение отфильтрованных наборов данных.
* Получение различного рода сгруппированных промежуточных наборов данных.
* Получение конечных наборов данных для визуализации путем различных преобразований промежуточных данных.

**Цель анализа данных** — получение знаний о клиентах банка, необходимых для реализации компании по их удержанию в банке.

**Данный проект** является итоговым проектом и направлен на демонстрацию освоенных приемов обработки исходных данных, их визуализацию, анализ и очистку на примере датасета резюме, предоставленном ресурсом HeadHunter.

**О структуре проекта:**
* [data](./data) - папка с исходными табличными данными
* [images](./images) - папка с изображениями, необходимыми для оформления проекта
* [Project-1_Analyse-HH.ipynb](./Project-1_Analyse-HH.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором демонстрируются методы подготовки, визуализации и анализа данных


## Описание данных
В этом проекте используются данные с ресурса HeadHunter.

Файл с исходными данными [dst-3.0_16_1_hh_database.csv](./data/dst-3.0_16_1_hh_database.csv)
Файл с курсами валют [ExchangeRates](./data/ExchangeRates.csv)

## Используемые зависимости
* Python (3.7.6):
    * [numpy (1.21.6)](https://numpy.org)
    * [pandas (1.3.5)](https://pandas.pydata.org)
    * [plotly (5.18.0)](https://plotly.com)
    
## Установка проекта

```
git clone https://github.com/mtsulina/Project_1_Analyse_HH.git
```

## Использование
Вся информация о работе представлена в jupyter-ноутбуке Project-1_Analyse-HH.ipynb. В файле представлены задания по визуализации и анализу данных и их выполнение.

## Авторы

* Цулина Марина

## Выводы

В результате проделанной работы были закреплены приемы преобразования, визуализации и анализа данных. Были освоены медоты обработки табличных данных при помощи DataFame-ов из библиотеки pandas, а также расширены приемы и знания по работе с диаграммами из библиотеки plotly.