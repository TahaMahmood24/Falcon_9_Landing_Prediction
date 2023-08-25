# Falcon_9_Launch
This is a capstone project for the IBM Data Science Professional Certification, In this project, we aim to predict the successful landing of Falcon 9's first stage, which is reusable and saves costs compared to other rocket providers. We will collect and verify data from an API to aid in determining the cost of launch and help other companies in bidding against SpaceX.

## Content
- [Executive Summary](#executive-summary)
- [Methodology](#methodology)
- [Data Collection](#data-collection)
- [Predictive Analysis](#predictive-analysis)
- [Results](#results)
- [Conclusion](#conclusion)

## Executive Summary
- Summary of methodologies
-- Utilized public SpaceX API and Wikipedia to collect data. 
-- Explored data with SQL, visualization, folium maps, and dashboards. 
-- Selected relevant columns as features and converted categorical variables to binary using one hot encoding. 
-- Standardized data and utilized GridSearchCV to determine optimal machine learning model parameters. 
- Summary of all results
-- Logistic Regression, Support Vector Machine, Decision Tree Classifier, and K Nearest Neighbors produced similar accuracy rates of about 85.21%.

##  Methodology
- Data collection methodology:
-- Request to the SpaceX API & clean the requested data
- Perform data wrangling
-- Segregating successful and unsuccessful landings
- Perform exploratory data analysis (EDA) using visualization and SQL
- Perform interactive visual analytics using Folium and Plotly Dash
- Perform predictive analysis using classification models
-- Run multiple predictive analysis models and check for accuracy.

##  Data Collection
1.  SpaceX API
![image](https://github.com/EmperorTaha/Falcon-9-Landing-Analysis/assets/69377374/e0c55f5c-2c77-46cc-ab2c-816cbe074ba0)

## Data Collection
2. Scraping
![image](https://github.com/EmperorTaha/Falcon-9-Landing-Analysis/assets/69377374/f304cf2e-8c5c-4601-b50d-0f23e990db3e)

## Predictive Analysis (Classification)
![image](https://github.com/EmperorTaha/Falcon-9-Landing-Analysis/assets/69377374/0ec22ebb-67a6-4a2b-a8de-ba7f1cb6b614)

## Results
- Model Accuracy
![image](https://github.com/EmperorTaha/Falcon-9-Landing-Analysis/assets/69377374/2175bfb8-9a5d-4fbe-829c-52d7ad399945)
Decision Tree Classifier tends to have the best performance of 85%; however, other models did not trail by a significant amount.

- Confusion Matrix
![image](https://github.com/EmperorTaha/Falcon-9-Landing-Analysis/assets/69377374/219538d0-dcc9-4f3c-9e59-83ccd951f1af)
Since all models performed similarly, the confusion matrix is consistent. The models predicted eleven successful landings and five unsuccessful landings, with one false positive and one false negative. 

## Conclusion
Our task is to develop a machine learning model for Space Y to predict the successful landing of Stage 1, saving ~$100 million USD. We use data from SpaceX API and Wikipedia, create data labels, store data in DB2 SQL database, create a dashboard for visualization, and achieve 83% accuracy. Allon Mask of SpaceY can use this model to predict the success of a launch before launch, and more data would improve the accuracy.






