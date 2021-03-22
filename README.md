## Project Description
India is seeing an explosion of new competitors in the Broadband space. 'India Broadband' is a company that is now seeing a lot of customer churn due to customer dissatisfaction because of broadband outages. The company has now curated a dataset, where it tracks several variables that it believes impact the `outage_duration`. They have tracked three different outage durations, `0` for no outage, `1` for short outages that last anywhere between a few minutes and a maximum of 2 hours, and `2` for long outages that can last from 2 hours to sometimes even a couple of days. The objective is to build a machine learning model to predict outages and reduce customer churn.

## Data file description
+ train_data.csv : Unique event id for each observation of outage detection in a particular area code
+ test_data.csv: contains samples for which network outage is to be predicted
+ broadband data: contains customer ids and broadband type
+ contains customer ids and outage type
+ contains id, log-report-type and volume
+ contains ids and server types
+ train data clean : contains cleaned data after performing ETL operations on all tables

## Dependencies

+ Python 3.6 or higher
+ numpy
+ pandas
+ scikit learn
+ matplotlib
+ seaborn
+ imblean
+ dython
+ keras
+ tensorflow
+ catboost
+ lgbm

## Results summary
The catboost classifier was used to make the final predictions. The model achieves a macro f1 score of 0.60
