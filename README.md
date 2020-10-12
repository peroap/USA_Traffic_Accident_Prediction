# USA_Traffic_Accident_Prediction

## Project Description:
This project bases on the work of Moosavi et al (2019) and aims to analyze the traffic data in the USA between February 2016 and June 2020 in order to predict the severity of traffic accidents.

There is a video that briefly describes my apporach in YoutTube: https://www.youtube.com/watch?v=6-PIHEJz2-Q&t=26s

The project is divided in 6 scripts, 3 for each iteration out of the 2 that were performed:
1.	USAccidents_data_exp.ipynb: First data exploration and high-level data preprocessing. Many plots are displayed in order to get as many insights as possible. This script outputs an new csv file (US_Accidents_June20_CLEAN_Week1.csv) that will be used in the next script. It also outputs a table that summarizes the features of the dataset with feature description, data types and an example.
2.	USAccidents_etl_and_feature_eng.ipynb: This script prepares the data to be fed to the model. In a first step it typecasts all features to the right category. Then it creates and transforms features (i.e. frequency domain) that are more useful for the model. In a last step, categorical features are encoded. This script outputs a new csv file (US_Accidents_June20_CLEAN_Week2.csv).
3.	USAccidents_model_def_train_evaluate.ipynb: This model researches the prediction power of different machine learining models. In a first step, a basic model is deployed in order to define a baseline performed. Afterwards, two more state of the art machine learning models are implemented and finally a basic deep learning model is also compared to the other models.

All scripts were run on a local machine and all data required is in the csv provided by the publication of Moosavi et al.