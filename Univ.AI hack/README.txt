Problem Statement

An organization wants to predict who possible defaulters are for the consumer loans product. They have data about historic customer behavior based on what they have observed. Hence when they acquire new customers they want to predict who is more risky and who is not.

What do you have to do?

You are required to use the training dataset to identify patterns that predict default. Apply the patterns on test dataset to identify “potential” defaulters.

Evaluation Criteria

Submissions will be evaluated on the basis of roc_auc_score. Only the last submission will be considered for the leaderboard.

Data
The feature descriptions of the dataset is provided below. The risk_flag indicates whether there has been a default in the past or not.
All values were provided at the time of loan application.
Column
	
Description
	
Type
income	Income of the user 	int
age	Age of the user	int
experience	Professional experience of the user in years	int
profession	Profession	string
married	Whether married or single	string
house_ownership	Owned or rented or neither	string
car_ownership	Does the person own a car	string
risk_flag	Defaulted on a loan	string
current_job_years	Years of experience in the current job	int
current_house_years	Number of years in the current residence	int
city	City of residence	string
state	State of residence	string