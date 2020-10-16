# Overview

This project creates a machine learning model that will be able to predict the success of investing in a business venture. The CSV data file used for this project contains more than 34,000 organizations that have received various amounts of funding and the outcome of the invest (status of successful or unsuccessful). The data file is imported, processed, encoded, and standardized. The machine learning model is then trained, tested, and optimized to be able to predict if a future investment will be successful.

# Data

The data, once read into a dataframe, can be viewed below:

![Data](https://github.com/Waking-Dreamer/Deep_Learning_Funding_Orginizations/blob/master/Images/Data.png)

# Running Instructions

To run this code, open and run the Jupyter Notebook file Investment_Prediction_Deep_Learning.ipynb. This code references the charity_data.csv file located in the Resources folder.

# Conclusion

In an attempt to achieve target model performance, several different changes were tested. During the data processing phase, different binning amounts were explored. The higher the bin threshold, the lower the accuracy. During the model creation and testing phases, several different configurations were tested in an attempt to improve model accuracy. At first, a single neural layer network was tested. Different testing layers, node amounts, activation functions, and epochs were tested. Greater model complexity did not improve the accuracy rate. 

In the end, the model had 2 layers and both used the Relu activation function. The first layer had 10 neurons and the second layer had 5 neurons. 80 epochs were used. With all of the above, a lesser amount would decrease accuracy and a greater amount did not increase accuracy. Having a greater amount of epochs, neurons, or layers with no direct impact on accuracy just increases the chances of overfitting. 

Machine Learning Model Details:

![Machine_Learning_Model](https://github.com/Waking-Dreamer/Deep_Learning_Funding_Orginizations/blob/master/Images/Machine_Learning_Model.png)

The model had an accuracy rate of 73.9%, which did not achieve the target model performance amount of 75%. 

![Model_Accuracy](https://github.com/Waking-Dreamer/Deep_Learning_Funding_Orginizations/blob/master/Images/Model_Accuracy.png)

If a different model was implemented to solve this classification problem, I would want to test both Support Vector Machine learning (SVM) and the Random Forest method because they are both supervised types of machine learning that could achieve a similar model accuracy rate while requiring less coding and computational resources.
