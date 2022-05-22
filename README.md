# Neural_Network_Charity_Analysis

## Overview of the Analysis

### The main goal of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Machine learning and neural networks algorithms were used to analyze the dataset that contains more than 34,000 organizations that received funding from Alpabhet Soup over the years. To be able to complete this analysis. the following steps were done:
    1. Preprocessed data for a neural network model.
    2. Compiled, trained, and evaluated the model, and;
    3. Optimized the model through modification.
    
 ## Results
 
 ### Data Preprocessing
 
 #### The preprocessing of the dataset was done to remove and identify relevant/essential variables:
   - Target Variable: IS_SUCCESSFUL
   - Feature Variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, & ASK_AMT,
   - Neither: EIN & NAME
  
  ### Compiling, Training, and Evaluating the Model
  -  I created three models. The first model has 2 hidden layers, one has 80 and the other has 30 neurons. The activation function used was *relu* and *sigmoid* for output layer. The second model was similar to the first model, however, the activation function wasc changed to *tahn*. Lastly, the third model is also similar to the first model, however, there is an added hidden layer with 20 neurons.

  - Despite optimizations made in each model, the 75% target model performance was not achieved. The average model performance of the three models was 65.3%, with highest of 73.2% and lowest of 49.8%.

  - Some optimization measures take were adding another hidden layer, changing activation function, adding and/or reducing the number of epochs, and reducing the number of features.

  ## Summary

  ### In conclusion, the utlization of deap neural network classification model to predict applicant's success using targeted parameters only acheived 73.2% accuracy (highest among three models). This fell a little short below the 75% target model performance despite optimization measures taken. One particular suggestion to improve the model is polishing the data by removing potential outliers and dropping more least sigficicant features.

  ### One could also use another supervised machine learning model, the *random forest classifier*. Supervised machine learning is a good way to classifying outcomes. This perfectly fits the goal of this analysis, which is to predict applicant's success. 
