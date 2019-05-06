# AV-club-mahindra
AnalyticsVidhta club mahindra data olympics

![Competition banner](images/banner.jpg)


[Competition Link](https://datahack.analyticsvidhya.com/contest/club-mahindra-dataolympics/)

#### Problem Statement
###### Food & Beverages Spend Prediction in Club Mahindra Resorts
Club Mahindra (Club M) makes significant revenue from Food and Beverages (F&B) sales in their resorts. 
The members of Club M are offered a wide variety of items in either buffet or À la carte form. 
Following are some benefits that the model to predict the spend by a member in their next visit to a resort will bring:

1. Predicting the F&B spend of a member in a resort would help in improving the pre-sales during resort booking through web and mobile app.

2. Targeted campaigns to suit the member taste and preference of F&B

3. Providing members in the resort with a customized experience and offers

4. Help resort kitchen to plan the inventory and food quantity to be prepared in advance

Given the information related to resort, club member, reservation etc. the task is to predict average spend per room night on 
food and beverages for the each reservation in the test set.

#### Dataset Description

###### train.zip
train.zip contains train.csv and data_dictionary.csv.
* train.csv contains the training data with details on a set of reservations with the average spend per room night
* Data_Dictionary.xlsx contains a brief description of each variable provided in the training and test set.

###### test.csv
test.csv contains details of all reservations for which the participants need to predict the average spend on FnB per room night

###### sample_submission.csv
sample_submission.csv contains the submission format for the predictions against the test set. A single csv/zip needs to be submitted as a solution.

#### Evaluation Metric
Submissions are evaluated on 100 * Root Mean Squared Error (RMSE) on the variable amount_spent_per_room_night_scaled

#### Club Mahindra Baseline
To qualify for the Prizes, the RMSE of your submitted predictions on the private set or the private leaderboard score must 
beat the baseline RMSE set by Club Mahindra = 97

#### Public and Private Split
Test data is further randomly divided into Public (30%) and Private (70%) data.
	*  Your initial responses will be checked and scored on the Public data.
	*  The final rankings would be based on your private score which will be published once the competition is over.
	
#### Code & Approach Submission
* Setting the final submission is mandatory. Without a final submission, the submission corresponding to best public score will be taken as the final submission
* Code file and approach document are mandatory while setting final submission. For GUI based tools, please upload a zip file of snapshots of steps taken
* Participants must adhere to the approach document format provided at this [link](https://drive.google.com/file/d/1_t12CPk3R50xZ3uX-tww4zRftzSAaM2b/view).

#### Approach
- Feature engineering 
- Tried K-fold LGBM

#### Score
- Private LB score: 97.466 (Rank: 140/4105)
- Public LB  score: 96.365 (Rank: 123/4105)	