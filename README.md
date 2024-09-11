# udacity-starbucks-project

#Libraries

The libraries used for this project are pandas, matplotlib and sklearn.

#Motivation

The motivation for this project is that I am a regular Starbucks customer and I wanted to utilize this dataset to understand how Starbucks reward programs work. The scope of the project is restricted to predicting if a customer will complete an offer based on the customer’s age and income.

#Files in this project

There are 6 files and 1 link in this project as listed below.
1- README.md which provides a short overview of the project itself and the relevant files.
2- datasets.zip/profile.json which provides has data on the customers from Starbucks who uses the rewards program.
3- datasets.zip/portfolio.json which provides data on the actual offers which Starbucks defines.
4- datasets.zip/transcript.json which provides data on the actual offer and customer associations which result in purchases.
5- Starbucks_Capstone_notebook.ipynb which is the notebook.
6- Starbucks_Capstone_notebook_output.html which is the output of the notebook.
7- https://medium.com/@dexterbujan/starbucks-capstone-challenge-31fe0ada144e This is a link to the blog post.


Project Definition:
This project uses Starbucks data from the rewards program to engage with customers on various offers Starbucks has. The motivation for this project is that I am a regular Starbucks customer and I wanted to utilize this dataset to understand how Starbucks reward programs work. The scope of the project is restricted to predicting if a customer will complete an offer based on the customer’s age and income.

Problem Statement-
The problem selected for this project is to predict if a customer will complete an offer based on the customer’s age and income. This is significant in addressing so that Starbucks can utilize the most appropriate offers targeted to the relevant age and income groups hence increase sales.

Results:

Below shows the confusion matrix for the decision tree which shows a high level of accurate predictions. This was also confirmed by the accuracy score of 0.7589.
Below shows the confusion matrix for the random forest which shows a high level of accurate predictions. This was also confirmed by the accuracy score of 0.7564.

Conclusion:

Although the Decision Tree model accuracy is 0.7589, it can be used to predict if a customer will complete the offer or not and improved over time. Starbucks can now use this to target the relevant age and income groups to try to get more sales. Monitoring of the model’s performance should be done so that any improvements to the processing time or accuracy can be done.

Improvements:

There are a number of other areas which can be further analyzed if I had more time like determining impact of increasing the reward amount etc., increasing/decreasing the duration of an offer, other metrics and other models to evaluate to select the best one to use.

Acknowledgment:

I would like to thank the person in Udacity for helping resolve the missing data files for this project. Also, I would like to thank the persons from the relevant websites below for their content in these webpages.

https://www.w3schools.com/python/pandas/pandas_json.asp

https://sparkbyexamples.com/pandas/pandas-replace-nan-with-blank-empty-string/

https://www.geeksforgeeks.org/merge-two-pandas-dataframes-on-certain-columns/

https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html

https://www.projectpro.io/article/pandas-apply-lambda/951

https://scikit-learn.org/stable/
