# Защита данных клиентов страховой компании

[ipynb](p11_portfolio.ipynb)

## Описание проекта

Необходимо защитить данные клиентов страховой компании. Для этого необходимо разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию, при преобразовании данных качество моделей машинного обучения не должно ухудшаться.

## Навыки и инструменты
*python, numpy, scikit-learn*  <br><br> *линейная алгебра, регрессия* 

## Общий вывод

Для решения задачи был предложен подход, заключающийся в умножении матрицы признаков на случайную обратимую матрицу, что позволило зашифровать данные, сохранив их взаимосвязи. Проверка алгоритма продемонстрировала, что качество модели машинного обучения не изменилось: метрика R2 осталась на прежнем уровне как на исходных, так и на преобразованных данных.


