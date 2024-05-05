<p align = "center"> 

  ![5-Sales-Tips-to-Increase-Conversion-and-Accelerate-Revenue](https://github.com/coding-dojo-data-science/Project1_Exemplar/assets/158508098/fa6f1995-6ae4-4cb4-b9fc-eb62849322d2)

</p>


# ML-Occupied-Office


Muhanned Shaheen

### main goal of the project is to build a machine learning model to predict whether an office room is occupied based on certain measurements in the dataset


For this dataset, there were 1758 rows and 6 columns.

## Data Dictionary

<p align = "center"> 
  
 <img width="290" alt="download (19)" src="https://github.com/MuhannedSh/ML-Occupied-Office/assets/158508098/2303b056-1409-46b4-a07b-cd92a6e07948">


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





- The Final Model Chosen was a `Random Forest Regressor Model` with the n_estimators tuned to 50.
- For the testing set on the model, `56.3%` of the variance in y was explained by x. 
- The Mean Absolute Error was off by about `$31,998.94`.
- The Mean Squared Error was `$2,044,264,641.83`.
- The Root Mean Squared Error had a calculation of `$45,213.55`.

Using this model to make predictions about the best places to live and which careers to choose to earn the most money would not be a very reliable. Considering the previous regression metrics from how the model performed, there is a disparity between the R^2 score and also the Root Mean Squared Error that cannot be ignored.

## Recommendations

Data Science Insights

- For those who have an interest in Data Science:
  - Data Analytics Leads & Principal Data Engineers earn the most amount of money. However, this are usually not entry level careers and I would recommend going through a program, like Coding Dojo, where you can earn your data science certificate and then map out your career to these positions.

  - Data Engineers & Data Scientists have the most 100% remote positions. So, if you are wanting to work from home, or work from anywhere in the world, choosing one of the top five remote positions would be a good choice to build your career upon.
  
  - Lastly, the trend for the last three years show that data science and related fields are increasingly earning more money each year. So, choosing a career in one of these fields can be very lucrative.

Model Performance
- Overall, the best model is definitely the tuned Random Forest Regressor Model. There was still some bias in the model, but by far it outperformed the linear regression model. 


## Limitations & Next Steps

From here, a student could use the insights from the visuals on how to tailor their path for their career. As mentioned before, Coding Dojo has a fantastic program that prepares inspiring data scientists for the field of data science. 

## For Further Information

For any additional questions, please contact: 
- Sherlin Whaley (Data Science Instructor)
- swhaley@codingdojo.com

