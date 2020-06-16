# IMDb_Class_Prediction
Although IMDb rating is not absolutely accurate, it can be considered as a useful and informative tool to evaluate whether a film is successful.   

In this project, We are working on how to predict imdb rating classes. The scores are classified into 4 levels and imdb_class is considered as the response variable. Several prediction models are built with different algorithms (Logistic, Random Forest Classifier, XGBoost Classifier, CNN) and are evaluated by the confusion matrix. The optimized model can successfully predict movie IMDb class with important features. It will be helpful for the film companies to get the trick of success of films. 

**1. Introduction**  

    1.1 Data Description  
    1.2 Problem Object   
    
    
**2. Exploratory Data Analysis**   

    2.1 Data Profile     
       * Data Variables  
       * Data Types  
       * Descriptive statistics 
   
    2.2 Data Cleaning
       * Duplicates Data  
       * Remove Redundant Variables
       * Missing Values     
   
    2.3 Data Visualization  
       * Univariate distributions   
            - Barplot of important categorical variables
            - Histogram of important numerical variables                
       * Bivariate distributions
            - Pairlot between two Numerical variables
            - Boxplot between a Numerical variable and Categorical Variable
      
      * Correlations   
            
            
**3. Data Pre-processing**

    3.1 Bin Response Variable     
    
    
**4. Building Classification Models with Multiple Algorithms**  

    4.1 Make a pipeline for data preprocessing  
    4.2 Multiple Algorithms
       * Logistic Regression
       * Random Forest
       * XGBoost  Classifier
       * Deep-Learning models
   
    4.3 Make a pipeline for data prediction
    4.4 Interpretation of classification models results

**5.  Conclusions** 

- The Neural-network model is the optimized model to predict IMDb rating class. 
- User_vote, gross, ratio of critic reviews’,  duration,  Facebook likes to director and actor_1 are very important variables, while face number in post, content and country are not so crucial to the quality of the movies.


