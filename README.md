## Predicting  Pokemon Type
![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/International_Pok%C3%A9mon_logo.svg.png)
![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/dims.jpeg)

## Goal
Build best fit machine learning models to predict type of a Pokemon

## Data Source
The data was web scraped from https://www.pokemon.com/us/ 
and saved as a pokemon.csv file

https://www.pokemon.com/us/ is a website run by Pokemon, owned by the parent company of Nintendo. It is a site that mains current and past records of all Pokemon statistics and types.

## Python Tools:
   - Pandas
   - Beautifulsoup
   - Sklearn
   - Seaborn/Matplotlib
   - SciPy/NumPy

## Statitstical Tests Used
In order to determine a bestfit model, the following 9 were tested. As you can see below KNN was the most effective with a K value of 1.

## KNN
![img](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/Screen%20Shot%202019-12-12%20at%207.44.04%20PM.png)

## Visualization of Model Confusion Matrix 
## Baseline Model
![img](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/baseline_conf_martix.png)
  
## Logistic Regression
 ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/log_conf_martix.png)
  
## KNN
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/knn_conf_martix.png)
 
## Decision Tree
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/dt_conf_matrix.png)
 
## Random Forest
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/rf_conf_matrix.png)
 
## Bagged Tree
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/bt_conf_matrix.png)

## AdaBoost
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/ada_conf_matrix.png)

## Gradient Boost
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/gbt_conf_matrix.png)

## XGBoost
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/xgb_conf_matrix.png)

## SVM
  ![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/svm_conf_matrix.png)


## Performance of ML Models
![header](https://github.com/toprakmehmet/pokemon_types/blob/master/pics/result.png)

## Future Applications
As one of many avid pokemone fans out there. This model can assist in detemining the type of each pokemon and help trainers all over the digital universe to be the very best. As the nintendo company keeps releaseing new pokemone with every generation, this model can also be used to predict the type of pokemon that will be released as Pokemon does try to keep a balance in their creations.
