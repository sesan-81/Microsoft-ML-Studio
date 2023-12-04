# Microsoft-ML-Studio

1. Executive Summary

In response to the assignment objectives, this report details the steps taken to utilize automated machine learning (AutoML) using Microsoft Machine Learning Studio for creating a predictive model. The primary goal was to compare the performance of the AutoML model with a hand-built model developed in the previous week.  This week's focus shifted towards leveraging automated machine learning (AutoML) using Microsoft Machine Learning Studio. The objective was to assess whether AutoML could outperform the manually developed models for cyclist traffic prediction. The methodologies applied in Week 7 laid the foundation for understanding the data and modeling approach, guiding the integration of AutoML into the existing framework.

2. Recap of Week 7:

2.1 Overview

A brief recap of the predictive analytics report for cyclist traffic, highlighting key aspects such as dataset features, data preprocessing, feature engineering, and model selection. This serves as the baseline for evaluating AutoML performance.

2.2 Model Performance Metrics

Reiterating the metrics used to evaluate the performance of Random Forest Regressor and Gradient Boosting Regressor in Week 7. Mean Squared Error (MSE) and R2 Score were identified as key indicators of model accuracy.

3. Integration of AutoML

3.1 Accessing Microsoft Machine Learning Studio

The initial steps involved logging into the platform and navigating to the relevant workspace. Familiarity with the interface was crucial for a seamless integration process.



3.2 Uploading Week 7 Data

The cleaned and processed dataset used in Week 7 was uploaded to Microsoft Machine Learning Studio, ensuring consistency in the data used for AutoML experimentation.


![image](https://github.com/sesan-81/Microsoft-ML-Studio/assets/104377031/91657d84-71d4-47ca-93ca-8e1d49e701b9)
 

3.3 Configuring AutoML Experiment

The AutoML experiment was set up, specifying the target variable and features. Time and resource constraints were configured to align with the experiment's scope.
 
![image](https://github.com/sesan-81/Microsoft-ML-Studio/assets/104377031/4b70d7ec-51b1-466a-aacf-9b0d03009cc2)



After creating a new project, assets were added to the project.


![image](https://github.com/sesan-81/Microsoft-ML-Studio/assets/104377031/5afccb98-3c23-4bee-bb92-74daf7fd6c91)


 

And the cyclist data was added, and a new experiment was created.

![image](https://github.com/sesan-81/Microsoft-ML-Studio/assets/104377031/5d5ef07b-d5f5-4bac-be84-f90aad4ca198)


 
4. AutoML Model Training

4.1 Running the AutoML Experiment

The AutoML experiment was executed, and the platform's automated processes were monitored. The diverse set of machine learning models proposed by AutoML was explored.
 

![image](https://github.com/sesan-81/Microsoft-ML-Studio/assets/104377031/e1f8340d-8a8e-421c-840f-9eb20633de1b)


5. Evaluation Metrics:
   
5.1 Comparing with Week 7 Metrics:

The evaluation metrics used in Week 7 (MSE and R2 Score) were compared with the metrics obtained from AutoML. A critical analysis of whether AutoML surpassed the manually developed models in terms of coefficient of determination.

5.2 Random Forest Regressor Metrics as manual model:

●	Mean Squared Error (MSE): 738304.46
●	R-Squared (R2): 0.9208

5.3 Decision Forest Regressor Metrics:

●	Mean Squared Error (MSE): 0.2639
●	R-Squared (R2): 0.831


6. Results Submission
   
6.1 Retrieving AutoML Model Output
   
The results of the AutoML experiment were extracted, ensuring completeness and accuracy in submission. A screenshot is included to provide a visual representation of the AutoML model's performance.


![image](https://github.com/sesan-81/Microsoft-ML-Studio/assets/104377031/77f928ad-1db1-4490-83e9-9c2e0a853ccb)

 
6.2 Comparative Analysis

A comparison between the results of AutoML and the models developed in Week 7 shows insights into whether AutoML demonstrated inferior predictive capabilities and the factors contributing to its performance. The autoML model achieved a lower coefficient of determination while at the same time having a lower MAE.

7. Conclusion:
The report concludes with reflections on the efficacy of AutoML in enhancing the accuracy of cyclist traffic predictions and its potential implications for future data science endeavors. Even when the auto ML is good, it just is not fit for this very task.


