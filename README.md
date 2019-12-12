## Predicting  Pokemon Type



## Goal
Build best fit machine learning models to predict type of a Pokemon

## Data Source
The data was gathered with web scraping method from https://www.pokemon.com/us/ page
and saved as pokemon.csv file

## Python Tools:
   - pandas
   - beautifulsoup
   - sklearn
   - Seaborn/Matplotlib
   - SciPy/NumPy

## Visualization of Model Confusion Matrix 
  -Baseline Model
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/baseline_model.png)
  
  -Logistic Regression
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/log_conf_matrix.png)
  
  -KNN
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/knn_conf_matrix.png)
 
 -Decision Tree
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/dt_conf_matrix.png)
 
 -Random Forest
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/rf_conf_matrix.png)
 
 -Bagged Tree
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/bt_conf_matrix.png)

-AdaBoost
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/ada_conf_matrix.png)

-Gradient Boost
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/gbt_conf_matrix.png)

-XGBoost
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/xgb_conf_matrix.png)

-SVM
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/svm_conf_matrix.png)


## Performance of ML Models
![header](https://github.com/toprakmehmet/pokemon_types/blob/master/result.png)

## Conclusion
After my machine learning models experiments and extensive feature selection, i had good results with that my best model used  XGBoost.
