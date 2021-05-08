# Sentimental-Analysis-Amazon-Fine-Food-Reviews-with-Deployment

# Objective
To perform Sentimental Analysis to determine whether the given review is Postive or Negative.

# Dataset Information
Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454

Number of users: 256,059

Number of products: 74,258

Timespan: Oct 1999 - Oct 2012

Number of Attributes/Columns in data: 10

# Attribute Information

1.Id

2.ProductId - unique identifier for the product

3.UserId - unqiue identifier for the user

4.ProfileName

5.HelpfulnessNumerator - number of users who found the review helpful

6.HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not

7.Score - rating between 1 and 5

8.Time - timestamp for the review

9.Summary - brief summary of the review

10.Text - text of the review

# Model used

Trained model using SGD Classifier with testing accuracy of 89.5%.

# Deployment

Used Flask framework for deployment with the saved model.

