# Описания проекта - "Выбор локации для скважины"


## Данные

Нам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов.
  
Признаки:
- Уникальный идентификатор скважины
- Три признака точек (неважно, что они означают, но сами признаки значимы)
 
Целевой признак:
- Объём запасов в скважине (тыс. баррелей)

## Задача

Построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируем возможную прибыль и риски техникой Bootstrap.

## Используемые библиотеки
*pandas*, *matplotlib*, *seaborn*, *scikit-learn*.

### Установка необходимых библиотек (Это поможет использовать код без ошибок и склеек)

В Jupiter:
```
!pip install pandas # установка pandas

!pip install matplotlib # установка matplotlib

!pip install seaborn # установка seaborn

!pip install scikit-learn # установка scikit-learn

!pip install numpy # установка numpy

```

В Anaconda:
```
conda install pandas # установка pandas

conda install matplotlib # установка matplotlib

conda install seaborn # установка seaborn

conda install scikit-learn # установка scikit-learn

conda install numpy # установка numpy

```

## Документация на используемые библиотеки:
- [Pandas](https://pandas.pydata.org/docs)
- [Matplotlib](https://matplotlib.org/stable/index.html)
- [Seaborn](https://seaborn.pydata.org/index.html)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [NumPy](https://numpy.org/doc/1.23)
