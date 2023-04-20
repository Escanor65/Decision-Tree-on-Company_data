# Decision-Tree-on-Company_data
The code provided is using the scikit-learn library to build decision tree models for 
a dataset containing information about a company's products, such as their prices, advertising budget, and sales.
The code first imports the necessary libraries, reads in the data from a CSV file, and performs some exploratory data analysis by creating a new categorical variable 'SalesCategory' based on the 
values in the 'Sales' column. It then transforms the data by creating dummy variables for the categorical variables using the 'get_dummies()' function.
Next, the code splits the data into training and testing sets using the 
'train_test_split()' function, and builds two decision tree models using the 'DecisionTreeClassifier()' function with different splitting criteria, 'entropy' and 'gini'. The models are fit to the training data using the 'fit()' method and the resulting decision trees are plotted using the 'plot_tree()' function.

Finally, the code generates predictions for the testing set using both models and evaluates the performance of the models using metrics such as accuracy, 
classification report, mean squared error, and R-squared score.
