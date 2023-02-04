# Titanic


![Titanic](https://user-images.githubusercontent.com/121724612/216768501-4483aa81-16d8-4740-adf6-c9d316571335.jpg)



## Description:

The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone on board, resulting in the death of 1502 out of 2224 passengers and crew.
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

## Overview
The data has been split into two groups:

       1.training set (train.csv)
       2.test set (test.csv)

## About Dataset

**The training set** is used to build our machine learning models. For the training set, we are provide the outcome (ground truth) for each passenger. Our model will be based on “features” like passengers, gender and class.

**The test set** should be used to see how well your model performs on unseen data. For this, we do not provide the ground truth for each passenger. Our job to predict whether the passenger survived or not by using the model that we trained.



## Data Dictionary
 
Passengerid: Id of the passenger<br>
pclass: A proxy for socio-economic status [ 1st = Upper   2nd = Middle   3rd = Lower]<br>
name:  Name of the passengers<br>
sex:   Gender of the passenger<br>
Age: 	 Age in years	<br>
sibsp:  siblings / spouses aboard the Titanic [ Sibling = brother, sister, stepbrother, stepsister Spouse = husband, wife]<br>
parch: parents / children aboard the Titanic  [ Parent = mother, father  Child = daughter, son, stepdaughter, stepson]<br>
ticket:	Ticket number	<br>
fare: 	Passenger fare	<br>
cabin:	Cabin number	<br>
embarked:	Port of Embarkation	[ C = Cherbourg Q = Queenstown  S = Southampton]
