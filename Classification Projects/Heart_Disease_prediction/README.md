# Project : Heart Disease Prediction

# Overview

Preventing heart disease is important. Good data-driven systems for predicting heart disease can improve the entire research and prevention process, making sure that more people can live healthy lives.

In the United States, the Centers for Disease Control and Prevention is a good resource for information about heart disease.Accorting to their [website](https://www.cdc.gov/heartdisease/facts.htm).

- About 610,000 people die of heart disease in the United States every year–that’s 1 in every 4 deaths.
- Heart disease is the leading cause of death for both men and women. More than half of the deaths due to heart disease in 2009 were in men.
- Coronary heart disease (CHD) is the most common type of heart disease, killing over 370,000 people annually.
- Every year about 735,000 Americans have a heart attack. Of these, 525,000 are a first heart attack and 210,000 happen in people who have already had a heart attack.
- Heart disease is the leading cause of death for people of most ethnicities in the United States, including African Americans, Hispanics, and whites. For American Indians or Alaska Natives and Asians or Pacific Islanders, heart disease is second only to cancer.

So, in this project I have applied different machine learning algorithm to predict heart disease based on several features present in the dataset
such as Age, Maximum heart rate, Blood pressure levels etc.

## About Dataset

This dataset is from a study of heart disease that has been open to the public for many years. The study collects various measurements on patient health and cardiovascular statistics, and of course makes patient identities anonymous.
Data is provided courtesy of the [Cleveland Heart Disease] (http://archive.ics.uci.edu/ml/datasets/statlog+(heart)) Database via the UCI Machine Learning repository.

Aha, D., and Dennis Kibler. "Instance-based prediction of heart-disease presence with the Cleveland database." University of California 3.1 (1988): 3-2.

This dataset contains 13 attributes (which have been extracted from
a larger set of 75)       

## Attribute Information:
------------------------
      -- 1. age       
      -- 2. sex       
      -- 3. chest pain type  (4 values)       
      -- 4. resting blood pressure  
      -- 5. serum cholestoral in mg/dl      
      -- 6. fasting blood sugar > 120 mg/dl       
      -- 7. resting electrocardiographic results  (values 0,1,2) 
      -- 8. maximum heart rate achieved  
      -- 9. exercise induced angina    
      -- 10. oldpeak = ST depression induced by exercise relative to rest   
      -- 11. the slope of the peak exercise ST segment     
      -- 12. number of major vessels (0-3) colored by flourosopy        
      -- 13.  thal: 3 = normal; 6 = fixed defect; 7 = reversable defect     

## Attributes types
-----------------

Real: 1,4,5,8,10,12
Ordered:11,
Binary: 2,6,9
Nominal:7,3,13

## Variable to be predicted
------------------------
Absence (1) or presence (2) of heart disease

No missing values.

270 observations

# Dependencies
This project requires Python 3.x and the following Python libraries installed:
- [Numpy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [scipy](https://www.scipy.org/)

Use **pip** to install any missing dependencies.
I also reccommend to install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project which also include jupyter notebook to run and execute [IPython Notebook](http://ipython.org/notebook.html).

## Run :

In a terminal or command window, navigate to the top-level project repo Classification Projects/Heart_Disease_prediction (that contains this README) and run one of the following commands:

```ipython notebook heart_disease.ipynb```
or

```jupyter notebook heart_disease.ipynb```

This will open the iPython Notebook software and project file in your browser.

# Model Evaluation :
I have done model evaluation based on following sklearn metric.
- Confusion Matrix
- Sklearn classification report
- Model score
