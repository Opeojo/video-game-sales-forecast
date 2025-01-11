# Video Game Sales Forecast Project

## Overview
This project is as result of the desire of a Video Game Company to be able to synchronise their supply to the demand from their customers.
The capability to be able to control logistics as regards the inventory needed for supply. This company plan to go about it by being able to forecast monthly sales which would then inform 
the nesessary procurement to meet the available demand. This aids the company to combat wastage, bottlenecks in the supply chain and logistics, improve service to clients/customers, increase 
profit, help cut unnecessary cut, better management and control of warehouse and scalability.

**Business Problem**:
We try to achieve this by exploring the time series dataset provided by the company, a rigorous indepth analysis of the time series and eventually implement a suitable time series forecast model to 
predict future sales by implementing several models and evaluating their performance.


## Data
Data was obtained from Amdari Consults. The data contain 8 features of different data type. The features are listed thus:
- Date
- Monthly Sales
- Year
- Product Category
- Holiday
- Promotion
- Day of week
- Platform
The sample size of the time series 264, it's such a small dataset, quite irregular with not palpable trend or seasonality.

## Libraries and Packages Used
The project was written in python and in the data science python ecosystem. Pandas, Numpy,  and visualisation libraries such as matplotlib, seaborn, and plotly were used. in addition, statsmodels, scipy, 
are al ready used, however, not-to-common packages feature-engine, arm-mango were used as well to enhance EDA.
For the implementation of the models, statmodels which aws mentioned eary on and Facebook prophet were used, nonetheless, sktime, a package that that makes time series forecasting very easy 
that also share similar API with scikit-learn was used as well.

## Metrics Used
Majority of the traditional machine learning metrics for regression are suitable to evaluate time series models as well so included are rmse, mae, mape, geometric mean absolute error (gmae) and for 
final evaluation, two scaled metrics are added: rmsse and mase.

# Key Aspects of the Project
- Exploration of categorical data with respect to monthly sales.
- Exploration and analysis of date features.
- Indepth analysis of the effect of holiday and promotion on average monthly sales
- Decomposition of the Time Series.
- Check for stationarity.
- Spliting of time series into training and testing set. 20% allotted to test set.
- Implementation of the ETS models.
- Implementation of Arima models. A model developed by pacf and acf functions and then a model whose parameter was determined by cross-validation.
- Implementation of a SARIMA model.
- Implementation of 3 prophet models. A naive model, another by hyperparameter tuning (cross-validation) and the last that was backtested.
- Final model evaluation and forecasting.

# Future Implementation
It will be interesting to see how traditional ML algorithms can be applied to time series data. It only requires a thorough and informed feature engineering to achieve this.

# Contributors
- @rene fonfude
- @opeojo
