# Takehome_User_Assesment

TakeHome User Assesment

Step 1 : Importing Data and Libraries
======================================
	- First we upload the data and explore what are the column present in it of you see the data it has the time column as a object type which is ver important feature for us to explore.

Step 2 : Data Cleaning
=======================
	- data are going to need to be merged between the user_engagement dataset and the user dataset.
Since the question mentioned seven day units I will need to code weekly units. 
	- so we converted the datetime andwe also seperated as Year/Week/day/Month
	- This is useful to know so we know where the start and finish of the trial exists
	- Create Year,Month,Week,and Day units. To be fair I would be doing this regardless of use,
	- since I know I will be working with time its useful to have options for working with the data

Step 3 : Model Preparation
==========================
- Training and Testing the model 
----------------------------------
	- y we taking it as a Absoulte user and remaining we taking it has a x
	- based on that we are creating a test and train model

- Random Forest Classification Model
--------------------------------------
	 - We are consider and taking the random forest classification model and by using this method we are getting a accuracy score of 99% but alsi which i also consider it as a overfiiting bcoz the data we have is insufficient.
	- Regardless of the reasoning we can see the most important features for predicting the 'Adopted Users' in the dataset
	-  I think the data needs more features that describe user details in order to get a proper model for describing user adoption.
