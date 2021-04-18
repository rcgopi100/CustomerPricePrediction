# CustomerPricePrediction

Customer Sales Order price prediction is one of the biggest tasks in any real-time environment because it has many features that should be considered before giving price to the customer for example.

a)	Customer in top tier pricing
b)	Customer volume pricing
c)	Customer upsell product pricing
d)	Customer cross-sell product pricing
e)	Customer seasonal pricing
f)	Customer stock variance pricing
g)	Customer shelf life nearing pricing
h)	Customer demand pricing
i)	And so on…

This is one cumbersome process that predicts the price for a particular product in any industry.  
Can we use Machine Learning to predict a customer price based on Supervised Learning with minimal features?
It is definitely possible and let’s see the outcome on prediction vs actual and what is the error rate for each prediction.
We are going to use 6 attributes that includes Sold To (Customer Buyer), Ship To (Ship to Customer), Material (Product), Price per Qty, Qty, Total Price.
Here we are predicting the Price Per Qty for Customers.

Libraries used:
Numpy
Pandas
Matplotlib
Scikit-learn: Machine learning Logistics Regression

Conclusion:
This gives us an idea that Machine Learning Supervised Learning can do wonders with data. However, it doesn’t give an accurate prediction to implement in the production system as Root mean squared error 222, so we need to reduce the error rate to get accurate prediction.  In the future, we can add more attributes to get less error rate in Prediction vs Actual. As a starting point, we can use Logistics Regression to test and check how it predicts with Actual vs Predicted values.  I will slowly build different models and will check which one is able to give fewer errors and make an accurate prediction.

Steps to follow:

1. Download customer_data.csv file
2. Download Customer Price Prediction.ipynb
3. Open Jupyter notebook 
4. Open Customer Price Prediction.ipynb
5. Point your directory whre you customer_data.csv downloaded in DATA_FILES_PATH = r"C:\\Documents\\Anaconda\\" (Windows PC)
6. Run all cells

