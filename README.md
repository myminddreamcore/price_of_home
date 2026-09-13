# Прогноз стоимости недвижимости в Турции

## Описание
Проект по предсказанию цены недвижимости на основе данных
турецкого сайта объявлений (~400 000 записей).

## Этапы
1. EDA — разведочный анализ данных
2. Предобработка — очистка, кодирование, масштабирование
3. Модели — LinearRegression, Ridge, DecisionTree, RandomForest,
   HistGradientBoosting, KNN
4. Оценка — MAE, RMSE, MAPE, R², MedAE
5. Форма прогноза — ipywidgets в Jupyter
6. Дашборд — DataLens (ссылка в dashboard_link.txt)

## Результаты
| Модель | R² test | MAE test |
|---|---|---|
| LinearRegression | 0.5347 | 74 329 TRY |
| Ridge | 0.5348 | 74 327 TRY |
| DecisionTree | 0.7251 | 68 126 TRY |
| RandomForest | 0.7755 | 60 814 TRY |
| **HistGradientBoosting** | **0.7760** | **60 106 TRY** |
| KNN | 0.8190 | 44 273 TRY |
## Дашборд
https://datalens.yandex/rr53abvpln68a?_share_link=public

**Финальная модель:** HistGradientBoosting
- R² = 0.7760
- MAE = 60 106 TRY
- MAPE = 37.0%

## Как запустить
- загрузите папку artefacts и файл Comand-Work(1).ipynd загрузите их в Jupiter Notebook
- откройте файл Comand-Work(1).ipynd
- ознакомьтесь с содержимым
- в конце файла ознакомьтесь с дашбордом, перейдя по ссылке
- ознакомьтесь со справкой для использования приложения
- введите входные данные
- нажмите "Расчитать"
