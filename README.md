# models
For work

1. agregator_return: предсказание вероятности возврата совершенных покупок. **Градиентный бустинг на деревьях** (CatBoost).
2. cash_mashines: расчет индекса популярности банкоматов. **K ближайших соседей и градиентный бустинг на деревьях** (KNeighborsClassifier и LightGBM). 
3. lookalike: выделение из общего массива респонденов максимально похожих на заданную группу. **Positive-Unlabled классификация** (LogisticRegression). 
4. marketplace_loyal: определение лояльных покупателей. **К средних** (K means).
5. retail_uplift: оценка эффективности взаимодействия с покупателем. **Градиентный бустинг на деревьях** (LightGBM). 
6. time_series: прогнозирование количества визитов в магазины. **sARIMA**. 
