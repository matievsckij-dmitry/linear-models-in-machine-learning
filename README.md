# Линейные модели в машинном обучении

**Описание задачи**

Исследовательский анализ данных о коровах (удой, качество молока, кормление, порода и т.д.) для выявления закономерностей и построения моделей прогнозирования удоя и вкуса молока.  Фермер хочет, чтобы каждая бурёнка давала не менее 6000 килограммов молока в год, а её надой был вкусным — строго по его критериям, ничуть не хуже.

**Цель задачи**

Определить факторы, влияющие на удой и вкус молока, построить модели прогнозирования, выбрать лучшую модель для предсказания удоя и оптимизировать модель для предсказания вкуса, исходя из приоритета заказчика (только вкусное молоко).

**Вывод**

Выявлены ключевые факторы, влияющие на удой (возраст, ЭКЕ, процент жира, SPR, порода отца, количество сырого протеина) и вкус молока (SPR, ЭКЕ, тип пастбища). Построены три модели для прогноза удоя, лучшая из которых (третья) демонстрирует высокую точность (R² = 0.8247), отсутствие систематических ошибок и стабильность. Для прогноза вкуса построена модель логистической регрессии (Accuracy = 0.59, Recall = 0.72, Precision = 0.63). Для достижения требуемой заказчиком точности определения *только* вкусного молока (Precision = 1) порог классификации оптимизирован до 0.81. В результате, для покупки не рекомендовано ни одной коровы, так как ни одна не гарантирует 100% вкусного молока.
