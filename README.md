# Projects of Data Science

## Machine Learning

### Forecasting


[Product Forecasting for a Agriculture Company:](/Forecasting_LightGBM.ipynb) A LightGBM model was implemented for 1000 products belonging to an agricultural company using historical data with at least 66 instances per threshold, employing lags. Forecasting was performed using Multistep for 12 months from their last sale. L2 regularization was applied, but a certain category of products still shows signs of overfitting.


[Forecasting Store Sales:](https://github.com/cristianBMJ/ProjectsDataScience/blob/main/forecasting-store-salesPB.ipynb) The goal is to forecast store sales in Ecuador, considering different store locations across the country. The hybrid model used for learning consists of two components: **RandomForestRegressor** and **LinearRegression**.


[Forecasting Store Sales of Drinks ]( https://github.com/cristianBMJ/ProjectsDataScience/blob/main/pronostico_ventas_bebidas.ipynb) The goal was to determined the  daily sales for the  month of Febraury 2022, to achieve this, the  **RandomForestRegressor** model was used, which resulted in a root mean squear error **RMSE** of 4.65.


### Classification

[Stars Categorization:]( https://github.com/cristianBMJ/ProjectsDataScience/blob/main/classification-star.ipynb)   Classification of Star Giants  or  Dwarfs , consider the  [dataset](https://www.kaggle.com/datasets/vinesmsuic/star-categorization-giants-and-dwarfs). The categorization the Stars was studied according to criteria the Morgan–Keenan (MK) classification system. Firstly, the dataset was cleaned  and then it was balanced. In order to apply  three models's Machine Learning, being **Random Forest Classification**   the one with the better results, obtaining a precision of 94% used metrics **F1**.   





[Discovering Exoplanets:](https://github.com/cristianBMJ/ProjectsDataScience/blob/main/DiscoveryExoplanets.ipynb) Problem of Classification the Explanets. we  used the [source](https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html). It was worked **Random Forest Classification**, findings hiperparameters with **RandomSearchCV**, achieve a 74,65% for the metric **F1**. In turn, displayed **Confusion Matrix**

[Income:](https://github.com/cristianBMJ/ProjectsDataScience/blob/main/Ingresos.ipynb) The project is about determined Income for some Adults
, the target is divide in two interval, `<=50K` and `>50K`. Therefore,  it is problem of Classification. The Metric used is **F1** and **Confusion Matrix**, to obtaing a precision aproximately of  81 %.

### Regression


[House Prices:](https://github.com/cristianBMJ/ProjectsDataScience/blob/main/fork-of-houseprices.ipynb) This project aims to implement Advance Tecnique  Regression for predicting house prices. To achieve this, I have utilized a forked version of Ryan Holbrook's notebook. In this modified version, I incorporated more depth Exploratory Data Analysis. In turn, to had been  added new  models, fit by  hypeterparameters with the library **Optuna**.


## Deep Learning

[Emojis:](https://github.com/cristianBMJ/ProjectsDataScience/blob/main/objectoLocalization.ipynb) In this project, the goal was determined Object Localization, correspond one Emojis. The problem consisted in  dectection  exactly only instance of one object. To do this, we trained a model with **Convolutional Neural Network** (CNN), utilized for it, the library **TensorFlow**. The project  comes from Guided Project of Coursera.


[Petal of the Metal:](https://github.com/cristianBMJ/PortfolioDataScience/blob/main/petals-to-the-metal.ipynb)The current machine learning model focuses on classifying 104 types of flowers based on their images. To achieve this, new layers have been added to enhance the model's architecture. Transfer learning techniques have been employed, utilizing pre-trained applications such as Xception and DenseNet201, which serve as a foundation for the hybrid model.

 
