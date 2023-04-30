# Customer-Segmentation-Prediction

Project Summary

Charles Book Club Customer Segmentation and Targeted Marketing

​

Objective:

The primary objective of this project was to improve the targeted marketing efforts of the Charles Book Club (CBC) by leveraging their customer database to identify the most profitable customers and prospects. This was achieved by using various data mining techniques, such as RFM segmentation, k-nearest neighbors, and logistic regression, to create targeted marketing campaigns based on customer behavior data.

Dataset: The dataset, CharlesBookClub.csv, contained information on 4000 customers, including demographic data, purchase history, and responses to a test mailing for the book "The Art History of Florence." The dataset was randomly partitioned into three parts: Training Data (1800 customers), Validation Data (1400 customers), and Test Data (800 customers).

​

Methodology:

RFM Segmentation: Customers were segmented based on Recency (R), Frequency (F), and Monetary (M) variables. Different combinations of RFM codes were analyzed, and those with above-average response rates in the training data were identified.

k-Nearest Neighbors (k-NN): The k-NN technique was used to classify cases based on product proximity and purchase propensity using variables R, F, M, FirstPurch, and RelatedPurch. The best k was determined based on the validation set, and a lift curve was created for the best k model.

Logistic Regression: Three logistic regression models were constructed with "Florence" as the outcome variable and different sets of predictors. A lift chart summarizing the results from the three models was created, along with the expected lift for a random selection of an equal number of customers from the validation dataset.

​​

Key Findings:

RFM segmentation revealed several combinations with above-average response rates in the training data, which were used to target customers in the validation data.

The k-NN approach identified the best k value for classification and prediction. The lift curve for the best k model showed an improvement in targeting customers compared to random selection.

Logistic regression models with different sets of predictors provided valuable insights into the factors affecting customer behavior. The lift chart showed that models with a subset of predictors and the full set of predictors performed better than the model with only R, F, and M variables.

Using a cutoff criterion of a 30% likelihood of purchase, logistic regression models were able to identify targeted customers in the validation data, resulting in an improved response rate.

​​

Conclusion:

This project successfully employed data mining techniques to improve Charles Book Club's targeted marketing efforts. By using RFM segmentation, k-nearest neighbors, and logistic regression models, the company can now better understand its customer base and create tailored marketing campaigns to increase the response rate and profitability. This showcases the power of data-driven decision-making in enhancing the effectiveness of marketing strategies.
