# DOCEREE_machine-learning-hackathon_round_1

##  Leaderboard
* Rank:4
* Score:99.8824

### Competition hosted on <a href="https://www.techgig.com/codegladiators/machine-learning-hackathon">Techgig</a>

### Problem
Create a model that can accurately predict whether a user belongs to the HCP(Healthcare Professional) category or not. Based on server logs.

### Evaluation
#### Evaluation metric for this competition is Accuracy.

### Solution:

### Exploratory Data Analysis
#### The basic exploratory data analysis of the data,
* Target distribution
* Categorical column level count
#### The above analysis had done by using,
* pandas 
* numpy
* seaborn
* matplotlib

### Model
#### Created catboost classifier model and tuned hyperparameters by using optuna framework. The model was evaluated by Accuracy.
#### Packages Used,
      * Sklearn
      * Pandas
      * Numpy
      * Matplotlib
      * catboost
      * optuna
      * shap
      
#### [For more detailed information about the model.](https://github.com/hariprasath-v/DOCEREE_machine-learning-hackathon_round_1/blob/main/Approach_Doceree_Machine_Learning_Hackathon.pdf)     

### Catboost Model Feature Importances
![Alt text](https://github.com/hariprasath-v/DOCEREE_machine-learning-hackathon_round_1/blob/main/Model%20interpretation%20visualization/Catboost%20Model%20Top%20Feature%20Importances.png)

### SHAP Catboost Model Feature Importances
![Alt text](https://github.com/hariprasath-v/DOCEREE_machine-learning-hackathon_round_1/blob/main/Model%20interpretation%20visualization/Catboost%20SHAP%20feature%20importance%E2%80%99s.png)

### Catboost Model train and validation accuracy
![Alt text](https://github.com/hariprasath-v/DOCEREE_machine-learning-hackathon_round_1/blob/main/Model%20interpretation%20visualization/Overall%20Train%20and%20Validation%20Accuracy.png)

### Catboost Model validation data confusion matrix
![Alt text](https://github.com/hariprasath-v/DOCEREE_machine-learning-hackathon_round_1/blob/main/Model%20interpretation%20visualization/Validation%20data%20Confusion%20matrix.png)

### File information

doceree-machine-learning-hackathon-1-eda.ipynb[![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/hari141v/doceree-machine-learning-hackathon-1-eda/notebook)
 
doceree-machine-learning-hackathon-1-model.ipynb[![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/hari141v/doceree-machine-learning-hackathon-1-model)
 
 
   
        


