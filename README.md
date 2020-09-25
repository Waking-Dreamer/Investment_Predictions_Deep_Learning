# Overview

This project creates a machine learning model that will be able to predict the success of investing in a business venture. A CSV data file containing more than 34,000 organizations, that have received various amounts of funding, is imported, processed, encoded, and standardized. The machine learning model is then trained, tested, and optimized to be able to predict if a future investment will be successful.

# Conclusion

In an attempt to achieve target model performance, several different changes were tested. During the data processing phase, different binning amounts were explored. The higher the bin threshold, the lower the accuracy. During the model creation and testing phases, several different configurations were tested in an attempt to improve model accuracy. At first, a single neural layer network was tested. Different testing layers, node amounts, activation functions, and epochs were tested. Greater model complexity did not improve the accuracy rate. 

In the end, my model had 2 layers and both used the Relu activation function. The first layer had 10 neurons and the second layer had 5 neurons. 80 epochs were used. With all of the above, a lesser amount would decrease accuracy and a greater amount did not increase accuracy. Having a greater amount of epochs, neurons, or layers with no direct impact on accuracy just increases the chances of overfitting. My model had an accuracy rate of 73.9%, which did not achieve the target model performance amount of 75%. 

If a different model was implemented to solve this classification problem, I would want to test both Support Vector Machine learning (SVM) and the Random Forest method because they are both supervised types of machine learning that could achieve a similar model accuracy rate while requiring less coding and computational resources.
