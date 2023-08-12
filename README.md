# Waiter-Tips-Prediction
> Waiter Tips (Case Study):

* The food server of a restaurant recorded data about the tips given to the waiters for serving the food. The data recorded by the food server is as follows:
  
* total_bill: Total bill in dollars including taxes

* tip: Tip given to waiters in dollars

* sex: gender of the person paying the bill

* smoker: whether the person smoked or not

* day: day of the week

* time: lunch or dinner

* size: number of people on a table 

* So this is the data recorded by the restaurant. Based on this data, our task is to find the
factors affecting waiter tips and training a machine learning model to predict the waiter’s tipping.

* Waiter Tips analysis is to identify on which day a waiter gets higher Tips and vice versa.

> Loading Data:

* The script reads a CSV file named "tips.csv" using Pandas and stores it in the data DataFrame. The print(data.head()) statement displays the first few rows of the dataset.

> Scatter Plots for Relationships:

* The script uses Plotly Express to create scatter plots that visualize relationships between different variables. Three scatter plots are created using the same data but with different color-coding and trendlines.

> Pie Charts for Tip Distribution:

* The script creates pie charts using Plotly Express to show the distribution of tips based on different factors.

> Data Preprocessing:

* Categorical variables ('sex', 'smoker', 'day', and 'time') in the data DataFrame are mapped to numerical values for further analysis and modeling. This step is crucial because machine learning models require numerical inputs.

> Waiter Tips Prediction Model:

* The script uses scikit-learn to build a linear regression model to predict 'tip' based on various features.

* Data is split into training and testing sets using the train_test_split function.

* A Linear Regression model is instantiated using LinearRegression().

* The model is trained using the training data with the fit method.

* Now let’s test the performance of this model by giving inputs to this model according to the features that we have used to train this model.

> Conclusion:

* So this is how I  predict waiter tips with machine learning using Python. Waiter Tips analysis is one of the popular data science case studies where we need to predict the tips given to a waiter for serving the food in a restaurant.
