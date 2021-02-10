# GBT-Feature-Relationships
A repo containing the Gradient Boosted Trees (GBT) feature relationships script.  
The dashboards relating to these python scripts can be found here:


### KK Box Data Prep
This python notebook performs all the data manipulation required to prepare the data for the model. The data is taken from this Kaggle challenge:  
https://www.kaggle.com/c/kkbox-churn-prediction-challenge/data

### LightGBM - Feature relationships
This notebook trains a light GBM model on the data prepared in the KK Box Data Prep notebook. The code in this section can be applied across a wide range of different use cases with only minor adaptations. This notebook also extracts the feature contributions, required to plot the feature relationships in the Power BI visual.  
Note: Model was not cross validated for simplicity
