# TEAM_5-Z133
## MiniProject for SC1015 LAB GROUP Z133 TEAM 5

Group Members: 
- Malcolm Tay (U2222599H) 
- Belvedere Song (U2222304L) 
- Rapheal Liew (U2220628L) 

To run the project, please use the version for python and jupyter as stated in the requirements.txt file. 

## Project Description: 

With the increasing attention on diabetes and its serious impact on one's health, especially among youths. My team is curious to find out what are the key indicators/factors that are predictive of diabetes for our age group (i.e 18-24, young adult). As such we went to kaggle to find a dataset regarding diabetes. 

The dataset we obtain from kaggle contains datas on individuals health status that has diabetes and no diabetes from all ages. 

To kick start our investigation, we first cleaned the data to obtain datas from our targeted aged group and realise that only a small population is diagnosed with diabetes. We then went on to carry out Uni-Variate Exploration to better understand the youths in our data. 

From our Uni-Variate Exploration, we realise that only a small population of individuals have unhealthy eating habits, lifestyle and poor medical condition. We then proceed with our Bi-Variate Exploration but found no indicator per se, has a strong correlation with one's diabetic status. 

This gives us some insight and direction to explore further and investigate if the combination of indicators could increase one's diabetes risk or one being diagnosed with diabetes could be due to certain combination of indicators. Since only a small population in our dataset is diagnosed with diabetes. Our team plan to use multi-variate classifaction and anomaly detection. To deal with imbalance classes for classification, our team plans to use SMOTE. 

Our rationale for using machine learning in this project is because we would want to build a model that is build upon (say) 5 indicators that has the same accuracy as a model that is build upon all the indicators. If both models has similar accuracy and the accuracy is good, we can say that those 5 indicators are able to represent all the indicators that are predictive of diabetes, thereby answering our problem statement. 


## Reference: 
Dataset: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset?select=diabetes_binary_5050split_health_indicators_BRFSS2015.csv

Diabete inf: https://www.myheart.org.sg/tools-resources/bmi-calculator/

smote - https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/

Code Reference: 

Visualisation -  https://www.kaggle.com/code/gabrielsober/diabetes-eda-prediction

Visualisation - https://www.kaggle.com/code/yannansu/predict-diabetes-with-health-indicators

One Class SVM -  https://colab.research.google.com/drive/1o2_ZctA26Kqk2tYhe3zu8lbIoRcO8Hf7?usp=sharing#scrollTo=6cH3gfgnUxcB

Isolation Forest - https://grabngoinfo.com/isolation-forest-for-anomaly-detection-and-imbalanced-classification/
