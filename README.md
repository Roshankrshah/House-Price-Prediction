# House-Price-Prediction

The objective of this project is to predict the house prices so as to minimize the 
problems faced by the customer. The present method is that the customer 
approaches a real estate agent to manage his/her investments and suggest suitable 
estates for his investments. But this method is risky as the agent might predict 
wrong estates and thus leading to loss of the customer’s investments. The manual 
method which is currently used in the market is out dated and has high risk. So 
as to overcome this fault, there is a need for an updated and automated system.

In our project, the proposed system works on Linear Regression Algorithm. In 
today’s real estate world, it has become tough to store such huge data and extract 
them for one’s own requirement. Also, the extracted data should be useful. The 
system makes optimal use of the Linear Regression Algorithm. The system makes 
use of such data in the most efficient way.

# Dataset
This dataset was prepared as a record for the house prices of different houses at 
different locations in the city of Bengaluru by various government authorities. 
This dataset is a large collection of over 13321 records and 9 columns of house 
price data collected by various trusted sources. It consists of the following 
features: area_type, availability, loaction, size, society, total_sqft, bath, balcony,
price. In these features, the price column is the labelled attribute.

# Techniques
In this paper, the linear regression algorithm helps to full fill customers by 
increasing the accuracy of estate choice and reducing the risk of investing in an 
estate. A lot of features that could be added to make the system more widely 
acceptable.
We have applied very efficient and logical feature extraction techniques so as to 
increase the accuracy. For example, we have done removal of outliers by using 
the business logic and bathroom feature. We know that if someone is going to 
buy a house of say 2000 sqft, then he should have at least 3 to 4 bedrooms. Any 
other cases in which there are only 2 rooms in 2000 sq ft, has been removed as 
an outlier. Another feature is the removal of cases where there are absurd numbers 
of bathrooms. By our logic, the total number of bathrooms should be at most 1 
more than total number of bedrooms, i.e. total bath=total BHK+1. Therefore, we 
removed any other cases from the data frame where the cases were contradictory.

# METHODOLOGY 
1. Pre-Processing and Data Cleaning 
Data preprocessing is an integral step in Machine Learning as the quality of data 
and the useful information that can be derived from it directly affects the ability 
of our model to learn; therefore, it is extremely important that we preprocess our 
data before feeding it into our model.

2. Feature Engineering
Feature engineering is the process of using domain knowledge of the data to 
create features that make machine learning algorithms work. If feature 
engineering is done correctly, it increases the predictive power of machine 
learning algorithms by creating features from raw data that help facilitate the 
machine learning process. Feature Engineering is an art .In our project, it includes 
exploring the total_sqft feature and also adds new feature price per square feet.

3. Dimensionality Reduction and Outlier Removal 
Dimensionality reduction refers to techniques for reducing the number of input 
variables in training data. Fewer input dimensions often mean correspondingly 
fewer parameters or a simpler structure in the machine learning model, referred 
to as degrees of freedom. In our project, any location which had number of houses 
less than 10 has been marked as “others” so as to reduce the dimensions of the 
dataset. Outliers badly affect mean and standard deviation of the dataset. These 
may statistically give erroneous results. It increases the error variance and reduces 
the power of statistical tests. If the outliers are non-randomly distributed, they can 
decrease normality. So, we applied various logics such as business logic, 
bathroom feature to remove the outliers. 

4. Model Building and Accuracy 
In our project, the model was implemented using the Linear Regression 
Algorithm. All the necessary libraries were imported and training of the model 
was done. We saw that in 5 iterations we get a score above 85% all the time. This 
was a very good accuracy score and we continued to use the algorithm. Also we 
compared different algoritms, such as Lasso Regression, Decision Tree and 
Linear Regression using the GridSearchCV technique to find the model with best 
accuracy, which we found that it is Linear Regression.

# Result
![image](https://user-images.githubusercontent.com/91787844/186562191-f65aee4e-81f1-41bd-92b8-1aca0a37db02.png)
