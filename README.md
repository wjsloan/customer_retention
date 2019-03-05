# Telecommunications customer retention

Full details of this project are given in the [Jupyter notebook](https://github.com/wjsloan/customer_retention/blob/master/customer_retention.ipynb).

This data science project centres on the problem of predicting whether or not customers of a telecommunications company will cancel their subscription. These predictions are based on information about the customers and their services, such as their gender, how long they have been with the company, and what kind of internet connection they have. The dataset used is available [here](https://www.kaggle.com/blastchar/telco-customer-churn).

I used a random forest classifier to make predictions, and this was around 78% accurate (with ~78% recall for both customers who stayed and customers who left). This is pretty high performance considering the inherent difficulty of predicting human behaviour using limited information (19 different variables). The most informative features for these predictions were the length of the customers' contracts, how long they had been with the company, how much they had spent in total on their services, and how much they pay every month.

This sort of predictive modelling can be very valuable for businesses. For example, running a full set of customers through this classifier would allow us to identify a group of the customers who are especially likely to terminate their services soon, and then perhaps we can develop a strategy to keep them based on the demographic they belong to.