# xgboost_deployment

Convert XGBoost dump file to .py

For instuctions, you may read this article: https://towardsdatascience.com/xgboost-deployment-made-easy-6e11f4b3f817


### Warnings- before you use the codes 

1. The codes work well under python 3.5.2 + xgboost 0.6. It's not guranteed to generate correct results for other versions.   
2. I haven't done any error handling in my codes.   
3. The .py is designed for scoring python dictionaries, but you can do a little bit revisions to suit for your own use case.   
4. Before you generate the .py file, make sure there's no .py file with the same name in the target folder. 
