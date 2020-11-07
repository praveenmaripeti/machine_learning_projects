Recommendation Engine

In this challenge we are required to build a model to predict the number of attempts taken by participants for a successful submission to online programming challenges. Data of programmers and questions they solved previously were given along with the time they took to solve the questions.

Input data contains three files:

train_submissions.csv - This contains 1,55,295 submissions which are selected randomly from 2,21,850 submissions. It contains 3 columns (‘user_id’, ‘problem_id’, ‘attempts_range’). The variable ‘attempts_range’ denotes the range of attempts that the users made to get the solution accepted which is our target. It takes values between 1 and 6.

user_data.csv - This file contains data of users. It contains the following features :-

user_id - unique ID assigned to each user
submission_count - total number of user submissions
problem_solved - total number of accepted user submissions
contribution - user contribution to the judge
country - location of user
follower_count - amount of users who have this user in followers
last_online_time_seconds - time when user was last seen online
max_rating - maximum rating of user
rating - rating of user
rank - can be one of ‘beginner’ ,’intermediate’ , ‘advanced’, ‘expert’
registration_time_seconds - time when user was registered
problem_data.csv - This file contains data of the problems. It contains the following features :-

problem_id - unique ID assigned to each problem
level_id - the difficulty level of the problem between ‘A’ to ‘N’
points - amount of points for the problem
tags - problem tag(s) like greedy, graphs, DFS etc.
Test data has one file:

test_submissions.csv - This contains the remaining 66,555 submissions from total 2,21,850 submissions. Contains 1 column (ID). The ‘attempts_range’ column which is to be predicted.

My notebook contains:
EDA
Feature Engineering
Modelling
Submission