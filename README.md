# Predictive
Health Insurance Cross Sell Prediction 🏠 🏥

Predict Health Insurance Owners who will be interested in Vehicle Insurance


**Problem Statement**

Our client is an Insurance company that has provided Health Insurance to its customers. Now they need your help in building a model to predict whether the policyholders (customers) from the past year will also be interested in Vehicle Insurance provided by the company.
An insurance policy is an arrangement by which a company undertakes to guarantee compensation for specified loss, damage, illness, or death in return for the payment of a fixed premium. A premium is money the customer must regularly pay to an insurance company for this guarantee.
For example, you may pay a premium of Rs. 5000 each year for a health insurance cover of Rs. 200,000/- so that if, God forbid, you fall ill and need to be hospitalized in that year, the insurance provider company will bear the cost of hospitalization etc. for upto Rs. 200,000. Suppose you are wondering how the company can take such high hospitalization costs when it charges a premium of only Rs. 5000/-. In that case, the concept of probabilities comes into the picture. For example, like you, maybe 100 customers paying a premium of Rs. 5000 every year, but only a few of them (say 2-3) would get hospitalized that year and not everyone. This way, everyone shares the risk of everyone else.
Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of a certain amount to the insurance provider company so that in case of an unfortunate accident by the vehicle, the insurance provider company will provide compensation (called ‘sum assured’) to the customer.
Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can plan its communication strategy accordingly to reach out to those customers and optimize its business model and revenue.
Now, to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel), etc.



Data Description

You are provided with two files: train.csv and test.csv

**Variable	            Definition**

id	                  Unique ID for the customer

Gender	              Gender of the customer

Age	                  Age of the customer

Driving_License     	0 : Customer does not have DL, 1 : Customer already has DL

Region_Code	          Unique code for the region of the customer

Previously_Insured  	1 : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance

Vehicle_Age	          Age of the Vehicle

Vehicle_Damage        1 : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.

Annual_Premium	      The amount customer needs to pay as premium in the year

PolicySalesChannel  	Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

Vintage	              Number of Days, Customer has been associated with the company

Response            	1 : Customer is interested, 0: Customer is not interested

**Evaluation Metric**

The evaluation metric would be the ROC_AUC score.

