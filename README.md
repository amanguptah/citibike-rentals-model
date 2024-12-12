# citibike-rentals-model
Problem Explanation:
The basic idea is to use a deep learning classifier model and data about NYC Citi Bike Rentals to predict the most popular Lyft bike destination stations. 
The input data has various features, such as starting station, start time, trip duration, start location, weather, etc. The model will give these features varying levels of importance/weight during training.
The model will take as input an entry from the data and output the most likely end station. This end station label will be the assigned class.
To determine if our model is an improvement on basic prediction strategies, we will compare our results to that from a baseline logistic regression model.
By measuring feature importance we will be able to determine which features in the data are most relevant for the user in deciding where they are going. For future work, less important features could be removed to improve efficiency of training.
