<p align = "center"> 

  ![61Lwp7UkRvL](https://github.com/MuhannedSh/ML-Occupied-Office/assets/158508098/f20adb8b-0ab4-47a6-8e3a-0e1f6ca70317)


</p>


# ML-Occupied-Office


Muhanned Shaheen

### main goal of the project is to build a machine learning model to predict whether an office room is occupied based on certain measurements in the dataset


For this dataset, there were 1758 rows and 6 columns.

## Data Dictionary

<p align = "center"> 
  
 ![image_2024-05-08_112309392](https://github.com/MuhannedSh/ML-Occupied-Office/assets/158508098/0628cfe3-096a-461c-9346-3e58e0751fd3)



</p>


## To prepare this data, the data was cleaned, and the following processes were performed:

  
 ### Exploring Data Analysis 
    - To visualize the data for explantory purposes, stripplot and box plot was chosen.


<p align = "center"> 
  
  ![download (20)](https://github.com/MuhannedSh/ML-Occupied-Office/assets/158508098/96f23a1b-8b6e-4c0c-a0cc-1b93acfa2202)


</p>

- The chart illustrate that offices tend to be occupied during weekdays but are completely unoccupied on weekend.

<p align = "center"> 
  
 ![download (21)](https://github.com/MuhannedSh/ML-Occupied-Office/assets/158508098/b681359e-3f7b-4bac-a45c-2f2210158f86)

</p>


- The plot illustrates that the unoccupied office rooms are, on average, on day 7 of the month, while the average occupancy of office rooms on day 6.


 ### Maching Learning Using the Following Models:

  , Random Forest
    - KNN
    - Tuned KNN
    - Logistic Regression
    - Tuned Logistic Regression
    - Random Forest Classifier Model
    - Tuned Random Forest Classifier Model
    
    
## Models Evaluated & Results


- logistic Regression Model (Testing Set):
  
  - Precision for class 0: 0.86
  - Recall for class 0: 0.80
  - F1-score for class 0: 0.83
  - Support for class 0: 194
  - Precision for class 1: 0.74
  - Recall for class 1: 0.81
  - F1-score for class 1: 0.77
  - Support for class 1: 136


- Tuned Logistic Regression Model (Testing Set):
  
  - Precision for class 0: 0.86
  - Recall for class 0: 0.80
  - F1-score for class 0: 0.83
  - Support for class 0: 194
  - Precision for class 1: 0.74
  - Recall for class 1: 0.81
  - F1-score for class 1: 0.77
  - Support for class 1: 136

  
-  KNN Model (Testing Set):
- 
  - recision for class 0: 0.82
  - Recall for class 0: 0.86
  - F1-score for class 0: 0.84
  - Support for class 0: 194
  - Precision for class 1: 0.79
  - Recall for class 1: 0.74
  - F1-score for class 1: 0.76
  - Support for class 1: 136

- Tuned KNN (Testing Set):
  
  - Precision for class 0: 0.86
  - Recall for class 0: 0.82
  - F1-score for class 0: 0.84
  - Support for class 0: 194
  - Precision for class 1: 0.76
  - Recall for class 1: 0.81
  - F1-score for class 1: 0.79
  - Support for class 1: 136
    

- Default Random Forest Classifier (Testing Set):

  - Precision for class 0: 0.76
  - Recall for class 0: 0.83
  - F1-score for class 0: 0.79
  - Support for class 0: 194
  - Precision for class 1: 0.72
  - Recall for class 1: 0.62
  - F1-score for class 1: 0.67
  - Support for class 1: 136


- Tuned Random Forest Classifier (Testing Set):

  - Precision for class 0: 0.80
  - Recall for class 0: 0.85
  - F1-score for class 0: 0.82
  - Support for class 0: 194
  - Precision for class 1: 0.77
  - Recall for class 1: 0.70
  - F1-score for class 1: 0.73
  - Support for class 1: 136

 
- Random forest classifier using SMOTE (Testing Set):

  - Precision for class 0: 0.89
  - Recall for class 0: 0.80
  - F1-score for class 0: 0.85
  - Support for class 0: 194
  - Precision for class 1: 0.75
  - Recall for class 1: 0.86
  - F1-score for class 1: 0.80
  - Support for class 1: 136



- The Final Model Chosen was a `Random Forest Classifier with SMOTE preprocessing`.
- Recall for Occupied (Class 1): `86%`. 
- Recall for Not Occupied (Class 0) `80%`.


The Random Forest model with SMOTE preprocessing achieved the highest recall for both classes, indicating its effectiveness in correctly identifying occupied and unoccupied office rooms. This model can be considered for deployment in your application to predict office room occupancy based on the provided measurements.




