# Background
Food Delivery services like Zomato and Swiggy need to show the accurate time it will take to deliver your order to keep transparency with their customers. These companies use Machine Learning algorithms to predict the food delivery time based on how much time the delivery partners took for the same distance in the past.

# Dataset & Features
To predict the food delivery time in real-time, we need to calculate the distance between the food preparation point and the point of food consumption. After finding the distance between the restaurant and the delivery locations, we need to find relationships between the time taken by delivery partners to deliver the food in the past for the same distance.

So, for this task, we need a dataset containing data about the time taken by delivery partners to deliver food from the restaurant to the delivery location.

The dataset you are given here is a cleaned version of the original dataset submitted by Gaurav Malik (https://www.kaggle.com/gauravmalik26) on Kaggle. Below are all the features in the dataset:

ID: order ID number \
Delivery_person_ID: ID number of the delivery partner\
Delivery_person_Age: Age of the delivery partner\
Delivery_person_Ratings: ratings of the delivery partner based on past deliveries\
Restaurant_latitude: The latitude of the restaurant\
Restaurant_longitude: The longitude of the restaurant\
Delivery_location_latitude: The latitude of the delivery location\
Delivery_location_longitude: The longitude of the delivery location\
Type_of_order: The type of meal ordered by the customer\
Type_of_vehicle: The type of vehicle delivery partner rides\
Time_taken(min): The time taken by the delivery partner to complete the order\

# Methods
Optimizer: Adam Optimizer
Error: Mean Squared Error
Training size: 0.90

# Experiment


# Conclusion
