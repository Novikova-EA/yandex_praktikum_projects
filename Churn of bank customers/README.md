# Прогнозирование оттока клиентов банка

## Описание проекта

Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

## Задача

На основе данных из банка определить клиента, который может уйти.

## Навыки и инструменты

- **Python**
- **Pandas**
- **Matplotlib**
- **Sklearn**

## Общий вывод

На основании данных о поведении клиентов и расторжении ими договоров с банком осуществлен прогноз ухода клиента из банка в ближайшее время. Для этого были построены три модели машинного обучения с подбором оптимальных метрик:

- без учета дисбаланса классов,
- с учетом применения техник для борьбы с дисбалансом классов: взвешивание классов, upsampling (увеличение выборки), downsampling (уменьшение выборки).

Проведено тестирование лучшей модели на тестовой выборки.

## Статус проекта

Завершен.


