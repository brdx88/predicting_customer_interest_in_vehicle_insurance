# Health Insurance Cross Sell

![a](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/images/vehicle.jpg)

The cllient is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company. This dataset can be found on [Kaggle](https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction).

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

## Problems
Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.

## Goals
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

## Exploratory Data Analysis
![a](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/images/0.png)
![a](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/images/7.png)
![a](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/images/1.png)
![a](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/images/2.png)
![a](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/images/3.png)
![a](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/images/8.png)
![a](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/images/9.png)
![a](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/images/10.png)


## Conclusions
1. **Customers who said no interest, 52% of them are not interested not because they don't want but because they already have.** And Customers who said interested 99.66% of them said they don't have vehicle insurance. This means that we still have a chance that our vehicle insurance still interested by many people. The future is bright!
2. **Customer who has vehicle less than a year, 95.63% of them says no interest for our vehicle insurance.** But wait, 66.3% customer who has vehicle less than a year already has insurance. It means they don't interest not because they don't want but because they already have.
3. **Most customer who has not vehicle insurance, has faced vehicle damage in the past compare to they who don't.** In other hand, most customer who has vehicle insurance, has not faced vehicle damage in the past.
4. **Machine Learning Model can predict whether the customer interested or not with Recall 0.97 of 1.0** using Logistic Regression algorithm that already tuned. Using Recall from evaluation matrix because we want to minimize the False Negative which said customers are interested but we predict they aren't interested. This is dangereous! We could lose our chance to offer our vehicle insurance as well.

## Recommendations
1. **Educate more to the people about vehicle insurance.** The market of vehicle insurance is still growing. Most of our customers may not interest not because they don't want it, because they already had.
2. **Eyes on the New Vehicle.** Since we are targetting all customers who have vehicle, how about we divide it by vehicle age. We see that 66.3% customer who has vehicle less than a year already has insurance. The options is two: we could target everyone who has vehicle or the easiest one, people who buy a new car.
3. **Using Machine Learning Model for predicting if they are interested or not.** We could use our model that we built to speed up our sales by predicting the customers if they interested or not. So we can use our energy and time to serve more to customers who interest at our vehicle insurance only.


#### For more insights, please visit the notebook [here](https://github.com/brdx88/predicting_customer_interest_in_vehicle_insurance/blob/main/health_insurance_sell.ipynb)
