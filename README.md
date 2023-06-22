# Mobile-Price-Prediction
Abstract:
A mobile phone, cell phone, or hand phone, sometimes shortened to
simply mobile, cell or just phone, is a portable telephone that can
make and receive calls over a radio frequency link while the user is
moving within a telephone service area. Mobile phone has become a
common commodity and usually the most common purchased item.
Thousands of types of mobiles are released every year with new
features and new specification and new designs. So, the real question
is prediction is that what is the real price of the mobile and to estimate
the price of the mobile within the market for optimal marketing and
successful launch of the product. Price has become a major factor for
development of any product and its sustainability in the market.

Problem Statement:
Develop a Supervised learning model using Classification algorithms
to predict the price range of mobile phones in the ranges: 0(low cost),
1(medium cost),2(high cost) and 3(very high cost). The objective of
this project is to find out some relation between features of a mobile
phone and its selling price. In this problem, we do not have to predict
the actual prices but a price range indicating how high the price is.
Data Summary:
We have records of 2000 mobile phones with 21 columns/features.
Each column represents the features of the mobile.
We have zero null values.

Data Preparation:
Train-Test Split: The train-test split procedure is used to estimate
the performance of machine learning algorithms when they are used
to make predictions on data not used to train the model. It is a fast
and easy procedure to perform, the results of which will allow us to
compare the performance of machine learning algorithms for our
prediction. Although it is simple to use and interpret, there are times
when this procedure should not be used, such as when we have a
small dataset. The train-test split procedure is appropriate when we
have a large dataset, a costly model to train, or require a good
estimate of model performance quickly

Evaluation Metrics: Different performance metrics are available
for evaluating different machine learning algorithms. The metrics
chosen influence how the performance of a machine learning
algorithm is measured and compared. The performance for our
classification purpose is measured or evaluated by a confusion
matrix. The confusion matrix is one of the most intuitive and easiest
metrics used for determining the accuracy of a model. It is used for
classification problems where the output can be of two or more
classes. The confusion matrix is a table with two dimensions
“Actual” and “Predicted” and sets of “Classes” in both dimensions.
The confusion matrix in itself is not a performance measure as such,
but almost all performance metrics are based on the confusion
matrix.

Algorithms used for predictive modelling:
1) Decision Tree
2) Random Forest
3) K-nearest Neighbors
4) XG Boost
5) Logistic regression
Conclusion:
● The dataset contained 2000 records which were a mix of
categorical features and numerical features. ● The dataset was almost
cleaned as there were no null values present or duplicate records
found.
● Few features had zero values which had to be removed before
proceeding further.
● The target classes were almost balanced so we didn’t need to worry
about class imbalance problem.
● Most of the categorical features had a similar distribution except
‘three_g’ where there were very few records for mobile phones not
having 3G access.
● The story remains the same for categorical features when we break
down the distribution across different price ranges.
