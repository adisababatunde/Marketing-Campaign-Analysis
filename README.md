# Marketing-Campaign-Analysis

Marketing strategy analysis
programming insight and technical report

                                                 Deliverables from this Project
1.	Analytics-enabled Marketing Strategy to predict most probable buyers from ~90% of loyalty program participants
2.	With the objective of optimizing profitability & market penetration, given: a Revenue from a successful buyer = $1,500
3.	b. The cost of the promotional sample kit is $440

	Assumptions
	missing values imputed with mode/mean
	label encoding is used (conversion of categorical features to numbers)
	

	A classification model was trained for predicting the probability of buying/not buying. The Logistic Regression Classifier algorithm was used.
	The model was trained and tested in an 80/20 ratio with the data gathered from the outcome (buy/not buy) of the top 10% of Loyal customers that got the promotional sample kit.
	The model gave 81% accuracy. It was saved and used to predict the % of customers that should be targeted in order to get the desired outcome of buying.
	Strategic marketing options for a 90 percent loyalty base as revealed by the output of the model
	For Market Penetration: Top 40% of the customer base should be targeted, that’s at a 24.4% probability threshold.
	For Profit Maximization: Top 30% of the customer base should be targeted, that’s at a 31.1% probability threshold.
