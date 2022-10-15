# Описания проекта - "Исследование технологического процесса очистки золота"


## Данные

Используем данные с параметрами добычи и очистки предоставленные компанией «Цифры». 

**Технологический процесс**<br>
Rougher feed — исходное сырье<br>
Rougher additions (или reagent additions) — флотационные реагенты: Xanthate, Sulphate, Depressant<br>
*-Xanthate — ксантогенат (промотер, или активатор флотации)*<br>
*-Sulphate — сульфат (на данном производстве сульфид натрия)*<br>
*-Depressant — депрессант (силикат натрия)*<br>
Rougher process (англ. «грубый процесс») — флотация<br>
Rougher tails — отвальные хвосты<br>
Float banks — флотационная установка<br>
Cleaner process — очистка<br>
Rougher Au — черновой концентрат золота<br>
Final Au — финальный концентрат золота<br>
**Параметры этапов**<br>
air amount — объём воздуха<br>
fluid levels — уровень жидкости<br>
feed size — размер гранул сырья<br>
feed rate — скорость подачи<br>
**Наименование признаков**<br>
Наименование признаков должно быть такое:<br>
[этап].[тип_параметра].[название_параметра]<br>
Пример: rougher.input.feed_ag<br>
Возможные значения для блока [этап]:<br>
*rougher — флотация<br>
primary_cleaner — первичная очистка<br>
secondary_cleaner — вторичная очистка<br>
final — финальные характеристики<br>*
Возможные значения для блока [тип_параметра]:<br>
*input — параметры сырья<br>
output — параметры продукта<br>
state — параметры, характеризующие текущее состояние этапа<br>
calculation — расчётные характеристики<br>*

## Задача

Спрогнозировать концентрацию золота при проведении процесса очистки золота.

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
