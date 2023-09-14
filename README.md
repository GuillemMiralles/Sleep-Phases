# Deep in the Depths of Sleep: Creating Interpretable Models to Detect Sleep Phases Using Polysomnography Signals from Patients 🛌💤🔍

## Introduction 📝

Welcome to my sleep classification project! In this project, we explore and analyze different machine learning models to classify sleep between REM and non-REM phases. We use EEG and EMG signal data to train and evaluate our models.

## Objective 🎯

The main objective of this project is to develop accurate sleep classification models and understand which variables influence sleep phase prediction.

## Techniques Used 🤖

In this project, we focus on using interpretable models, i.e., models that can be understood and explained clearly. The choice of interpretable models is crucial in medical applications as it enables healthcare professionals to understand the reasoning behind predictions.

## Key Results 📊

Below is a table of results for the models used:

| Model            | Accuracy | Sensitivity | Specificity | Best Model |
|------------------|----------|-------------|-------------|------------|
| Logistic Regression | 0.85     | 0.79        | 0.89        | ❌          |
| Random Forest    | 0.94     | 0.98        | 0.66        | ✅          |
| Rule-Based Model (CBA) | 0.93 | 0.99      | 0.66        |            |

✅ **Best Model**: Random Forest

- The Random Forest model achieved an accuracy of approximately 94% in sleep classification, with high sensitivity (98.9%) but lower specificity (66.4%).

- We identified that variables related to channel standard deviation are crucial in classification, especially in the Random Forest model.

- We observed interesting interactions between the variables of standard deviation of channel O1 and the electromyograms.

- We used techniques like LIME and Shapley to interpret models at a local level and understand how variables affect predictions.

## Conclusions and Social Potential 🚀

In this project, we have successfully developed accurate machine learning models for sleep classification. These models have the potential to be used in medical applications to assist in the assessment of patients with sleep disorders.

Furthermore, we have demonstrated the importance of using interpretable models in healthcare applications, as they enable more informed and transparent decision-making.

In summary, this project represents an important step towards improving sleep classification and supporting healthcare professionals in their daily work.

