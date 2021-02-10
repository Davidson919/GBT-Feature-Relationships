# GBT-Feature-Relationships
A repo containing the Gradient Boosted Trees (GBT) feature relationships script.  
The dashboards relating to these python scripts can be found here:


### KK Box Data Prep
This python notebook performs all the data manipulation required to prepare the data for the model. The data is taken from this kaggle challenge:  
https://www.kaggle.com/c/kkbox-churn-prediction-challenge/data

### LightGBM - Feature relationships
This notebook creates and trains a light GBM model on the data prepared in the KK Box Data Prep notebook. This code could be applied across a wide range of different use cases and is semi-reusable, only needing minor adaptations. This notebook also extracts the feature contributions, required to plot the feature relationships in the Power BI visual.
