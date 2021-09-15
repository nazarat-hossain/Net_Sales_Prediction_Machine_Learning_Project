# Net_Sales_Prediction_Machine_Learning_Project
 
 
Title: Net Sales Prediction using Machine Learning Models

Problem Statement: Strings Ramen is a ramen chain restaurant, which has been voted as Chicago’s Best Ramen Restaurant, and top 10 ramen stores in America. Strings make fresh noodles daily using only their unique dough mixer and noodle maker imported straight from Japan. Therefore, it has attained remarkable achievements during the past four years opening of its first store. Recently, the owner and stake holders have decided to establish a franchise brand of the store and expand in mid-west market. In order to develop new sales approaches, marketing plan and drive strategic decisions more effectively and efficiently for overcoming challenges in the markets, now they would like to predict the future daily sales based on their historical sales data.

Data Overview: The point of sales data is collected between Feb 19, 2015 and Dec 31, 2019. The dependent variables are net sales and independent variables are orders, guests, date etc. As sales are related with weather, so weather (daily temperature, precipitation etc.) data is also added as independent variables.

Analysis Approach: The owner wanted to know the sales condition/class (good, bad or average), while some stakeholders (store manager) wanted to know the predicted net sales value. To address this issue, both regression and classification analysis approach are used.
Analysis Results: In regression analysis for predicting net sales, ordinary least squares Linear Regression, gradient descent linear regression with different batch sizes, and support vector machine (SVM) are used. Among those models, gradient descent linear regression with batch size 500 shows better results: lower mean square error and higher-squared value.

On the other hand, logistic regression, random forest, SVM with different kernels and other classification models are used to predict the class of net sales. Among them, linear kernel SVM performs well. Random forest model is overfitted as it shows 100% accuracy in training data, but fails to perform good in test data. 

Conclusion: The manager who want to know predicted net sale will use gradient descent linear regression model, while the owner and stakeholders who want to know sales condition/class will use linear kernel SVM model.
