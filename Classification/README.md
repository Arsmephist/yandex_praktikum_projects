# Прогноз оттока клиентов 


## Задача

Оператор связи хочет научиться прогнозировать отток клиентов. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

Поставлена задача разработать модель, которая будет предсказывать намерение клиента отключиться от оператора. В качестве метрики оценки модели должен выступать AUC, который должен быть больше 0.88 на тестовых данных. Также необходимо вывести долю правильных ответов итоговой модели.

## Стек

Python, библиотеки:

- *pandas,*
- *scipy,*
- *sklearn,*
- *LightGBM,*
- *XGBoost,*
- *seaborn,*

## Описание проекта

При выполнении проекта были проведены следующие этапы:
1) Проведен анализ исходных данных, отсеяны лишние признаки, сформированы новые;
2) На тренировочных данных обучен спектр моделей, их метрики сравнены между собой и отобраны лучшие модели. На основании оценки моделями важности признаков убраны наименее важные. Подобраны наилучшие гиперпараметры на очищенных данных для этих моделей;
3) Метрики моделей проверены на тестовых данных, лучшая модель показала AUC = 0.937, Acc = 0.884;

## Статус

Завершен.