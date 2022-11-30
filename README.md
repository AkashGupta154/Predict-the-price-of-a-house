# Predict-the-price-of-a-house
Problem statement: The goal is to understand the relationship between house features and how these variables affect the house price. Using more than one model, predict the price of the house using the given dataset. 

### Steps Involved in the prediction of House Price Based on features 
:- 1 - importing libraries   
:- 2 - load Dataset    
:- 3 - Load Summarize or EDA    
4- 
#### Here the distribution of all the Numeric Varibale

![download](https://user-images.githubusercontent.com/100993371/204781159-c9fb9140-4c33-4485-a662-fff5eae035cc.png)

:- 5 - Visualizing the location of the houses based on latitude and longitude.    

![download](https://user-images.githubusercontent.com/100993371/204783584-4408094e-fbf6-44d7-a7ee-031e204fa621.png)

:- 6 - Split the dataset into train and test     
:- 7 - Standardize the data    
:- Standardize training and test datasets    

:- Feature scaling is to bring all the independent variables in a dataset into same scale, to avoid any variable dominating
the model, Here we will not transform the dependent variables.

:- 8 -  model deployment : Here I used regression algorithm like Linear Regression , Random Forest regression, Decision Tree regressor based on their accuracy and performs     
# Linear Regression 
![download](https://user-images.githubusercontent.com/100993371/204783674-b0ebf25d-de3a-40c3-8e7f-e9ee86d59486.png)

### Decision Tree Regression
![download](https://user-images.githubusercontent.com/100993371/204783709-5f47e16f-f8c0-414a-9dfc-c612a918f138.png)


### Random Forest Regressor
![download](https://user-images.githubusercontent.com/100993371/204783751-7357d910-402a-4477-b49d-1cec24dfa36f.png)

:- Accuracy Score/metrics of Linear Regression is Test 7.454135914547555 , Train 9.097513878212775     
:- Accuracy Score of Decision Tree Regression is 7.789184274421779    
:- Accuracy Score of Random Forest Regression is 5.782578483890736     

So Linear Regression algorithms is quite better than the other two algorithm on the given house dataset in Accuracy and performance.
