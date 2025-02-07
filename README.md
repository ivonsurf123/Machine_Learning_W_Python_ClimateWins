# **ClimateWins Weather Prediction Project**

## **Overview**
This project is part of a machine learning course focused on predicting weather variations using advanced algorithms. The aim is to help ClimateWins, an organization committed to forecasting and understanding climate change, achieve its goals. The project spans two achievements, each exploring different machine learning techniques applied to historical weather data to predict atmospheric conditions.

![Weather-Forecasting-840x525](https://github.com/user-attachments/assets/bf425f81-59be-4118-8633-2e81f3561da5)


## **Objectives**
 * Identify weather patterns outside the regional norm in Europe.
 * Determine if unusual weather patterns are increasing over time.
 * Generate possibilities for future weather conditions.
 * Identify the safest places for people to live in Europe.


## **DATA Source and Biases**

For this project, the following datasets were used:

1. **Weather Conditions Dataset**  
   Downloaded from Kaggle, this dataset includes images of various weather conditions such as sunny, cloudy, rainy, and snowy.  
   [Download the dataset here](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset)

2. **European Historical Weather Data**  
   This dataset includes historical weather data from various European cities used for training and testing weather prediction models.  
   [Download the dataset here](https://drive.google.com/file/d/1YZu-pqA2wMqDJJtYz82LN-7yMDIAgKAx/view?usp=sharing)

3. **Answers Dataset for Pleasant Weather Prediction**  
   Provided by Career Foundry, this dataset labels "pleasant" days as `1` and "unpleasant" days as `0`. It was used to evaluate different machine      learning models for predicting pleasant weather based on weather observations.  
   *(This dataset is proprietary and not publicly available for download.)*
   
4. The data set based on weather was collected from 18 different weather stations across Europe.

5. The data set contain information that rang from the late 1800s to 2022.

6. Features include average temperature, humidity, wind speed, and more, with labels for "pleasant" and "unpleasant" days.

7. Collection Bias: Data is collected only from European weather stations.

8. Location Bias: Weather data may not generalize to regions outside of Europe.

9. Temporal Bias: Older data may not accurately represent current weather patterns.


# Achievements Summary

**Achievement 1:** Statistical and Machine Learning Models

**Data Analysis:** Performed exploratory data analysis (EDA) on historical weather data.

**K-Nearest Neighbors (KNN):** Used to classify weather conditions based on temperature and other features.

**Linear and Logistic Regression:** Developed regression models for temperature trends and to classify binary outcomes (e.g., rain/no rain).

**Random Forest:** Applied to enhance prediction accuracy by combining multiple decision trees.
![Text](https://github.com/ivonsurf123/Machine_Learning_W_Python_ClimateWins/blob/b76e39e6c3e069a385d6ef554f2f5b6fd0d6a224/05%20Sent%20to%20Client/pic1.jpg)
![Text](https://github.com/ivonsurf123/Machine_Learning_W_Python_ClimateWins/blob/b76e39e6c3e069a385d6ef554f2f5b6fd0d6a224/05%20Sent%20to%20Client/pic2.jpg)
![Text](https://github.com/ivonsurf123/Machine_Learning_W_Python_ClimateWins/blob/b76e39e6c3e069a385d6ef554f2f5b6fd0d6a224/05%20Sent%20to%20Client/pic3.jpg)


## **Achievement 2: Deep Learning Techniques**

**Convolutional Neural Network (CNN):** Built a CNN for visual weather pattern recognition using images of different weather conditions (cloudy, sunny, rainy).

**Recurrent Neural Network (RNN):** Applied to predict time-series weather data, leveraging sequential data.

**Hyperparameter Tuning:** Implemented techniques like grid search and random search for optimizing model performance.

**Model Evaluation:** Assessed models using accuracy, loss, and confusion matrices to ensure reliability.

![Text](https://github.com/ivonsurf123/Machine_Learning_W_Python_ClimateWins/blob/f40a5c9a38358b9d7513b402fd69b9a25e8712a7/05%20Sent%20to%20Client/pic4.jpg)
![Text](https://github.com/ivonsurf123/Machine_Learning_W_Python_ClimateWins/blob/f40a5c9a38358b9d7513b402fd69b9a25e8712a7/05%20Sent%20to%20Client/pic5.jpg)


## **Key Results**

**CNN Model for Visual Classification:** Achieved a validation accuracy of 80% when classifying weather conditions from images.

**Random Forest Model:** Improved the accuracy to 72% using hyperparameter tuning techniques like grid search.

**Time-Series Analysis:** Demonstrated the capability to predict weather patterns using RNN, focusing on long-term climate trends.


## **Summary of Experiments for ClimateWins**

**Predicting Weather Anomalies with Random Forest:** Focus on using ensemble models to analyze shifts in weather patterns based on historical data.

**Deep Learning for Complex Weather Interactions:** Utilize Convolutional Neural Networks (CNNs) to detect patterns in satellite images and radar data.

**GANs for Synthetic Weather Projections:** Generate possible future weather scenarios using GANs to simulate climate variations.


## **Recommendation**

* Use Random Forest models for immediate analysisof feature importance and to identify key predictors of abnormal weather patterns.
* Implement CNNs for analyzing satellite data and weather imagery to improve real-time classification of weather conditions.
* Invest in developing GANs for longer-term scenario simulation, helping ClimateWinsplan for potential future climates.

## **Next Steps**

* Validate model predictions with real-time data.
* Collaborate with meteorologicalagencies for improved data access.
* Explore scaling the models to include more complex climate data.
