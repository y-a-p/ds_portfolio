# Прогнозирование оттока клиента Банка

[ipynb](p7_portfolio.ipynb)

## Описание проекта

Из банка стали уходить клиенты. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

## Навыки и инструменты
*python, pandas, matplotlib, scikit-learn* <br><br> *выбор модели МО,* <br> *подбор гиперпараметров*

## Общий вывод

Удалось построить модель, удовлетворяющую требованиям по метрике F1 (>0.59).
Применение методов борьбы с дисбалансом классов существенно повысило качество модели.
Модель RandomForestClassifier с балансировкой классов и оптимальными гиперпараметрами показала наилучшие результаты.
Высокое значение ROC AUC свидетельствует о надежности модели в различении классов и потенциале для практического применения
